---
title: Run / Run-counter
tags:
  - fundamentals
  - intended
  - move
  - vanilla
  - va
socialImage:
socialDescription: One of the moves in Rain World 3
---
<div class="hidden-alts">
runcounter
</div>

## Description
It is possible to run by holding a horizontal input direction while standing on the ground.

## Notes
Each tick while running a variable is incremented (called `initSlideCounter` internally) until it reaches 30 at which point it will stop, this variable decays by 1 per tick while having neutral inputs and standing on the ground and is cleared on turning around, if while turning the run counter is at 11 or above [[turn]] variable will be gained instead.

## Used by
[[turn]], [[dashturn]], [[turnflip]], [[turnjump]], [[turndrop]]

## Allows for
[[runstore]]

## Chains to
[[jump]], [[slide]], [[coyotejump]], [[dashturn]]

___
# Gifs
## Bulk
![[run_0.gif]]
![[run_1.gif]]
![[run_2.gif]]
![[run_3.gif]]
![[run_4.gif]]
![[run_5.gif]]
![[run_6.gif]]
![[run_7.gif]]
![[run_8.gif]]
![[run_9.gif]]