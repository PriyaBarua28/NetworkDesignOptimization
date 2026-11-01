# Network Design Optimization Using Prim's and Kruskal's Algorithm in C++

Project Overview

Network Design Optimization is a C++ based project that finds the minimum cost required to connect different cities using graph algorithms.

This project implements **Prim's Algorithm** and **Kruskal's Algorithm** to calculate the Minimum Spanning Tree (MST) of a network. It helps identify the most cost-effective connections while ensuring that all cities are connected.

 Objectives

- To understand graph representation and Minimum Spanning Trees.
- To implement Prim's Algorithm using C++.
- To implement Kruskal's Algorithm using C++.
- To calculate the minimum connection cost.
- To compare the performance of both algorithms.

 Features

- Add new cities to the network.
- Add connections between cities with different costs.
- Display all cities and network connections.
- Find MST using Prim's Algorithm.
- Find MST using Kruskal's Algorithm.
- Compare the results and execution time of both algorithms.
- Load a predefined sample network.
- Check network connectivity before generating an MST.

 Technologies Used

- **Programming Language:** C++
- **IDE:** Visual Studio Code
- **Compiler:** GCC / G++
- **Concepts:** Graph Theory, Minimum Spanning Tree, Greedy Algorithms
- **Libraries:** iostream, vector, string, algorithm, ctime, climits

 Algorithms Used

1. Prim's Algorithm

Prim's Algorithm starts from a selected vertex and repeatedly selects the minimum-weight edge that connects a visited vertex to an unvisited vertex.

**Time Complexity:** O(V²) in this implementation.

2. Kruskal's Algorithm

Kruskal's Algorithm sorts all edges according to their weights and selects the smallest edges without forming a cycle.

It uses the Disjoint Set Union (DSU) technique.

**Time Complexity:** O(E log E).
 Project Structure

text
NetworkDesignOptimization/
│
├── NetworkDesign.cpp
│
├── .vscode/
│   └── tasks.json
│
└── README.md

How to Run the Project

 Step 1: Clone the Repository

```bash
git clone https://github.com/PriyaBarua28/NetworkDesignOptimization.git
```

Step 2: Open the Project Folder

```bash
cd NetworkDesignOptimization
```

Step 3: Compile the Program

```bash
g++ NetworkDesign.cpp -o NetworkDesign.exe
```

 Step 4: Run the Program

**Windows:**

```bash
.\NetworkDesign.exe
```

 Main Menu

```text
========================================
      NETWORK DESIGN OPTIMIZATION
========================================
1. Add City
2. Add Connection
3. Display Network
4. Find MST using Prim's Algorithm
5. Find MST using Kruskal's Algorithm
6. Compare Both Algorithms
7. Load Sample Network
8. Exit
========================================
Enter your choice:
```

Sample Output

For the predefined sample network:

| Algorithm | Minimum Cost |
|---|---:|
| Prim's Algorithm | 320 |
| Kruskal's Algorithm | 320 |

Both algorithms produce the same minimum spanning tree cost.

Algorithm Comparison

| Prim's Algorithm | Kruskal's Algorithm |
|---|---|
| Starts from a vertex | Starts by sorting edges |
| Selects the minimum connecting edge | Selects the minimum available edge |
| Uses an adjacency matrix | Uses an edge list |
| Complexity: O(V²) | Complexity: O(E log E) |

 Applications

- Computer network design
- Road and railway network planning
- Telecommunications
- Electrical power distribution
- Transportation network optimization

 Future Scope

- Develop a graphical user interface.
- Add real-time network visualization.
- Support larger networks and more input options.
- Display MST graphs visually.
- Store network information in a database.

Project Information

**Project Title:** Network Design Optimization Using Prim's and Kruskal's Algorithm in C++

**Project Type:** Academic / Mini Project

**Language:** C++

Conclusion

This project demonstrates how Prim's and Kruskal's algorithms can be used to solve network optimization problems. Both algorithms generate a Minimum Spanning Tree with minimum total connection cost. The project improves understanding of graph theory, greedy algorithms, and practical applications of data structures.



⭐ If you find this project useful, feel free to explore the source code and learn about graph algorithms.
