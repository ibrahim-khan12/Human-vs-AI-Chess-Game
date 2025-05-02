# ♟️ Human vs AI Chess Game

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)

A simplified **Chess game** implemented in Python, featuring a **Human vs AI** mode. The AI opponent uses the **Minimax algorithm with Alpha-Beta Pruning** to make strategic decisions. The game includes a fully interactive **Graphical User Interface (GUI)** built using Tkinter and supports all essential chess mechanics including legal moves, capturing, check, and checkmate detection.

---

## 📌 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Usage](#usage)
- [System Design](#system-design)
- [Minimax & Alpha-Beta Pruning](#minimax--alpha-beta-pruning)
- [Screenshots](#screenshots)
- [Development](#development)
- [Contributors](#contributors)
- [License](#license)

---

## 📖 Overview

This project demonstrates a fully playable chess game between a human and an AI. The AI evaluates the game state using the **Minimax algorithm**, enhanced with **Alpha-Beta Pruning** for improved performance. The GUI built with `tkinter` offers intuitive controls and visual feedback to make gameplay smooth and interactive.

---

## ✨ Features

- ✅ Human vs AI mode
- ✅ Tkinter-based graphical user interface
- ✅ Legal move enforcement for all standard chess pieces
- ✅ Check and checkmate detection
- ✅ Move highlighting for selected pieces
- ✅ Real-time board updates and user interaction
- ✅ Efficient AI using Minimax + Alpha-Beta pruning
- ✅ Material-based evaluation function

---

## 🧰 Technology Stack

- **Language**: Python 3.8+
- **GUI Library**: Tkinter
- **Algorithm**: Minimax Search with Alpha-Beta Pruning
- **Design Pattern**: Object-Oriented Programming

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/ibrahim-khan12/human-vs-ai-chess.git
cd human-vs-ai-chess
```
## ▶️ Usage
- You (the human) will play as White.
- The AI will play as Black.
- Click on a piece to see its possible moves.
- Click a valid square to move your piece.
- The AI will respond immediately after your move.

## 🧱 System Design
🧩 Key Components
- Board: Manages the state of the game, piece locations, and rules.
- Piece Classes: Each chess piece (Pawn, Knight, Rook, etc.) has its own class with movement logic.
- AI: Computes the best possible move using Minimax with Alpha-Beta Pruning.
- GUI: Renders the chessboard, processes user interaction, and displays game status.

# 🔄 Game Flow
-Human selects and moves a piece.
- Game engine checks for legal moves, check, or checkmate.
- AI processes the move and responds.
- GUI updates the board state visually.
- Repeat until checkmate or draw.

## 🧠 Minimax & Alpha-Beta Pruning
- The AI uses a recursive Minimax function to simulate future game states and determine the optimal move.
- Alpha-Beta Pruning cuts off unneeded branches in the decision tree, improving performance drastically.
- Evaluation Function is based on:
Material advantage (pawn = 1, knight = 3, bishop = 3, rook = 5, queen = 9)
- Simple checkmate scoring
## 👥 Contributors
This project was developed as part of an academic AI and Game Theory project.
- Ibrahim Khan 

# 📄 License
This project is licensed under the MIT License.
See the LICENSE file for details.

© 2025 Human vs AI Chess Game. All rights reserved.

