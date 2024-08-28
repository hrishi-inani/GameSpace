# GameSpace

Welcome to GameSpace! This is a web-based gaming platform offering a variety of classic games, each enhanced with advanced algorithms and optimized for an engaging user experience.

## About the Project

GameSpace currently includes five games:

- **Chess**
- **Tic-Tac-Toe**
- **Sudoku**
- **2048**
- **Minesweeper**

Each game comes with multiple difficulty modes (Easy, Medium, Hard), providing a challenging experience for users of all skill levels. One of the main goals of this project was to explore algorithms used in decision-making and optimization in game theory. The **minimax** algorithm is used in both the chess and tic-tac-toe games.

![Overview](https://github.com/user-attachments/assets/f2519290-0c03-42f2-afe3-646b0af46974)

## Overview of the Website

- **User Authentication:** Users can sign in or sign up.
- **Game Modes:** Player-vs-computer mode for all games.
- **Instructions:** Each game comes with brief instructions.
- **Unique Features:** 
  - Chess engine and Sudoku solver built from scratch.
  - Unbeatable Tic-Tac-Toe using the minimax algorithm.
  - Multiplayer functionality for chess using websockets.
- **Blog Section:** A platform for posting updates about the website and general topics.

## Game Details

### 1. Chess
- Implemented a chess engine using the minimax algorithm, achieving an Elo rating close to 1800.
- Offers three difficulty levels: Easy, Medium, and Hard.
- Additional analysis mode for in-depth game review.
- Features include move-history, move-back, and new game options.
- Supports online multiplayer using websockets.

![Chess Screenshot](https://github.com/user-attachments/assets/42b03f61-aad1-4cee-a96f-1bc0080b65fc)

### 2. Tic-Tac-Toe
- Includes Easy, Medium, and Hard (unbeatable) modes.
- Players can choose between X and O.
- The unbeatable mode is implemented using the minimax algorithm.

![Tic-Tac-Toe Screenshot](https://github.com/user-attachments/assets/77fc5bbb-5c32-4392-8856-37967ad05ea7)

### 3. Sudoku
- Three difficulty levels: Easy, Medium, Hard.
- Built-in Sudoku solver using backtracking.
- Optimized user interface for a smooth experience.

![Sudoku Screenshot](https://github.com/user-attachments/assets/73ec4c94-21e3-4495-a0bb-30ffcaed9ca2)

### 4. 2048
- A fun and engaging puzzle game implemented using JavaScript.

![2048 Screenshot](https://github.com/user-attachments/assets/76597427-a154-4e1c-88ee-5de31928b502)

### 5. Minesweeper
- Classic puzzle game reminiscent of the old Windows version.
- Use logic and strategy to avoid the mines.

![Minesweeper Screenshot](https://github.com/user-attachments/assets/d5ef202c-e39f-4185-95ec-afd92a073883)

## To-Do List

- Add personal profile pages for users to view their stats (highest score, winning streak, etc.).
- Implement personal messaging for individual users.
- Include more games to expand the gaming experience.

## How to Host the Website Locally

To run the project locally, ensure you have the latest version of Node.js installed. Follow these steps:

```bash
$ git clone https://github.com/hrishi-inani/GameSpace.git
$ cd GameSpace
$ npm install
$ npm start
