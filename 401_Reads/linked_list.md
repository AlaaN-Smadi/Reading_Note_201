## Linked  List

**A Linked List is a sequence of Nodes that are connected/linked to each other.**
**each Node references the next Node in the link.**

=> There two types of linked list :
1. Singly : Means that there is only one reference, and the reference points to the Next node in a linked list.
2. Double : Means that there is a reference to both the Next and Previous node.


###  What is **Node** ?

**Nodes are the individual items/links that live in a linked list. Each node contains the data for each link.**

### What is **Next** ? 

**Each node contains a property called Next. This property contains the reference to the next node.**

### What is **Head** ?
**The Head is a reference of type Node to the first node in a linked list.**

### What do we mean by **Current**

**The Current is a reference of type Node to the node that is currently being looked at. When traversing, you create a new Current variable at the Head to guarantee you are starting from the beginning of the linked list.**


## Difference Between Linked List and Arrays =>

Difference | Array | Linked list
 --------- | ----- | -------
Access Data | O(1) | O(n)
Add, Delete | O(n) | O(n)
Memory Allocation | Static | Dynamic
When is beter to use | When you need to access data because it is fast | When you need to make a lot insert, add and delete because it is fast 

