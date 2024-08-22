# Overview of the Project: Symbolic Graph Project

## Objective
The primary objective of this project was to work with symbolic graphs using Binary Decision Diagrams (BDDs) to perform operations like reachability analysis, transitive closure, and verification of logical statements. The focus was on verifying a specific condition related to the reachability of nodes in a graph constructed using BDDs, specifically checking whether for every prime number node, there exists an even number node that is reachable in a positive even number of steps.

## Project Components and Steps
The project can be broken down into several key steps and components:

### Graph Construction
The graph `G` consists of 32 nodes. An edge exists between nodes `i` and `j` if:
- \((i + 3) \% 32 = j \% 32\)
- \((i + 8) \% 32 = j \% 32\)

These edges are encoded using BDDs, which allow for efficient Boolean operations and graph manipulations.

### Defining Sets
- **Prime Nodes:** The set of prime numbers among the nodes is defined.
- **Even Nodes:** The set of even numbers among the nodes is also defined.

Both sets are represented as BDDs.

### Reachability Computations
- **Two-Step Reachability (RR2):** This BDD represents the set of node pairs such that one node can reach the other in exactly two steps.
- **Transitive Closure (RR2\*):** The reflexive-transitive closure is computed to determine all pairs of nodes such that one can reach the other in a positive even number of steps.

### Verification of Statement A
The final part of the project involves verifying the statement: _"For each node `u` in the set of primes, there exists a node `v` in the set of evens such that `u` can reach `v` in a positive even number of steps."_

This verification is done using the BDD operations, specifically through the use of the smoothing function to eliminate variables and verify the existence of paths that satisfy the condition.

## Code Implementation
The Python code provided implements the above steps using the `pyEDA` library. The key functionalities include:

- **Graph Construction:** The graph is symbolically represented as a BDD where edges are based on modulo conditions.
- **BDD Operations:** The code performs various operations on BDDs, such as composition, smoothing, and transitive closure.
- **Testing and Verification:** The code includes test functions to validate the BDD logic and to ensure that the graph properties hold as expected. Finally, it verifies whether the condition in Statement A is true or false.

## Achievements
The project successfully achieves its goals by:

1. **Symbolically Representing the Graph:** Using BDDs, the project avoids explicit graph search methods like DFS, which would have resulted in a lower grade as per the project requirements.
2. **Efficiently Computing Reachability:** The project computes the reachability of nodes in the graph using logical operations on BDDs, making the process efficient and scalable.
3. **Verifying the Logical Statement:** The final output of the project confirms whether the required condition for prime-to-even reachability in even steps is satisfied.

## Conclusion
This project demonstrates the application of symbolic methods in graph theory, particularly through the use of BDDs to handle complex graph operations. By leveraging the `pyEDA` library and efficient BDD operations, the project successfully validates a non-trivial logical statement regarding reachability in a specially constructed graph.

