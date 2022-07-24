Sudoku-Solver

This is a program which solves 9x9 Sudoku puzzles. Written completely in C++ and built wholly from scratch, this program reads input either from a user or from a file containing the Sudoku values and solves the puzzle. It employs concepts such as backtracking and recursion.



How It Works

This particular algorithm employs the use of backtracking, one of the more common methods to solve Sudoku puzzles. I've written a simple algorithm to give an idea of how the program works.

Start.
We start with the first empty cell.
We generate a list of possible valid values that can be filled in that cell.
We iterate over this list and start with the first value. This value is placed in the required cell.
We move on to the next cell. We again generate a list of possibilities. However, if no list can be generated, then this means that there is something wrong with the value of the previous cell. We then move back to the previous cell and place the next value on the generated list in the cell now. We repeat this step until the current cell has a valid value placed inside it.
We stop when we reach the 81st cell (the last cell in a Sudoku puzzle) and have placed a valid value.
The puzzle has now been solved.
Stop.



Tools

VS Code Compiler
