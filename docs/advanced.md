---
layout: default
title: Advanced
nav_order: 7
---

# Advanced Tricks
{: .no_toc }

This section is primarily about combining tricks to your advantage but it also includes higher-level expansions on tricks and glitches stated earlier for players who'd like to fine tune their skills even more. Learning these mechanics can greatly improve the speed and accuracy with which you can perform them. This tech is also generally more difficult to pull off. 
{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Advanced Rocketing

Friend
{: .label .label-green }
Piggyback
{: .label .label-green }

> Credit: ForestOfLight

Rocketing is a bit of an art. It may seem inconsistent because there are many factors to determine your launch. First, you must understand that what your screen shows and what your friend’s screen shows are different. Each player launches in the direction they’re facing (as well as up). The player to let go of the other first will be the leader. Whoever doesn’t let go will be sent to the other player. So, decide who will lead before launching, and position the leader facing the desired launch direction with the other player in front of them, facing them. 

Here are two videos showing the same launch from both players’ perspectives. Notice the difference in direction.

| Player One                                            | Player Two                                             |
|:------------------------------------------------------|:-------------------------------------------------------|
|![](../../assets/videos/Rocket Compare_ Player 1.mp4)  | ![](../../assets/videos/Rocket Compare_ Player 2.mp4)  |

Something else to take into account when rocketing is player height. Jumping onto a smaller player will give you a larger angle. Jumping onto a larger player will give you a smaller angle.

Another factor is your graphics settings. Changing the game’s FPS will change the speed of the launch from your point of view (0 is 2/3 speed, 1&3 are normal, 2 is 2x speed).

If you’d like to go underwater, simply start the rocket in the water. Only one player will go underwater so that player must let go. Be wary of crashes!

---

## Sonic / Supersonic Drive

Friend
{: .label .label-green }
Table
{: .label .label-green }

> Credit: Cheng/Euemj(程程)

{: .new }
> Changes have been made to this entry for the 0.19.1 patch!

This glitch creates the same effect as the [driving](#drive--advanced-table-uber) trick, but it moves much, much quicker. It can be quite hard to control when using the fast version, but it can even slice through wind walls! Other players don't see this glitch in action, but they can teleport to you once it's over or teleport automatically with an [uber](../clipping/#table-uber) setup.

<div style="width:100%;height:0px;position:relative;padding-bottom:56.250%;"><iframe src="https://streamable.com/e/vxr5g1?loop=0" frameborder="0" width="100%" height="100%" allowfullscreen style="width:100%;height:100%;position:absolute;left:0px;top:0px;overflow:hidden;"></iframe></div>

1. Place your table.
2. Have a friend sit at the table.
3. Grab your friends hand at the same time as they do any friend emote. (Similar to [Advanced Uber](../movement/multi-player/#drive--advanced-table-uber).)
4. Have your friend [hard freeze](../terms-and-methods/#freezing).
5. Drag your table out and zoooom.
6. When you're finished, place the table down. Your friend can stop freezing.

{: .note }
> Due to how placeable props work, your table will first teleport you to the [origin](../terms-and-methods/#the-origin) before you have much means of control. If any [reset walls](../terms-and-methods/#reset-walls-and-loading-zones) are between you and the [origin](../terms-and-methods/#the-origin) you will be reset to where you started the Supersonic Drive. You and your friend(s) will likely be split up by the servers as well.
> In addition, going through a [loading zone](../terms-and-methods/#reset-walls-and-loading-zones) will cause Sky to freeze. If this happens, just restart the game.

{: .highlight }
> Some manipulations for this trick:
> 1. Boat props are a great way to move across water.
> 1. Being piggybacked with your frozen friend (friend asks for piggyback and freezes before you accept) will make your sonic slower and easier to control. However, to make it more reliable it's easiest to piggyback on another friend and have them hold your frozen friend's hand.
> 1. Your friend can actually stand on or sit at your table and doesn't need to offer a friend emote, but they won't be taken with your table when they unfreeze.

---

## Table Fling v2

Placeable Prop
{: .label .label-green }

> Credit: ShanKa (rediscovery, research), ForestOfLight (optimization, research, usage)

{: .new }
> This entry has been added for the 0.19.1 patch!

This trick is extremely precise. It essentially lets you teleport to any location, but only if you've found a setup that works to get you there. Here's the usage process:

1. Place down your placeable prop and stand on top of it.
1. Open your emote menu and ready the screenshot button.
1. Tap the screenshot button and move the prop icon within the same [frame](../terms-and-methods/#graphics-and-fps).
1. Clear your photos when you're done! 😂

{: .highlight }
On iPhones, you must use the [portrait mode](../miscellaneous/#portrait-mode) work-around to get access to the screenshot button while the emote menu is open. Androids should be able to tap the screenshot button through the menu.

<div style="width:100%;height:0px;position:relative;padding-bottom:177.723%;"><iframe src="https://streamable.com/e/33tlgs?loop=0" frameborder="0" width="100%" height="100%" allowfullscreen style="width:100%;height:100%;position:absolute;left:0px;top:0px;overflow:hidden;"></iframe></div>

{: .note }
> The video shows only a *tap* on the prop icon while taking a screenshot. This is because of the lag spike when you take a photo in Sky. In reality, the icon is being *dragged*. Tapping the icon by itself will not work.

Finding a working setup for this glitch can be a little mathy, so pay attention if you'd like to use it to get to impossible places! First, the location you end up in is affected by a few variables:

- Your player's distance from the origin.
- Your player's rotation from the positive Z-axis.
- The rotation (yaw) of the *prop that you place during the screenshot* (not the one under your feet) in relation to the Z-axis.
- The other orientations of that prop (pitch and roll) in relation to the positive Y-axis.

{: .highlight }
> It can be confusing, so remember that the prop that you standing on at the begging of the glitch does **not** affect the final outcome! From now on, "prop" means the one you place during your screenshot.

Let's talk about player location first. This is the player's coordinates in relation to the [origin](../terms-and-methods/#the-origin). At your position, you have both a distance from the origin and an angle that starts at the positive Z-axis and continues clockwise around the plane. This distance is the same as the distance you will travel *from your prop*.

Next, the rotation that you place your prop in relation to the positive Z-axis *at the player's position*. Meaning, basically, which direction you face when you place down your prop. This angle is added to the angle from your player's position. Together, they make the angle (again, in relation to the positive Z-axis) that your fling will take you.

{: .note-title }
> Example
> 
> For simplicity, imagine you're directly on the Z-axis, so your location angle is 0. In addition, you're facing away from the origin, so your prop angle is also 0. When you table fling, you final location will be your initial location *plus* the distance that you placed your prop from your player.

The beginning of the video below may help you get a grasp for how your angles affect your final position. Note that the graphs are to-scale for Sky. The video also includes a derivation of a function with which you can use your player and prop's x and z coordinates to determine your final position. If you'd like them in a copy-able format, here they are:

```
xi (x_initial) is the x coordinate of the player.
zi (z_initial) is the z coordinate of the player.
xp (x_prop) is the x coordinate of the prop.
zP (z_prop) is the z coordinate of the prop.

x_final = xp + sqrt(xi^2 + zi^2) * sin(arctan(zi/xi) + arctan((zp-zi)/(xp-xi))), xp > xi
x_final = xp - sqrt(xi^2 + zi^2) * sin(arctan(zi/xi) + arctan((zp-zi)/(xp-xi))), xp < xi

z_final = zp + sqrt(xi^2 + zi^2) * sin(arctan(xi/zi) + arctan((xp-xi)/(zp-zi))), zp > zi
z_final = zp - sqrt(xi^2 + zi^2) * sin(arctan(xi/zi) + arctan((xp-xi)/(zp-zi))), zp < zi
```

<div style="width:100%;height:0px;position:relative;padding-bottom:56.250%;"><iframe src="https://streamable.com/e/mlxsbq" frameborder="0" width="100%" height="100%" allowfullscreen style="width:100%;height:100%;position:absolute;left:0px;top:0px;overflow:hidden;"></iframe></div>

{: .note }
> Keep in mind that this glitch also affects your Y-axis! If you're placing your prop on a flat surface, it'll effectively double your Y-coordinate.

---

## Legging Clip / Advanced Chibi Clip

This section is an expansion on the [Chibi Clip](../clipping/#chibi-clip--chibi-fall). The sneaky stance isn’t strictly required to perform this glitch, but it is highly recommended as it makes the glitch much more consistent. It’s also possible to do this without being chibi at all. Not much is known about clipping like this without chibi or the sneaky stance because it’s so fiddly.

{: .note }
> When active, the Firework Staff, Harp, Horn, Umbrella (not Lightseekers Ultimate Gift), Flute, Bass Drum (from Season of Prophecy), and Lantern can be a replacement for the sneaky stance.

{: .highlight }
> If you have the tea table you can clip into a flat floor by positioning yourself near a cup, [legging](../terms-and-methods/#legging) a foot towards the ground, and performing a Chibi Clip. Credit: Dough
> 
> <span class="fs-3">
> [Video](https://streamable.com/e/ws8d1n){: .btn .btn-blue}
> </span>

---

## Pushing Through Water

Friend
{: .label .label-green }
Table
{: .label .label-green }

> Credit: ForestOfLight

This glitch can be used to much more actively control your position underwater than other underwater tricks. This glitch was previously able to be performed in the same way as with wind walls. However, it can be done much easier (and now faster) with the help of a friend. Careful in oil (water that depletes your light) though, it doesn’t stop hurting below the surface!

<div style="width:100%;height:0px;position:relative;padding-bottom:56.250%;"><iframe src="https://streamable.com/e/kvbpp0?loop=0" frameborder="0" width="100%" height="100%" allowfullscreen style="width:100%;height:100%;position:absolute;left:0px;top:0px;overflow:hidden;"></iframe></div>

1. Initiate an [advanced uber](#drive--advanced-table-uber).
1. Drag your table as far as you can underwater.
1. Use the [midair table placement](../movement/single-player/#midair-prop-placement) mechanic to place the table where you’d like to go by facing your camera in the desired direction. Be cautious not to have any placeable surfaces in the direction you’re facing.
1. Since it only moves you a little bit, repeat step 3 until you’re in whatever location you’d like! Careful not to tap any of the “hold hand” or “sit” buttons on-screen (your friend shouldn’t either).

{: .highlight }
> More friends can go for the ride by holding your hand before initiating the [advanced uber](#drive--advanced-table-uber) or by sitting at the table like a normal [uber](../clipping/#table-uber). The former is preferable because there are fewer buttons that can make the trick fail crowding up the screen. If that somehow doesn’t bother you, go ahead and take a whole server down.