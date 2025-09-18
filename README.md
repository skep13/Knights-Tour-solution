# Knights-Tour-solution
knights tour solution using python 
Board initialization:
Creates an N x N chessboard initialized with -1.

Knight’s movement:
Defined by moves_x and moves_y arrays (8 possible L-shaped moves).

Backtracking recursion (solve_util):

Try each possible knight move.

Mark the move on the board.

Recursively attempt the next move.

If no valid move is found, backtrack by resetting the square to -1.

Termination condition:
If move_i == N * N, the knight has visited every square → solution found.

Result:
Prints the final chessboard tour or "No solution exists."
