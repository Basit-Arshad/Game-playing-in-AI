# Game Playing in AI

An AI project that demonstrates how intelligent agents solve games and optimization problems using **Adversarial Search**, **Local Search**, and **Heuristic Evaluation Functions**. This repository contains implementations of **Tic-Tac-Toe**, **Checkers**, and the **8-Queens Problem** using Python and Jupyter Notebooks.

## Project Overview

This project explores different AI techniques used in game-playing systems and optimization problems. It focuses on how agents make intelligent decisions using search algorithms, heuristics, and performance evaluation. The repository includes interactive notebooks that demonstrate both competitive game AI and local search problem solving.

## Implemented Games and Algorithms

### 1. Tic-Tac-Toe
This notebook implements a **4x4 Tic-Tac-Toe** game where the AI plays using:
- **Minimax**
- **Alpha-Beta Pruning**

It also compares performance using:
- nodes explored
- execution time
- search depth

### 2. Checkers
This notebook implements a playable **Checkers** game with human-vs-AI interaction.  
The AI supports:
- **Minimax**
- **Alpha-Beta Pruning**

The implementation includes:
- move generation
- heuristic board evaluation
- game-over detection
- performance comparison through plots

### 3. 8-Queens Problem
This notebook solves the **8-Queens Problem** using local search methods:
- **Hill Climbing**
- **Simulated Annealing**
- **Local Beam Search**

It compares algorithms based on:
- number of iterations
- remaining conflicts
- convergence behavior

## Tech Stack

- **Python**
- **Jupyter Notebook**
- **NumPy**
- **Pygame**
- **Matplotlib**

## Features

- Interactive board-based gameplay
- AI vs Human gameplay in Checkers
- Adversarial search using Minimax and Alpha-Beta Pruning
- Local search visualization for 8-Queens
- Heuristic-based AI decision making
- Performance tracking and comparison using graphs

## Repository Structure

```bash
Game-playing-in-AI/
│── 8_queen.ipynb
│── checkers.ipynb
│── tic_tac_toe.ipynb