# Dyanmic Programming
An algorithmic technique for solving an optimization problem by breaking it down into simpler subproblems and utilizing their recurrent formula to understand that the solution is the accumulation of all the subproblems results;

## Memoization (Top Down)
An optimization technique where you cache previously computed results, and return the cached result when the same computation is needed again.

- MAKE IT WORK
  - Visualize the problem as a tree
  - Implement the tree using recusrion (BRUTE FORCE WAY)
  - Test it
- MAKE IT EFFICIENT
  - Implement a memo object
  - Implement a new base case to return memo values
  - Store previous return values into the memo

## Tabulation (Bottom Up)
A process of filling a table and then computing a solution to the original problem based on the results in the table.

- Visiualize the problem as a table
- Size the table based on the inputs
- Initialize tbe table with evaluated default values
- Seed the trivial answer into the table
- Iterate through the table
- Fill further positions based on the current position