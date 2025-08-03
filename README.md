# ♟️ Chess-Sudoku Hybrid Game

A two-player turn-based game blending the logic of chess threats with Sudoku-style placement rules — designed for fun and strategic competition on an 8×8 chessboard grid.

---

## 🎮 How to Play

- The game is played on a standard **8x8 grid**.
- Two players take turns **placing chess pieces** (King, Queen, Rook, Bishop, Knight, Pawn) on empty squares.
- A player **cannot place a piece in a square that is threatened** by any of the opponent's previously placed pieces.

---

## 🔁 Turn Rules

- **Player 1** starts first and places one piece.
- Then **Player 2** places one of their pieces.
- This continues until either:
  - One player **places all 8 pieces legally**, or
  - **All 64 squares are filled**, or
  - A player **submits defeat** using the “End Game” button.

---

## ⚔️ Threat Rules

- A piece cannot be placed on a square that is **under threat** by an opponent's piece.
- Threat rules follow standard chess logic:
  - 🧙 Queen – All directions
  - ♖ Rook – Rows & columns
  - ♗ Bishop – Diagonals
  - ♘ Knight – L-shapes
  - ♔ King – One square in any direction
  - ♙ Pawn – No threat logic (passive piece)

---

## ⚖️ Piece Limits

Each player can place:
- **1 King**
- **1 Queen**
- **2 Rooks**
- **2 Bishops**
- **2 Knights**
- **Pawns** are **only allowed** after 16 total pieces have been placed on the board.

Attempts to place more than allowed will result in an error popup.

---

## 🏁 Win Conditions

A player **wins** if:
1. They are the **first to place all 8 valid pieces**, OR
2. They **submit fewer invalid moves and place more pieces** if the board fills, OR
3. The opponent **clicks “End Game”** and submits defeat.

---

## 🛠️ How to Run Locally

1. **Clone this repo** or download the `index.html` file.
2. Open the file in your browser:
   ```bash
   xdg-open index.html
