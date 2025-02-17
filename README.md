# Maze-Generation-solving

Maze generation and maze solving in java

The maze is generated using an implimentation of Prim's iterative algorithm    
 + Start with a grid full of walls.
 + Pick a cell, mark it as part of the maze. Add the walls of the cell to the wall list.
 + While there are walls in the list:  
 + Pick a random wall from the list. If only one of the cells that the wall divides is visited, then:  
 + Make the wall a passage and mark the unvisited cell as part of the maze.  
 + Add the neighboring walls of the cell to the wall list.
 + Remove the wall from the list.

   [!NOTE]
> Note that simply running classical Prim's on a graph with random edge weights would create mazes stylistically identical to Kruskal's, because they are both minimal spanning tree algorithms. Instead, this algorithm introduces stylistic variation because the edges closer to the starting point have a lower effective weight.




<img width="500" alt="image" src="https://github.com/user-attachments/assets/b930e229-4742-4f41-b04a-8899a73e0b3a" />


This is a demonstration of the maze generator in action  

 


https://github.com/user-attachments/assets/88a05883-93a0-4cd0-a56f-618299038f75


# Maze solving 
+ to solve I decided to use dfs (depth first search).

+ Depth first search works by choosing a path to go down and exploring it all the way till it hits a dead end (hence the name "depth". This is also called recursive backtracking.


# Other sources for further reading
https://bost.ocks.org/mike/algorithms/#maze-generation

https://en.wikipedia.org/wiki/Maze_generation_algorithm

