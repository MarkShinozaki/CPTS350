# Sample Exam Questions:

### 1. (10 pts, easy)
**Please mark true or false to each statement below, no explanations are needed:**
1. SCC algorithm was invented by Dijkstra.
2. Shortest path algorithm was invented by Tarjan.
3. Karatsuba algorithm is a greedy algorithm.
4. Minimal spanning tree algorithm is a divide and conquer algorithm.
5. LCS is a dynamic programming algorithm.
6. Deciding whether a number is even or not is in NP.
7. There are infinitely many problems outside NP.
8. SAT is NP-complete.
9. Graph isomorphism is unknown to be NP-complete.
10. It is an open problem whether RSA is unbreakable.

### 2. (10 pts, standard)
**Design an algorithm that finds the longest common subsequence between two given strings such that the subsequence starts with "ab" and does not contain the symbol 'c'.** When the desired subsequence does not exist, your algorithm returns `None`. I will grade on the efficiency of your algorithm.

### 3. (5 pts, be careful)
A lot of students will miss this ridiculously simple problem. This problem says that if humans still use unary instead of digital numbers today as we did half a million years ago on cave walls, RSA is breakable. Unary number is to use only one kind of symbol to represent a number. For instance, unary number 11111 means five. **Show that the following problem is in P (i.e., the problem is solvable in deterministic polynomial time; so do not use GUESS anywhere in this problem):**

Given: a unary number `n`  
Question: are there unary numbers `p` and `q` with `p, q` at least 2 such that `n = p * q`?  
(Hint: what is the size of the input `n`? Is it `n` or `log n`?)

### 4. (5 pts, easy)
**FACT** is the following problem:  
Given: a number `n` in digits  
Question: are there three numbers `p`, `q`, and `r` with `p, q, r` at least 2 such that `n = p * q * r`?  
Show that FACT is in NP. (Hint: what is the size of the input `n`? Is it `n` or `log_10 n`?)

### 5. (10 pts, standard)
**Describe an efficient algorithm that solves the following problem:**

Given: a directed graph `G` and three distinct nodes `v1`, `v2`, `v3` in `G` (the graph may contain many other nodes),  
Question: is there an infinite walk from `v1` such that the walk passes node `v2` for an infinite number of times and passes `v3` exactly twice?

### 6. (15 pts, not too hard)
Let `G` be a DAG and `v0`, `v1` be two distinct and designated nodes in `G` (G can have many other nodes).

1. (8 pts) Design an efficient algorithm to compute the total number of walks from `v0` to `v1` in `G`. (I need pseudocode. You can simply call topological-sort without explaining it.)
2. (7 pts) Sketch in English an efficient algorithm to compute the total number of even-length walks from `v0` to `v1` in `G`.

### 7. (5 pts, standard)
Show that if `A ≤_m B`, `B ∈ NP`, then `A ∈ NP`.

### 8. (10 pts, hard)
Let `C` be a chessboard of `k x k`, with `k ≥ 8`, on which there is only one piece called Knight. Initially, the Knight sits in the square in the top left corner. As we all know, Knight can only make L-moves within the board; e.g., move to right by two squares and move down by one square. Suppose that a few squares of the board are already pre-labeled with "forbidden" so that the Knight cannot move to a forbidden square. Please sketch an efficient algorithm to decide whether the Knight can eventually move to the bottom right corner.

### 9. (10 pts, standard)
In the BDD project, we have learned how to represent a directed graph `G` with a BDD `RR` and how to manipulate the BDD to do graph search using `pyeda`. Recall that `RR` is to represent the set of node pairs `(u, v)` such that `u → v` (i.e., `u to v` is an edge in `G` and hence `u` can reach `v` in one step.). Suppose that `G` has 4 nodes.

Write a few lines of python code to compute, from `RR`, a BDD `Bad` to represent the set of node pairs `(u, v)` such that `u` can reach `v` in two or four steps in `G`.

### 10. (10 pts, homework problem)
Let `G` be a directed graph where each edge is assigned with a positive integer called weight. In particular, there is a designated node in `G` called the initial node and there is a designated node in `G` called the final node. For each path `w` from the initial to the final, one can multiply the weights on the path and therefore, a number `W(w)` is obtained. Find a path `w` from the initial to the final such that `W(w)` is minimal.

---

## Explanation and Approach to Solve the Problems

### True/False Questions:

These questions are straightforward. You need to know the historical background and fundamental concepts of algorithms and complexity classes (NP, NP-complete, etc.).

### Longest Common Subsequence (LCS) Problem:

You can use dynamic programming to find the longest subsequence that starts with "ab" and avoids 'c'. This involves creating a DP table and modifying it to check for the "ab" prefix and the exclusion of 'c'.

### Unary Number Factorization Problem:

The problem size is n because the unary representation directly corresponds to the size. To determine if n can be factored into p * q, iterate through all pairs of factors and check if they divide n.

Problem:

Show that verifying a solution is in NP by verifying the factors p, q, and r of n efficiently (polynomial time). The size of n is log_10 n, which makes it feasible to verify in polynomial time.

### Infinite Walk Problem:

Use graph traversal techniques such as DFS. Track visits to v2 and ensure that the walk passes v3 exactly twice while allowing infinite revisits to v2.

### Walk Count in DAG:

Use dynamic programming on the topologically sorted order of the DAG to count walks. For even-length walks, use a similar approach but track steps modulo 2.

### Reduction to NP:

Prove that if A reduces to B and B is in NP, then A must also be in NP by leveraging the polynomial-time reduction.
Knight’s Move Problem:

Model this problem as a shortest-path problem on a graph, where nodes represent board squares and edges represent valid Knight moves. Use BFS or A* search to decide if the bottom right corner is reachable.

### BDD Python Code:

Use the BDD operations provided by the pyeda library to compute the required set of node pairs. You need to understand basic BDD manipulation and graph theory.

### Minimal Weight Path Problem:

This is a classic shortest-path problem on a weighted graph, but instead of summing weights, you multiply them. A logarithmic transformation of weights can convert this into a summation problem, allowing the use of algorithms like Dijkstra’s or Bellman-Ford.
