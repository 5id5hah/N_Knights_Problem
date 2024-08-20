## 🛡️ N_Knights Problem

This Java program solves the N-Knights problem by placing `n` knights on an `n x n` chessboard such that no two knights can attack each other. The algorithm uses backtracking to explore all possible configurations. The `isSafe` method ensures that knights are placed in non-threatening positions, and the solution is displayed in a readable format.

### ⚙️ How it Works
- **♞ Knights Method:** Recursively attempts to place knights on the board, backtracking if a configuration is invalid.
- **🔍 isSafe Method:** Checks if placing a knight at a given position is safe based on knight movement rules.
- **📋 display Method:** Outputs the chessboard with knights ('♞') and empty spaces ('⬜').
