# trees-graphs-visualization
Its a reference to visualize some of core concepts of **Trees** and **Graphs** data structures  



## Normal Tree vs Programming Tree - visualization  
<img src="https://github.com/ahmednabil88/trees-graphs-visualization/blob/master/Trees%20-%20Normal%20Tree%20vs%20Programming%20Tree/Normal%20Tree%20vs%20Programming%20Tree.gif" >  

## Difference between (Node Depth) and (Node High) - visualization  
	The Depth of a node
		1. Is the number of edges from the node to the tree's root node
		2. Root node will have a Depth of 0
	The Height of a node
		1. Is the number of edges on the longest path from the node to a leaf
		2. Leaf node(s) will have a Height of 0
		
<img src="https://github.com/ahmednabil88/trees-graphs-visualization/blob/master/Trees%20-%20Node%20Depth%20vs%20Node%20High/Trees%20-%20Node%20Depth%20vs%20Node%20High.gif" >  

## Graph data structure representation - visualization  
	In terms of programming, there are two common ways to represent a graph.
		1. By Adjacency List
		2. By Adjacency Matrix
		
<img src="https://github.com/ahmednabil88/trees-graphs-visualization/blob/master/Graph%20-%20Adjacency%20List%20vs%20Adjacency%20Matrix/Graph%20-%20Adjacency%20List%20vs%20Adjacency%20Matrix.gif" >

## Trees Traversals - visualization  
	PreOrderTravesal
		1. [[ traverse current node ]]
		2. traverse left tree
		3. traverse right tree
	InOrderTravesal
		1. traverse left tree
		2. [[ traverse current node ]]
		3. traverse right tree
	PostOrderTravesal
		1. traverse left tree
		2. traverse right tree
		3. [[ traverse current node ]]

<img src="https://github.com/ahmednabil88/trees-graphs-visualize/blob/master/Trees%20Traversals/Pre-In-Post%20Traversal.gif" >

## Graph Search - visualization  
For simplicity, we will visualize over Trees as Trees are special subtype of Graghs  
*Trees are already Graphs but without CYCLES*

	DFS (Depth First Search)
		1. [[ traverse current node ]]
		2. [[ mark current node as visited ]]
		3. For Each NON-Visited neighbors 
			=> visit it (Recursion)
			Note: DFS can be also implemented by Stack (Iterative)
	BFS (Breadth First Search)
		1.  Enqueue root node into a Queue
		2.  While Queue is not empty => (Iterative)
			2.1 Dequeue Queue - current node
			2.2 [[ traverse current node ]]
			2.3 [[ mark current node as visited ]]
			2.4 For Each NON-Visited neighbors 
				=> Enqueue into Queue

<img src="https://github.com/ahmednabil88/trees-graphs-visualization/blob/master/Graph%20Search/Graph%20Search.gif" >


