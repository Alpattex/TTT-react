# Tic-Tac-Toe Game using React

This is a simple Tic-Tac-Toe game built using React. Below, you'll find an overview of the code structure and functionality.

## Overview



### Files
1. **TicTacToe.js**
   - Main component that manages the game state and logic.
2. **Square.js**
   - Component representing individual squares on the game board.
3. **EndGame.js**
   - Component displaying the end game screen with the result and a button to start a new game.
4. **App.js**
   - Main entry point where the `TicTacToe` component is rendered.

### Game Logic
- The game board is represented by a 1-dimensional array of length 9, initialized with empty values.
- Players take turns to click on squares, and their moves are reflected in the game state.
- The game checks for a win or draw after each move and displays the result when the game is finished.
- The `EndGame` component allows the player to start a new game.

## How to Run

1. Clone the repository.
2. Install dependencies using `npm install`.
3. Run the application with `npm start`.

Feel free to explore and modify the code to enhance your understanding of React and game development.

## Additional Features (Future Improvements)
- Multiplayer functionality.
- Animation for a more interactive user experience.
- Enhanced styling for a visually appealing interface.
