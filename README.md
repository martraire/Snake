# Snake: Game developed in JavaScript

This code reproduces the famous "Snake Game". The aim is to eat as many apples as possible, directing the snake. Of course, you have to avoid collisions with walls and/or the body of the snake. Indeed, the length of the snake increases with the number of apples eaten. In addition, the speed of the snake double every 5 apples.

To direct the snake, use the arrows (left, right, top, bottom).
 
   ==> Enjoy and Bon appétit ;)


## HTML FILE: index.html
This file is only used to link the JavaScript file "script.js" and to launch the game on your web browser (Google Chrome, Firefox, …).


## JAVASCRIPT FILE: script.js
This script contains 3 different functions to build the game :

**SnakeGame**: 
- Fixes the dimension of the canvas (900x600)px
- Initializes the snake and the apple
- Calls the functions snake & apple  
- Defines conditions if collisions with wall/body
- Refreshes the canvas at each action, …
- Writes the score and defines GameOver.
             
**Snake**: 
- Draws the snake
- Defines how to move the snake with arrows
- Detects if the snake ate the apple. 

**Apple**: 
- Draws the apple
- Sets a new position of the apple (random position)
- Condition to be sure that the position of the new apple will not be on the snake.


