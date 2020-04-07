# A-Path-Finding-Visualization
A python visualization of the A* path finding algorithm. It allows you to pick your start and end location,
 and view the process of finding the shortest path.

This is a basic pathfinding algorithm, based on Dijkstra's algorithm. Also known as a best-first search algorithm, 
 the core logic is shared with many algorithms, such as A*('A star')
 
# Modules used:
- TKinter
- Pygame
 
 
A-star (also referred to as A*) is one of the most successful search algorithms to find the shortest path between nodes or graphs.
 It is an informed search algorithm, as it uses information about path cost and also uses heuristics to find the solution.
 
# Illustrations:
F = G + H
One important aspect of A* is f = g + h. The f, g, and h variables are in the Node class and get calculated every time we create a new node.
 
 Here, these variables means;
F- is the total cost of the node.
 G- is the distance between the current node and the start node.
 H- is the heuristic — estimated distance from the current node to the end node.
 
# Types of Algorithms used:
# Breadth First Search;- explores equally in all directions.
 This is an incredibly useful algorithm, not only for regular path finding,
 but also for procedural map generation, flow field pathfinding, distance maps, and other types of map analysis.
 
# Dijkstra’s Algorithm (also called Uniform Cost Search);-
 lets us prioritize which paths to explore. Instead of exploring all possible paths equally, 
 it favors lower cost paths. We can assign lower costs to encourage moving on roads, higher costs to avoid forests, 
 higher costs to discourage going near enemies, and more. When movement costs vary, this is mostly used instead of Breadth First Search.
 
# A*;- 
  Is a modification of Dijkstra’s Algorithm that is optimized for a single destination. 
  Dijkstra’s Algorithm can find paths to all locations; A* finds paths to one location, or the closest of several locations. 
  It prioritizes paths that seem to be leading closer to a goal.
 
 

# Links for further learning and documentation:
#      https://towardsdatascience.com/a-star-a-search-algorithm-eb495fb156bb
#      https://www.python.org/doc/essays/graphs/
#      https://medium.com/@nicholas.w.swift/easy-a-star-pathfinding-7e6689c7f7b2
#      https://www.codementor.io/blog/basic-pathfinding-explained-with-python-5pil8767c1
#      https://www.redblobgames.com/pathfinding/a-star/introduction.html
#      https://www.analytics-link.com/post/2018/09/14/applying-the-a-path-finding-algorithm-in-python-part-1-2d-square-grid
#      https://www.reddit.com/r/Python/comments/2cifcb/introduction_to_the_a_pathfinding_algorithm_in/cjg2kwg/
