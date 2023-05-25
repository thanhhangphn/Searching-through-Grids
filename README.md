# Searching-through-Grids

This project uses Heap (Priority Queue), Queue, Stack, Grid, and LinkedList to use different search algorithms to search through grids, which is to compare the implementations of DFS, BFS, and A* search algorithms.

The result is a graphic visualization of components of each search, along with analysis of the operation of those three different algorithms.

## Description

BFS and A* give paths with relatively similar lengths, while BFS always gives paths with significantly longer lengths, especially when the density
gets lower: When the density is lower, there are more possible paths to reach the target and DFS, not taking into account the shorter paths, would likely go into the longer paths. As BFS explores all possibilities, it would stop at the path that first reaches the target, which is the shortest path. As A* prioritize the shortest estimated distance to target when choosing Cells to explore, it will likely go the shortest path.

The number of cells explored by DFS and BFS is always higher than that of A*: DFS is likely to go into a very long path, which takes up many cells and BFS explores all a breadth of possibilities, which also takes up many cells. A* has a priority system thus is more likely to use less cells.

In a priority queue, the elements have a priority: the elements with higher priority are served first. Thus, priority queues are used to select the next process to
run, ensuring high-priority tasks run before low-priority ones. Like BFS, A* search uses a queue to keep track of the next set of nodes to visit, but a priority queue
ensures that nodes with minimum cost are visited first. Thus, the PriorityQueue / Heap helps to access the elements in a faster way, allowing time efficiency.

## Sources/Credits
Colby College's CS231 (Data Structures and Algorithms)'s resources
