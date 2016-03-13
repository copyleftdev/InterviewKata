Understand insertion and deletion. Know array and linked list implementations.


Stacks support last-in, first-out semantics for inserts and deletes, whereas queues are first-in, first-out. Both are ADTs, and are commonly implemented using linked lists or arrays. Similar to lists, stacks and queues are usually building blocks in a solution to a complex problem, but can make for interesting problems in their own right.
As an example consider the problem of evaluating Reverse Polish notation expres¬ sions,i.e.,expressionsof theform"3,4,X,1,2,+,+","1,1,+,-2,x",or"4,6,/,2,/" A stack is ideal for this purpose—operands are pushed on the stack, and popped as operators are processed, with intermediate results being pushed back onto the stack.
