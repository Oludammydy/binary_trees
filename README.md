# C - Binary trees

# binary_trees

A C-project assigned to a team of 2 by ALX
This is a group project where we learnt about the advantages,
and disadvantages of using trees as data structures. We learned how to
qualify trees and also, how to traverse them. 
Throughout the project, we implemented binary, made use of binary search, AVL, and Max Binary Heap trees.

## Tests :heavy_check_mark:

* [tests](./tests): Folder of test files for all tasks. Provided by ALX.

## Helper File :raised_hands:

* [binary_tree_print.c](./binary_tree_print.c): C function that prints binary
trees in a pretty way.

## Header File :file_folder:

* [binary_trees.h](./binary_trees.h): Header file containing definitions and
prototypes for all types and functions written for the project.

Data Structures
```
struct binary_tree_s
{
    int n;
    struct binary_tree_s *parent;
    struct binary_tree_s *left;
    struct binary_tree_s *right;
};

typedef struct binary_tree_s binary_tree_t;
typedef struct binary_tree_s bst_t;
typedef struct binary_tree_s avl_t;
typedef struct binary_tree_s heap_t;
```

Function Prototypes

| File                             | Prototype                                                                                        |
| -------------------------------- | ------------------------------------------------------------------------------------------------ |
| `binary_tree_print.c`            | `void binary_tree_print(const binary_tree_t *tree)`                                              |
| `0-binary_tree_node.c`           | `binary_tree_t *binary_tree_node(binary_tree_t *parent, int value);`                             |
| `1-binary_tree_insert_left.c`    | `binary_tree_t *binary_tree_insert_left(binary_tree_t *parent, int value);`                      |
| `2-binary_tree_insert_right.c`   | `binary_tree_t *binary_tree_insert_right(binary_tree_t *parent, int value);`                     |
| `3-binary_tree_delete.c`         | `void binary_tree_delete(binary_tree_t *tree);`                                                  |
| `4-binary_tree_is_leaf.c`        | `int binary_tree_is_leaf(const binary_tree_t *node);`                                            |
| `5-binary_tree_is_root.c`        | `int binary_tree_is_root(const binary_tree_t *node);`                                            |
| `6-binary_tree_preorder.c`       | `void binary_tree_preorder(const binary_tree_t *tree, void (*func)(int));`                       |
| `7-binary_tree_inorder.c`        | `void binary_tree_inorder(const binary_tree_t *tree, void (*func)(int));`                        |
| `8-binary_tree_postorder.c`      | `void binary_tree_postorder(const binary_tree_t *tree, void (*func)(int));`                      |
| `9-binary_tree_height.c`         | `size_t binary_tree_height(const binary_tree_t *tree);`                                          |
| `10-binary_tree_depth.c`         | `size_t binary_tree_depth(const binary_tree_t *tree);`                                           |
| `11-binary_tree_size.c`          | `size_t binary_tree_size(const binary_tree_t *tree);`                                            |
| `12-binary_tree_leaves.c`        | `size_t binary_tree_leaves(const binary_tree_t *tree);`                                          |
| `13-binary_tree_nodes.c`         | `size_t binary_tree_nodes(const binary_tree_t *tree);`                                           |
| `14-binary_tree_balance.c`       | `int binary_tree_balance(const binary_tree_t *tree);`                                            |
| `15-binary_tree_is_full.c`       | `int binary_tree_is_full(const binary_tree_t *tree);`                                            |
| `16-binary_tree_is_perfect.c`    | `int binary_tree_is_perfect(const binary_tree_t *tree);`                                         |
| `17-binary_tree_sibling.c`       | `binary_tree_t *binary_tree_sibling(binary_tree_t *node);`                                       |
| `18-binary_tree_uncle.c`         | `binary_tree_t *binary_tree_uncle(binary_tree_t *node);`                                         |
| `100-binary_trees_ancestor.c`    | `binary_tree_t *binary_trees_ancestor(const binary_tree_t *first, const binary_tree_t *second);` |
| `101-binary_tree_levelorder.c`   | `void binary_tree_levelorder(const binary_tree_t *tree, void (*func)(int));`                     |
| `102-binary_tree_is_complete.c`  | `int binary_tree_is_complete(const binary_tree_t *tree);`                                        |
| `103-binary_tree_rotate_left.c`  | `binary_tree_t *binary_tree_rotate_left(binary_tree_t *tree);`                                   |
| `104-binary_tree_rotate_right.c` | `binary_tree_t *binary_tree_rotate_right(binary_tree_t *tree);`                                  |
| `110-binary_tree_is_bst.c`       | `int binary_tree_is_bst(const binary_tree_t *tree);`                                             |
| `111-bst_insert.c`               | `bst_t *bst_insert(bst_t **tree, int value);`                                                    |
| `112-array_to_bst.c`             | `bst_t *array_to_bst(int *array, size_t size);`                                                  |
| `113-bst_search.c`               | `bst_t *bst_search(const bst_t *tree, int value);`                                               |
| `114-bst_remove.c`               | `bst_t *bst_remove(bst_t *root, int value);`                                                     |
| `120-binary_tree_is_avl.c`       | `int binary_tree_is_avl(const binary_tree_t *tree);`                                             |
| `121-avl_insert.c`               | `avl_t *avl_insert(avl_t **tree, int value);`                                                    |
| `122-array_to_avl.c`             | `avl_t *array_to_avl(int *array, size_t size);`                                                  |


</details>