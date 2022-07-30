Status: #toreview
Note Type: #movetype
Tags: #fundimentals, #intended

# Air-Jump
## Description
When slugcat becomes airborn without use of the jump button, there is a 5-frame window after leaving the ground to hop by pressing jump. There is an equivalent window for a [[walljumptype]], with 15 frames within which slugcat is still able to [[jump]] after leaving a [[wallslide]].

## Notes
The variables in code which account for this are canJump and canWallJump. They are set to 5 and 15 respectively when in contact with the floor or wall respectively, and decrement by 1 every frame. While they are non-zero, slugcat is able to jump as normal. They are set to 0 upon jumping.

## Variants
[[coyotewalljump]], [[coyotejump]], [[crawlturnjump]], [[extendedslideairjump]], [[throwdoublewalljump]], [[extendedcoyotejump]], [[flippolemomentumjump]], [[groundeddoublewalljump]], [[jumppolemomentumjump]], [[momentumwallhop]], [[poleboostpolemomentumjump]], [[polecoyotejump]], [[polemomentumjump]], [[slidepolemomentumjump]]

___
# Gifs
## Bulk
![[airjump_0.gif]]
![[airjump_1.gif]]
![[airjump_2.gif]]
![[airjump_3.gif]]
![[airjump_4.gif]]
![[airjump_5.gif]]
![[airjump_6.gif]]
![[airjump_7.gif]]
![[airjump_8.gif]]
![[airjump_9.gif]]