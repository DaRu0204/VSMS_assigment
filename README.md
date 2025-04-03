# A* Pathfinding Algorithm Visualization
## Overview
This project is a visualization of the A* pathfinding algorithm using Python and Pygame. It generates a grid where obstacles, start, and end points are randomly placed, allowing users to see the algorithm in action as it finds the shortest path.
## Features
*   **Grid-based visualization:** A 50x50 grid where each cell represents a node.
*   **A* pathfinding algorithm:** Finds the shortest path efficiently.
*   **Interactive user control:**
*   Generate a random maze with obstacles.
*   Press SPACE to start the algorithm.
*   Press C to clear the grid and generate a new maze.
*   **Color-coded cells:**
*   Orange -> Start node
*   Turqoise -> End node
*   Black -> Barriers
*   Green -> Open nodes
*   Red -> Closed nodes
*   Purple -> Final path
## Requirements
Ensure you have Python 3.x and Pygame installed.
## Code Structure
*   Node class: Represents each grid cell.
*   algorithm(): Implements the A* pathfinding algorithm.
*   make_grid(): Creates a 2D list of Node objects.
*   draw(): Renders the grid and updates the display.
*   main(): Handles the game loop and user interactions.
## Contributing
If you'd like to contribute, fork the repository and create a pull request with your changes.
## License
This project is licensed under the MIT License.