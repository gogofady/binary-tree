# binary-tree
binary tree data structures implemented in java 


This code implements a binary tree data structure, which is a tree data structure in which each node has at most two children, referred to as the left child and the right child. 

## Usage

To use this code, create an instance of the `BinaryTree` class and start adding nodes to the tree using the `insert` method. For example:

```java
BinaryTree tree = new BinaryTree();
tree.insert(5);
tree.insert(3);
tree.insert(8);
tree.insert(1);
tree.insert(4);
tree.insert(7);
tree.insert(9);
This will create a binary tree with the following structure:
       5
     /   \
    3     8
   / \   / \
  1   4 7   9
  
  The BinaryTree class also provides methods to traverse the tree in different orders:

inorder: Inorder traversal (left subtree, root, right subtree)
preorder: Preorder traversal (root, left subtree, right subtree)
postorder: Postorder traversal (left subtree, right subtree, root)
For example, to perform an inorder traversal of the tree and print the values of each node: tree.inorder();

## Implementation
The BinaryTree class is implemented using a recursive approach, where each node in the tree is an instance of the Node class. Each Node object contains a value and references to its left and right children.
