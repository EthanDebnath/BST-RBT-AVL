`# Tree Data Structures: Binary Search Tree, Red-Black Tree, and AVL Tree

Implementationz of these 3 tree data structures:

1. **Binary Search Tree (BST)**
2. **Red-Black Tree (RBT)**
3. **AVL Tree**

Each tree is implemented with basic operations: `insert`, `delete`, and `search`, specifically for integer data.

Tests are included to demonstrate and validate the functionality of each implementation.

## Project Structure

- `bst.py` - Implementation of a Binary Search Tree.
- `rbt.py` - Implementation of a Red-Black Tree.
- `avl.py` - Implementation of an AVL Tree.
- `tests/` - Contains test scripts for each tree type.

Usage
-----

Each tree class (BST, RBT, AVL) has three main operations:

-   `insert(key)`: Inserts a key into the tree.
-   `delete(key)`: Deletes a key from the tree.
-   `search(key)`: Searches for a key in the tree and returns the node if found.

### Running the Code

To test each implementation, you can run the Python files in the `tests` directory:

bash

Copy code

`# Test Binary Search Tree
python tests/test_bst.py

# Test Red-Black Tree
python tests/test_rbt.py

# Test AVL Tree
python tests/test_avl.py`

Each test script includes cases for inserting, searching, and deleting nodes, verifying the properties of each tree type.

Tree Details
------------

### 1\. Binary Search Tree (BST)

A basic implementation of a binary search tree where each node has at most two children. This tree is not self-balancing, so it can become unbalanced with skewed insertion sequences.

### 2\. Red-Black Tree (RBT)

A balanced binary tree where nodes are either red or black. The tree maintains balance using color properties and rotations, ensuring efficient operations. This implementation includes color flipping and rotation methods to preserve red-black properties.

### 3\. AVL Tree

A self-balancing binary search tree that maintains a balance factor of `-1`, `0`, or `1` for every node. Rotations are applied during insertions and deletions to ensure balance, keeping operations efficient.

Tests
-----

Each tree has a corresponding test script in the `tests` directory. Run the tests to verify the following:

-   Nodes are inserted and deleted correctly.
-   Tree-specific properties (balance in AVL and red-black properties in RBT) are maintained.

feel free to contribute!
