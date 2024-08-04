# Tic Tac Toe Game

Welcome to the Tic Tac Toe Game! This is a simple command-line implementation of the classic Tic Tac Toe game written in Python.

## Features

- Two-player game: Player X and Player O take turns to place their marks on a 3x3 grid.
- The game checks for win conditions after each turn.
- The game can be restarted by pressing any key after it ends.

## How to Play

1. Player X starts the game.
2. Players take turns to enter a value corresponding to the position they want to mark on the grid (0-8).
3. The grid positions are numbered as follows:
0	1	2
3	4	5
--	---	--
6	7	8


4. The game checks for a win after each turn. If a player wins, the game announces the winner and ends.
5. After the game ends, press any key to restart the game.

## Code Overview

- `sum(a, b, c)`: Returns the sum of three values.
- `printBoard(xState, zState)`: Prints the current state of the board.
- `checkwin(xState, zState)`: Checks if there is a winning combination on the board.
- `restart_game()`: Resets the game state to start a new game.

## Getting Started

### Prerequisites

- Python 3.x installed on your system.


cd tic-tac-toe
Example Gameplay
Welcome to tic tac toe
0 | 1 | 2
--|---|--
3 | 4 | 5
--|---|--
6 | 7 | 8
X's chance
plz enter a value: 0
X | 1 | 2
--|---|--
3 | 4 | 5
--|---|--
6 | 7 | 8
0's chance
plz enter a value: 4
X | 1 | 2
--|---|--
3 | O | 5
--|---|--
6 | 7 | 8
...
Game over!!
X won the game !...
Press any key to restart the game...

Acknowledgments
Inspired by the classic Tic Tac Toe game.
Made with Python.

