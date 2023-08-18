# Tic-Tac-Toe-AI
Tic-Tac-Toe AI with minimax alogorithm using pygame module of python.

This is a simple implementation of the classic game Tic-Tac-Toe using the Pygame library, with an AI opponent that uses the Minimax algorithm to make optimal decisions.

## Introduction

Tic-Tac-Toe is a two-player game where players take turns marking a cell in a 3x3 grid with their designated symbol (usually "X" and "O"). The goal is to have three of your symbols in a row, either horizontally, vertically, or diagonally.

In this implementation, you can play against an AI opponent that employs the Minimax algorithm, which guarantees optimal gameplay by evaluating all possible moves and selecting the best one.

## Requirements

To run this program, you'll need:

- Python
- Pygame library

## Installation

1. Clone or download this repository to your local machine.
2. Make sure you have Python installed.
3. Install the Pygame library using pip:
   
   ```bash
   pip install pygame
   ```

## Usage

1. Navigate to the directory where you've cloned/downloaded the repository.
2. Open a terminal/command prompt and run the following command:

   ```bash
   python tictactoe.py
   ```

3. Select the game by pressing (1) for player vs player,
    press (2) to play with a AI that choses moves randomly,
    press (3) to play with AI that uses minimax algorithm to make moves effieciently,
    or press (Q) to quit.

4. The game window will open. You can start playing against the AI by clicking on an empty cell.

## Algorithm Explanation

The AI opponent uses the Minimax algorithm to determine the best move it should make in order to win or at least tie the game. The algorithm recursively explores all possible game states by simulating moves for both players and assigning a score to each state. Positive scores are assigned when the AI is winning, negative scores for the player, and a score of 0 for a tie.

The AI selects the move with the highest score when it's the AI's turn, and the move with the lowest score when it's the player's turn. This ensures that the AI will either win or force a draw if both players play optimally.

