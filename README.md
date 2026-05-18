# Graph Algorithms on Spatial Data

This project implements and analyzes different graph algorithms on a set of 2D spatial datapoints using Python. The project focuses on:

- Minimum Spanning Tree (MST) using Prim’s Algorithm
- t-Round MST Neighborhood Graph
- Shortest Path Computation using Dijkstra’s Algorithm

The implementation uses libraries such as NetworkX, NumPy, SciPy, and Matplotlib for graph processing and visualization.

---

## Project Structure

├── Problem_1.py   # Prim's Algorithm for Minimum Spanning Tree  
├── Problem_2.py   # t-Round MST Neighborhood Graph  
├── Problem_3.py   # Shortest Path using Dijkstra’s Algorithm  
└── README.md      # Project Documentation

---

## Problem 1: Minimum Spanning Tree using Prim's Algorithm

### Description
This program computes the Minimum Spanning Tree (MST) for a given set of 2D points using Prim’s Algorithm.

### Features
- Calculates Euclidean distance between points
- Builds MST incrementally using a priority queue (Min Heap)
- Outputs:
  - MST edges
  - Total weight of the MST

### Algorithm Used
- Prim’s Algorithm

### Libraries Used
- math
- heapq
- collections

### Output
- List of MST edges
- Total MST weight

---

## Problem 2: t-Round MST Neighborhood Graph

### Description
This program constructs a t-round MST neighborhood graph by repeatedly computing MSTs and removing previously selected edges.

### Features
- Creates a complete weighted graph
- Computes MST multiple times
- Combines edges from all MST rounds
- Visualizes the resulting graph

### Algorithm Used
- Minimum Spanning Tree (NetworkX)
- Euclidean Distance Graph

### Libraries Used
- networkx
- scipy
- matplotlib
- numpy
- time

### Output
- t-round MST neighborhood graph
- Computation time
- Graph visualization

---

## Problem 3: Shortest Path Computation

### Description
This program computes shortest path distances from a source node to all other nodes using Dijkstra’s Algorithm.

### Features
- Constructs a weighted graph using Euclidean distances
- Computes shortest paths from source node
- Displays computation time

### Algorithm Used
- Dijkstra’s Algorithm

### Libraries Used
- networkx
- math
- time

### Output
- Shortest distance from source node to all nodes
- Execution time

---

## Dataset

The dataset consists of multiple 2D coordinate points representing vertices in a graph. Euclidean distance is used as the edge weight between nodes.

---

## Installation

### Clone the Repository
```bash
git clone <repository-url>
cd <repository-folder>
