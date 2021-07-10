# AI
Grid play game implementation for artificial intelligence.
Depth first search and Breath First Search implementation for AI.

## Programming Language
The language used is python. 

## Platform
Google Collaboratory Environment for Python

## Problem

Find the Shortest path from Starting point S to the end. 1st denote obstacles and 0s denote clear path. Two algorithms implemented to find the solution. 

-BFS

-DFS

## BFS

Breadth first search is a graph traversal algorithm that starts traversing the graph from root node and explores all the neighbouring nodes. Then, it selects the nearest node and explore all the unexplored nodes. The algorithm follows the same process for each of the nearest node until it finds the goal.

The algorithm starts with examining the node A and all of its neighbours. In the next step, the neighbours of the nearest node of A are explored and process continues in the further steps. The algorithm explores all neighbours of all the nodes and ensures that each node is visited exactly once and no node is visited twice.

## DFS

Depth first search (DFS) algorithm starts with the initial node of the graph G, and then goes to deeper and deeper until we find the goal node or the node which has no children. The algorithm, then backtracks from the dead end towards the most recent node that is yet to be completely unexplored.

The data structure which is being used in DFS is stack. The process is similar to BFS algorithm. In DFS, the edges that leads to an unvisited node are called discovery edges while the edges that leads to an already visited node are called block edges.

## Functions

1- Print grid 
2- Search Visited Array
3- BFS
4- DFS
