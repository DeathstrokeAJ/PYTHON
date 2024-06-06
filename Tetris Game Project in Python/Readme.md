# Tetris Game by AJ Games

Welcome to the Tetris Game developed by AJ Games! This README file provides an overview of the game, its features, installation instructions, and gameplay controls.

## Overview

This Tetris game is a classic implementation of the popular Tetris game, with additional features such as high score tracking, sound effects, and a sleek graphical interface. The game is built using Pygame, a set of Python modules designed for writing video games.

## Features

- Classic Tetris gameplay
- High score tracking
- Sound effects for various game events
- Pause functionality
- Smooth graphics and animations
- User-friendly menu interface

## Installation

### Prerequisites

- Python 3.x
- Pygame library

### Steps

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/Tetris Game Project in Python.git
   cd Tetris Game Project in Python
   ```

2. **Install Pygame:**
   ```sh
   pip install pygame
   ```

3. **Run the game:**
   ```sh
   python index.py
   ```

## Gameplay Controls

- **Arrow Keys / WASD:**
  - `Up Arrow` / `W`: Rotate the tetromino
  - `Left Arrow` / `A`: Move the tetromino left
  - `Right Arrow` / `D`: Move the tetromino right
  - `Down Arrow` / `S`: Move the tetromino down faster

- **Space Bar:** Hard drop the tetromino
- **P:** Pause the game
- **Escape:** Quit to the main menu

## Game Structure

### Main Classes

- **Matris:** Manages the Tetris matrix, handles tetromino movement, rotation, and collision detection.
- **Game:** Handles the main game loop, updating the game state, and rendering graphics.
- **Menu:** Manages the main menu interface and handles user interactions.

### Key Functions

- **set_tetrominoes:** Sets the current and next tetromino.
- **hard_drop:** Instantly drops the tetromino to the bottom of the matrix.
- **update:** Updates the game state based on user input and elapsed time.
- **draw_surface:** Draws the game surface including the matrix and tetrominoes.
- **gameover:** Handles game over logic, including high score saving and sound effects.

## Resources

- **Tetrominoes:** Defined in `tetrominoes.py`, contains the shapes and rotation logic for tetrominoes.
- **Scores:** Defined in `scores.py`, handles loading and saving of high scores.
- **Sound Effects:** Stored in the `resources` directory and loaded using the `get_sound` function.

## Customization

You can customize various aspects of the game such as the background color, block colors, and sound effects by modifying the respective parts of the code. The block colors and sound effects are defined in the `Matris` class, and the game window dimensions and colors are defined at the beginning of the main script.

Feel free to reach out if you have any questions or suggestions. Happy gaming!

AJ Games
