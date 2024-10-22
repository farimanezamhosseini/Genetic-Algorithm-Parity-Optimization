# Genetic-Algorithm-Parity-Optimization
This repository contains a Python implementation of a genetic algorithm designed to optimize a matching problem between an array of integers and an array of booleans based on their parity (odd/even).

## Code Overview

- The code initializes a population of candidate solutions, each represented as a pair of random integer and boolean arrays.
- A fitness function evaluates how well each candidate matches the target (the correct parity).
- The algorithm evolves the population through crossover and mutation operations over multiple generations, aiming to find the optimal solution.
- Input an integer n, which determines the size of the integer and boolean arrays.
## Output

The algorithm prints the best seed found that achieves the maximum fitness value, along with the corresponding integer and boolean arrays.

