# Snake Game

This is a simple console-based Snake Game implemented in C++. The game is played on a grid where the player controls a snake that moves around, eats food, and grows longer. The goal is to eat as much food as possible without colliding with the walls or the snake's own body.

## Features

- Console-based game
- Snake grows longer as it eats food
- Increasing difficulty with speed as the score increases
- Simple user interface

## Controls

- `W`: Move up
- `A`: Move left
- `S`: Move down
- `D`: Move right

## Getting Started

### Prerequisites

To compile and run the game, you'll need a C++ compiler. The game uses Windows-specific libraries, so it is designed to run on Windows systems.

### Compilation

To compile the game, use the following command in your terminal:

```bash
g++ -o snake_game snake_game.cpp -lwinmm
