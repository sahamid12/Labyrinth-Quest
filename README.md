
# Labyrinth Quest JS

## Overview

**Labyrinth Quest JS** is an immersive, physics-based maze navigation game built with JavaScript and Matter.js. In this game, players control a sphere through a dynamically generated maze, aiming to reach a designated endpoint. The game challenges players with interactive physics simulations that enhance the gameplay experience through realistic motion and collisions. This project demonstrates the effective use of web technologies to create engaging, interactive applications.

## Features

- **Dynamic Maze Creation**: Every game loads with a newly generated maze, ensuring a unique challenge using a depth-first search algorithm.
- **Physics-Driven Gameplay**: Incorporating Matter.js, the game simulates real physics for object movements and interactions, including collisions and object control.
- **Interactive Controls**: Players use keyboard inputs to navigate the maze, enhancing the interactive experience with intuitive movement controls.
- **End Game Celebrations**: Upon reaching the goal, the maze reacts by becoming non-static, simulating a 'collapse' for a satisfying visual finale.
- **Sleek UI Design**: The game sports a minimalist design, allowing players to focus entirely on the maze and gameplay without unnecessary distractions.

## Technologies Used

- **Matter.js**: A robust 2D physics engine for the web.
- **HTML5**: For structuring the content of the game.
- **CSS3**: Used to style the game environment and ensure responsiveness.
- **JavaScript**: Drives the core game functions and event handling.

## Getting Started

To run **Labyrinth Quest JS**, follow these steps:

1. Clone the GitHub repository to your local machine.
2. Navigate to the project directory.
3. Open `index.html` in a web browser of your choice.
4. Use the arrow keys to start navigating through the maze.

## Sample Code Snippet

```javascript
// Setup engine and renderer
const engine = Engine.create();
const { world } = engine;
const render = Render.create({
    element: document.body,
    engine: engine,
    options: {
        wireframes: false,
        width: window.innerWidth - 3.5,
        height: window.innerHeight - 3.5
    }
});
