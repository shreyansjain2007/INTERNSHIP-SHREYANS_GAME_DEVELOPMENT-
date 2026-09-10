# Guess the Number Game 🎯

A simple command-line **Guess the Number** game written in Python. The computer randomly selects a number between 1 and 100, and the player keeps guessing until they find the correct number.

## Features

- Generates a random number between 1 and 100
- Gives **Too High** or **Too Low** hints after each guess
- Validates user input
- Prevents guesses outside the allowed range
- Counts the number of attempts
- Allows the player to play again after finishing a round

## Requirements

- Python 3.x
- No external libraries are required

The program only uses Python's built-in `random` module.

## How to Run

1. Download or clone the project.
2. Open a terminal in the project folder.
3. Run:

```bash
python guess_the_number.py
```

If your system uses `python3`, run:

```bash
python3 guess_the_number.py
```

## How to Play

1. The program selects a random number between **1 and 100**.
2. Enter your guess.
3. The program will tell you:
   - `Too Low!` if your guess is smaller than the secret number.
   - `Too High!` if your guess is greater than the secret number.
4. Keep guessing until you get the correct answer.
5. After winning, the program displays the number of attempts.
6. Enter `y` to play again or any other input to exit.

## Example

```text
=== Welcome to Guess the Number! ===

I'm thinking of a number between 1 and 100.
Can you guess it?

Enter your guess: 50
Too High! Try again.

Enter your guess: 25
Too Low! Try again.

Enter your guess: 32

🎉 Correct! The number was 32.
It took you 3 attempts.

Would you like to play again? (y/n): n

Thanks for playing! Goodbye.
```

## Project Structure

```text
Guess-The-Number/
├── guess_the_number.py
└── README.md
```

## Technologies Used

- **Language:** Python
- **Module:** `random`

## Author

Created as a simple Python project to practice loops, conditional statements, functions, user input validation, and random number generation.
