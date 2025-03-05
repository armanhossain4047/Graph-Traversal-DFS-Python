# Graph Traversal Algorithms

This repository contains Python implementations of two popular graph traversal algorithms: **Depth-First Search (DFS)** and **Breadth-First Search (BFS)**. The graph is represented using an adjacency matrix. 

## Features

- DFS (Depth-First Search) implementation
- BFS (Breadth-First Search) implementation
- Example graphs with adjacency matrix representation
- Clear and easy-to-understand code with output examples

## Prerequisites

- Python 3.x

## Files

- `DFS.py`: Contains the DFS class implementation.
- `BFS.py`: Contains the BFS class implementation.
- `graph.py`: Example graph adjacency matrices.

## Example Usage

### Depth-First Search (DFS)

```python
from DFS import DFS

graph = [
    [0, 1, 1, 0, 0, 0], 
    [0, 0, 1, 1, 0, 0], 
    [0, 0, 0, 1, 0, 0], 
    [0, 0, 0, 0, 1, 0], 
    [1, 1, 0, 0, 0, 1], 
    [0, 0, 0, 0, 0, 0]
]

source = 2
dfs_obj = DFS(graph, source)
dfs_obj.st_dfs(source)
