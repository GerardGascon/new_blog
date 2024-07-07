---
title: The Art of Making Dumb Tools
date: "2024-07-07"
image: /assets/img/covers/the-art-of-making-dumb-tools.png
categories: [Personal, Projects]
tags: [dumb, tools, godot, C#]
---

> This short post mentions the word dumb exactly 22 times.
{: .prompt-warning }

For those who know me, already know that I love to experiment with things no matter how dumb they are (see [Well of Ideas post](https://blog.gerardgascon.com/posts/the-Well-of-Ideas/)).

Dumb tools may be useful or not, but one thing they are to me is fun as nothing else in the world, whether you are using or creating them.

## How does a dumb tool get created?

- **Short answer?** By thinking that a dumb thought can be turned into reality.
- **Long answer?** Let me tell you how I made one of my dumb tools.

### The Controller Slide Presenter (version a bit dumb)

Some time ago, while I was searching for references for my Homebrew Development talk, I stumbled across this presentation: [**Wii Homebrew: Running and writing software for the Wii**](https://www.youtube.com/watch?v=D03wx9Uz8IY), at first when I saw the guy making the presentation I thought he was passing his PowerPoint slides using a Wiimote, just to later see that in fact his slides where running on the Wii!

> Just read my Well of Ideas and saw that this isn't my first dumb idea with the Wii 😅
{: .prompt-info }

This made me think about making a small program to use your Switch Joy-Con or Wiimote to pass the slides, and long story short, a couple of days later I had this working:

{% include videos-width.html width="50%" folder="personal/the-art-of-making-dumb-tools" name="version1" %}

So yeah, a Switch Slide Presenter, finally a dumb but useful way to present my slides without having to go from side to side of the stage (and without spending money buying a real slide presenter), but my dumb goal wasn't accomplished yet, I needed the Wiimote to work, and sure, fast forward a couple of days and here it was:

{% include videos-width.html width="50%" folder="personal/the-art-of-making-dumb-tools" name="version2" %}

This dumb tool is now available in my GitHub: <https://github.com/GerardGascon/Controller-Slide-Presenter> (only Windows and Linux support at the moment)

But while holding the Wiimote testing the app, I thought "Umm, I have a tool to emulate a slide presenter, but slide presenters have lasers to point, why don't I try making a Wii pointer for PC?", my real dumb tool idea finally came into existence.

---

### The Controller Slide Presenter (version a lot dumber)

Let's fast forward a couple days until the last Barcelona Game Creators (a great event where you should go btw). So well, after getting bored of working on boring things, I remembered that dumb idea and created a new Godot project to try making this a reality.

I decided to only support Joy-Cons for this project as they where easier to hook, had a better gyro than the Wiimote and they where dumb enough, and after a couple of hours trying to comprehend how the hell Quaternions work, I ended up with a Wii pointer moving across my laptop screen.

{% include videos-width.html width="50%" folder="personal/the-art-of-making-dumb-tools" name="version3" %}

This is also available in my GitHub: <https://github.com/GerardGascon/Controller-Cursor> (only Windows support at the moment)

---

I personally love these kind of things, in this case I talked about tools, the "useful" side of this dumb creativity, but some other sides of the dumbness are alternative control games (one dumb thing that I have yet to experiment with) or the [**Ig Nobel Prize**](https://en.wikipedia.org/wiki/Ig_Nobel_Prize), as for sure there are many more.

So yeah, dumb tools, a dumb power that comes with dumb responsibilities.
