Use for representing hierarchical data. Know about depth, height, leaves, search path, traversal sequences, successor/predecessor operations.


A binary tree is a data structure that is used to represent hierarchical relationships. Binary trees most commonly occur in the context of binary search trees, wherein keys are stored in a sorted fashion. However, there are many other applications of binary trees. Consider a set of resources organized as nodes in a binary tree. Processes need to lock resource nodes. A node may be locked if and only if none of its descendants and ancestors are locked. Your task is to design and implement an application programming interface (API) for locking.

A reasonable API is one with isLockO, lock(), and unLockO methods. Naively implemented the time complexity for these methods is 0(n),where n is the number of nodes. However these can be made to run in time 0(1),0(h),and0(h),respectively, where h is the height of the tree, if nodes have a parent field.
