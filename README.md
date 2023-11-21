# C# maze game

This repository contains code of a learning project called: "C# maze game".

It's purpose is to build a game that generates and solves mazes.

## Idea

A desktop game that uses graph algorithms to generate and solve mazes. The game should use a graph data structure to represent the maze and a stack to implement a depth-first search algorithm to find a path from the start to the end. To generate a unique maze, you can use one of the many algorithms available for maze generation, such as the randomized version of Prim’s algorithm or the recursive backtracker algorithm. Once you have generated the maze, you can use a hashing technique to store the visited cells and a heap to implement a priority queue for a Dijkstra’s algorithm to find the shortest path.

## Learning

- C#
- GRASP
- SOLID
- Patterns
- Graph
- Stack
- Hashing
- Heap/priority queue
- Depth-first search algorithm
- Dijkstra's algorithm
- Randomized version of Prim's algorithm
- Recursive backtracker algorithm

## Requirements

- A unique maze should be generated everytime a new maze is created.
- A maze must be able to be generated using multiple algorithms.
- The maze must be represented by a graph.
- The maze must be visualized in a GUI.
- The shortest path from the start to the end must be visualized in the same GUI using a red line.
- A path from the start to the end must be visualized in the same GUI using a purple line.
- The user must be able to select whether to show the red line, purple line or both.
- The user must be able to select what algorithm to generate the maze with when they first start the GUI.
- The user must be able to generate a new maze without leaving the GUI.
