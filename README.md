# AVL Trees

## Introduction

Consider the case when the following values are inserted in order into a Binary Search Tree : 1, 2, 3, 4
This would generate a skewed BST as follows :

<img src="./images/skewedBST.png" alt="Skewed BST"
	title="Skewed BST" width="150" height="100" />

Such a tree is not desirable since the complexities of all operations become Linear 

| Operation     |  Cool  |
| ------------- | -----: |
|     Search    |  O(n)  |
|     Insert    |  O(n)  |
|     Delete    |  O(n)  |

Hence AVL Trees are used. AVL Trees are self-balancing Binary Search Trees that balance the height of the tree after any insertion or deletion.

## Properties of AVL Trees

1. -1 ≤ h^R - h^L ≤ 1
	where h^R is the height of the right subtree and h^L is the height of the left subtree
The height of the left and right subtrees differ by no more than 1

2. The expression h^R - h^L is known as the Balance Factor, which can take only the values {-1, 0, 1}

<img src="./images/skewedBST.png" alt="Skewed BST"
	title="Skewed BST" width="350" height="300" />
	
(source : Wikipedia https://en.wikipedia.org/wiki/AVL_tree) shows how AVL Trees balance their height.

