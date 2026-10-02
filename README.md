# 🎮 AI-Based Tic-Tac-Toe

A Python-based Tic-Tac-Toe game where a human player competes against an AI opponent using the **Minimax algorithm** for decision-making.

## 🚀 Run in Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/ai-tic-tac-toe/blob/main/Tic_Tac_Toe_Minimax.ipynb)

> Replace `YOUR_USERNAME` with your GitHub username.

## 📌 Project Overview

This project implements an AI-based Tic-Tac-Toe game using Python.

The human player competes against an AI opponent. The AI uses the **Minimax algorithm** to evaluate possible game states and select an optimal move.

The project includes board management, player input, AI decision-making, win detection, draw detection, input validation, multiple rounds, and score tracking.

## 🎯 Objective

The main objective of this project is to understand how an AI agent can make decisions by evaluating possible future game states.

### Key Objectives

- Implement a Tic-Tac-Toe game in Python
- Create a human-vs-AI gameplay system
- Implement the Minimax algorithm
- Evaluate possible future game states
- Enable AI-based decision making
- Detect wins and draws
- Track player and AI scores

## 🛠️ Technologies Used

- Python
- Minimax Algorithm
- Recursion
- Backtracking
- Game Tree Search
- Command-Line Interface (CLI)

## ⚙️ How the Game Works

1. A 3×3 Tic-Tac-Toe board is created.
2. The human player uses **X**.
3. The AI player uses **O**.
4. The human selects an available position.
5. The game checks for a win or draw.
6. The AI evaluates available moves using Minimax.
7. The AI selects its move.
8. Turns continue between the player and AI.
9. The game ends when a player wins or the board is full.
10. The scoreboard is updated.
11. The player can start another round.

## 🧠 Minimax Algorithm

The **Minimax algorithm** is a decision-making algorithm commonly used in two-player games.

In this project:

- **AI (`O`)** acts as the maximizing player.
- **Human (`X`)** acts as the minimizing player.
- An AI win receives a positive score.
- A human win receives a negative score.
- A draw receives a score of zero.

The algorithm recursively evaluates possible future moves and selects the move with the best possible outcome for the AI.

## 🤖 AI Decision-Making

For each available move, the AI:

1. Temporarily places `O` on the board.
2. Evaluates the resulting game state.
3. Recursively explores possible future moves.
4. Calculates a Minimax score.
5. Reverts the temporary move.
6. Compares available moves.
7. Selects the move with the highest score.

## ✨ Key Features

- Human vs AI gameplay
- Minimax-based AI
- Recursive game-tree evaluation
- Automatic winner detection
- Draw detection
- Valid move checking
- Invalid input handling
- Multiple game rounds
- Scoreboard tracking
- Replay functionality
- Command-line interface

## 🧪 Example Gameplay

```text
New Round! You are 'X' and AI is 'O'.

 1 | 2 | 3
---+---+---
 4 | 5 | 6
---+---+---
 7 | 8 | 9

Enter your move (1-9): 5

AI is calculating the optimal move...
