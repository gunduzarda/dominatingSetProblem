# Dominating Set Problem
  This repository contains an analysis of the Dominating Set problem and its algorithms. The Dominating Set problem involves finding the smallest subset of vertices in an undirected graph such that every vertex in the graph is either in the subset or adjacent to at least one vertex in the subset.
This repository contains an analysis of the Dominating Set problem and its algorithms. The Dominating Set problem involves finding the smallest subset of vertices in an undirected graph such that every vertex in the graph is either in the subset or adjacent to at least one vertex in the subset. The problem is known to be NP-complete.

  The analysis begins with a description of the problem and its applications in various fields such as sensor placements and computational biology. It then presents two algorithms for solving the Dominating Set problem: the brute force algorithm and the greedy algorithm.

  The brute force algorithm exhaustively searches for all possible subsets of vertices and checks whether each subset is a dominating set. It guarantees finding the optimal solution but has exponential time complexity, making it inefficient for large graphs.

  The greedy algorithm, on the other hand, iteratively selects nodes that maximize the domination of the graph. It starts with an empty dominating set and adds nodes that are not dominated along with their adjacent nodes. The greedy algorithm is faster than the brute force algorithm and provides an approximate solution with a bound on the size compared to the optimal solution.

  The analysis includes detailed explanations of the algorithms, their correctness proofs, and complexity analyses. It also provides code implementations for both algorithms and performs experimental analyses to evaluate their performance and correctness.

  Functional testing is conducted to verify the correctness of the algorithms' outputs, while performance testing measures the running time for different input sizes. The results of the performance testing confirm the expected time complexity of the algorithms.

  Overall, the analysis provides insights into the Dominating Set problem, its algorithms, their correctness, and performance. It serves as a comprehensive guide for understanding and implementing solutions to the Dominating Set problem.
