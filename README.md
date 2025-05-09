# Snake-Game

A classic Snake game implementation using Pygame. Control a snake to eat food, grow longer, and avoid collisions with walls and yourself.

## Demonstration

[![Snake Game Demo](https://img.youtube.com/vi/AAINqRDRcaA/0.jpg)](https://www.youtube.com/watch?v=AAINqRDRcaA)

## Overview

This Snake game features:
- Grid-based movement
- Food generation and collection
- Score tracking
- Game over detection with restart option
- Visual grid system for orientation

## How to Play

1. Use the arrow keys to control the snake's direction
2. Eat red food blocks to grow longer and increase your score
3. Avoid hitting the walls or running into your own snake body
4. When game over occurs, press 'R' to restart

## Implementation Details

The game is built using Pygame and structured with object-oriented programming:

- **SnakeGame class**: Encapsulates all game functionality
- **Color constants**: Defines colors for visual elements
- **Grid system**: Simplifies positioning and collision detection
- **Game state management**: Tracks game over conditions and handles restarts

## Game Logic

1. **Snake Movement**: The snake moves in the direction set by the player
2. **Food Generation**: Food spawns at random locations not occupied by the snake
3. **Collision Detection**:
   - Wall collisions end the game
   - Self-collisions end the game 
   - Food collisions increase score and snake length
4. **Game Over**: When collision occurs, displaying final score and restart option

## Requirements

- Python 3.x
- Pygame library

## Installation

1. Ensure Python is installed on your system
2. Install Pygame:
```
pip install pygame
```
3. Run the game:
```
python snake.py
```

## Controls

- **Up Arrow**: Move up
- **Down Arrow**: Move down
- **Left Arrow**: Move left
- **Right Arrow**: Move right
- **R key**: Restart game after game over
