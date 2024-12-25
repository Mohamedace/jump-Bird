# Flappy Bird Game

## Overview
This is a Python implementation of the classic **Flappy Bird** game, where players navigate a bird through a series of pipes. The objective is to achieve the highest score by successfully passing through gaps between the pipes without colliding.

## Features
- Smooth gameplay with realistic gravity and controls.
- Dynamic obstacles (pipes) with randomized gaps.
- Ground scrolling animation for added realism.
- Start and Game Over screens for a polished experience.
- Tracks and displays the player's score.

## Technologies Used
- **Python**: Core language for development.
- **Pygame**: Library used for game development and rendering.

## How to Play
1. Launch the game by running `main.py`.
2. On the start screen, press the **Spacebar** to begin.
3. Control the bird by pressing the **Spacebar** to make it flap.
4. Avoid hitting the pipes or the ground.
5. If you collide, press **R** to restart the game.

## Controls
- **Spacebar**: Make the bird flap.
- **R**: Restart the game after a collision.
- **ESC**: Quit the game.

## File Structure
- `main.py`: The main Python file containing the game logic.
- `assets/`: A directory containing all the game assets.
  - `bird_down.png`, `bird_mid.png`, `bird_up.png`: Images for bird animations.
  - `background.png`: Background image.
  - `ground.png`: Ground image.
  - `pipe_top.png`, `pipe_bottom.png`: Images for the pipes.
  - `start.png`: Start screen image.
  - `game_over.png`: Game over screen image.

## Setup Instructions
1. Clone or download the repository.
2. Install the required dependencies:
   ```bash
   pip install pygame
   ```
3. Place the `assets` folder in the same directory as `main.py`.
4. Run the game:
   ```bash
   python main.py
   ```

## Screenshots
### Start Screen:
![Start Screen](assets/start.png)
### Gameplay:
![Gameplay](assets/gameplay.png)
### Game Over:
![Game Over](assets/game_over.png)

## Challenges Implemented
- Smooth collision detection using Pygame's sprite collision.
- Dynamic randomization of pipe heights and gaps.
- Realistic gravity and flapping mechanics for the bird.

## Future Enhancements
- Add a leaderboard to save high scores.
- Include sound effects for flapping, scoring, and collisions.
- Implement levels with increasing difficulty.

## Author
**Mohamed Amr**

