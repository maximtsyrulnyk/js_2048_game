# 2048 Game

2048 is a classic puzzle game implemented in vanilla JavaScript.
The goal of the game is to combine tiles with the same values to reach the 2048 tile.

The project focuses on game logic, state management, keyboard controls, and DOM rendering without using external frameworks.

## Live Preview
https://maximtsyrulnyk.github.io/js_2048-game/

## Repository
https://github.com/maximtsyrulnyk/js_2048_game

## Technologies Used

- JavaScript (ES6+)
- HTML
- CSS
- OOP (class-based architecture)
- DOM manipulation

## Getting Started

Clone the repository:

```bash
git clone https://github.com/your-username/2048-game.git
cd 2048-game
````

Open the project locally:
```
open index.html
````
Or run it using a local server (recommended).

## Features

### • Classic 2048 gameplay
Implements the original 4×4 grid gameplay with tile merging rules identical to the classic 2048 game.

### • Keyboard controls
The game is fully controlled using keyboard arrow keys:
- ArrowLeft
- ArrowRight
- ArrowUp
- ArrowDown

### • Game state management
The game tracks:
- Current board state
- Score
- Game status (idle, playing, win, lose)

### • Score calculation
Scores are dynamically updated based on merged tile values.

### • Win and lose detection
The game automatically detects:
- Win condition when a 2048 tile is reached
- Lose condition when no moves are available

### • Restart functionality
Players can restart the game at any time using the Start / Restart button.

### • Random tile generation
After each valid move, a new tile (2 or 4) is added to a random empty cell.

### • Clean architecture
Game logic is separated into a dedicated Game class, keeping rendering and input handling decoupled from core logic.
