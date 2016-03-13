Arrays & strings

Fast access for element at an index, slow lookups (un-less sorted) and insertions. Be comfortable with notions of iteration, resizing, partitioning, merging, etc. Know how strings are represented in memory. Under-stand basic operators such as comparison, copying, matching, joining, splitting, etc.


Conceptually, an array maps integers in the range [0, n - 1] to objects of a given type, where n is the number of objects in this array. Array lookup and insertion are fast, making arrays suitable for a variety of applications. Reading past the last element of an array is a common error, invariably with catastrophic consequences.
The following problem arises when optimizing quicksort: given an array A whose elements are comparable, and an index i, reorder the elements of A so that the initial elements are all less than A[i], and are followed by elements equal to A[i], which in turn are followed by elements greater than A[i\, using 0( 1) space.
The key to the solution is to maintain two regions on opposite sides of the array that meet the requirements, and expand these regions one element at a time. 
