### Tic Tac Toe (Console)

A simple, beginner-friendly Tic Tac Toe game you can play in your terminal. Two players take turns as X and O, entering cell numbers 1–9 to place their marks. The game announces wins and draws and validates inputs.

### Features
- **Two-player**: X and O alternate turns
- **Random start**: Randomly selects which player starts
- **Input validation**: Rejects invalid or occupied cells
- **Win/Draw detection**: Ends the game with a clear message

### Requirements
- **Python**: 3.8 or newer
- OS: Works on Linux, macOS, and Windows (also fine in WSL)

### Getting Started
1. Open a terminal.
2. Navigate to the project directory:

```bash
cd "/home/farshad/Pytopia/Project-Based-Python/Farshad's exercises on Project-Based-Python/Tic Toc Toe"
```

3. Run the game:

```bash
python3 main.py
```

### How to Play
- The board cells are numbered as follows:

```
1 | 2 | 3
---------
4 | 5 | 6
---------
7 | 8 | 9
```

- On your turn, enter a number for an empty cell (1–9).
- The game prints the board after each move.
- The first player to get 3 in a row (horizontal, vertical, or diagonal) wins.
- If all cells are filled with no winner, it’s a draw.

### Project Structure
- `main.py`: Game logic and console interface
- `test.ipynb`: Scratch/experiments in a Jupyter notebook (optional)
- `readme.md`: This file

### Notes
- To restart, simply run the program again.
- Feel free to modify `main.py` to change messages or add features (e.g., AI opponent).


