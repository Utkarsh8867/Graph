## Graphs in Data Structures and Algorithms

A **graph** is a non-linear data structure that consists of a set of nodes (also called vertices) and edges that connect pairs of nodes. Graphs are used to model relationships between objects, such as networks, paths, or connected components.

### Key Terminology:
- **Vertex (V)**: A point or node in the graph.
- **Edge (E)**: A line or link connecting two vertices.
- **Directed Graph**: A graph where edges have a direction, going from one vertex to another.
- **Undirected Graph**: A graph where edges have no direction, meaning the connection between two vertices is bidirectional.
- **Weighted Graph**: A graph where each edge has a numerical value (or weight) representing the cost, distance, or capacity of that edge.
- **Unweighted Graph**: A graph where all edges are considered equal and have no specific value.

### Types of Graphs:
- **Directed Acyclic Graph (DAG)**: A directed graph with no cycles.
- **Complete Graph**: A graph where every pair of vertices is connected by a unique edge.
- **Sparse Graph**: A graph with few edges relative to the number of vertices.
- **Dense Graph**: A graph with many edges, close to the maximum number of edges possible.

### Graph Representation:
1. **Adjacency Matrix**: A 2D array where `matrix[i][j]` indicates if there is an edge from vertex `i` to vertex `j`.
2. **Adjacency List**: A list of lists, where each vertex has a list of adjacent vertices.
3. **Edge List**: A list of all edges, where each edge is represented as a pair (or tuple) of vertices.

### Graph Traversal:
- **Depth-First Search (DFS)**: Explores as far down a branch as possible before backtracking.
- **Breadth-First Search (BFS)**: Explores all neighbors of a vertex before moving to the next level of neighbors.

### Common Graph Algorithms:
- **Dijkstra's Algorithm**: Finds the shortest path from a source vertex to all other vertices in a weighted graph.
- **Kruskal's Algorithm**: Finds the minimum spanning tree for a graph, connecting all vertices with the minimum possible total edge weight.
- **Prim's Algorithm**: Another approach to finding the minimum spanning tree, starting from a specific vertex and growing the tree one edge at a time.

### Applications of Graphs:
- **Social Networks**: Represent users as nodes and connections as edges.
- **Navigation Systems**: Represent locations as nodes and paths as edges, used for finding the shortest routes.
- **Web Crawlers**: Use graph traversal techniques to crawl interconnected web pages.
