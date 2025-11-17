📌 Project 1 — PageRank via Eigenvectors, Power Iteration & Random Walks

This project implements the PageRank algorithm using three different mathematical formulations, providing a deep comparison of their numerical behavior.

Methods Implemented

Eigenvector method using numpy.linalg.eig

Power iteration method for efficient iterative approximation

Random walk / Markov chain formulation to obtain the stationary distribution

Handling of dangling nodes, column normalization, and teleportation (damping factor)

Analysis of convergence, computational complexity, and stability

Dataset

Berkeley–Stanford Web Graph (Matrix Market format)

Loaded via scipy.io.mmread, processed into a directed graph using NetworkX

Key Results

Comparison of top PageRank nodes across all methods

Effect of damping factor α on stability and ranking

Discussion of why eigenvector and iterative solutions may slightly differ

Evaluation of runtime: O(n³) for eigen-decomposition vs O(kn²) for power iteration
