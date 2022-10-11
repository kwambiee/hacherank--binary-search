## BINARY SEARCH TREES
The height of a binary search tree is the number of edges between the tree's root and its furthest leaf. You are given a pointer, root , pointing to the root of a binary search tree. Complete the getHeight function provided in your editor so that it returns the height of the binary search tree.
Sample Input = [7,3,5,2,1,4,6,7]
Sample output = 3
![BinaryTrees.png]

## Here are the basic facts and terms to know about binary trees:

    - The convention for binary tree diagrams is that the root is at the top, and the subtrees branch down from it.
    - A node's left and right subtrees are referred to as children, and that node can be referred to as the parent of those subtrees.
    - A non-root node with no children is called a leaf.
    - Some node `a` is an ancestor of some node `b` if `b` is located in a left or right subtree whose root node is `a` . This means that the root node of binary tree `t`  is the ancestor of all other nodes in the tree.
    - If some node `a` is an ancestor of some node `b`, then the path from `a` to `b` is the sequence of nodes starting with `a`, moving down the ancestral chain of children, and ending with `b`.
    - The depth (or level) of some node `a` is its distance (i.e., number of edges) from the tree's root node.
    - Simply put, the height of a tree is the number of edges between the root node and its furthest leaf.
    - ![Screenshot (201).png]
    - ![Screenshot (203).png]