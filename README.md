---
title: "A* PATHFINDER - A 2D Navigation Simulator"
authors:
  - "Shyam Shivaji J, S4, 2510603"
  - "Santhosh P. S., S4, 2510662"
license: "MIT"
language: "Python 3"
---


# A* PATHFINDER -  A 2D Navigation Simulator
![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Pygame](https://img.shields.io/badge/Pygame-2.x-green.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Status](https://img.shields.io/badge/Project-Active-brightgreen.svg)

Welcome to the A* PATHFINDER - A 2D Navigation Simulator, This project implements and visualizes the A* pathfinding algorithm on a 2D grid. It allows users to interact with the grid, place obstacles, define start and end nodes, and observe how the algorithm computes the shortest path. The visualizer is designed to provide a clear, structured understanding of how heuristic search operates.
## **🌐 Key Features**

- **Interactive Grid**  
  Set start and goal nodes, draw barriers, and modify the grid layout freely.

- **Real-Time Visualization**  
  View the exploration of nodes, frontier expansion, and final shortest path as the algorithm progresses.

- **Modular Code Structure**  
  Components such as node logic, grid management, heuristic functions, and the A* algorithm loop are neatly separated.

- **Efficient Reset Options**  
  Clear or rebuild the grid to test multiple scenarios easily.

## **🎮 Usage and Controls**
**Mouse Left Click** : 

-  **First click**: Set Start Node 🟧

-  **Second click**: Set End Node 🟦

-  **Additional clicks**: Add Barriers ⬜

**Mouse Right Click** :

- Remove Start, End, or Barrier nodes

**Spacebar** : 

- Run the A* pathfinding algorithm

**C Key** : 

- Clear the grid

## **📌 How A-Star Algorithm Works**

A* evaluates nodes based on two cost estimates:

- `g(n)`: Actual cost from the start node to the current node  
- `h(n)`: Heuristic estimate from the current node to the goal


- The heuristic function uses Manhattan distance here:
  **`|x1 - x2| + |y1 - y2|`**


- The Final Shortest path is Calculated using the Following:
   **`f(n) = g(n) + h(n)`**

  
- The algorithm always selects the nodes from the neighbours with the lowest `f(n)` value.

## 🛠️ Installation and Running 

### Requirements

- Python 3.x  
- Pygame  

### Install dependencies:

```bash
pip install pygame
```
### Cloning Repository:
```bash
git clone https://github.com/shyamdotexe/A-star-PATHFINDER-2D-Navigation-Simulator.git
cd AStarPATHFINDER
```
### Running the program:
```
python main_simulation.py
```

## 📄 License 

 This Project is Licensed under the **MIT License** , Can be **Used, Modified, Extended Etc.**
