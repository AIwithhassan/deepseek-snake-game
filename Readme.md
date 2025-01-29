# Classic Snake Game in Python

A simple implementation of the classic Snake game built with Python's Pygame library. This repository is designed for educational purposes and serves as a starting point for learning game development basics.

## Features
- Classic snake gameplay mechanics
- Score tracking (snake length)
- Collision detection (walls and self)
- Responsive controls
- Simple and clean code structure

## Prerequisites
- Python 3.6 or higher
- Pygame library installed

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/AIwithhassan/deepseek-snake-game.git
   ```
2. Install the required library:
   ```bash
   pip install pygame
   ```


## How to Run
1. Navigate to the repository directory:
   ```bash
   cd deepseek-intro-repo
   ```
2. Run the game:
   ```bash
   python snake_game.py
   ```

## Controls
- Use arrow keys to control the snake's direction:
  - `←` (Left)
  - `→` (Right)
  - `↑` (Up)
  - `↓` (Down)

## Game Rules
- Eat the red food to grow longer
- Avoid hitting the window boundaries
- Avoid colliding with the snake's own body

## Customization
- Adjust the snake speed by modifying `snake_speed`
- Change the window size by modifying `window_width` and `window_height`
- Customize colors by modifying the color constants
- Modify the snake block size by changing `snake_block`
