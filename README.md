# Homeworks/Assignments

## [Homework 1](https://github.com/MarkShinozaki/CPTS350-Design-AnalysisOfAlgorithms/tree/Homeworks/Homework%201)

### Requirements:

### Language Problem Mapping:
Link the concept of a problem being a language, as learned in Cpts 317, to Cpts 350. For example, consider a graph and determine whether it is connected. You must identify the languages corresponding to several problems:

- **Problem 1:** Given a number `n` and two primes `p` and `q`, is `n = p * q`?
- **Problem 2:** Given a number `n`, is `n = p * q` for some primes `p` and `q`?
- **Problem 3:** Given a Nondeterministic Finite Automaton (NFA) `A` and a word `w`, does `A` accept `w`?
- **Problem 4:** Given an NFA `A`, is there a word `w` such that `A` accepts `w`?

### Big-O Notation Proofs:
Prove why specific functions fit within Big-O notation for certain bounds. For instance, show that:

- The function `2n^3 − 18n` is `O(n^3)`, `O(n^4)`, but not `O(n^2 log n)`.
- The function `3n^2 * 2^(2n)` is `2^O(n)`.

### Real-World Problem and Algorithm Design:
Design an algorithm to compute a similarity metric between two protein molecules based on their 3D structures. The problem requires:

- Describing how such an algorithm could help in drug development.
- Choosing a data structure to represent protein molecules.
- Defining and sketching two similarity metrics and associated algorithms to compute these metrics.

### Topics:
- Language theory and problem encoding.
- Big-O notation and complexity analysis.
- Bioinformatics and algorithm design for real-world applications.
- Protein structure analysis and data representation.

### Summary:
This assignment challenges students to link concepts from language theory to problem-solving in algorithm analysis. It explores the theoretical aspects of Big-O notation and pushes students to design algorithms for complex real-world problems, specifically in bioinformatics. Students need to think critically about data representation and algorithm efficiency, particularly in the context of protein molecule similarity, with a focus on applications in drug development.

---

## [Homework 1 Prime (Bonus Problem)](https://github.com/MarkShinozaki/CPTS350-Design-AnalysisOfAlgorithms/blob/Homeworks/Homework%203/homework1prime.pdf)

### Requirements:

1. **Input Size and Complexity:**
   - The problem emphasizes understanding how input size affects computational complexity. Students must correctly determine input sizes and understand how they impact the performance of algorithms.

2. **Memory Usage:**
   - The problem also requires students to distinguish between read-only memory and additional memory required by an algorithm, particularly in the context of space complexity.

3. **Blum’s Speedup Theorem:**
   - The core of the problem is related to Blum’s speedup theorem, which states that for any algorithm, it is possible to create a faster algorithm that performs better on almost all inputs. The problem provides an example of speeding up a multiplication algorithm by processing digits two at a time rather than one at a time.

### Topics:
- Input Size and Complexity: Understanding how to measure and optimize based on input size.
- Space Complexity: Distinguishing between read-only memory and additional memory usage.
- Blum’s Speedup Theorem: Applying the theorem to understand algorithmic optimization.

### Summary:
The bonus problem in Homework 1 is a theoretical exploration of algorithm optimization, focusing on Blum’s speedup theorem. Students are required to demonstrate their understanding of input size, memory usage, and how to speed up algorithms by processing more significant chunks of data at once. This problem highlights the importance of theoretical computer science in practical algorithm design.

---

## [Homework 2](https://github.com/MarkShinozaki/CPTS350-Design-AnalysisOfAlgorithms/tree/Homeworks/Homework%202)

### Requirements:

#### Dynamic Programming and Optimization:
The assignment involves designing and analyzing dynamic programming algorithms for specific problems. The problems test the students' ability to break down problems into subproblems and efficiently solve them using dynamic programming techniques.

#### Graph Theory Applications:
Apply graph algorithms to solve real-world problems, such as finding the shortest paths, optimizing routes, and analyzing connectivity within graphs. The problems require understanding and implementing algorithms like Dijkstra’s or Bellman-Ford.

### Topics:
- Dynamic programming: Optimization problems and subproblem decomposition.
- Graph theory: Shortest path algorithms, connectivity analysis, and network optimization.
- Algorithm design and complexity analysis.

### Summary:
Homework 2 delves into the practical application of dynamic programming and graph theory. It focuses on teaching students how to efficiently solve complex problems by decomposing them into smaller, manageable subproblems. The assignment emphasizes algorithm design and optimization, particularly in the context of real-world applications involving graphs and networks.

---

## [Homework 3](https://github.com/MarkShinozaki/CPTS350-Design-AnalysisOfAlgorithms/blob/Homeworks/Homework%203/Homework%203.pdf) 

### Requirements:

1. **Algorithmic Problem Solving:**
   - The assignment focuses on applying algorithmic techniques to solve problems related to sorting, dynamic programming, and computational complexity. Students are required to understand and apply these concepts to devise efficient solutions to the given problems.

2. **Dynamic Programming:**
   - Problems include designing algorithms that use dynamic programming techniques. This involves breaking down problems into subproblems and solving them in a bottom-up manner.

3. **Graph Theory and Optimization:**
   - Some of the questions might require applying graph theory algorithms, such as shortest path, minimum spanning tree, or network flow algorithms, focusing on optimizing specific properties of graphs.

### Topics:
- Sorting Algorithms: Understanding the implementation and optimization of sorting techniques.
- Dynamic Programming: Application of dynamic programming for problem-solving, focusing on optimization and minimizing computational overhead.
- Graph Theory: Algorithms related to graph traversal, optimization, and network analysis.

### Summary:
Homework 3 is designed to test students on their understanding and application of advanced algorithmic concepts. The problems cover a range of topics from sorting algorithms to dynamic programming and graph theory. Students are expected to design efficient solutions that minimize time and space complexity, showcasing their problem-solving skills.

---
## [Homework 4](https://github.com/MarkShinozaki/CPTS350-Design-AnalysisOfAlgorithms/blob/Homeworks/Homework%204/CPTS350%20HW4.pdf)

### Requirements:

### 1. Sorting Problem (Purple-Haired Babies Sorting Algorithm):
- The first problem involves designing an efficient algorithm to sort an array of items based on specific criteria, in this case, sorting babies by hair color (purple, brown, black) using a one-pass, in-place, and linear time approach. The problem encourages creativity in designing a solution that meets all the criteria, using pointers or similar methods to achieve the desired result.

### 2. Algorithm Design and Analysis:
- The assignment requires not only the design of an efficient algorithm but also the analysis of its performance. Students must explain how their algorithm satisfies the constraints of one-pass, in-place sorting, and linear time complexity. The assignment likely includes additional tasks that require similar levels of design and analysis.

### Topics:
- Sorting algorithms: Understanding and implementing sorting methods that meet specific constraints (e.g., one-pass, in-place, linear time).
- Algorithm analysis: Evaluating the efficiency of algorithms in terms of time and space complexity.
- Pointer manipulation: Utilizing pointers or similar techniques to manage multiple elements during sorting.

### Summary:
Homework 4 is focused on the design and analysis of sorting algorithms under strict constraints. Students are required to creatively develop a solution that sorts an array based on specific characteristics, such as hair color, while adhering to conditions like one-pass traversal, in-place operation, and linear time complexity. The assignment tests the student’s ability to design efficient algorithms, analyze their performance, and justify their approach.

---

## [Homework 5](https://github.com/MarkShinozaki/CPTS350-Design-AnalysisOfAlgorithms/blob/Homeworks/Homework%205/Cpts350%20-%20HW5.pdf)

### Requirements:

### 1. Pseudo-code for Partition Algorithm:
- The first problem asks students to write pseudo-code for the `partition(A, p, q)` function, which is typically a part of the QuickSort algorithm. This tests students' understanding of how to split an array into two parts based on a pivot element.

### 2. Average-Case Complexity of Insertion Sort:
- The second problem explores the average-case complexity of the Insertion Sort algorithm when the input array has a 1% probability of being monotonically decreasing. Students are required to show that under these conditions, the average-case complexity is Θ(n²).

### 3. Complexity Analysis of `iqsort` Algorithm:
- The third problem introduces a variant of QuickSort called `iqsort`, where QuickSort is applied to the lower part of the array, and Insertion Sort is applied to the upper part. Students must compute the best-case, worst-case, and average-case time complexities of this hybrid sorting algorithm.

### 4. Complexity Analysis of `mixsort` Algorithm:
- The fourth problem involves another hybrid sorting algorithm called `mixsort`, where `mixsort` is recursively applied to the lower part, and Insertion Sort is applied to the upper part. Similar to the previous problem, students must compute the best-case, worst-case, and average-case time complexities.

### Topics:
- Sorting Algorithms: Understanding and implementing sorting algorithms like QuickSort, Insertion Sort, and their hybrids.
- Time Complexity Analysis: Calculating and comparing the best, worst, and average-case complexities of different algorithms.
- Algorithm Design: Writing pseudo-code and designing efficient algorithms for sorting and other operations.

### Summary:
Homework 5 focuses on the design and analysis of sorting algorithms. It challenges students to write pseudo-code, analyze the time complexity of hybrid sorting algorithms, and understand the conditions under which certain sorting algorithms perform optimally or suboptimally. The assignment emphasizes the importance of algorithm design, particularly in balancing different sorting techniques to achieve better performance.

---

## [Homework 6](https://github.com/MarkShinozaki/CPTS350-Design-AnalysisOfAlgorithms/blob/Homeworks/Homework%206/350-HW6.pdf)

### Requirements:

### 1. Maximal and Minimal Element Selection:
- The assignment requires designing an algorithm that selects both the maximal and minimal elements from an array of `n` elements using only 1.5n comparisons. This involves optimizing the number of comparisons required to find the extremum values.

### 2. Average-Case Complexity Comparison:
- Students must compare the average-case complexities of two algorithms (S and T) for selecting the smallest elements from an array. The analysis involves determining under what conditions each algorithm outperforms the other based on the choice of `i`.

### 3. Worst-Case Complexity Analysis for Linear Select:
- The assignment requires demonstrating the worst-case complexities for the linear select algorithm, specifically when the group size `k` is 3 or 7. This extends the complexity analysis taught in class.

### 4. Hybrid Selection Algorithm Analysis:
- Students are required to analyze a hybrid selection algorithm (`ilselect`) that combines quickselect and linear select. They must compute both the worst-case and average-case time complexities for this algorithm.

### 5. Sorting with a Minimal Number of Operations:
- The final problem involves determining the minimal number of operations required to sort `n` distinct numbers using a specific operation (5com), which sorts five numbers at a time.

### Topics:
- **Algorithm Design and Optimization:** Focusing on optimizing comparisons for selecting maximal and minimal elements.
- **Complexity Analysis:** Detailed comparison of average-case complexities, worst-case analysis, and hybrid algorithms.
- **Sorting Algorithms:** Understanding the complexity and efficiency of sorting with minimal operations using specific constraints.

### Summary:
Homework 6 is designed to test students on advanced algorithmic concepts, particularly in optimizing and analyzing algorithms. The assignment covers a range of topics, including efficient selection algorithms, complexity analysis for both average and worst cases, and designing minimal operation sorting techniques. The problems challenge students to apply theoretical knowledge to practical algorithm design and to provide rigorous analysis of their solutions.


--- 

## [Homework 7](https://github.com/MarkShinozaki/CPTS350-Design-AnalysisOfAlgorithms/blob/Homeworks/Homework%207/Mark%20350%20HW%207.pdf)

### Requirements:

### 1. Karatsuba Algorithm Analysis:
- The assignment includes questions regarding the Karatsuba algorithm, a fast multiplication algorithm that reduces the time complexity of multiplying large numbers. Students are required to understand the divide-and-conquer strategy used in Karatsuba and analyze its time complexity compared to traditional multiplication methods.

### 2. Algorithm Design and Complexity Analysis:
- Students must design algorithms for specific problems and analyze their time and space complexity. The focus is on optimizing the algorithms to achieve better performance and understanding the theoretical underpinnings of these optimizations.

### 3. Problem-Solving with Constraints:
- The assignment includes solving problems under specific constraints, such as limiting the number of operations or optimizing for worst-case scenarios. This requires a deep understanding of algorithmic principles and the ability to apply them creatively.

### Topics:
- **Karatsuba Algorithm:** A key focus is on understanding and applying the Karatsuba algorithm for fast multiplication, including analyzing its efficiency and comparing it to standard multiplication methods.
- **Divide and Conquer:** The assignment emphasizes divide-and-conquer strategies, particularly in the context of the Karatsuba algorithm and other optimization problems.
- **Complexity Analysis:** Detailed analysis of time and space complexity for various algorithms, with an emphasis on optimizing performance.

### Summary:
Homework 7 challenges students to apply advanced algorithmic concepts, particularly the Karatsuba algorithm, to solve complex problems efficiently. The assignment requires a strong grasp of divide-and-conquer techniques, algorithm design, and complexity analysis. Students must demonstrate their ability to optimize algorithms and understand the theoretical aspects of their performance.

--- 


## [Homework 8](https://github.com/MarkShinozaki/CPTS350-Design-AnalysisOfAlgorithms/blob/Homeworks/Homework%208/Scanned%20Documents%203.pdf)

### Requirements:

### 1. Graph Theory and Boolean Operations:
- The assignment involves representing graphs using Boolean formulas and Binary Decision Diagrams (BDDs). Students must work with graphs encoded in BDDs and perform operations such as transitive closure to analyze reachability within the graph.

### 2. Symbolic Representation and Computation:
- The assignment requires coding in Python using the `pyEDA` library to handle BDDs and implement symbolic computations on graphs. Students need to construct BDDs for specific graph properties, compute relationships between nodes, and verify logical statements related to the graph's structure.

### 3. Complex Logical Verification:
- A critical part of the assignment is to verify a logical statement related to graph properties. Specifically, students need to determine whether, for each prime number node in the graph, there exists an even number node that is reachable in a positive even number of steps.

### Topics:
- **Graph Theory:** Focus on representing and analyzing graph structures using BDDs.
- **Boolean Algebra:** Application of Boolean operations to represent and manipulate graph properties.
- **Algorithm Design in Python:** Implementing symbolic algorithms using the `pyEDA` library for graph analysis.
- **Transitive Closure:** Computing and using transitive closure to determine node reachability within graphs.

### Summary:
Assignment 8 emphasizes the application of symbolic methods in graph theory using BDDs. The task requires students to leverage Boolean operations and Python coding to analyze and verify complex properties of a graph. The assignment combines theoretical concepts from graph theory and Boolean algebra with practical algorithm design, providing a comprehensive exercise in symbolic computation and logical verification.











