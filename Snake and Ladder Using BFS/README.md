## Snake and Ladder Using BFS

## Project Overview

The Snake and Ladder Using BFS (Breadth-First Search) project is a Python-based implementation of the classic Snake and Ladder game using a graph traversal algorithm.

The project uses BFS to find the minimum number of dice throws required to reach square 100 from square 1. The board is represented as a graph, where each square is a node and each possible dice outcome represents a move. Snakes and ladders change the player's position when the corresponding square is reached.

This project demonstrates the practical application of graph traversal, queues, and shortest-path algorithms using Python in Jupyter Notebook.

## Objectives

- Understand the Breadth-First Search (BFS) algorithm.
- Represent the Snake and Ladder board as a graph.
- Implement a queue to explore possible moves.
- Find the minimum number of dice throws needed to reach square 100.
- Understand shortest-path searching in an unweighted graph.

## Technologies Used

- Programming Language: Python
- Platform: Jupyter Notebook
- Algorithm: Breadth-First Search (BFS)
- Python Module: "collections.deque"

## Features

- Implements the Snake and Ladder board using Python dictionaries.
- Includes predefined snake and ladder positions.
- Explores possible dice outcomes from 1 to 6.
- Prevents moves beyond square 100.
- Uses BFS to find the minimum number of dice throws.
- Displays the minimum number of throws and one shortest path.
- Runs directly in Jupyter Notebook without additional third-party libraries.

## How BFS Works

Breadth-First Search explores possible moves level by level using a queue.

1. Start from square 1.
2. Add the starting square to the queue.
3. Generate possible moves for dice values from 1 to 6.
4. Apply snake or ladder transitions when necessary.
5. Mark visited squares to avoid repeated exploration.
6. Continue until square 100 is reached.
7. Display the minimum number of dice throws and the path found.

Because BFS explores paths in increasing order of the number of moves, it finds the minimum number of dice throws under the game's movement rules.

## How to Run the Project

1. Install Python if it is not already installed.
2. Install and open Jupyter Notebook.
3. Download or clone this repository.
4. Open "Snake_and_Ladder_Using_BFS.ipynb" in Jupyter Notebook.
5. Run each cell using Shift + Enter or select Run All.
6. View the output showing the minimum dice throws and one shortest path.

No additional Python libraries need to be installed.

## Project Structure

Snake-and-Ladder-BFS/
│
├── Snake_and_Ladder_Using_BFS.ipynb
└── README.md

## Complexity Analysis

Let "N" be the number of squares on the board and "D" be the number of possible dice outcomes, which is 6.

- Time Complexity: O(N × D), or O(N) when the dice has a fixed six outcomes.
- Space Complexity: O(N), for the queue, visited set, and parent dictionary.

For a standard 100-square board, the algorithm has linear time and space complexity with respect to the number of squares.

## Learning Outcomes

After completing this project, we can understand:

- Graph representation and traversal.
- Queue operations using FIFO.
- The role of visited nodes in BFS.
- Shortest-path searching in an unweighted graph.
- Applying data structures and algorithms to a real-world game.

## Conclusion

The Snake and Ladder Using BFS project demonstrates how Breadth-First Search can be used to solve a shortest-path problem. The implementation identifies the minimum number of dice throws required to reach square 100 while accounting for snakes and ladders. It provides a practical introduction to graph algorithms and their applications using Python.

## Project Information

Project Title: Implementation of Snake and Ladder Using BFS
Domain: Data Structures and Algorithms
Language: Python
Execution Environment: Jupyter Notebook
