---
title: Sant Jordi Jam 2024 Post Mortem
date: "2024-04-23"
image: /assets/img/covers/roses.png
categories: [Personal, Projects]
tags: [game jams]
---

During this past few days I’ve been working with a very tiny Game Jam entry, Roses, a game about making Catalan flourish.

The game was made for the [Sant Jordi Jam 2024](https://itch.io/jam/sant-jordi-24){:target="_blank"}, under the theme “LLEGENDA & DIADA”, where we had to reference the legend and/or the tradition related to Sand Jordi, celebrated on April 23.

Basically the tradition says that a knight defeated a dragon and from his blood flourished a flower that was given to the princess, and the tradition related to it is that on April 23 guys give a rose to their loved ones and girls give a book to their loved ones (explained in a really short way, I’m not going to [go deep about this](https://en.wikipedia.org/wiki/The_Day_of_Books_and_Roses){:target="_blank"}).

---

## The Jam

So a friend of mine one day told me that he was trying to organize a jam related to the books and roses tradition of Sant Jordi, where the game was the equivalent of the book and when you submit it you send a rose to a random participant as well as you receive a rose from another random one.

## The Idea

At first, I wanted to participate alone with one of my many weird ideas, but I quickly lost motivation while working on it, but if you want to know what my idea was, here is a short summary:

> Basically, a Sant Jordi-themed minit-like game. You are Sant Jordi and you have to defeat the dragon with some obstacles in your way, the fun part is that every step you take and any interaction you do gets written into a book, and you have a limited amount of ink, so you must finish the game before the ink runs out and at the end you can take a look at your “legendary story”.

It was fun to hear, but not so fun to make it a reality while being alone in the team. Luckily, after a few days someone popped up on their Discord server asking for a programmer for a very little game, so I quickly responded and joined the team. Their idea was very simple but really interesting:

> A background app that reads your input and whenever you press a typical Catalan letter or digraph, you give the flower energy to grow, making it flourish and plant it in your garden.

---

## Programming the Game

Although the game idea seems simple, programming the game had some interesting aspects that I want to share.

Basically, it had a few points that had to be done for the app to work as it was planned:

1. It has to read input in the background
2. It has to be always on top.
3. It has to have custom window borders.

So to do it I have to use the magical Win32 API, thankfully C# allows you to access the `user32.dll` via the `DllImportAttribute`, so by doing it and reading their “awesome” documentation I was able to access fairly easily their system calls.

### Reading Input in the Background

I think that reading the input of the keyboard was the hardest thing of the entire development. This was because Microsoft, as usual, had a thousand different ways to do the same thing but most of them don’t work as they should so they were making the game crash and the documentation didn’t help while troubleshooting. Luckily, after a few hours of searching, I found the simplest call and the only one that I needed.

```csharp
[DllImport("User32.dll")]
public static extern short GetAsyncKeyState(int vKey);
```

This allowed me to see if a key was currently being pressed or not.

### Always on Top & Custom Window Borders

Luckily for these two things, I quickly found a [GitHub repository](https://github.com/sator-imaging/AppWindowUtility){:target="_blank"}, that allowed me to make these two things fairly quick. Giving me more time to develop the game and not suffer trying to understand the code behind the Win32 API.

---

## Art & Music

<div markdown="1" style="display: inline-block;">
![Rosa](/assets/img/personal/sant-jordi-jam-2024-post-mortem/Rosa.gif){: .right .w-50 }

Even though I didn’t draw the art and compose the music (which is actually a good thing), they play the most important role in this game, so I want to dedicate some words to it.

The art has been hand-drawn by Raquel and Arnau, making sure that the colors and the animations are as good as they can achieve in the jam period.

For implementing the animations in the game, this time I decided to create my **very** basic animation system for Unity, as I thought that it would satisfy my needs better than what Unity’s one would do.

The music was composed by Índigo, the goal of the game audio is to be a perfect fit for a background app, being really calm for this set.

The audio was implemented using FMOD as it allowed the sound designer to program randomly played ambient sounds without needing me to program it.
</div>

---

## Final Words

I have nothing bad to say about this jam, the game we created is very small and also very polished. During the development of the entry I also practiced some TDD along with the MVP architecture, while also trying to do some test, build and deploy with GitHub Actions.

This game jam showed me how much I love making small games, so no matter what happens in the future, I would love to continue making this small but beautiful experiences.

If you haven't already, you can check out [Roses on itch.io](https://arnaums1.itch.io/roses){:target="_blank"} and leave a comment of what you think about it.

And that's all for this game, I hope you liked this concept and until the next project!
