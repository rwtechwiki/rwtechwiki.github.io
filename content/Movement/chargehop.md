---
title: Charge-Hop
tags:
  - fundamentals
  - intended
  - move
  - variant
  - vanilla
socialImage: embedHeaders/chargehop_header.gif
socialDescription: One of the moves in Rain World 3
---
<div class="hidden-alts">
pounce
chargepounce
superjump
</div>

![[chargehop_header.gif]]
## Description
By holding jump for at least 20 ticks when crouching, slugcat's back arches and horizontal inputs are restricted until the jump button is released. Slugcat will then leap forward with a longer arc than a normal jump, allowing it to cross further gaps.

## Notes
The game checks if the player can do a pounce by using the variable superLaunchJump, which while crouched and holding jump increases by 1 per tick up to 20. This move does not use a fixed arc, so holding forward from the very start of the hop is important for maximizing distance traveled. Any horizontal input can be safely held if the variable superLaunchJump is 11 or more, as the game will only start reading the input once jump is released. Releasing jump early makes you do a small hop in place, holding any directional inputs before the 11 ticks or any vertical after decreases the superLaunchJump variable by 1 per tick, so with the correct timing it's possible to move while storing the charge as long as it's below 11, though it is generally useless due to being very slow.

Like all [[hoptype]] moves, it is possible to input up to [[airorient|orient]] slugcat into the standing state midair. This allows for a [[ledgepullup]] or [[polebounce]], helping with certain long jumps.

## Performed from


## Allows for
[[airorient]]

## Chains to


___
# Gifs
## Bulk
![[chargehop_0.gif]]
![[chargehop_1.gif]]
![[chargehop_2.gif]]
![[chargehop_3.gif]]
![[chargehop_4.gif]]
![[chargehop_5.gif]]
![[chargehop_6.gif]]
![[chargehop_7.gif]]
![[chargehop_8.gif]]
![[chargehop_9.gif]]