# Strawberry Hunt

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Built With](#built-with)
- [Installation](#installation)
- [How to Play](#how-to-play)

---

## Overview
**Strawberry Hunt** is a 2D rendition of the classic snake game, built using C++ and the `raylib` game development library. The objective is to navigate the snake to eat strawberries, increasing your score as the game becomes progressively faster and more challenging.

## Features
- **Movement**: Control the snake’s movement in four directions.
- **Strawberry Item**: The strawberry serves as the main asset and food for the snake.
- **Score Tracking**: Each strawberry eaten increases the player's score.
- **Audio Integration**: Background gameplay music and eat and collision sound-effects have been applied.
- **Increasing Difficulty**: As the snake eats strawberries, it becomes longer and moves faster, intensifying the game.

## Built With
- **C++**: Core language for game logic and mechanics.
- **raylib 5**: Graphics library for rendering game visuals.
- **CMake**: Build tool for compiling and managing project dependencies.

## Installation

#### Pre-requisites:
  - It works with raylib version 4.5 and up.
  - Tested on both Windows 10 and Windows 11.
    
To run **Strawberry Hunt** locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/pushpitasaha/StrawberryHuntGame.git
   cd StrawberryHuntGame
   ```
2. **Build the game:** Ensure you have CMake installed and set up with raylib.

  ```bash
  mkdir build
  cd build
  cmake ..
  make
  ```

3. **Run the game:**
  ```bash
  ./StrawberryHuntGame
  ```
## How to Play
  - **Objective:** Guide the snake to eat as many strawberries as possible to increase your score.
  - **Controls:** Use arrow keys to move the snake in the desired direction.
  - **Goal:** Avoid crashing into the walls or the snake’s own body as it grows longer and faster with each strawberry consumed.

Have fun with the game! 🍓
