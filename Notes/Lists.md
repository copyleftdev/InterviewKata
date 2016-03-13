Lists

Understand trade-offs with respect to arrays. Be com-fortable with iteration, insertion, and deletion within singly and doubly linked lists. Know how to imple-ment a list with dynamic allocation, and with arrays.

An abstract data type (ADT) is a mathematical model for a class of data structures that have similar functionality. Strictly speaking, a list is an ADT, and not a data structure. It implements an ordered collection of values, which may be repeated. In the context of this book we view a list as a sequence of nodes where each node has a link to the next node in the sequence. In a doubly linked list each node additionally has a link to the prior node.

A list is similar to an array in that it contains objects in a linear order. The key differences are that inserting and deleting elements in a list has time complexity 0(1). On the other hand, obtaining the fc-th element in a list is expensive, having 0(n) time complexity. Lists are usually building blocks of more complex data structures.
