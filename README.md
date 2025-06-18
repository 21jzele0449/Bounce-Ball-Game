# Bounce-Ball-Game

## Bounce Ball Game in Python:

A simple and fun **Bounce Ball Game** developed using **Python** and **Tkinter**, applying concepts from **Object-Oriented Programming (OOP)** and **Data Structures**. This game was created as part of a course project under the supervision of **Sir Irfan Ahmad**.


## Course:

**Object-Oriented Programming & Data Structures**  
Department of Electrical Engineering


## Project Objectives:

- Demonstrate practical understanding of **OOP** and **data structures** using Python.
- Implement a playable game using **class-based design** and event-driven programming.
- Gain hands-on experience with **Python libraries** like `Tkinter` for GUI-based applications.


## Game Overview:

## Bounce Ball Game Rules:
- A ball bounces within the canvas and must be kept in play using a movable paddle (pole).
- Colored "stones" are placed at the top of the canvas. The goal is to destroy all stones by hitting them with the bouncing ball.
- The ball must not fall past the paddle. If it does, the game ends.
- The paddle can be moved left or right using the **arrow keys**.
- Press **Enter** to start and **Spacebar** to pause the game.


## Key Programming Concepts Used:

- **Object-Oriented Design**: Classes used for Ball, Paddle (Pole), and Stone.
- **Tkinter GUI Framework**: For canvas rendering and game interface.
- **Event Binding**: Handling keyboard inputs for movement and game state.
- **Basic Physics Simulation**: Ball direction and collision logic.
- **Randomization**: Ball speed and stone colors.


## Technologies Used:

| Technology | Purpose                        |
|------------|--------------------------------|
| Python     | Core programming language      |
| Tkinter    | GUI and canvas-based rendering |
| OOP        | Game structure and logic       |
| Lists      | Handling stone grid            |
| Random     | Random speed & color generation |



## How It Works:

- The game initializes with a paddle at the bottom and multiple rows of colored stones.
- A ball is released and starts bouncing.
- When the ball hits a stone, the stone disappears and score increases.
- The game ends when:
  - All stones are destroyed → **"YOU WON!"**
  - The ball touches the bottom of the canvas → **"GAME OVER!"**

