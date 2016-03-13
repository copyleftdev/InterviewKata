An algorithm is a step-by-step procedure for performing a calculation. We classify common algorithm design patterns in Table 4.2. Roughly speaking, each pattern corresponds to a design methodology. An algorithm may use a combination of patterns.



Sorting Recursion
Uncover some structure by sorting the input.
If the structure of the input is defined in a recursive manner, design a recursive algorithm that follows the input definition.

Divide and conquer
Divide the problem into two or more smaller independent subproblems and solve the original problem using solutions to the subproblems.


Dynamic programming
Compute solutions for smaller instances of a given problem and use these solutions to construct a solution to the problem. Cache for performance.

The greedy method
Compute a solution in stages, making choices that are locally optimum at step; these choices are never undone.


Incremental improvement Elimination
Quickly build a feasible solution and improve its qual¬ ity with small, local updates.

Parallelism
Decompose the problem into subproblems that can be solved independently on different machines.

Caching Randomization
Store computation and later look it up to save work.

Approximation
Efficiently compute a suboptimum solution that is of acceptable quality.

State
Identify an appropriate notion of state.
