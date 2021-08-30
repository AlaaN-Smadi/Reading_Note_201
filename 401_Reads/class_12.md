## Class_12

### Socket.io


**What is the benefit of transforming data into packets?**

- meet the demands of pervasive data-centric applications and services.

- redundancies for full visibility

- most cost-effective, efficient, and scalable networks for content delivery.


**UDP is often refereed to as a connectionless protocol. Why is this?**

**because it is analogous to sending a letter where you don't acknowledge receipt.**
UDP : (User Datagram Protocol) is a lightweight data transport protocol that works on top of IP.

**Can a socket server application have multiple socket connections?**

Yes, Multiple connections on the same server can share the same server-side IP/Port pair as long as they are associated with different client-side IP/Port pairs, and the server would be able to handle as many clients as available system resources allow it to.

**Can a socket connection application be connected to multiple socket servers?**

A connected socket is assigned to a new (dedicated) port, so it means that the number of concurrent connections is limited by the number of ports, unless multiple sockets can share the same port.(16bit)

**Can an application be both a socket server and a socket connection?**

No, you can’t have two client sockets connect to each other in TCP, as the low-level connection protocol doesn’t work that way.

------------------------------

### Term =>

**Observer Pattern** : The observer pattern is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods.


**Listener** : An event listener is a procedure in JavaScript that waits for an event to occur. The simple example of an event is a user clicking the mouse or pressing a key on the keyboard.


**Event Handler** : is a callback routine that operates asynchronously and handles inputs received into a program (events)


**Event Driven Programming** : In computer programming, event-driven programming is a programming paradigm in which the flow of the program is determined by events such as user actions (mouse clicks, key presses), sensor outputs, or message passing from other programs or threads.


**Event Loop** :  is a programming construct or design pattern that waits for and dispatches events or messages in a program.


**Event Queue** : is a repository where events from an application are held prior to being processed by a receiving program or system. Event queues are often used in the context of an enterprise messaging system.


**Call Stack** : is a stack data structure that stores information about the active subroutines of a computer program


**Emit/Raise/Trigger** : The emit() function raises the specified event. First parameter is name of the event as a string and then arguments. An event can be emitted with zero or more arguments.


**Subscribe** : To receive messages sent to a particular channel, you subscribe to it.


**database** : is an organized collection of structured information, or data, typically stored electronically in a computer system