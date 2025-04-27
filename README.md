
# Tic-Tac-Toe AI with Minimax and Alpha-Beta Pruning

This project implements a Tic-Tac-Toe game where you can play against an unbeatable AI using the **Minimax algorithm**, and an optimized version using **Alpha-Beta Pruning**.

Even though the gameplay appears similar (since Tic-Tac-Toe is a small game tree), Alpha-Beta Pruning significantly improves the efficiency internally.

## 🎥 Demo Videos

> Note: Visual differences are subtle due to the small search space of Tic-Tac-Toe.  
> However, Alpha-Beta Pruning dramatically improves speed in deeper search trees.

## ✨ Features

- Human vs AI gameplay.
- Two modes:
  - **Minimax** (complete search).
  - **Minimax with Alpha-Beta Pruning** (optimized search).
- Clear console-based interface.
- Proper error handling for invalid moves.

## 🧠 Algorithms Overview

- **Minimax Algorithm:**  
  Explores all possible future moves to ensure the AI plays optimally.

- **Alpha-Beta Pruning:**  
  Skips unnecessary branches in the search tree, improving the AI’s move calculation speed.

## 📂 File Structure

```
├── Minimax.py               # Basic Minimax version
├── Minimax Alpha-Beta prunning.py     # Alpha-Beta Pruning optimized version
├── Demo Videos.rar               #Two demo videos showcasing the gameplay of each algorithm.
├── README.md                 # This file
```


## 🚀 Future Improvements

- Add a difficulty setting.
- Add a GUI using Pygame or Tkinter.
- Extend to a 4x4 Tic-Tac-Toe (connect-4 style).
