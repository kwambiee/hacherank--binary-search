## BINARY SEARCH TREES

## Here are the basic facts and terms to know about binary trees:

    - The convention for binary tree diagrams is that the root is at the top, and the subtrees branch down from it.
    - A node's left and right subtrees are referred to as children, and that node can be referred to as the parent of those subtrees.
    - A non-root node with no children is called a leaf.
    - Some node `a` is an ancestor of some node `b` if `b` is located in a left or right subtree whose root node is `a` . This means that the root node of binary tree `t`  is the ancestor of all other nodes in the tree.
    - If some node `a` is an ancestor of some node `b`, then the path from `a` to `b` is the sequence of nodes starting with `a`, moving down the ancestral chain of children, and ending with `b`.
    - The depth (or level) of some node `a` is its distance (i.e., number of edges) from the tree's root node.
    - Simply put, the height of a tree is the number of edges between the root node and its furthest leaf.
    
![Screenshot (201)](https://user-images.githubusercontent.com/62090797/195047572-625b4c64-e90f-434e-908d-f7d13c6f9af7.png)
![Screenshot (203)](https://user-images.githubusercontent.com/62090797/195047676-b24b3553-5444-449d-b365-f8054ea1bb96.png)

## FIND DEPTH OF BST
The height of a binary search tree is the number of edges between the tree's root and its furthest leaf. You are given a pointer, root , pointing to the root of a binary search tree. Complete the getHeight function provided in your editor so that it returns the height of the binary search tree.
Sample Input = [7,3,5,2,1,4,6,7]
Sample output = 3
![Screenshot (204)](https://user-images.githubusercontent.com/62090797/195047745-e6aa6c47-7f0d-46dd-aaba-fba2cf8c8517.png)  ![Screenshot (205)](https://user-images.githubusercontent.com/62090797/195047827-d277d0df-ffb5-4b59-9b0c-944deb34b0e6.png)
