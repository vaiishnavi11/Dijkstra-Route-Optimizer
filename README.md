# Dijkstra Route Optimizer

A modular C++ implementation of Dijkstra's Shortest Path Algorithm designed to calculate the most efficient path between network nodes (simulating a delivery or navigation route tracking system).

## Project Structure
* **Edge.h**: Defines the connections and weights between network locations.
* **Graph.h**: Manages the structural adjacency list representing the bidirectional network maps.
* **Dijkstra.h**: The core pathfinding execution engine using a min-priority queue.
* **Result.h**: Formats and prints the final calculated distance and route layout.
* **main.cpp**: The entry point that initializes the graph structure and runs the test network.

## How to Compile and Run
Open your terminal and execute:
```bash
g++ main.cpp -o route_optimizer
./route_optimizer