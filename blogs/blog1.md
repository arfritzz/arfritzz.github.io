# Some Haskell Fundamentals

## Trees

Trees can be characterized by the amount of children per node. For example, a binary search tree (BST) allows each node to have only two children. This type of representation comes in handy often. Lets say we want to create a structure to hold all students enrolled in a university. To do this, we might alphabetize the students and arrange them such that the left branch of the tree holds students with names A-N and the right half hold those M-Z. In this way, when we want to know more about a student with a last name F, we must only search half the tree. 

