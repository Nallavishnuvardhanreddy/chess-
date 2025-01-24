# chess-
# Chess Game

A browser-based chess game implementation using JavaScript, offering an interactive and modular design with reusable components for gameplay rendering and events. The project leverages `deepcopy` for handling deep cloning operations in the global game state.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [How It Works](#how-it-works)
- [Contributing](#contributing)
- [License](#license)

---

## Features

- **Interactive Chess Gameplay**: Full chessboard rendered dynamically in the browser.
- **Event Handling**: Modular global event system for gameplay interactions.
- **Reusable Components**: Clean and reusable code for game initialization, rendering, and events.
- **State Management**: Global game state managed with utilities for performance optimization.
- **Modern JavaScript**: Leveraging ES6+ features for clean and maintainable code.

---
How It Works
Game Initialization:

initGame() initializes the global game state with a matrix of squares representing the board.
Rendering:

initGameRender() dynamically generates the chessboard and positions the pieces in their starting positions.
Event Handling:

GlobalEvent() manages user interactions (e.g., moving pieces).
Utilities:

Custom String.prototype.replaceAt() method to modify strings in the game logic.
