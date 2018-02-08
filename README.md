##AVL Tree

###This is a self-balancing binary search tree

According to Wikipedia, an **AVL tree** , named after inventors **A**delson-**V**elsky and **L**andis is a self-balancing binary search tree. The heights of the two child subtrees of any node differ by at most one; if at any time they differ by more than one, rebalancing is done to restore this property. 



__BalanceFactor = Heigh of Right Subtree - Height of Left subtree__

__Insertion__

Whenever a node insertion happens, the tree rotates based on the _BalanceFactor_, thereby adding the new node to the best place where the tree is most balanced. 



__Rotation__

There are two types of rotations - single rotation and double rotation 