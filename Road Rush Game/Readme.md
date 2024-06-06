### Road Rush Game

#### Overview
Road Rush Game is a simple and exciting 2D car racing game built using Python and Pygame. The player controls a car, trying to avoid collisions with other cars on the road. The game becomes increasingly challenging as the player's score increases. 

#### Features
- Player-controlled car
- Randomly generated enemy cars
- Moving walls on both sides
- Score tracking with high score saving
- Simple and intuitive controls
- Cheat modes (reverse and slow motion)

#### Controls
- **Arrow Keys or WASD**: Move the car
- **Z**: Reverse cheat mode
- **X**: Slow motion cheat mode
- **ESC**: Quit the game

#### Requirements
- Python 3.x
- Pygame

#### Setup Instructions
1. **Install Python 3.x**: Download and install Python from the official website [here](https://www.python.org/downloads/).

2. **Install Pygame**: Use the following command to install Pygame:
   ```bash
   pip install pygame
   ```

3. **Clone the Repository**: Clone this repository to your local machine using the following command:
   ```bash
   git clone https://github.com/yourusername/Road Rush Game.git
   ```

4. **Navigate to the Game Directory**: Change to the directory where the game files are located:
   ```bash
   cd Road Rush Game
   ```

5. **Run the Game**: Execute the game script to start playing:
   ```bash
   python index.py
   ```

#### How to Play
1. **Start the Game**: Run the game script. The game will start with an introductory screen. Press any key to start playing.
2. **Control the Car**: Use the arrow keys or WASD to navigate your car and avoid collisions with enemy cars.
3. **Score Points**: Keep driving to increase your score. The game will end if you collide with an enemy car.
4. **High Score**: If your score exceeds the current high score, it will be saved and displayed the next time you play.
5. **Game Over**: When the game ends, you can press any key to restart the game.

#### File Structure
- **road_rush_game.py**: The main game script
- **assets/**: Directory containing the game's image files
  - `car1.png`: Player's car
  - `car2.png`, `car3.png`, `car4.png`: Enemy cars
  - `left.png`, `right.png`: Wall images
- **data/**: Directory for saving game data
  - `save.dat`: File to store the high score

#### Game Logic
1. **Initialization**: The game initializes Pygame, sets up the display, and loads images.
2. **Main Loop**: The game enters a loop where it continuously updates the game state and checks for user input.
3. **Event Handling**: The game handles key presses for movement and cheat modes.
4. **Collision Detection**: The game checks if the player's car has collided with any enemy cars or walls.
5. **Score Management**: The game updates and displays the current score and high score.
6. **Game Over**: The game displays a "Game Over" message and allows the player to restart.

Enjoy the game and have fun!
