# Selected Topics in Mathematical Optimization

*Edition 2017-2018*

**Dr. ir. Michiel Stock**

Notes and exercises of the optimization course given in the Master of Bioinformatics Bioscience Engineering and Systems Biology (Ghent University).

The goal of this course is to give students a general overview of the rich field of mathematical optimization. This course will put a particular emphasis on **practical implementations** and **performance**. After this course, students should be able to formulate problems from computational biology as optimization problems and be able to read, understand and implement new optimization algorithms.

## Contents

This course consists of three main parts:
1. Continuous convex optimization problems
2. Discrete optimization problems solvable in polynomial time
3. 'Dirty problems', NP hard problems and complex problems with no guarantees on optimality and performance


1. **Minimizing quadratic systems**
  - motivation
  - exact solution, scalar case, multi-dimensional case
  - conditions for optimality
  - large (sparse) systems and the need for iterative solutions
  - gradient descent, convergence and condition numbers
  - brief notion of conjugated gradient descent
  - gradient descent with momentum (intelligent search)
  - *application*: signal recovery
2. **Unconstrained convex problems**
  - convexity and convex problems
  - gradient descent revisited
  - steepest descent methods, coordinate descent
  - Newton's method:
    - as a special case of steepest descent
    - as a quadratic approximation of the original problem
  - quasi-Newton methods
  - numerically approximating the gradient and the Hessian
  - *application*: logistic regression
3. **Constrained convex problems**
  - quadratic systems with linear equality constraints: exact solution
  - Newton's method for convex systems with linear equality constraints
  - Lagrangians and the Karush–Kuhn–Tucker conditions
  - Convex problems with convex inequality constraints
    - geometric interpretation
    - the logarithmic barrier
    - the barrier method
  - *application*: maximum flow problems
4. **Project continuous optimization**: protein oligiomerization by minimizing the Gibbs free energy
5. **Optimal transport**:
  - motivation: the KERMIT dessert party
  - quick recap of probability distributions
  - Monge and Kantorovich formulation
  - Wasserstein distances and Geodesic displacements
  - Entropic regularization and the Sinkhorn algorithm
  - *applications*:
    - comparing distribitions (e.g. expression profiles)
    - color transfer
    - learning epigenetic landscapes
    - computational fluid dynamics
6. **Minimum spanning trees**:
  - graphs and basic data structures (i.e. `list`, `dict`, `set`)
  - introduction to time complexities
  - Kruskal's algorithm
  - Prim's algorithm
  - *application*: phylogenetic tree reconstruction, building a maze
7. **Shortest path algorithms**:
  - greedy search
  - Dijkstra's algorithm
  - A* algorithm: using a heuristic
8. **Project discrete optimization**: optimal routing through a city
9. **NP hard problems**
  - classification
  - example problems: knapsack, TSA, graph cutting
  - algorithms:
    - exhaustive
    - greedy
    - dynamic programming
    - branch and bound
  - longest common subsequence: golfing contest
10. **Bio-inspired optimization**:
  - hill climbing?
  - simulated annealing
  - genetic algorithms
  - other methods
  - *application*: Ising models or antimicrobial peptide optimization?
11. **Project dirty problems**: optimizing peptides or designing a microfluidics device
12. **Learning and optimization**
  - Bayesian optimization
  - Reinforcement Learning
  - Learning inverse mappings


## Thanks

- Bernard De Baets
- Raúl Pérez-Fernández
- Bram De Jaegher
