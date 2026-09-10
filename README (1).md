# Rock-Paper-Scissors Game 🪨📄✂️

A simple command-line **Rock-Paper-Scissors** game written in Python. The player competes against the computer, which randomly selects Rock, Paper, or Scissors. The winner is determined using the standard game rules.

## Features

- Play Rock, Paper, or Scissors against the computer
- Computer chooses its move randomly
- Validates the player's input
- Displays emojis for each move
- Keeps track of:
  - Player wins
  - Computer wins
  - Ties
- Allows the player to quit at any time
- Displays the final score when the game ends

## Game Rules

The standard rules are used:

- **Rock beats Scissors**
- **Scissors beats Paper**
- **Paper beats Rock**
- Same moves result in a **tie**

## Requirements

- Python 3.x
- No external libraries are required

The program uses Python's built-in `random` module.

## How to Run

1. Download or clone the project.
2. Open a terminal in the project folder.
3. Run:

```bash
python rock_paper_scissors.py
```

If your system uses `python3`, run:

```bash
python3 rock_paper_scissors.py
```

## How to Play

1. Run the program.
2. Enter one of the following:
   - `rock`
   - `paper`
   - `scissors`
3. The computer will randomly select its move.
4. The program will display both moves and announce the winner.
5. The score is updated after every round.
6. Enter `q` or `quit` whenever you want to stop playing.
7. The final score will be displayed after quitting.

## Example

```text
=== Rock, Paper, Scissors ===

Choose rock, paper, or scissors (or 'q' to quit): rock

You chose:      Rock 🪨
Computer chose: Scissors ✂️

You win this round! 🎉

Score -> You: 1  Computer: 0  Ties: 0

Choose rock, paper, or scissors (or 'q' to quit): q

Final Score:
  You:      1
  Computer: 0
  Ties:     0

Thanks for playing!
```

## Project Structure

```text
Rock-Paper-Scissors/
├── rock_paper_scissors.py
└── README.md
```

## Technologies Used

- **Language:** Python
- **Module:** `random`

## Concepts Used

This project demonstrates:

- Functions
- `while` loops
- Conditional statements (`if`, `elif`, `else`)
- Dictionaries
- Lists
- User input and validation
- Random selection
- Score tracking

## Author

Created as a simple Python project for practicing basic programming concepts and game logic.
