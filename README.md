# Simple Navigator Project Summary

## Introduction
The project is focused on implementing various graph algorithms, using a graph data structure to solve real-world problems. Graphs are vital in areas like navigation, circuit design, social networks, etc. The main goal of the project is to implement algorithms for traversing graphs, finding shortest paths, solving the traveling salesman problem, and others.

## Historical Background
The project draws inspiration from the famous "Seven Bridges of Königsberg" problem posed by Leonard Euler. Euler's work led to the foundation of graph theory, and the rules for traversing bridges without crossing them more than once form the basis of the algorithms in this project.

## Graph Theory Terms
The project uses fundamental graph theory concepts, including:
- **Types of Graphs** (undirected, directed, weighted, etc.)
- **Connectivity** (connected, disconnected graphs)
- **Trees** and **Spanning Trees**

## Graph Representation
The graph is represented using adjacency matrices. This allows efficient storage and traversal of the graph's vertices and edges.

## Task Breakdown

### Part 1: Graph Traversal
- Implement Depth-First Search (DFS) and Breadth-First Search (BFS) algorithms using a stack and queue respectively.

### Part 2: Shortest Path
- Implement Dijkstra's algorithm for finding the shortest path between two vertices.
- Use the Floyd-Warshall algorithm to find the shortest paths between all pairs of vertices.

### Part 3: Minimum Spanning Tree
- Implement Prim’s algorithm to find the minimum spanning tree of a graph.

### Part 4: Traveling Salesman Problem (TSP)
- Use the Ant Colony algorithm to solve the Traveling Salesman Problem, finding the shortest path that visits every vertex at least once and returns to the starting vertex.

### Part 5: Console Interface
- Create a console application to load a graph from a file and allow users to perform various graph operations (e.g., DFS, BFS, shortest path, spanning tree).

### Part 6: Bonus
- Implement and compare multiple algorithms for solving the TSP problem in terms of performance (e.g., Ant Colony vs two other algorithms).
