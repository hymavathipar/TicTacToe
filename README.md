# Tic Tac Toe Game

This is a simple **Tic Tac Toe** game built using **JavaScript**, **HTML**, and **CSS**. The game allows two players to take turns marking spaces on a 3x3 grid with their respective marks ("X" and "O"). The game tracks the score of both players and determines the winner or if the game ends in a draw. Players can replay the game or start a new one, and the score is displayed after each round.

---

## Features:
- **Two-player Mode**: Players alternate placing "X" and "O" on the grid.
- **Win Detection**: The game automatically detects a win when a player aligns three marks in a row, column, or diagonal.
- **Draw Detection**: If all cells are filled and no player wins, the game detects a draw.
- **Score Tracking**: The scores for Player X and Player O are displayed after each round.
- **Replay and New Game Options**: After a round, players can either replay the game or start a new game, which resets the board and the scores.
  
---

## How to Play:
1. **Start the Game**: Open the `index.html` file in your web browser to begin playing.
2. **Player Turns**: Player **X** always starts. Each player clicks on an empty cell to place their mark on the grid.
3. **Game Result**: After a player wins, the game highlights the winning cells and displays a message. If the grid is filled with no winner, the game declares a draw.
4. **Replay or New Game**: After each round, players can either click the **"Replay"** button to play the same game again or click **"New Game"** to reset both the board and the scores.

---

## Technologies Used:
- **HTML**: Used for the structure of the game, including the grid, scorecard, and control buttons.
- **CSS**: Styles the game grid, buttons, and layout, ensuring the game is responsive across different devices.
- **JavaScript (Vanilla)**: Implements the game logic, including turn handling, win/draw detection, and score updates. This project uses **pure vanilla JavaScript**, meaning no external libraries or frameworks are used.

---

## How to Run:
1. **Clone the Repository**:
    - To clone the repository, run the following command:
    ```bash
    git clone https://github.com/your-username/TicTacToeGame.git
    ```

2. **Open the Game**:
    - Navigate to the `TicTacToeGame` folder and open the `index.html` file in your browser to start playing.

3. **Start Playing**:
    - The game will begin, and you can start by clicking on the cells of the grid. Player **X** starts first, and players alternate placing their marks.

4. **Replay the Game**:
    - After a round ends, click **"Replay"** to replay the game with the current score.

5. **Start a New Game**:
    - Click **"New Game"** to reset the board and the scores.

---

---

## Game Logic Explanation:
- **Turn Alternation**: Players alternate between Player **X** and Player **O**, clicking on the empty cells to place their marks.
- **Win Conditions**: The game checks for a win after every move by verifying if any row, column, or diagonal has three of the same marks.
- **Draw Detection**: The game checks if all cells are filled and if no winner is found, declaring a draw.
- **Score Updates**: The score for the winning player is updated after each game, and the highest score is displayed.
- **Replay/New Game**: Players can either replay the current game or start a new game, which resets the board and scores.

---

## Features to be Added:
- **AI Opponent**: Implement an AI opponent for single-player mode.
- **Multiple Themes**: Provide options for players to choose from different visual themes for the game.
- **Leaderboard**: Implement a leaderboard to show the highest score across multiple game sessions.

---

## Demo Video:
You can view a video demonstration of the game [https://drive.google.com/file/d/16baP_Qpo48OYXqTXhs4XdhZxRcd3xd5U/view?usp=sharing](insert-your-link-to-video).

---

## Conclusion:
This **Tic Tac Toe** game is a simple, interactive web-based game built using ** JavaScript**. It allows two players to play against each other, automatically tracks the score, and provides replay and new game functionality. The game is lightweight, easy to understand, and serves as a great learning project for mastering core web development skills.





