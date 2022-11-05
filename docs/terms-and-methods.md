---
layout: default
title: Terms and Methods
nav_order: 2
---

# Terms and Methods
{: .no_toc }

Since OOBing can be a complicated process and some of the mechanics are not given a name in the game or need to be defined further, this section is necessary for understanding the Sky OOB Guide as well as the people in our communities. Feel free to refer to this page if you are confused by a term you're reading.
{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Out of Bounds
What *really* is out of bounds anyway? Is it somewhere you *have* to use glitches to get to or is it just somewhere off the beaten path? Our description of out of bounds is rather general:

{: .highlight }
> A location is considered out of bounds as long as it exists outside of the intended play area defined by the developers working on Sky: Children of the Light.

---

## Glide/Flight Mode

The default mode when you just take off (the button is in the *upright* position) will be referred to as glide mode. The longer, more controlled mode (the button is in the *downward* position) will be referred to as flight mode.

---

## Sustained Emotes

Any emote that continues infinitely until you move your skykid or perform another action. They include:

| Point             | Peek              | March             | Voila             |
| Come              | Handstand         | Telekenesis       | Navigate          |
| Welcome           | Boogie Dance      | Float (Meditate)  | Calm Down         |
| Butterfly         | Crab Walk         | Pray              | Ouch              |
| Clap              | Spin Trick        | Sparkler          | Headbob           |
| Belly Scratch     | Duck              | Doze              | Waving Light      |
| Shiver            | Faint (Play Dead) | Balance           | Raise the Roof    |
| Apologize         | Salute            | Slouch            | Rhythmic Clap     |

---

## Legging

Simply a term that refers to when you hold down on your character to pull a leg out in any direction. This can be quite useful for accurate positioning!

---

## Props

A prop is any item that you can wear on your back, like an instrument or table. Props that players can sit and chat at are known as tables. Props that can be placed down in the world, like the shelf or fox are known as placeable props. You can see a list of props and their categorizations [here](https://sky-children-of-the-light.fandom.com/wiki/Props#Availability_Legend). In most cases, it won't matter if you use a spell or an owned prop to do a trick. However, keep in mind that you may place down both a spell prop and an owned prop at the same time.

---

## Graphics and FPS

In the settings menu ingame, there’s a battery icon. This sets not only your graphics quality but also many frames are shown per second (FPS). There are four settings: 0, 1, 2, and 3. 0 runs at 20fps, 1 and 3 run at 30fps, and 2 runs at 60fps. Your fps are important for several reasons. First, you can only tap a button on screen during a frame, so turning down your fps can make the difficult timing of some tricks easier. *Speculation, not supported by code research:* Second, your player's position is calculated for each frame, making some tricks speedier with higher fps.

{: .highlight }
> Watch the FPS counter in the top right of the screen:
> <div style="width:100%;height:0px;position:relative;padding-bottom:56.250%;"><iframe src="https://streamable.com/e/9x7k08?loop=0" frameborder="0" width="100%" height="100%" allowfullscreen style="width:100%;height:100%;position:absolute;left:0px;top:0px;overflow:hidden;"></iframe></div>

---

## Collision Boxes

Any solid object that your player can collide with has what's called a *collision box*. In physics-based simulations (like in videogames where objects touch), when two objects intersect one another they repel or "snap to" each other so they don't pass through one another. This is what occurs when your player touches the floor, a wall, a pot, or another player. The "walls" of collision boxes are extremely thin and (in Sky) one-sided (ie. the inside of a collision box does not keep objects inside).

{: .note }
> Objects that repel you slowly like wind walls or clouds do not have the same type of thin-walled-instantly-repellant collision boxes. These objects repel you slowly once you are inside the bounds of their collision box, meaning you can't escape their push by going further inside them.

---

## Reset Walls and Loading Zones

<dl>
  <dt>Reset Wall</dt>
  <dd>Your sky kid is teleported to a place within the same level.</dd>
  <dt>Loading Zone</dt>
  <dd>Your sky kid is teleported to a new level entirely.</dd>
</dl>

The game deals with each of these a little differently, it's not important how for the moment, but it may affect the outcome of certain glitches.

---

## Freezing

Lightly disconnects a player from the game so that their position does not change (or changes more slowly) for the duration of the freeze.

<dl>
  <dt>iOS / Android</dt>
  <dd>Go into multitasking or lock your device.</dd>
  <dt>Switch</dt>
  <dd>Press the HOME button.</dd>
  <dt>Mac</dt>
  <dd>Focus on any tab other than Sky.</dd>
</dl>

There are different types of freezes depending on how your device handles apps that aren't actively in use. The most useful is a *hard* freeze. During a hard freeze, your client does not update your position whatsoever. Less useful--but still interesting--is a *soft* freeze, where your client updates your position very slowly instead of a normal rate.

Ways to *hard* freeze:
- App losing focus on Mac
- Going to the Switch HOME screen
- Going to the iOS home screen (impermanent)
- Locking your iOS or Android device (impermanent)

Ways to *soft* freeze:
- Going to the Android multitasking view
- (Going to the iOS multitasking view)

{: .important }
> There are differences in which type of freeze you will get on different types of Android devices. Contact Forest with your device model and freeze type if it contradicts the Guide.

---

## The Origin

The center of a map is technically important in Sky. The *origin* is wherever the coordinates of the current map hit (0, 0, 0). Several things happen at the origin. Most notably, it's the place where objects that don't otherwise have a defined position rest. These could be:

1. Players that have recently disconnected or gone through a [loading zone](#reset-walls-and-loading-zones).
2. Tables that have not been placed yet, or (in patch 0.19.1) are just starting to be placed.

Glitches that manipulate the coordinates of your player, like [table flings](../../patched/pre-0.14.5/#table-fling--table-yeet), also must be done with respect to where the origin is.

---

## Servers

A "server" in Sky consists of eight players or less in one level. These servers are kept optimized for players by a process called *server merging*, in which players are disconnected from or connected to a server with other players. Servers don't only store players but also temporary level data like which candles have been lit and which doors are open. When merging, lit candles and open doors override unlit candles and closed doors. When a server has zero players in it, it's level data is reset so new players can come along and interact with it.

Server merges are some of the most powerful but elusive features in Sky and people have been attempting to trigger server merges on purpose since the beginning. **The only factors that allow server merges is a player's distance from other players and the time since the last merge for that player.** Methods like deep-calling or placing tables have no effect.

{: .highlight }
> Due to it being technically simpler to merge one player into a server than multiple, travelling by yourself will make you experience more server merges than if you travel with a friend.