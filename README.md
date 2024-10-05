# Cutting Stock Problem Optimization

## Project Overview
This project focuses on optimizing the cutting stock problem using various computational intelligence techniques. The cutting stock problem is a classical optimization challenge, aiming to minimize waste when cutting larger sheets of material into smaller pieces.

## Authors
- Maja Milenković
- Veljko Prodan

## Algorithms Implemented
1. Simulated annealing
2. Genetic algorithm
3. Simulated annealing and genetic algorithm hybrid

For comparison: [CPLEX](https://www.ibm.com/products/ilog-cplex-optimization-studio)

## Project Structure
```
root/
│
├── src/
│ ├── cplex.ipynb
│ ├── simulated_annealing.ipynb
│ ├── genetic_algorithm.ipynb
│ └── ga_sa_hybrid.ipynb
│
├── comparison/
│ ├── comparison.ipynb
│ └── tables/
│
├── doc/
│ └── seminarski.pdf
│
└── test_instances/
```

## Features
- Implementation of multiple optimization algorithms for the cutting stock problem
- Comparison of algorithm performance using CPLEX as a benchmark
- Randomly generated test instances
- Documentation and analysis of results

## Results and Performance
Results and performance metrics can be found in the `comparison` folder. The `tables` subfolder contains performance data for each algorithm across test instances.
