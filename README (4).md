# Snake Game 🐍

A simple **Snake Game** built with Python and the `pygame` library. Control the snake using the keyboard, eat food to increase your score and grow longer, and try to survive as long as possible.

## Features

- Classic Snake gameplay
- Keyboard controls using **Arrow Keys** or **WASD**
- Snake grows when it eats food
- Score tracking
- Increasing game speed as the score increases
- Wall collision detection
- Self-collision detection
- Game Over screen
- Restart option
- Quit option

## Requirements

- Python 3.x
- Pygame

Install Pygame using:

```bash
pip install pygame
```

## How to Run

1. Download or clone the project.
2. Make sure Python is installed.
3. Install Pygame.
4. Open a terminal in the project folder.
5. Run:

```bash
python snake_game.py
```

If your system uses `python3`, run:

```bash
python3 snake_game.py
```

## Controls

| Key | Action |
|---|---|
| ↑ / W | Move Up |
| ↓ / S | Move Down |
| ← / A | Move Left |
| → / D | Move Right |
| R | Restart after Game Over |
| Q | Quit the game |

## How to Play

1. Start the game.
2. Control the snake using the arrow keys or WASD.
3. Move the snake toward the food.
4. Each food item increases your score and makes the snake longer.
5. Every 5 food items, the snake's speed increases.
6. Avoid hitting the walls or the snake's own body.
7. The game ends when a collision occurs.
8. Press `R` to restart or `Q` to quit.

## Game Mechanics

### Food

Food is placed randomly on an empty cell of the game grid. It cannot appear on an occupied part of the snake.

### Scoring

Each time the snake eats food:

- Score increases by `1`
- Snake grows by one segment
- New food is generated

### Speed

The game starts at **8 moves per second** and increases in speed every **5 food items**, up to a maximum of **18 moves per second**.

## Example

```text
Score: 5

          🐍
        🐍
      🐍        🍎


GAME OVER

Final score: 12
Press R to restart or Q to quit
```

## Project Structure

```text
Snake-Game/
├── snake_game.py
└── README.md
```

## Technologies Used

- **Language:** Python
- **Library:** Pygame
- **Built-in Modules:** `random`, `sys`

## Concepts Used

This project demonstrates:

- Functions
- Lists
- Tuples
- Dictionaries
- Loops
- Conditional statements
- Keyboard input handling
- Random number generation
- Collision detection
- Game state management
- Score tracking
- Basic game development with Pygame

## Configuration

The game settings can be customized in `snake_game.py`, including:

- Cell size
- Grid width and height
- Starting speed
- Maximum speed
- Speed increase frequency

For example:

```python
CELL_SIZE = 20
GRID_WIDTH = 24
GRID_HEIGHT = 24
START_SPEED = 8
MAX_SPEED = 18
SPEED_INCREASE_EVERY = 5
```

## Author

Created as a Python game project to practice programming fundamentals and learn the basics of 2D game development using Pygame.
