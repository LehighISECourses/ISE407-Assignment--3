# Assignment 3

1. Implement matrix multiplication for your sparse matrix class from the last assignment. It should be possible to multiple matrices in different formats (natively, not by     converting to another format first). You should include a test scripts, as in previous assignments and `make test` should run appropriate tests. Perform experiments with various combinations to see what pairs of formats are the most efficient and report on your results. 
1. Define a _linear array of size `n` with a bus_ to be a linear array augmented with a single global bus. Every processor is connected to the bus and in one unit of time, one processor can write to the bus and all other processors can read from it. This allows broadcasting in unit time, but only of one data word per time step.
   1. State an efficient algorithm to sum `n` values, initially distributed one
      per processor, on such an architecture. What is the parallel cost of the algorithm? 
      Compare to the case of finding the sum of `n` values on a regular linear array without a bus. 
   1. Can the parallel cost of the algorithm be improved by increasing the
      amount of data initially allocated to each processor? 
1. Miller and Boxer, Chapter 5, Problem 1.
1. Miller and Boxer, Chapter 5, Problem 2.
1. The file `tree.py` contains a class `Tree`, which draws randomly generated trees in Python using the `turtle` package. Implement a non-recursive version of the `draw` functrion that precisely replicates it's behavior. 
