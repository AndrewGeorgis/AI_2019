# AI_2019
# Getting Started
The aim of the work is to apply search algorithms and find the best path in a square grid of dimensions $N\times N$. Initially, our goal is to construct search problems in square tracks, where there is at least one path to go from a starting point to a goal. 
The user gives a probability p and then we construct randomly a maze, within the two points. The regions of the grid are obstacles. As we create the maze we certify that inside the maze will be a path from the start point to the finish point. Thereafter we create an abstract pathfinding function that takes a number g which is the distance we have traversed from the beginning until the node that algorithm expand and the heuristic function that gives us an approximate distance from the current point to the finish point. After that the pathfindind class return the optimal path for different values of g(cost) and h(heuristic function). At the end we compare the different algorithms.

The left image is an arbitary map and the right image is the final map with the optimal path.

![alt text](https://github.com/AndrewGeorgis/AI_2019/blob/f1514293be90433e0a6f156025d4aef96ac109fe/initial.PNG)
![alt text](https://github.com/AndrewGeorgis/AI_2019/blob/45b02fd19a9080b09f0a9dbf5bad54345b92b8d7/finalpath.PNG)
