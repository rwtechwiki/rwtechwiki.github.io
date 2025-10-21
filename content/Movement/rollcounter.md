---
title: rollCounter
tags:
  - variable
  - intended
  - vanilla
socialImage:
socialDescription: One of the moves in Rain World 3
---
<div class="hidden-alts">
mvcntr
movecounter
</div>
## Description
rollCounter is a variable that locks the slugcat's momentum in a given direction blocking all directional inputs from affecting it.

## Notes
 The exceptions to this are things like grabbing poles and holding forward for [[wallpounce]]. The slugcat can still be affected by [[throwboost]] and entity collisions. There is a 5s failsafe which removes rollCounter if it goes over 200, it increments once per tick and is applied at on initial animation change starting at 0 for bellySlide(slide) and at 1 for roll. rollCounter is not reset upon canceling the animation before the 5s failsafe only deactivated, but it does get reset when applied again.

## Used by
[[slidespin]], [[slide]], [[roll]], [[slideinstantspin]]

## Allows for
[[concussionclimb]]


___
# Gifs
## Bulk
![[{{title}}_0.gif]]
![[{{title}}_1.gif]]
![[{{title}}_2.gif]]
![[{{title}}_3.gif]]
![[{{title}}_4.gif]]
![[{{title}}_5.gif]]
![[{{title}}_6.gif]]
![[{{title}}_7.gif]]
![[{{title}}_8.gif]]
![[{{title}}_9.gif]]