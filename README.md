# N-Queen Visualiser

- The N-Queens puzzle is the problem of placing N chess queens on an N×N chessboard so that no two queens threaten each other. Thus, a solution requires that no two queens share the same row, column, or diagonal.

- This algorithm is designed using recursion.
  
  **<p align='center'>You can find the website live <a href="https://queen-visualiser.netlify.app">here</a></p>**

The **eight queens puzzle** is the problem of placing eight chess queens
on an `8×8` chessboard so that no two queens threaten each other.
Thus, a solution requires that no two queens share the same row,
column, or diagonal. The eight queens puzzle is an example of the
more general *n queens problem* of placing n non-attacking queens
on an `n×n` chessboard, for which solutions exist for all natural
numbers `n` with the exception of `n=2` and `n=3`.
For example, following is a solution for 4 Queen problem.
![N Queens](https://cdncontribute.geeksforgeeks.org/wp-content/uploads/N_Queen_Problem.jpg)
The expected output is a binary matrix which has 1s for the blocks
where queens are placed. For example following is the output matrix
for above 4 queen solution.
```
{ 0, 1, 0, 0}
{ 0, 0, 0, 1}
{ 1, 0, 0, 0}
{ 0, 0, 1, 0}
```