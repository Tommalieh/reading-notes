## Message Queuing:
Message queue provides an asynchronous communications protocol,which is a system that puts a message onto a message queue and does not require an immediate response to continuing processing.

## Message queuing:
allows applications to communicate by sending messages to each other. The message queue provides temporary message storage when the destination program is busy or not connected. 

## Message: the message is the data transported between the sender and the receiver application;it's essentially a byte array with some headers at the top.

## the queue: is a line of things waiting to be handled,starting at the beginning of the line and processing it in sequential order.

## event:  is What event has happened during transporting data (delete, add, update or connection lost ...etc)

## The payload : is the data associated with the event.

## Namespace: It is a declarative region that provides a scope to the identifiers (the names of types, functions, variables, etc) inside it. 
Namespaces are used to organize code into logical groups and to prevent name collisions that can occur especially when your codebase includes multiple libraries.

## Default namespace
We call the default namespace / and it’s the one Socket.IO clients connect to by default, and the one the server listens to by default.
