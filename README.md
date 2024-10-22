# Tic Tac Toe Game

A simple **Tic Tac Toe** game built using **HTML**, **CSS**, and **JavaScript**. The game allows two players to take turns placing "O" and "X" in a 3x3 grid, with the goal of aligning three symbols in a row to win.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [How to Play](#how-to-play)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [License](#license)

## Features

- **Two-player mode**: Take turns playing as "O" and "X".
- **Winning detection**: The game automatically detects when a player wins or if the game is a draw.
- **New Game and Reset Game**: Start a new game or reset the current game at any time.
- **Responsive Design**: Works on various screen sizes (desktop, tablet, and mobile).

## Technologies Used

- **HTML5**: Markup for structuring the game.
- **CSS3**: Styling the game elements and ensuring responsiveness.
- **JavaScript**: Game logic and interactivity (handling clicks, checking for winners, etc.).

## How to Play

1. The game is played on a 3x3 grid.
2. The first player places an "O", and the second player places an "X".
3. Players take turns marking empty spaces.
4. The first player to align three of their marks (either horizontally, vertically, or diagonally) wins.
5. If all 9 boxes are filled without a winner, the game ends in a draw.

You can use the "Reset" button to clear the board and start over, or the "New Game" button to start a new round after a winner is announced.

## Project Structure

```plaintext
TicTacToe/
│
├── index.html           # HTML structure of the game
├── style.css            # CSS file for game styling
├── app.js               # JavaScript file containing game logic
└── README.md            # This file (Project description)
