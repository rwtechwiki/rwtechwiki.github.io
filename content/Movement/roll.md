---
title: Roll
tags:
  - fundamentals
  - intended
  - roll
  - move
  - vanilla
socialImage: embedHeaders/roll_header.gif
socialDescription: One of the moves in Rain World 3
---
![[roll_header.gif]]
## Description
It is possible to roll under certain conditions by holding down and left/right. A roll can last between 15-60 ticks (140 with [mushrooms](https://rainworld.miraheze.org/wiki/Mushroom)). From a roll, a jump input will produce a variable-height [[rollpounce]].

## Notes
To start a roll the following conditions need to be met:
- holding [[downdiagonal|down diagonal]]
- not already being rolling animation
- either:
	- having speed above 12
	- being in [[flip]] animation
	- being in [[slidepounce| slide pounce]] state
- colliding with a floor instead of a wall/ceiling
- allowRoll variable being above 0
	- gets set to 15 if tile below is empty otherwise decrements by 1 per tick
- having held the same down diagonal for at least 7 ticks (decreased to 2 ticks if speed is above 24) 

Rolling stops when any of the following are true:
- the head is above the body and either of the following is true:
	- the roll has lasted for over 15 ticks and down isn't being held
    - the roll has lasted for over 30 ticks (mushroom effect extends it up to 110 ticks)
- the roll has lasted for over 60 ticks (mushroom effect extends it up to 140 ticks)
- stopRollingCounter is over 6, which is incremented once per tick if either of the following is true, otherwise it's set to 0:
	- the slugcat is touching a forwards wall, but not if there is a wall on the immediate forwards tile and not in the top forwards as long as the immediate top tile is empty
	- the slugcat isn't touching a floor and neither of the two tiles below it are solid



Rolls can ascend 1-tile differences in floor geometry.

There is a window at the very end of the roll in which a jump input produces a [[rollslide]] without needing to re-press down and forward.

## Performed from
[[droproll]], [[crawlturnroll]], [[crouchtumble]], [[jumptumble]], [[pounceroll]], [[fliproll]]

## Allows for
[[rollpickup]], [[fastroll]]

## Chains to
[[rollslide]], [[rollpounce]]

___
# Gifs
## Bulk
![[roll_0.gif]]
![[roll_1.gif]]
![[roll_2.gif]]
![[roll_3.gif]]
![[roll_4.gif]]
![[roll_5.gif]]
![[roll_6.gif]]
![[roll_7.gif]]
![[roll_8.gif]]
![[roll_9.gif]]