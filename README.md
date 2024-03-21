A Yashi game scenario is defined on a n by n grid, where n is an integer greater than or equal to 2. The grid must have a minimum of two nodes on it. The goal consists of connecting all the nodes, and ending up with a planar spanning tree where each line cannot be a diagonal one.

More specifically, the game is defined with these constraints:

(1) Diagonals lines not permitted (no overlap);

(2) All points must be connected;

(3) Lines should not cross each other;

(4) The total number of lines used must be exactly n-1, where n represent the total number of points;

(5) The structure must not form any cycles.

There is three versions of the game:

Version 1: Determine whether there is a valid solution.

Version 2: If a solution is possible, calculate the total number of solutions.

Version 3: If a solution exists, identify the one with the least cost.

The notebook provided contains the complete implementation of the game to solve the three versions.
