# 🚀 Graph Traversal using BFS and DFS

This repository contains Python implementations of **Breadth-First Search (BFS)** and **Depth-First Search (DFS)** for graph traversal. The graph is represented as an **adjacency matrix**.

## 📌 How It Works
The code performs BFS and DFS traversal efficiently using Python's built-in data structures.

### 🔥 Step-by-Step Execution

### BFS Traversal (Breadth-First Search) 🏃‍♂️
1. **Graph Representation** 📊
   - The graph is stored as an **adjacency matrix**, where `1` represents an edge between nodes, and `0` represents no connection.

2. **Initialization** ⚙️
   - The `BFS` class initializes with:
     - `graph` (Adjacency matrix)
     - `source` (Starting node for BFS traversal)
   - It maintains:
     - `queue` (To process nodes in a FIFO manner)
     - `visited_node` (Set of visited nodes)

3. **BFS Traversal** 🔄
   - Starts from the **source node**.
   - Explores all adjacent nodes before moving to the next level.
   - Ensures nodes are visited in **level order**.

4. **Output** 🖥️
   - Prints the **BFS traversal order**.

### DFS Traversal (Depth-First Search) 🔍
1. **Graph Representation** 📊
   - Similar to BFS, the graph is stored as an **adjacency matrix**.

2. **Initialization** ⚙️
   - The `DFS` class initializes with:
     - `graph` (Adjacency matrix)
     - `source` (Starting node for DFS traversal)
   - It maintains:
     - `visited_node` (Set of visited nodes to avoid repetition)

3. **DFS Traversal** 🔄
   - Starts from the **source node**.
   - Recursively explores adjacent nodes before backtracking.
   - Ensures nodes are visited in **depth order**.

4. **Output** 🖥️
   - Prints the **DFS traversal order**.

## 💻 Example Input & Output
### BFS Execution:
```python
source = 4
```
### BFS Output:
```
Graph Adjacency Matrix:
[0, 1, 1, 0, 0, 0]
[0, 0, 1, 1, 0, 0]
[0, 0, 0, 1, 0, 0]
[0, 0, 0, 0, 1, 0]
[1, 1, 0, 0, 0, 1]
[0, 0, 0, 0, 0, 0]
Source node is: 4
BFS Traverse: 4 0 1 5 2 3
```

### DFS Execution:
```python
source = 2
```
### DFS Output:
```
Graph Adjacency Matrix:
[0, 1, 1, 0, 0, 0]
[0, 0, 1, 1, 0, 0]
[0, 0, 0, 1, 0, 0]
[0, 0, 0, 0, 1, 0]
[1, 1, 0, 0, 0, 1]
[0, 0, 0, 0, 0, 0]
Source node is: 2
DFS Traverse: 2 3 4 0 1 5
```

## 📂 Files
- `bfs.py` → Python script implementing BFS.
- `dfs.py` → Python script implementing DFS.
- `README.md` → This file (Project documentation).

## 🛠️ How to Run
1. Clone the repository:
   ```sh
   git clone https://github.com/armanHossain4047/Graph-Traversal-BFS-DFS.git
   ```
2. Navigate to the project directory:
   ```sh
   cd Graph-Traversal-BFS-DFS
   ```
3. Run BFS script:
   ```sh
   python bfs.py
   ```
4. Run DFS script:
   ```sh
   python dfs.py
   ```

## 🤝 Contributing
Feel free to fork this repository, submit issues, or suggest improvements!

## 📜 License
This project is **open-source** and available under the **MIT License**.

Happy Coding! 🚀🎯

