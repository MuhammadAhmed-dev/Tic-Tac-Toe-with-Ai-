# Tic-Tac-Toe AI with Minimax and Alpha-Beta Pruning

This project implements a Tic-Tac-Toe game where you can play against an unbeatable AI using the **Minimax algorithm**, and an optimized version using **Alpha-Beta Pruning**.

Even though the gameplay appears similar (since Tic-Tac-Toe is a small game tree), **Alpha-Beta Pruning** significantly improves the efficiency of the AI by reducing the number of nodes evaluated during the search.

---

## 🎥 Demo Videos

Note: The visual differences between the two demos are subtle due to the small search space of Tic-Tac-Toe. However, the output clearly shows the number of nodes evaluated during the search.
Alpha-Beta Pruning significantly reduces the number of nodes evaluated, improving performance. The difference is more pronounced when the search tree becomes larger (in more complex games).

---

## ✨ Features

- Human vs AI gameplay.
- Two AI modes:
  - **Minimax** (standard, exhaustive search).
  - **Minimax with Alpha-Beta Pruning** (optimized search).
- Console-based interface showing AI decisions and iterations.
- Error handling for invalid moves.

---

## 🧠 Algorithms Overview

- **Minimax Algorithm:**  
  Explores all possible future moves and selects the optimal move for the AI.

- **Alpha-Beta Pruning:**  
  Optimizes the Minimax algorithm by pruning branches of the search tree that do not affect the final decision, improving speed.

---

## 📂 File Structure

```
├── minimax.py               # Basic Minimax version
├── minimax_alpha_beta.py     # Alpha-Beta Pruning optimized version
├── Demo_videos.rar           # The Demo videos for gameplay and output
├── README.md                 # This file
```

---

## 🚀 Future Improvements

- Add adjustable difficulty levels.
- Create a GUI using Pygame or Tkinter.
- Extend the game to larger grids, e.g., 4x4 Tic-Tac-Toe or Connect-4 style.

---

## Video Link🔗

https://www.youtube.com/watch?v=iVSdKNcXpHs&ab_channel=ZohaibKhan
