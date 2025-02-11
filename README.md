# Maze-Generation-solving
Maze generation and maze solving in java

The maze is generated using an implimentation of Prim's iterative algorithm

  Start with a grid full of walls.

  Pick a cell, mark it as part of the maze. Add the walls of the cell to the wall list.

  While there are walls in the list:
  
  Pick a random wall from the list. If only one of the cells that the wall divides is visited, then:
  
  Make the wall a passage and mark the unvisited cell as part of the maze.
  
  Add the neighboring walls of the cell to the wall list.

  Remove the wall from the list.
Note that simply running classical Prim's on a graph with random edge weights would create mazes stylistically identical to Kruskal's, because they are both minimal spanning tree algorithms. Instead, this algorithm introduces stylistic variation because the edges closer to the starting point have a lower effective weight.

<img width="746" alt="image" src="https://github.com/user-attachments/assets/b930e229-4742-4f41-b04a-8899a73e0b3a" />
