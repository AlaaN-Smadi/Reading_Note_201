## class 14

## Event Driven Architecture

#### What’s the difference between a FIFO and a standard queue?

=> Standard queue tries to preserve the order of messages (best-effort), but there is a possibility of a message being delivered out of order.
=> FIFO queue, messages are grouped into Message groups and all messages within a message group are sent and received in strict order.



#### How can the server be assured a message was properly received?

=> By storing the messages at the message queue until the client is confirmed that the message was received, then delete it .



#### What classic design pattern is best represented by event driven programming?

=> Event-driven from end to end: the request-reply model is especially common in browser-server interactions.

=> Consume and Project: this pattern can help when you have a bottleneck legacy service that stores “popular” data of large domain objects.

#### How do you test an event driven system?

=> By providing different events that test a variety of different conditions.