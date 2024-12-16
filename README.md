# Tic-Tac-Toe Game

## Overview
This is a simple Tic-Tac-Toe game implemented using HTML, CSS, and JavaScript. The game supports two players and includes functionality for detecting winners and game draws.

---

## Features
- **Player Turns:** Players alternate turns, marking `X` or `O` on the grid.
- **Win Detection:** Checks for winning patterns after each move.
- **Draw Detection:** Declares the game as a draw if all boxes are filled and no player has won.
- **Reset Game:** Players can reset the game at any time or start a new game after a win or draw.

---

## File Structure
### `index.html`
The main HTML file contains the structure for the game:
- A 3x3 grid represented as buttons.
- Reset and New Game buttons.
- A message container to display the game outcome.

### `style.css`
Provides styling for:
- The game layout and buttons.
- The message container for winner or draw announcements.

### `app.js`
Handles the game logic and interactivity:
- Tracks player turns.
- Disables already selected boxes.
- Checks for winners and draws.
- Resets the game state.

---

## How to Use
1. Open `index.html` in a web browser.
2. Players take turns clicking on the boxes to mark their symbol (`X` or `O`).
3. The game will declare a winner if a player forms a row, column, or diagonal.
4. If all boxes are filled without a winner, the game declares a draw.
5. Use the **Reset Game** button to clear the grid and play again.
6. Use the **New Game** button to start a new match after a win or draw.

---

## Winning Patterns
The game detects the following winning combinations:
- **Rows:** Top, middle, and bottom rows.
- **Columns:** Left, middle, and right columns.
- **Diagonals:** Top-left to bottom-right and top-right to bottom-left.

---

## Dependencies
No external libraries or frameworks are required. The game uses:
- JavaScript for logic.
- HTML and CSS for structure and styling.

---

## Future Improvements
- Add AI for single-player mode.
- Enhance UI with animations or themes.
- Include a scoreboard to track wins and draws.

---

## Author
This Tic-Tac-Toe game is developed as a learning project to practice JavaScript and web development skills.

