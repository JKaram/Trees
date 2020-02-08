# Trees
 
While learning how to program we learn about functions, arrays, strings, integers, booleans, ... etc.  Before learning how to program I liked trees, they are colorful and convert harmful carbon dioxide into air. That's really cool! However after learning how to program I dislike trees. Why is something that is so familiar so hard to understand?
 
## What are Trees?
 
Trees on the surface are actually easy to understand. Trees represent hierarchy and can be traversed recursively. Like a real tree we start at the root. The root node is the base to any tree,every node in a tree either has a child or is considered a leaf node (a node with no children). A root node is just like any node, in that it is part of a data structure which consists of one or more fields with links to other nodes and contains a data field; it simply happens to be the first node. Nodes are linked to their parent or child.
 
!["Binary Tree"](https://raw.githubusercontent.com/JKaram/Trees/master/docs/tree.png)
 
Take this diagram for example. Node '2' is the root, and has two children. Node 7 has one parent Node '2' and three children Node '2', Node '10', and Node '6'.
 
Node '5', 11 , and 4 are considered leaf nodes.
 
## How to traverse a tree
 
So how do we traverse a tree. An array is easy to loop through, but how can one access the data they need if it's scattered about.
 
We use recursion!
 
!["Recursion"](https://github.com/JKaram/Trees/blob/master/docs/1_appBwh6_RtvocVxwqpplHA.jpeg?raw=true)
 
 
Recursion allows us to as the node what data it has. If its not what we need the helpful node will point us to its parent of its child.
 
 
## Do I need to know this?
 
Yes. Trees are unlike other data structures that we use but they are very necessary and do not have to be that scary.


## Sources

https://www.techopedia.com/definition/21839/root-node

https://en.wikipedia.org/wiki/Tree_(data_structure)