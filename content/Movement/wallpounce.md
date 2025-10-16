Status: #partdone 
Note Type: #move 
Tags: #fundimentals, #intended, #pounce

# Wall Pounce
![[pounce_header.gif]]
## Description
With the slugcat approching any vertical wall or terrain with enough horizontal speed, holding forward and pressing jump roughly within 3 pixels from the wall will make the slugcat bounce off the terrain in the opposite direction with considerable height and speed.

## Notes
There are two conditions for a wallpounce to trigger from the jump input:
1. The slugcat needs to have a horizontal speed over 7.5
2. The slugcat's upper body needs to hit the wall before the lower body

As long as both conditions are met, pressing jump at the right timing will always trigger a wall pounce, no matter the source of the initial motion. Some examples for setting up a wallpounce are: [[chargehop]], [[rollpounce]].

Successfully triggering a wall pounce creates a spark-like visual effect.

The jump input can be buffered a few frames before hitting the wall.

The slugcat's movement becomes unresponsive to directional inputs after a wallpounce, meaning that wallpounces always have a fixed trajectory, regardless of the speed when approaching the wall.

If the slugcat is grounded when triggering a wallpounce, the wallpounce becomes a [[spring]], which has different properties and is generally higher.

Wallpounces can be chained together if both sides are enclosed by walls. This allows quick ascension in chimney type of terrains.

## Performed from
[[chargehop]], [[rollpounce]], [[turnflip]]

## Chains to
[[wallpounce]]

___
# Gifs
## Bulk