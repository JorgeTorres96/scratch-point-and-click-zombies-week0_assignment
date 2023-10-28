# Point and Click Zombies! - CS50 Week 0 Assignment
Asignment for CS50, Week 0: Scratch

[see on mit.edu](https://scratch.mit.edu/projects/915442199/)

## Mechanics: 
Max PlayerHP: 100HP.
Zombie colliding with Player = reduce 10 PlayerHP+Zombie Dies.
After 1.5 seconds not being hit, PlayerHP starts to regenerate at a 1point per 0.15s rate.
Point and click zombies to kill them and score one point.
Zombies get a compounding 1% additional speed every 10 seconds.

## Debugging

Change DEBUG_BUILD to 1 inside Stage>Initialize to see the values of all hidden variables.

## Hidden Variables:
isGameOver = Bit used as Bool.

ZombieSpeed = Float, initially 1.75

ZombieSpeedIncreaseTimer = Float, Counts from 0 to 10s recursively while playing.

isPlayerHit = Bit used as Bool. 1.5s cooldown when triggered, triggering it again resets the cooldown.

isGameStarted = Bit used as Bool.

ControlsEnabled = Bit used as Bool.

isGamePaused = Bit used as Bool. 
(Unimplemented)

EnemyPoolInitiated = Bit used as Bool.

NumberOfZombies = Int, max 25 zombies on screen at any point.
