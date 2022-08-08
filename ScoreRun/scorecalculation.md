Status: #partdone
Note Type: 
Tags: #score, #spoilers

# Score Calculation 
At the end of a [[huntermode|Score Run]], a player's score is calculated using the following formula:

```
Final Score = (1 + Passages) * {  
    (1*Food) + (10*Survives) + ((-3)*Deaths) + ((-3)*Quits) + ((-1)*Minutes) + 
    KillScore + ((100)*(Delivered Payload?) + ((40)*(Helped Pebbles?)) + ((300)*(Ascended?))
}
```

To simplify it, everything inside the curly brackets is added up, then multiplied by 1 plus the number of passages obtained in game. Each value from the formula is explained below.

- [[passages|Passages]]: the amount of Passages the player has achieved in the run.
- Food: the amount of food the player has consumed during the run.
- Survives: the amount of cycles the player has succesfully completed in the run.
- Deaths: the amount of times the player has died during the run.
- Quits: the amount of times the player has quit the game during the run.
- Minutes: the total gameplay time in minutes (does not include menus).
- [[pointstable|KillScore]]: the total amount of points gained through killing creatures during the run.
- *Delivered Payload?*: if the player gave the green neuron to Looks to the Moon, this is a value of 1. Otherwise, it's 0.
- *Helped Pebbles?*: if the player showed the green neuron to Five Pebbles, this is a value of of 1. Otherwise, it's 0.
- *Ascended?*: if the player was able to enter the void sea and ascend, this is a value of 1. Otherwise, it's 0.

In conclusion, killing creatures, eating, surviving cycles, obtaining Passages and completing story objectives increases a player's score, while dying, quitting the game and taking too long decreases it. 