Rubik's Cube Solver


This project implements a Rubik's Cube solver utilizing Korf's IDA* algorithm, alongside other search algorithms, to efficiently solve jumbled cube states. The cube itself is meticulously modeled in C++ using Object-Oriented Programming (OOP) principles to facilitate accurate simulation and algorithmic exploration.

Key Features and Implementations:

Object-Oriented Cube Representation: A robust C++ object-oriented model of the Rubik's Cube enables accurate state representation, manipulation, and simulation for various solving algorithms.

Diverse Solver Algorithms: The project incorporates and evaluates multiple search algorithms for solving the Rubik's Cube:

Uninformed Search: Achieved solving times under 4 seconds for cubes jumbled 8 times using Breadth-First Search (BFS), Depth-First Search (DFS), and Iterative Deepening Depth-First Search (IDDFS).

Korf's IDA* Algorithm: Implemented Korf's Iterative Deepening A* (IDA*) algorithm to efficiently solve cubes jumbled up to 13 times, consistently achieving solutions in under 10 seconds.

Memory Optimization: Memory usage was optimized by 50% through the implementation of nibble arrays for cube representation, significantly improving performance and resource efficiency.


