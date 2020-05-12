**[Back](https://clayton-jones.github.io/reading-notes/)**

# Class 18 Reading - Socket.io  

## Discussion Questions:  
  
1. **What does it mean that web sockets are bidirectional? Why is this useful?**  

    *It means that the server can communicate to the socket, and vice versa. This is useful because it allows for easier implementation.*  

2. **Does socket.io use HTTP? Why?**  

    *Yes, it maintains the connection between the client and server.*  

3. **What happens when a client emits an event? What happens when a server emits an event?**  

    *Client emit: sent to the server.* 
    *Server emit: sent to all connected sockets.*

