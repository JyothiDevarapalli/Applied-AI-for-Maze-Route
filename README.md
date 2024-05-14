# Applied-AI-for-Maze Navigation Using DFS and BFS

This Python project applies Depth-First Search (DFS) and Breadth-First Search (BFS) algorithms to navigate a maze from a start point (blue cell) to a destination point (red cell). It's built using the pyamaze library, which allows for the creation and visualization of mazes in a graphical interface. Users can choose either DFS or BFS to solve the maze and visually track the pathfinding process.

**Maze Creation:** The maze is generated using the pyamaze library, which can be customized through a CSV file input.

**Algorithm Execution:** Depending on the user's choice, either DFS or BFS is executed to find the path from the start to the destination:

1. DFS utilizes a stack to explore the maze by going as deep as possible along a branch before backtracking.
2. BFS uses a queue to explore the maze level by level, ensuring the shortest path is found.
   
**Visualization:** The pathfinding process and the final path are displayed using agents in the pyamaze maze.
