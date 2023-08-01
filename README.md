## Readme - 2048 Game

---

## Github Repo: https://github.com/YonisJ/2048

## Link to game: https://yonisj.github.io/2048/

## 1. The Challenge

### 1a. Understanding the Task

The task at hand is to construct an internet-based edition of the game "2048" utilising HTML, CSS and JavaScript. This game is centred around moving tiles on a grid to merge them and craft a tile displaying the number 2048.

### 1b. Early Plan and Strategy

My approach is to fashion the game with object-oriented JavaScript, enclosing related operations within classes and managing the code with ES6 modules. I'll gradually expand the game, initially focussing on the grid and tile movement, then introducing the game logic. I aim to create well-explained, easy-to-read code, uphold best practices, and regularly conduct code assessments to guarantee code quality.

### 1c. Breakdown of the Task into Main Components

I've recognised the following primary tasks:

1. Establishing the game board
2. Instituting tile movement
3. Enacting game logic
4. Garnishing the game
5. Examination and bug resolution

### 1d. Initial Design Ideas and Phase Division

The game will contain three central classes: `Grid`, `Cell`, and `Tile`. The `Grid` class oversees the game board, `Cell` class handles each cell on the board, and `Tile` class regulates the game tiles.

---

## 2. Crafting the Game

### 2a. Adherence to Good Coding Standards

Throughout the creation process, I committed to maintain high coding standards, writing clean, understandable and modular code, and leveraging JavaScript's OOP capabilities efficiently.

### 2b. Phase 1: Tasks, Code Assessment and Adjustments

Phase 1 comprised setting up the basic HTML structure and initiating the game board in JavaScript. The `Grid` and `Cell` classes were developed during this phase. I continuously assessed the code to verify its effectiveness and alignment with the requirements.

### 2c. Phase 2: Tasks, Code Assessment and Adjustments

Phase 2 involved creating the `Tile` class and establishing tile movement. I reviewed the code to guarantee proper utilisation of classes and methods, and to confirm the tile movement functioned accurately.

### 2d. Phase 3: Tasks, Code Assessment and Adjustments

Phase 3 was dedicated to integrating the game logic, which included merging tiles and generating new ones. I ran code reviews to confirm the successful and efficient implementation of game logic.

### 2e. Ensuring Quality Through Testing and Debugging

I conducted extensive tests throughout the development, rectifying bugs as they appeared. The final product was also rigorously tested to ensure all functions performed as expected.

### 2f. Reflection on Major Design Challenges and Solutions

Implementing tile movement and combination posed a challenge. I tackled this by meticulously tracking each tile and cell's status, using this information to manage the movement and merging of tiles.

---

## 3. Evaluation

### 3a. Analysis of Code Refactoring and Reuse

Throughout the development, I regularly reviewed the code to pinpoint any code smells or areas needing improvement. For instance, I spotted repeated code for moving tiles in various directions, and refactored this into a shared function to enhance code reuse and readability.

### 3b. Utilisation of Advanced Programming Principles

Throughout the creation, I utilised advanced programming principles effectively, such as object-oriented programming, encapsulation, and ES6 modules, making the code more orderly, readable, and maintainable.

### 3c. Feature Highlight and Innovations

A noteworthy feature of this game is the smooth animation of the tiles, achieved with CSS transitions.

### 3d. Improvement of Algorithms – Research, Design, and Implementation

Throughout the creation, I researched and implemented efficient algorithms for handling the game logic. For example, I used a capable algorithm to identify the available moves and to combine the tiles.

### 3e. Reflective Review and Future Improvement Opportunities

I'm generally content with the final product, but I acknowledge there's always space for enhancement. For future projects, I plan to utilise automated testing more, ensuring every element of the game operates as expected. I also aim to continue learning and refining my JavaScript and general programming skills. One specific area of improvement could be the handling of the game's lose state – it might be more engaging if it were addressed in a more innovative way than simply an alert. Also, the only way to currently restart the game is to refresh the page, this could be handled better in the future by adding a "restart game" button once the player has lost.
