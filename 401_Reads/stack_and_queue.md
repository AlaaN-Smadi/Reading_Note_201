
### Stack and Queue

**Stack** =>

It is a data structure that consists of Nodes. Each Node references the next Node in the stack, but does not reference its previous.

**=> Common Methods**

- Push - Nodes or items that are put into the stack are pushed

- Pop - Nodes or items that are removed from the stack are popped. When you attempt to pop an empty stack an exception will be raised.

- Top - This is the top of the stack.

- Peek - When you peek you will view the value of the top Node in the stack. When you attempt to peek an empty stack an exception will be raised.

- IsEmpty - returns true when stack is empty otherwise returns false.


**Stacks Common Concepts =>**

1. First In Last Out 'FILO'
2. Last In First Out 'LIFO'

These two concepts mean : The first item added in the stack will be the last item popped out of the stack. && The last item added to the stack will be the first item popped out of the stack.

----------------------

**Queue** =>

It is a data structure that consists of Nodes. Each Node references the next Node in the stack, and reference its previous.


**=> Common Methods**

- Enqueue - Nodes or items that are added to the queue.

- Dequeue - Nodes or items that are removed from the queue. If called when the queue is empty an exception will be raised.

- Front - This is the front/first Node of the queue.

- Rear - This is the rear/last Node of the queue.

- Peek - When you peek you will view the value of the front Node in the queue. If called when the queue is empty an exception will be raised.

- IsEmpty - returns true when queue is empty otherwise returns false.

**Queue Common Concepts =>**

1. First In First Out 'FIFO'
2. Last In Last Out 'LILO'

These two concepts mean : The first item in the queue will be the first item out of the queue. && The last item in the queue will be the last item out of the queue.