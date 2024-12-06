# Tic Tac Toe Game with Persistent Score Tracking

This is a simple **Tic Tac Toe** game built with **vanilla JavaScript**, **HTML**, and **CSS**. It allows two players to take turns marking spaces on a 3x3 grid with their respective marks ("X" and "O"). The game tracks the score of both players and uses **localStorage** to persist the scores even after the page is refreshed or reopened.

---

## Features:
- **Two-player Mode**: Players alternate turns placing "X" and "O" on the grid.
- **Win and Draw Detection**: Automatically detects if a player wins (by aligning three marks in a row, column, or diagonal) or if the game ends in a draw (all cells filled without a winner).
- **Persistent Scores**: The scores of Player X and Player O are saved using **localStorage**. The scores persist even if the page is refreshed or the browser is closed and reopened.
- **Replay and New Game Options**: After a round, players can choose to **replay** the current game (keeping the scores) or start a **new game** (which resets the board and the scores).
- **Highest Score Tracking**: Tracks and displays the highest score (the player with the most wins).

---

## How to Play:
1. **Start the Game**: Open the `index.html` file in a web browser.
2. **Player Turns**: Player **X** always goes first. Players take turns clicking on an empty cell in the 3x3 grid to place their mark.
3. **Game Result**: After a player wins, the game highlights the winning cells and displays a congratulatory message. If the grid is filled and there’s no winner, the game declares a draw.
4. **Replay or New Game**: After a round ends, click **"Replay"** to replay the game (keeping the scores), or click **"New Game"** to reset the board and scores.

---

## Technologies Used:
- **HTML**: Used for the structure of the game grid, scorecard, and buttons.
- **CSS**: Styles the grid, buttons, and layout, ensuring the game is responsive on different screen sizes.
- **JavaScript**: Handles the game logic including turn tracking, win detection, score updates, and localStorage functionality. The game uses **vanilla JavaScript** (no external libraries or frameworks).

---

## How to Run:
1. **Clone or Download** the repository:
    ```bash
    git clone https://github.com/your-username/TicTacToeGame.git
    ```

2. **Open the game**:
    - Navigate to the `TicTacToeGame` folder and open the `index.html` file in your browser.

3. **Play**:
    - The game will start, and you can begin playing by clicking on the cells of the grid. Player X starts first.
    - The scores will be updated automatically after each round, and the highest score will be tracked.
    
---

---

## Game Logic Explanation:
- **Turn Alternation**: The game alternates between Player X and Player O. When a player clicks on an empty cell, their mark is placed in that cell.
- **Win Detection**: The game checks if a player has won after every move by verifying if any row, column, or diagonal has three of the same marks.
- **Draw Detection**: If all cells are filled and no player has won, a draw is declared.
- **Score Updates**: After each game, the score of the winning player is updated. The highest score is also tracked and displayed.
- **localStorage**: The scores for Player X and Player O are stored in **localStorage** so that they persist across page reloads.

---

## Features to be Added:
- **AI Opponent**: Implement an AI opponent for single-player mode.
- **Multiple Themes**: Add visual themes that players can choose from.
- **Leaderboard**: Implement a leaderboard to track the highest scores over multiple sessions.

---

## Demo Video:
You can view a video demonstration of the game [here](insert-your-link-to-video).

---

## Conclusion:
This project is a complete **Tic Tac Toe** game using **vanilla JavaScript**, allowing for two-player gameplay with persistent score tracking. It is lightweight, easy to modify, and provides a solid foundation for learning core web development concepts like DOM manipulation, event handling, and localStorage usage.

Let me know if you need any help or further explanations!


