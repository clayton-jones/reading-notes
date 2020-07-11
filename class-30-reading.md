**[Back](https://clayton-jones.github.io/reading-notes/)**

# Class 30 Reading - Graphs  


Graphs are... not really graphs. They are essentially linked lists, or messy trees, that maybe have a defined structure, but maybe not. A graph generally has a starting point, which is a node, and that node could be linked to other nodes. Graphs can also be cyclic, which means that at some point, a node links back to the starting node, so it is important to modify a property on each node when traversing, so that you don't get stuck in loop hell. You could represent a graph with an object, where each key is a vertices, or node, and it's value is an array of all other nodes that that node is connected to.


I found [this video](https://www.youtube.com/watch?v=DBRW8nwZV-g) to be a nice short explanation and visualization of graphs.