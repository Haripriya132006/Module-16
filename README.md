# 📘 Module 16: Advanced Tree Data Structures in C
## 🏁 Aim
To implement and demonstrate operations on advanced tree data structures—AVL Trees, B Trees, and B+ Trees—using the C programming language.

## 📂 Contents
### AVL Trees:

delete_node_AVLtree.md: Deletion operation in an AVL Tree.

right_rotation_AVLtree.md: Right rotation operation in an AVL Tree.

### B Trees:

insert_and_delete_in_Btree.md: Insertion and deletion operations in a B Tree.

### B+ Trees:

insert_elements_in_a_B+tree.md: Insertion operation in a B+ Tree.

### Images:

image.png, image-1.png, image-2.png, image-3.png: Visual representations of tree structures and operations.

## 🔍 Algorithms Overview
### AVL Tree Operations
#### Deletion:

Locate the node to be deleted.

Perform standard BST deletion.

Update heights and balance factors.

Apply necessary rotations to maintain balance.

#### Right Rotation:

Identify the unbalanced node.

Perform a right rotation to rebalance the tree.
GitHub Docs

### B Tree Operations
#### Insertion:

Traverse to the appropriate leaf node.

Insert the key in sorted order.

If the node overflows, split and promote the median key.

#### Deletion:

Locate the key to be deleted.

If the key is in an internal node, find the predecessor or successor.

Merge or redistribute nodes as necessary to maintain properties.

### B+ Tree Operations
#### Insertion:

Navigate to the correct leaf node.

Insert the key in order.

If the leaf node overflows, split and propagate the middle key up.

## 📸 Visual Representations
The repository includes images (image.png, image-1.png, image-2.png, image-3.png) that illustrate the structure and transformations of the trees during various operations.

## ✅ Result
The programs effectively demonstrate the insertion, deletion, and rotation operations on AVL Trees, B Trees, and B+ Trees, maintaining their respective properties and ensuring balanced structures.
