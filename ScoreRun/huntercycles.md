Status: #toreview 
Note Type: 
Tags: #score, #spoilers 
# Hunter Cycles
Unlike Survivor and Monk, playing as Hunter includes a perma-death mechanic in the game. Hunter's cycle counter starts at 19 and decreases with every passing cycle - instead of starting at 1 and increasing, like the other slugcats. In case a death occurs after the cycle counter reaches 0, it will be permanent - meaning the player will no longer the able to access this save file.

## Negative Cycles and Red Illness
Starting on cycle 0, Hunter will display symptoms of what is called in code as "Red Illness". Besides the fact that a death will end the run, other factors will start influencing gameplay.
- Each cycle will start as if Hunter had starved. That means the food bar will start at 0 and will need to be filled up to a certain point to "fix" the illness' symptoms. This value is determined by your current cycle plus 1. So on cycle 0, you need one food pip, one cycle -1 you need two and so forth.
- From cycle -9 onwards, the Red Illness cannot be fixed. This means that resting without full food will result in an actual starve cycle and, in case this starve cycle isn't fixed by eating up to full, a starvation death will occur.
- The amount of food requeired to fill a food pip is now determined according to a formula based on the amount of cycles passed. The food factor is given by `Max(0.1, 1 / (cycle * 0.5 + 2))`. This means that Hunter needs to eat exponentially more each cycle to fill a food pip, up to a maximum of 10 food per food pip.
- During Red Illness cycles, Hunter will have periodical "fits" and "visual effects". "Fits" are random stuns that occur from time to time - similar to passing out from moving too much while starved. Additionally, there is a "severity" value that scales with the amount of negative cycles survived, meaning that "fits" will happen more frequently as a player advances through the negatives. Finally, the "visual effects" are random screen distortions and temporary fade-outs that happen along with the 'fits'.

## Extra Cycles and Visiting Pebbles
During a Hunter run, a visit to Five Pebbles' chamber will increase the player's cycle counter by 5. It is also worth noting that this visit by itself will not raise Hunter's max karma to 10 like the other slugcats, so it functions basically as an Echo for the purpose of increasing karma.