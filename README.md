# wdi-graphs

## Graph Definition
Graph data structure consists of a finite set of vertices, together with a set of unordered pairs of these vertices for an undirected graph or a set of ordered pairs for a directed graph. 

These pairs are known as edges, and for a directed graph are also known as arrows. 

## Real life uses of Graphs
+ Transportation networks
+ Facebook Social connections
+ Google Maps 


## Graph Components

<img width="651" alt="graph components" src="https://github.com/mclausaudio/wdi-graphs/blob/master/Screen%20Shot%202019-04-03%20at%209.59.40%20AM.png">

### Vertex
- also known as node
- holds individual data element of a graph

### Edge
- also known as arc
- the connecting link between two vertices

## Types of Graphs

<img width="651" alt="graph example" src="https://github.com/mclausaudio/wdi-graphs/blob/master/Screen%20Shot%202019-04-03%20at%2011.12.31%20AM.png">

Graphs can be **undirected** or **directed**.

**Undirected**: if 6 was a friend of 4, 4 would likewise be a friend of 6. The relationship exists in both directions :dancers:. 

**Directed**: if 6 has a crush on 4; doesn't necessarily mean 4 has to have a crush on 6. Feelings may not be reciprocal :broken_heart:. 

From these examples, these relationships are based on the direction of the edges. It can be a one way or two way relationship but it must be stated.


## Breadth First Search Vs Depth First Search 

<img width="300" alt="jokes" src="https://github.com/mclausaudio/wdi-graphs/blob/master/laugh.gif">


Both are algorithms used for traversing or searching tree or graph data structures. DFS (Depth First Search) use stacks and BFS (Breadth First Search use queues.

<img width="651" alt="graph example" src="https://github.com/mclausaudio/wdi-graphs/blob/master/bsvds.gif">

**Depth First Search**

 - Begins at a root node and will explore all possible branches of the most adjacent node before backtracking to search through the next adjacent node if present. (Recursive Algorithm)
 - Because it uses a stack to search through paths, it will use a LIFO method to search each path. The root node will be the last to exit the stack 
 
   **Applications for DFS**
    - Detecting a cycle in a graph
    - Path Finding
    - Topological Sorting
    - Solving puzzles with only one solution(Like a Maze)
    
  <img width="200" alt="" src="https://github.com/mclausaudio/wdi-graphs/blob/master/maze.gif">

    
**Breadth First Search**

 - Begins at a the "search key" node and will explore all neighbor nodes at the present depth prior to moving on to the nodes at the next level
 - Unlike the DFS, it will not backtrack because BFS uses queues (FIFO method) to search paths.
 
   **Applications for BFS**
    - Finding the shortest path between nodes
    - Peer to Peer Networks
    - Social Networking Sites
    - GPS Navigation
    - Broadcasting in Network

  <img width="200" alt="" src="https://github.com/mclausaudio/wdi-graphs/blob/master/BFS.gif">
  







## Resources
[A Gentle Introduction to Data Structures: How Graphs Work](https://medium.freecodecamp.org/a-gentle-introduction-to-data-structures-how-graphs-work-a223d9ef8837) 

[From Theory to practice. Representing Graphs.](https://medium.com/basecs/from-theory-to-practice-representing-graphs-cfd782c5be38)

[Graph Algorithms - Interview Questions](https://www.codementor.io/rishabhdaal/graph-algorithms-interview-questions-du1085u8l)

[Graph Data Structures for Beginners](https://adrianmejia.com/blog/2018/05/14/data-structures-for-beginners-graphs-time-complexity-tutorial/#Breadth-first-search-BFS-Graph-search)




