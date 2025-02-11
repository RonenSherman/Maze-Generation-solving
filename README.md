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


```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "id": 1,
      "properties": {
        "ID": 0
      },
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
              [-90,35],
              [-90,30],
              [-85,30],
              [-85,35],
              [-90,35]
          ]
        ]
      }
    }
  ]
}
```

<img width="500" alt="image" src="https://github.com/user-attachments/assets/b930e229-4742-4f41-b04a-8899a73e0b3a" />


This is a demonstration of the maze generator in action  

 


https://github.com/user-attachments/assets/88a05883-93a0-4cd0-a56f-618299038f75



