## Binary Tree

![Binary Tree](https://www.freecodecamp.org/news/content/images/size/w1000/2021/10/image-57.png)

## Description of a binary tree
A binary tree is a tree data structure used in computer science where each node can have a maximum of two children: a left child and a right child. It is a particular variety of k-ary tree, with k=2.

Set theory can be used to define a binary tree recursively. It is made up of the tuple (L, S, R), where L and R are binary trees that are themselves (or the empty set), and S is a singleton set that contains the root node. Notably, some authors also regard the empty set as a legitimate binary tree.

This concept emphasizes the binary tree's hierarchical structure, where nodes can be arranged into levels and have parent-child relationships with their neighboring nodes. Due to its adaptability and effective traversal characteristics, the binary tree structure is frequently employed in many algorithms and data structures in computer science.

## Binary Tree

``bash
  /**
 * struct binary_tree_s - Binary tree node
 *
 * @n: Integer stored in the node
 * @parent: Pointer to the parent node
 * @left: Pointer to the left child node
 * @right: Pointer to the right child node
 */
struct binary_tree_s
{
    int n;
    struct binary_tree_s *parent;
    struct binary_tree_s *left;
    struct binary_tree_s *right;
};

typedef struct binary_tree_s binary_tree_t;
```
- Binary Search Tree:
```bash
  typedef struct binary_tree_s bst_t;
```
- AVL Tree
```bash
  typedef struct binary_tree_s avl_t;
```
- Max Binary Heap
```bash
  typedef struct binary_tree_s heap_t;
```
## Author
- Ahmed Toukebri
