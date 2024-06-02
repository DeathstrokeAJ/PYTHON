# F1 Racing Game

Welcome to the F1 Racing Game! This is a fun and exciting car racing game built using Python and Pygame.

## Features
- **Dynamic Gameplay:** Navigate your car to avoid obstacles and increase your score.
- **Smooth Animations:** Enjoy a visually appealing experience with animated textures and car movements.
- **Sound Effects:** Engage with immersive sound effects for crashes and in-game actions.
- **High Score Tracking:** Keep track of your highest scores across game sessions.

## Prerequisites
To run this game, you'll need:
- Python 3.x
- Pygame library

## Installation
1. **Install Python:** If you don't already have Python installed, download and install it from [python.org](https://www.python.org/).
2. **Install Pygame:** Open your terminal or command prompt and run:
    ```sh
    pip install pygame
    ```

## Setup
1. **Download the Game Files:** Clone or download the game repository.
2. **Place Assets:** Ensure the following assets are in the same directory as the Python script:
   - `car.png`
   - `car_left.png`
   - `car_right.png`
   - `obstacle.png`
   - `texture.png`
   - `background.png`
   - `background_inv.png`
   - `intro1.wav`
   - `intro2.wav`
   - `car_crash.wav`
   - `ignition.wav`
   - `running.wav`
   - `high_score.txt` (initialize with a value, e.g., `0`)

## Running the Game
Navigate to the directory containing the game files and run:
```sh
python index.py
```


## How to Play
- **Controls:**
  - Move Left: `Left Arrow` or `A`
  - Move Right: `Right Arrow` or `D`
  - Pause: `Spacebar`
- **Objective:** Avoid obstacles to keep playing and increase your score.
- **Game Over:** The game ends if you crash into an obstacle or go off the track.

## Code Overview
### Key Functions and Features:
- **Main Functions:**
  - `game_intro()`: Displays the game intro screen with options to start or quit.
  - `game_loop()`: Main game loop where gameplay occurs.
  - `crash()`: Handles crash events and displays the crash screen.
- **Supporting Functions:**
  - `things_dodged(count, high_score, thing_speed)`: Displays score, high score, and speed.
  - `high_score_update(dodged)`: Updates the high score file.
  - `things(thingx, thingy)`: Draws obstacles on the screen.
  - `car(x, y, dir)`: Draws the player's car on the screen.
  - `message_display(text, shift_x, shift_y, color, sleep_time)`: Displays messages on the screen.
  - `title()`: Animates the title screen.
  - `motion_texture(thing_starty)`: Animates the road texture.
  - `count_321()`: Displays a countdown before the game starts.
  - `pause()`: Pauses the game.

## License
This project is open-source and available under the MIT License. Feel free to modify and distribute as needed.

