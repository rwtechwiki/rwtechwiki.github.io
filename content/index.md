---
title: Welcome!
socialImage: embedHeaders/home_header.gif
socialDescription: One of the wikis in Rain World 3
---
This is a comprehensive collection and explanation of Rain World tech, including movement and eventually exploits, strategies and guides! (huge work in progress)

# [Get started](slide.md)


## Wiki Structure
This wiki uses TPS (ticks per second) to describe how inputs should be performed for most tech. 
Rain World has a graphical frame rate and a physics tickrate; the physics tickrate is much more predictable, usually set to 40TPS though this number changes in certain circumstances (like being near an echo) while without capping, the graphical framerate can vary by hundred of frames per second. FPS will be explicitly mentioned in the wiki where it is relevant. 
Note: the tickrate is taken from `RainWorldGame.framesPerSecond` and while the variable is called "framesPerSecond", "ticks per second" or ticks is used to delineate from the graphical framerate.

Input explanations are in the format of
```
[Inputs]~[amount of ticks held]
```
with the inputs being
```
F(forwards aka direction scug is facing)
B(backwards aka opposite of direction sucg is facing)
R(right)
L(left)
D(down)
U(up)
J(jump)
T(throw)
G(grab)
M(map)
```
e.g.
```
FDJ~2
F~10
```
would be the slide inputs with 2 ticks of down forwards jump followed by 10 ticks of forwards.
