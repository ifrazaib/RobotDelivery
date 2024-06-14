## Automatic Robot Delivery System
## Overview
The Automatic Robot Delivery System is designed to simulate a robot delivering packages within a city. This project employs pathfinding algorithms, specifically Best-First Search and A* Search, to determine the most efficient routes for the robot to take. The project aims to demonstrate the application of these algorithms in a real-world scenario.

## Features
- City Grid Representation: A grid-based representation of the city where each cell represents a location.
- Best-First Search Algorithm: An algorithm that selects the most promising path based on a heuristic.
- A Search Algorithm:* An algorithm that combines the heuristic approach of Best-First Search with the path cost.
- Obstacle Handling: Ability to navigate around obstacles in the grid.
- Dynamic Pathfinding: Real-time pathfinding as the robot moves through the city.
## Algorithms
### Best-First Search
Best-First Search is a search algorithm that explores a graph by expanding the most promising node chosen according to a specified rule. It uses a priority queue to keep track of the nodes to be explored based on a heuristic function.
### A* Search
A* Search is an extension of Best-First Search that includes the cost to reach the node (g(n)) and the estimated cost to reach the goal from the node (h(n)), effectively balancing the path cost and the heuristic.
 
