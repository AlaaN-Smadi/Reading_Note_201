## Class_13

### Message Queues

**What does it mean that web sockets are bidirectional? Why is this useful?**

WebSockets allow for full-duplex bidirectional communication, this enables the server to send real-time updates asynchronously, without requiring the client to submit a request each time. Yes it’s useful.

**Does socket.io use HTTP? Why?**

a socket.io server will attach to an HTTP server so it can serve its own client code through /socket.io/socket.io.js ( to communication with clients

**What happens when a client emits an event?**

The client emits an event and then the server handles the event using the on method.it would go the event handler

**What happens when a server emits an event?**

The event gets passed from the server to the client.

**What happens if a client “misses” an event?**

Unhandled events will be ignored

**How can we mitigate this?**

We could assign unique IDs to events in order to track them, log events, and make sure the client recieved the event.(You could avoid missing messages by always having the handlers installed and then deciding in the handlers (based on other state) whether to do anything with the message or not.)



-------------------------------

### Terms

**Socket** : allow communication between two different processes on the same or different machines

**Web Socket** : Web Socket is a protocol that provides full-duplex(multiway) communication i.e allows communication in both directions simultaneously


**Socket.io** : It is a library that enables real-time, bidirectional and event-based communication between the browser and the server.


**Client** : person or group that uses the professional advice or services of a lawyer, accountant, advertising agency, architect, etc. a person who is receiving the benefits,


**Server** : It  is a computer or system that provides resources, data, services, or programs to other computers, known as clients, over a network. In theory, whenever computers share resources with client machines they are considered servers.


**OSI Model** : The Open Systems Interconnection (OSI) model describes seven layers that computer systems use to communicate over a network.


**TCP Model** : TCP model defines how devices should transmit data between them and enables communication over networks and large distances. The model represents how data is exchanged and organized over networks


**TCP** : TCP stands for Transmission Control Protocol a communications standard that enables application programs and computing devices to exchange messages over a network.


**UDP** : User Datagram Protocol, or UDP, is a communication protocol used across the Internet for especially time-sensitive transmissions such as video playback or DNS lookups.


**Packets** :  it is a small segment of a larger message.

