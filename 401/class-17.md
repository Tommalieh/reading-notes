# Socket  
 
## Web Sockets  
  - It is an advanced technology that makes it possible to open a two-way interactive communication session between the user's browser and a server  
  - you can send messages to a server and receive event-driven responses without having to poll the server for a reply  

## Socket.io  
  - is a library that enables real-time, bidirectional and event-based communication between the browser and the server  
  - It consists of:  
    + a Node.js server: Source | API  
    + a Javascript client library for the browser (which can be also run from Node.js): Source | API  
  - With Socket.io, you connect to a server over HTTP  
  - With Socket.io, the entire purpose is to have events shared between ‘disconnected’ participants. Through a mediator (server), clients connect, emit events, and respond to events from the server  

![socket.IO](https://realtimeapi.io/wp-content/uploads/2017/09/image09.png)  


## Difference Between WebSocket and Socket.io  
  1. **WebSocket**  
    - WebSocket helps in real-time communication between the Client and the web server  
    - This protocol helps in transforming to cross-platform in a real time world between the server and the client  
    - This also enables the business around the world for real-time web application to enhance and to increase the feasibility  
    - The major advantage it stands over an HTTP connection that it provides full duplex communication  

  2. **Socket.IO**  
    - It helps in broadcasting to multiple sockets at a time and handles the connection transparently  
    - It works on all platform, server or device ensuring the equality, reliability, and speed  
    - It automatically upgrades the requirement to WebSocket if needed  
    - It is a custom real-time transport protocol implementation on top of other protocols  
    - It requires both libraries to be used Client side as well as a server-side library  
    - IO works on work-based events. there are some reserved events which can be accessed using the Socket on server side like Connect, message, Disconnect, Ping and Reconnect  
    - There are some Client based reserved events like Connect, connect- error, connect-timeout and Reconnect etc.  

    



 

