# Tic Tac Toe 🎮

A simple command-line **Tic Tac Toe** game written in Python. The game supports both **two-player mode** and **player vs. computer mode** on a 3×3 grid.

## Features

- 3×3 Tic Tac Toe board
- Two game modes:
  - Two Players
  - Vs Computer
- Checks for wins after every move
- Detects draws
- Validates player input
- Prevents players from selecting an occupied position
- Simple computer AI
- Allows the player to play multiple games

## Game Rules

- The game uses a 3×3 grid.
- Players take turns placing `X` and `O`.
- A player wins by getting three of their symbols in:
  - A row
  - A column
  - A diagonal
- If all nine positions are filled without a winner, the game ends in a draw.

## Computer AI

When playing against the computer, the AI follows a simple strategy:

1. Tries to win if a winning move is available.
2. Blocks the human player if they are about to win.
3. Takes the center position if available.
4. Chooses an available corner when possible.
5. Otherwise, chooses any remaining position randomly.

## Requirements

- Python 3.x
- No external libraries are required

The program uses Python's built-in `random` module.

## How to Run

1. Download or clone the project.
2. Open a terminal in the project folder.
3. Run:

```bash
python tic_tac_toe.py
```

If your system uses `python3`, run:

```bash
python3 tic_tac_toe.py
```

## How to Play

When the program starts, choose a mode:

```text
Choose mode - (1) Two players, (2) Vs Computer:
```

### Board Positions

Enter a number from **1 to 9** to select a position:

```text
  1 | 2 | 3
 ---+---+---
  4 | 5 | 6
 ---+---+---
  7 | 8 | 9
```

For example, entering `5` places your symbol in the center.

## Example

```text
=== Tic Tac Toe ===

Choose mode - (1) Two players, (2) Vs Computer: 2

You are X, computer is O. X always goes first.

  1 | 2 | 3
 ---+---+---
  4 | 5 | 6
 ---+---+---
  7 | 8 | 9

Player X, enter your move (1-9): 5

  1 | 2 | 3
 ---+---+---
  4 | X | 6
 ---+---+---
  7 | 8 | 9

Computer's turn...

...

You win! 🎉

Play again? (y/n): n
Thanks for playing!
```

## Project Structure

```text
Tic-Tac-Toe/
├── tic_tac_toe.py
└── README.md
```

## Technologies Used

- **Language:** Python
- **Module:** `random`

## Concepts Used

This project demonstrates:

- Functions
- Lists
- Dictionaries/data structures
- `while` loops
- `for` loops
- Conditional statements
- User input validation
- Random selection
- Game logic
- Basic AI decision-making
- State management

## Customization

The game logic can be modified to add features such as:

- Difficulty levels
- Score tracking
- Different board sizes
- More advanced AI
- Player name support

## Author

Created as a simple Python project for practicing programming fundamentals, game logic, input validation, and basic artificial intelligence.
