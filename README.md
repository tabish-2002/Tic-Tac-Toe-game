Tic Tac Toe Game in Python

This is a simple implementation of the popular game Tic Tac Toe in Python. The game is played on a 3x3 board where each player takes turns marking either an X or an O on the board until a player gets three of their marks in a row, column, or diagonal or the board is full with no winner.
How to Play

    The program will ask the first player to choose between X and O.
    The players take turns making their moves by inputting the row and column they want to place their mark on.
    The game ends when either a player wins by getting three marks in a row, column, or diagonal, or the board is filled with no winner.

Code Overview

The code first prompts the first player to choose between X and O. If the first player chooses X, the second player is assigned O and vice versa.

The game board is represented by a 3x3 matrix of strings. A function isValid() checks if a player's move is valid or not by ensuring that the input row and column are within the bounds of the board and the cell is not already occupied.

The function playerMakeMove() asks the player to input their move until a valid move is entered, and the function then places the player's mark on the board.

Functions checkHorizontal(), checkVertical(), and checkDiagonal() check if there are three marks of the same type in a row, column, or diagonal respectively. Function checkWinner() returns True if any of these functions return True.

Function checkBoardFilled() returns True if the board is completely filled with no empty cells.

The main function ticTacToe() runs an infinite loop where each player takes their turn to make a move, checks if there is a winner or if the board is filled, and ends the game if any of these conditions are met
