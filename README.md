# Knight-Travails-Problem
A simple approach to solve the knight tour problem using backtracking algorithm.
This program has been written in C.

Another program named knight's shortest path has been written in Python using Queue Data Structure and BFS Algorithm.

We start by moving the knight and if the knight reaches to a cell from where there is no further cell available to move and we have not reached to the solution yet 
(not all cells are covered), then we backtrack and change our decision and choose a different path.

So from a cell, we choose a move of the knight from all the moves available, and then recursively check if this will lead us to the solution or not. 
If not, then we choose a different path.

We keep the track of the moves in a matrix. This matrix stores the step number in which we visited a cell. 
For example, if we visit a cell in the second step, it will have a value of 2.

We will start the tour of the knight from the cell (1, 1) as its first step. 

**Note:**

For much efficent approach than backtracking we can use Warnsdroff's Algorithm using C++ and we can even find the minimum number of steps to reach the target.
But all these can be easily done in C++,Java or Python


