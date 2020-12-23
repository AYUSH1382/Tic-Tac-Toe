#       						TIC TAC TOE 



Tic Tac Toe is a  game in which two players seek in alternate turns to complete a row, a column, or a diagonal with either three O's or three X's drawn in the spaces of a grid of nine squares. 

This Tic Tac Toe project is full ***Python*** based project. 



### Logics to WIN

------

There are 3 logics to win 

- Vertical Win : When the symbols i.e 'X' or 'O' are all same in a column then the corresponding player wins. There are 3 columns for a person to win.
- Horizontal Win : When the symbols i.e 'X' or 'O' are all same in a row then the corresponding player wins. There are 3 rows for  a person to win.
- Vertical Win : When the symbols i.e 'X' or 'O' are all same in any diagonal then the corresponding player wins. There are 2 diagonals to for  a person to win.



### Libraries used

------

1. ###### pygame

   ```python
   import pygame
   ```

   This module helps us to use  GUI in python in games. It is designed to build games. It makes the games interactive.

   In this project we have used pygame to perform a lot of functions

   - To display the screen/game board

   - To draw lines/make grids

   - To make the shapes 'X' and 'O'

   - To set the dimensions of the game board

   
> Note : If you don't have pygame installed, then use the following statement to install
   >
   > `pip install pygame`

2. ###### sys

   ```python
   import sys
   ```

   This module provides functions and variables used to manipulate different parts of the Python runtime environment.

3. ###### numpy

   ```python
   import numpy as np
   ```

   This python library is used for working with arrays.

   The tic tac toe grid is like an array. To perform the values on each element of the array we use this library.



#### Features

------

- Game starts with the board appearing on the screen

- Each player can alternately play their chance by clicking on an empty grid on the screen

- If a player wins then a line will be drawn across the three symbols indicating the win of the particular player

- After the game ends, which can be under 2 circumstances 

  1. Either one player wins
  2. Neither of the grids are empty nor did a player win

- In either of the above mentioned cases the game can be restarted by pressing the letter `r` from the keyboard.

  > Note:  The players can even restart the game anytime in between by pressing the letter `r` form the keyboard

- To give an interactive look we have set different colors for the background, grid lines and the symbols 'X' and 'O'

- To END the game anytime you can click on the close button on the window

  

  