# Maze Game with Dijkstra's Algorithm

## Project Overview
This project is a **Maze Game** developed using HTML, CSS, and JavaScript. Users can explore a randomly generated maze and visually follow the step-by-step operation of the **Dijkstra Algorithm** to find the shortest path.

## Key Features
- **Maze Generation**: Generates random mazes using Depth-First Search (DFS).
- **Dijkstra Algorithm Implementation**:
  - Calculates the shortest path between the start and end points in the maze.
  - Visually represents the pathfinding process.
- **Intuitive Interface**:
  - Use the `Next Step` button to proceed through the pathfinding process step by step.
  - Click the `New Game` button to generate a new maze and start exploring again.

## Algorithm Details

### Maze Generation (DFS)
- Initializes all cells as walls and uses DFS to carve random paths.
- Moves in steps of two cells to increase maze complexity.
- Ensures the start and end points are always accessible paths.

### Dijkstra Algorithm
1. Initializes the distance of the starting cell to 0.
2. Uses a priority queue to update possible paths from the current cell.
3. Processes the closest cell first to calculate the shortest path.
4. Visually updates the state of the cells during the pathfinding process.

## Example Image
> Below is an example of a maze and the pathfinding process using the Dijkstra Algorithm.

![Maze Example](#)
**

## Contributors
1. **김준기**
2. **이병찬**
3. **정인교**
4. **하예림**
