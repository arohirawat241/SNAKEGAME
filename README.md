# Snake Game 🐍 (JavaFX)

## Overview

A classic Snake Game built using JavaFX featuring real-time controls, multiple difficulty levels, and interactive game states such as start, pause, and restart. The project demonstrates core concepts of game loops, event handling, and collision detection.

---

## Features

* 🎮 Smooth real-time gameplay using JavaFX Timeline
* ⚡ Multiple difficulty levels (Easy, Medium, Hard)
* ⏸ Pause and resume functionality
* 🔁 Restart option after game over
* 🍎 Random apple generation
* 💥 Collision detection (walls and self)
* 📊 Score tracking

---

## Tech Stack

* Java
* JavaFX

---

## Controls

* **Arrow Keys** → Move snake
* **ENTER** → Start / Restart game
* **P** → Pause / Resume
* **1 / 2 / 3** → Select difficulty (before starting)

---

## How It Works

* The game uses a `Timeline` to create a continuous game loop
* Snake movement is handled using arrays to track body positions
* Collision detection checks for:

  * Wall boundaries
  * Self-collision
* Apple positions are generated randomly on the grid
* Game state is managed using flags (start, pause, running)

---

## How to Run

1. Ensure JavaFX is set up on your system
2. Compile the program:

   ```
   javac Snake.java
   ```
3. Run the application:

   ```
   java Snake
   ```

---

## Future Improvements

* Add high score tracking
* Add sound effects and animations
* Improve UI with themes
* Add increasing speed over time

---

## Project Highlights

* Implemented a real-time game loop using JavaFX Timeline
* Managed multiple game states (start, pause, game over)
* Designed modular functions for movement, collision, and rendering

---

## Author

* Arohi Rawat
