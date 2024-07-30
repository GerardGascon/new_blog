---
title: Using the Unity’s Input System the way Input Manager worked
image: /assets/img/covers/using the-unitys-input-system-the-way-input-manager-worked.png
categories: [Technical, Notes]
tags: [unity, input system]
---

When I started using Unity’s New Input System, I only saw how much they had overcomplicated the way input had to be implemented. The fact that I had to create an input action asset, create some actions with its bindings, create an instance within a class, and then subscribe to its callbacks made me stand away from it for quite a while.

Luckily, Unity has made things easier in recent updates, they introduced the [Project Wide Actions](https://docs.unity3d.com/Packages/com.unity.inputsystem@1.8/manual/ProjectWideActions.html), a way of having an Input Action Asset accessible from all scripts. This eases a lot of the implementation process, making it more similar to the Input Manager, and lots of other input management systems.

---

The way this works is by first assigning an Input Action Asset to the Project Settings > Input System Package menu, like so:

![Project Wide Actions](/assets/img/tech-notes/using the-unitys-input-system-the-way-input-manager-worked/Untitled.png){: .center }

After that, we can access it by first saving the actions into an InputAction field, and then you’ll be able to read its state directly in the Update.

```csharp
using UnityEngine;
using UnityEngine.InputSystem;

public class Example : MonoBehaviour {
    InputAction moveAction;
    InputAction doSomethingAction;

    private void Start() {
        doSomethingAction = InputSystem.actions.FindAction("DoSomething");
        moveAction = InputSystem.actions.FindAction("Move");
    }

    void Update() {
        Vector2 moveValue = moveAction.ReadValue<Vector2>();

        if (doSomethingAction.IsPressed()) {

        }
    }
}
```

Even though you could declare the InputAction and use it directly in the Update method, I think that it is a minimal setup that makes the performance a bit better.

---

Even though I ended up getting used to working with events (and I like it), I like how they ended up adapting the Input System to work the way it traditionally worked, making things easier for new developers to start working with a more powerful system.
