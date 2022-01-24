# Finding-Internal-Nodes-in-a-General-Tree

A function to find the number of internal nodes in a general tree, given a parent array. 
Let's assume we have a generic tree composed of consecutive integers (so if there is a 6 all numbers starting from and including 0 up to it also
need to exist on the tree).

Then we define this tree with a list L: [4, 4, 1, 5, -1, 4, 5] such as L(i) identifies the parent of i (the root has no parent and is denoted with -1).
An internal node is any node (except the root) of a tree that has at least one child.
