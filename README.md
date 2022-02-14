# CIU 1 "PONG"
The first of a series of projects for the subject **Creando Interfaces de Usuario** using Processing 3. This particular one consisted in the implementation of the classic game **PONG**.

*Author - Carlos Brito Pérez*

## INDEX
- Implementation
  - Movement
  - Menus
  - Sound Effects
- Result
- References

## IMPLEMENTATION
### MOVEMENT
In this section we have to differentiate between two, the players movements and the ball movement. Firstly, the players can only move in the Y-axis, each player can move its rectangle using either **W/S** or **UP/DOWN**.

Meanwhile the ball its in constant movement, both in the X and Y axis, and there are only three ocurrences that can alter it.
1. If the ball hits either the top or botton border the Y-movement will invert.
2. If the ball hits a player it will bounce, inverting the X-movement and adding a set amount so the ball keep accelerating until someone scores and changing the Y-movement to a random one in a set range.
3. If the ball hits either the left or right border it will count as a point an the ball will return to the center.

### MENUS
For this project I decided to creates different states or menus.
1. **Main menu** - The starting state, it has an explanation of both the rules and controls. By pressing ENTER you start the match.
2. **Ingame** - The base state of the game, two players playing against each other.
3. **Pause** - This menu can be accessed by pressing TAB, it will freeze the game until ENTER is pressed.
4. **Victory** - Whenever a player scores 7 points this menu will triggers and declare that player as the winner. You can return to de Main menu pressing ENTER.
### SOUND EFFECTS
Several sound effects were added. Inclunding a background theme, a bouncing effect and a score sound.
## RESULT

![pong](https://user-images.githubusercontent.com/72495040/153772698-436de993-1260-4478-be8c-f366018205b7.gif)


## REFERENCES
https://github.com/otsedom/otsedom.github.io/blob/main/CIU/P1/README.md

https://freewavesamples.com/
