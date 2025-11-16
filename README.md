# Chess AI Bot

A Python-based interactive chess game where players can make moves on a virtual chessboard.  
As you play, the system analyzes the board position in real time and suggests the best move using the **Stockfish** chess engine.  
Both the player’s and the AI’s moves update automatically as the game progresses.

---

## Features

- **Real-Time Best Move Suggestions** – Stockfish evaluates every position and returns the strongest move.
- **Virtual Chessboard** – See all moves visually (console or GUI depending on implementation).
- **Player vs AI Gameplay** – Make your move, then the AI responds instantly.
- **FEN Support** – Converts board states into FEN for accurate engine analysis.
- **Move Validation** – Ensures legal moves and correct game flow.

---

## How It Works

1. User inputs a move on the board (ex: `e2e4`).
2. The system converts the updated board state into **FEN**.
3. Stockfish analyzes the FEN with a configurable search depth.
4. The engine outputs:
   - Best move  
   - Evaluation  
   - Continuation line
5. The board updates with both the user's move and the AI move.
