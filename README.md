
      =============================================================
      Snake Game  -  developed in JavaScript by Diane Martraire  -
      =============================================================
    
                             Snake Game
                             ----------

    This code reproduces the famous ‘Snake Game’. The aim is to eat as
    many apples as possible, directing the snake. Of course, you have 
    to avoid collisions with walls and with the body of the snake.
    Indeed, the length of the snake increases with the number of apples
    eaten. In addition, the speed of the snake double every 5 apples.

    To direct the snake, use the arrows (left, right, top, bottom).
            ==> Enjoy and Bon appétit ;)




    1- HTML FILE : index.html

    This file is only used to link the JavaScript file ‘script.js’ and
    to launch the game on your web browser (Google Chrome, Firefox, …).



    2- JAVASCRIPT FILE : script.js

    This script contains 3 the different functions to build the game :

        - SnakeGame: Fixe the dimension of the canvas (900x600)px
                     Initialize the snake and the apple
                     Call the functions snake & apple 
                     Define conditions if collisions with wall/body
                     Refresh the canvas at each action, …
                     Write the score and defines GameOver.

        - Snake:     Draw the snake
                     Define how to move the snake with arrows 
                     Detect if the snake ate the apple.

        - Apple:     Draw the apple
                     Set a new position of the apple (random position)
                     Condition to be sure that the position of the new
                        apple will not be on the snake. 


