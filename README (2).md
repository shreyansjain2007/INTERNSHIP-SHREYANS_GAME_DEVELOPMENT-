# Quiz Application 📝

A simple command-line **Quiz Application** written in Python. The program asks multiple-choice questions, validates the user's answers, keeps track of the score, and displays the final result with a performance message.

## Features

- Multiple-choice quiz questions
- Validates user input
- Checks answers automatically
- Keeps track of the user's score
- Calculates the final percentage
- Displays performance feedback based on the score
- Shows the correct answer when the user answers incorrectly

## Questions Included

The current quiz contains **5 questions** covering:

- General knowledge
- Web development
- Mathematics
- Science
- Literature

## Requirements

- Python 3.x
- No external libraries are required

## How to Run

1. Download or clone the project.
2. Open a terminal in the project folder.
3. Run:

```bash
python quiz_app.py
```

If your system uses `python3`, run:

```bash
python3 quiz_app.py
```

## How to Use

1. Start the program.
2. Read each question and its four options.
3. Enter the letter of your chosen answer (`a`, `b`, `c`, or `d`).
4. The program will tell you whether your answer is correct.
5. Continue until all questions are completed.
6. Your final score and percentage will be displayed at the end.

## Scoring

The application provides feedback according to your percentage:

- **100%** — Perfect score! 🏆
- **70% or above** — Great job! 🎉
- **40% or above** — Not bad, keep practicing! 👍
- **Below 40%** — Keep studying and try again! 📚

## Example

```text
=== Welcome to the Quiz App ===

Q1: What is the capital of France?
  a) Berlin
  b) Madrid
  c) Paris
  d) Rome

Your answer: c
Correct!

...

==============================
Quiz Complete!
Your score: 4/5 (80.0%)
Great job! 🎉
==============================
```

## Project Structure

```text
Quiz-Application/
├── quiz_app.py
└── README.md
```

## Technologies Used

- **Language:** Python

## Concepts Used

This project demonstrates:

- Functions
- Lists
- Dictionaries
- `for` loops
- `while` loops
- Conditional statements
- User input validation
- Boolean values
- Score calculation
- Percentage calculation
- String formatting

## Customization

You can add or modify questions by editing the `QUESTIONS` list in `quiz_app.py`. Each question contains:

- The question text
- Four answer options
- The correct answer letter

## Author

Created as a simple Python project for practicing programming fundamentals, user input handling, conditional logic, and data structures.
