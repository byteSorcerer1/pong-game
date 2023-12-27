# Pong Game using HTML5 Canvas and JavaScript

This repository contains a simple implementation of the classic Pong game using HTML5 Canvas and JavaScript. The game features a responsive design and utilizes the React component structure.

## Getting Started

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/byteSorcerer1/pong-game.git
    ```

2. Open the `index.html` file in your web browser to play the game.

## Game Controls

- Move the user paddle up and down by moving the mouse within the game window.

## Game Rules

- The objective is to score points by hitting the ball past the opponent's paddle.
- The game keeps track of scores for both the user and the computer opponent.
- The ball's speed increases with each successful hit, providing an additional challenge.

## Code Structure

- The main game logic is implemented in the `gameLoop` function, which updates and renders the game at 60 frames per second.
- Paddle and ball objects are created using the `createPaddle` and `createBall` functions, respectively.
- Collision detection is handled by the `collision` function, ensuring accurate ball and paddle interactions.

## Screenshots

![Game Screenshot](screenshot.jpg)

## Acknowledgments

This project was created as a part of the React course at MEGA Software Academy. Feel free to explore the code, make improvements, or customize it to suit your preferences.

If you have any suggestions or questions, please don't hesitate to reach out. Happy gaming!

---

**GitHub Repository:** [byteSorcerer1/pong-game](https://github.com/byteSorcerer1/pong-game)
