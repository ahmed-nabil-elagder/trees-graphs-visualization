# trees-graphs-visualization
Its a reference to visualize some of core concepts of **Trees** and **Graphs** data structures  



## Normal Tree vs Programming Tree - visualization  
<img src="https://github.com/ahmednabil88/trees-graphs-visualization/blob/master/Trees%20-%20Normal%20Tree%20vs%20Programming%20Tree/Normal%20Tree%20vs%20Programming%20Tree.gif" >  


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
	BFS (Breadth First Search)
		1.  Enqueue root node into a Queue
		2.  While Queue is not empty => (Iterative)
			2.1 Dequeue Queue - current node
			2.2 [[ traverse current node ]]
			2.3 [[ mark current node as visited ]]
			2.4 For Each NON-Visited neighbors 
				=> Enqueue into Queue

<img src="https://github.com/ahmednabil88/trees-graphs-visualization/blob/master/Graph%20Search/Graph%20Search.gif" >

