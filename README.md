# 2048 Game Project

This is a Python project that implements the popular game 2048. It uses the Tkinter library for the graphical user interface (GUI) and leverages data structures and algorithms (DSA) for the game's logic.

## Files

The project consists of the following files:

1. `2048.py`: This is the main Python file that contains the entry point for the game. It initializes the GUI and starts the game loop.

2. `constraints.py`: This file defines the constraints and constants used in the game, such as the size of the game board and the target value.

3. `LogicsFinal.py`: This file contains the implementation of the game's logic. It includes functions for moving tiles, merging tiles, generating new tiles, and checking for game over conditions.

## Dependencies

To run this project, you need to have Python installed on your system. The project relies on the following Python libraries:

- Tkinter: This library provides the GUI framework for the game. It is usually included with Python installations.

## How to Run

To run the game, follow these steps:

1. Make sure you have Python installed on your system.

2. Clone or download the project files from the repository.

3. Open a terminal or command prompt and navigate to the project directory.

4. Run the following command to start the game:

   python 2048.py

5. The game window will appear, and you can start playing by using the W(UP), S(Down), A(Left), D(Right) keys to move the tiles on the board.

## Gameplay

The objective of the game is to reach the 2048 tile by combining tiles with the same value. The game starts with two randomly placed tiles of either 2 or 4. You can move the tiles in four directions (up, down, left, or right) using the W, S, A, D. When two tiles with the same value collide, they merge into one tile with the sum of their values. After each move, a new tile of value 2 or 4 will appear on the board. The game ends when there are no more valid moves or when you reach the 2048 tile.

## Acknowledgments

The implementation of the 2048 game logic in this project is inspired by the original game created by Gabriele Cirulli.
