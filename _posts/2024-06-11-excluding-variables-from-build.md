---
title: Excluding variables from build
date: "2024-06-11"
image: /assets/img/covers/excluding-variables-from-build.png
categories: [Technical, Notes]
tags: [unity, tools, C#]
---

Some times when we are working on a game we stumble upon the option to release a demo. Usually we don’t want to export all the game assets inside the demo build, but Unity doesn’t give you the option to exclude it depending on some Define Symbols and what decides if an asset is exported or not is if it is referenced in a scene.

For this reason I created this small code snippet in order to make this fairly simple and avoid having to add preprocessors to our variables.

---

## Demo Exclude Class

First we have to define a generic class for the values we want to exclude:

```csharp
using System;
using UnityEngine;

namespace DemoExclude {
	[Serializable]
	public class DemoExclude<T> {
#if !DEMO || UNITY_EDITOR
		[SerializeField] private T value;
		private DemoExclude(T value) {
			this.value = value;
		}

		public static implicit operator T(DemoExclude<T> v) => v.value;
		public static implicit operator DemoExclude<T>(T s) => new(s);
		public override string ToString() => value.ToString();
#endif
	}
}
```

Note that the UNITY_EDITOR is there to avoid losing dependencies when adding or removing the demo tag, if it wasn’t there unity would lose track of the variables once you enable the demo tag.

## Editor Visualization

By having done that, the exclusion is working properly, but we could add some editor view improvements. So let’s define a basic property renderer to add:

```csharp
#if UNITY_EDITOR
using UnityEditor;
using UnityEngine;

namespace DemoExclude {
	[CustomPropertyDrawer(typeof(DemoExclude<>), true)]
	public class DemoExcludeDrawer : PropertyDrawer {
		private const string WarningTooltip = "This variable won't be exported on build.";

		public override void OnGUI(Rect position, SerializedProperty property, GUIContent label) {
			SerializedProperty valueProperty = property.FindPropertyRelative("value");
#if DEMO
			Rect iconRect = new(position.x, position.y, 20, EditorGUIUtility.singleLineHeight);

			GUIContent warningIcon = EditorGUIUtility.IconContent("console.warnicon");
			warningIcon.tooltip = WarningTooltip;
			EditorGUI.LabelField(iconRect, warningIcon);

			Rect labelRect = new(position.x + 25, position.y, position.width - 25, EditorGUIUtility.singleLineHeight);
			Rect fieldRect = new(position.x + EditorGUIUtility.labelWidth, position.y,
				position.width - EditorGUIUtility.labelWidth, EditorGUIUtility.singleLineHeight);

			EditorGUI.PrefixLabel(labelRect, label);
			EditorGUI.PropertyField(fieldRect, valueProperty, GUIContent.none);

#else
			EditorGUI.PropertyField(position, valueProperty, label);
#endif
		}

		public override float GetPropertyHeight(SerializedProperty property, GUIContent label) {
			return EditorGUI.GetPropertyHeight(property.FindPropertyRelative("value"), label);
		}
	}
}
#endif
```

By doing this we get a basic view that shows when an exposed variable will be removed from build only if the DEMO tag is defined.

![Attribute Test](/assets/img/tech-notes/excluding-variables-from-build/Untitled.png){: .center }

---

With this simple bit of code we entirely remove the need of having to be constantly defining preprocessors in the variables of the current file.
