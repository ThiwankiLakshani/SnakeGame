# Hand-Tracking Snake Game

This is a Python-based Snake Game that uses OpenCV and cvzone for hand tracking. The game allows players to control the movement of the snake using their index finger detected via a webcam.

## Features
- Hand tracking using OpenCV and cvzone's HandDetector module
- Real-time snake movement based on finger position
- Randomly placed food items
- Score tracking
- Collision detection and game-over state

## Requirements
Ensure you have the following dependencies installed:

```bash
pip install opencv-python numpy cvzone mediapipe
```

## How to Run
1. Connect a webcam.
2. Run the script:
   ```bash
   python snake_game.py
   ```
3. Move your index finger to control the snake.
4. Press 'r' to restart when the game is over.

## File Structure
```
|-- snake_game.py   # Main game script
|-- Donut.png       # Food image used in the game
```

## Controls
- Move your index finger to direct the snake.
- The snake grows as it eats food.
- Avoid colliding with yourself to prevent game over.
- Press 'r' to restart the game.


## Author
**Thiwanki Lakshani**

## GitHub Repository
Find the source code on GitHub: [https://github.com/ThiwankiLakshani/SnakeGame]

