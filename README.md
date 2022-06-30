# Find-next-larger-element-of-an-integer-n-in-a-generic-tree
In this repo. i will post the code to find next larger element than an integer n in a generic tree

To solve this problem we will first declare a variable(ans) of type TreeNode and initialise it to null,
then we will check if root's value is greater than the given integer n,
if it's greater than we give ans variable the address of root

then we will iterate through the children of root to do the same process for them
If ans value of ans returned we children is less than the current answer we will update our answer

and finally we will return our answer
