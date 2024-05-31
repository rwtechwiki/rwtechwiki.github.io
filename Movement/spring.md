Status: #partdone 
Note Type: #move 
Tags: #fundimentals, #intended, #pounce

# Spring
![[spring_header.gif]]
## Description
With the slugcat approching any straight corner with enough horizontal speed, holding forward and pressing jump roughly within 3 pixels from the wall will make the slugcat bounce off the terrain in the opposite direction with considerable height and speed.

## Notes
There are three conditions for a spring to trigger from the jump input:
1. The slugcat needs to have a horizontal speed over 7.5
2. The slugcat's upper body needs to hit the wall before the lower body
3. The slugcat needs to be grounded

As long as both conditions are met, pressing jump at the right timing will always trigger a spring, no matter the source of the initial motion. Some examples for setting up a wallpounce are: [[roll]], [[turnboost]].

Successfully triggering a spring creates a spark-like visual effect.

A spring is significantly higher than a [[wallpounce]].

The jump input can be buffered a few frames before hitting the wall.

Unlike [[wallpounce]], the slugcat's movement is still responsive to directional inputs after a wallpounce, meaning that directional input will affect the slugcat's trajectory.

In special cases where the slugcat's running speed exceeds 7.5, it's possible to trigger a spring without any specific setup or movement tech. Rivulet can trigger a wall pounce by running to a wall, while the others can achieve the same under mushroom's effects.

## Performed from
[[run]], [[slide]], [[roll]], [[turnboost]]

## Chains to
[[wallpounce]]

___
# Gifs
## Bulk