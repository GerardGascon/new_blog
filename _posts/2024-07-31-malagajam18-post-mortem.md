---
title: MálagaJam18 Post Mortem
image: /assets/img/covers/malagajam18-post-mortem.png
categories: [Personal, Projects]
tags: [game jams, godot, post mortem, alt ctrl]
---

> In this Jam I’ve finally accomplished my well of idea’s idea of making a game with dumb controls.
{: .prompt-info }

This past weekend I’ve participated in the [MálagaJam Weekend 18](https://itch.io/jam/malagajam-weekend-18), during this game jam amazing things happened.

First off, MálagaJam is an in-person jam organized by a group of really cool volunteers that make the jam site a place even better that your own home. I’ve only participated in two MálagaJams, but this one has been truly special because of many things that I would like to talk about.

---

## Getting a Jam ticket

The crazy things of this jam start with the buyout of the tickets. These cost **only** 20€, and we, as participants, need only 10 seconds to buy all the 200 tickets available for this jam.

So yeah, some people may spend all their efforts buying tickets for the next Taylor Swift concert, but I like to put all my efforts into buying tickets for the next MálagaJam. We just play at a higher league than those people.

## The community around this edition

<div markdown="1" style="display: inline-block">
![streetpass](/assets/img/personal/malagajam18-post-mortem/streetpass.png){: .right .w-50 }

During this edition something special happened, many teams including mine, decided to make a game with alternative controls. But specifically one of them decided to make a Nintendo 3DS game, and not only that, they made a call for everyone to bring their 3DSs and play and share time together competing at Mario Kart 7.

My 3DS broke a couple of years back, so for this jam I wouldn’t have been able to play any of those games, and even less, exchanging Miis via StreetPass.

So during the jam’s day morning I spent it walking through Málaga searching for thrifts stores with Nintendo 3DSs until I finally found one and bought it to be able of exchange the Miis.

I finally ended up having 22 jam participants in my Mii Plaza.
</div>

---

## Our game

For a long time I’ve been wanting to make a game with alternative controls, but I never had the opportunity to do that. After playing one of the last jam games about [touching a box](https://culoextremo.itch.io/caja), I said to myself that in the next jam I would be finally doing a game with alternative controls.

And here I was, with other 4 people, with the idea of making something weird. This jam’s theme was “de mal en peor” (from bad to worse), a great theme in my opinion, with this theme we got many ideas like these:

> A game where you have to control a spaceship where you have dozens of different buttons, and you don’t know which one does what, and so you can only make things worse.

> A game where you are constantly changing the position of the stars using a trackball and by doing so you are changing the horoscope and making people’s lives that depend on them worse.

> A game where you are a newly employed god that needs to help its followers but the control panel is too complicated, and you start getting so many followers that you end up forgetting the things you have to do.

And some more of them, so if you have already seen the game, you know that our final idea was the first one. Of course, we had less than 48 hours (minus sleeping time obviously) to do this thing a reality, so we ended up just having a few buttons, sticks and a spinner, but they were so badly placed that they ended up being the perfect amount for this game.

### The controller

<div markdown="1" style="display: inline-block">
![controller](/assets/img/personal/malagajam18-post-mortem/controller.png){: .right .w-50 }

An alternative control game has two completely different parts, so let’s start with the one that makes it alternative.

In this game we decided to make something like a spaceship controller with two sticks for controlling each engine, a couple of buttons to set the panic levels of the spaceship, one button just to play dumb sounds and one placed on top of the screen to hit whenever the screen started glitching.

The buttons were placed so far between them that it was impossible to press all of them at once, so the average gameplay we watched, was seeing people go completely crazy trying to control the situation, a hilarious experience.
</div>

### The game

<div markdown="1" style="display: inline-block">
![screenshot](/assets/img/personal/malagajam18-post-mortem/screenshot.png){: .left .w-50 }

This time I made the game again using **Godot Engine**, even though we had some difficulties connecting an Arduino to it (which were solved by using C# with a NuGet package), I had so much fun developing it in there.

The game is entirely held inside a spaceship, and you are constantly receiving instructions on how to control the situation, like press some buttons or move the sticks.

Occasionally you have to move the dynamo in order to have electricity and be able to read the instructions. Also, you have a button on top of the screen, that one is the one you have to hit whenever you lose signal on the screen, like fixing an old TV.

The instructions that are given to you get more and more complicated as you advance, some of them are even impossible to make, but they are there just for fun. I loved how some players tried to even use their nose to reach all buttons.

All of this followed by some amazing drawings, an elevator-style background music and some retro-style shaders that make this game something quite unique to see and play.
</div>

---

## Making a game is the less important thing

One of the things I love the most about the MálagaJam is the *weird* fact that making a game is the less important thing. Instead of a *typical* jam, where your only goal is to make the best game possible, MálagaJam is like you just go there, and eventually you get something done.

What I mean with this is that most of the participants, including myself, are going to hang out together, whether is to compete in the *Elite Four of Table Tennis*, or the *Frisbee Pétanque*, or any other dumb activity. In this specific edition we had a small Mario Kart 7 “tournament” that wasn’t really a tournament, where all the people with 3DSs hang out to play Mario Kart together.

![mariokart-tournament](/assets/img/personal/malagajam18-post-mortem/mariokart-tournament.jpg)
_Selfie of the Mario Kart 7 tournament taken with my Nintendo 2DS_

And then, there’s the Saturday’s night bingo, some people say that that’s the only reason they are there, I won’t say that I’m one of those people, but kind of.

But the jam is not only about its games or its activities, it’s also about the people that participate, and sometimes we hang out to do dumb things, like making a MálagaJam version of the green gnome that goes through the stores, but now it goes through the desks of the participants, or the one I just said about Mario Kart.

---

## The end result

In this jam we created something weird and chaotic, but it was fun as hell. Even though that we hard coded all the events in a Godot Animation Node and our game crashed when it ended, the experience the players where having and us as developers watching them play, was one of the greatest ones I had in a game jam. The fact that player’s ended the game sessions with a ‘Godot Engine is not responding’ screen only made them laugh even more.

{% include embed/video.html src='/assets/img/personal/malagajam18-post-mortem/gameplay.mp4' %}

So yeah, this jam has been one of the funniest experiences I’ve had for a while and want to continue attending to all their next editions even though it costs me quite some money to get there.

I hope you liked this post and let’s see if eventually I make a second alt.ctrl game with at least a portion of the fun I had developing this one.
