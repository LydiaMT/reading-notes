## Read: Class 13 - Message Queues

### Review, Research, and Discussion

**1. What does it mean that web sockets are bidirectional? Why is this useful?**

It means that a socket must be handled by both the client-side and the server-side. It's useful for easily pushing data from the server to the client and vice versa[stackoverflow](https://stackoverflow.com/questions/12366651/how-the-websocket-bi-directional-concept-work)

**2. Does socket.io use HTTP? Why?**

Yes. You can provide it one, or if you do not provide one it will create one for you [stackoverflow](https://stackoverflow.com/questions/33188147/socket-io-without-http-server)

**3. What happens when a client emits an event?**

The event is passed from the client to the server through websockets [stackoverflow](https://stackoverflow.com/questions/48332454/how-does-socket-io-on-the-client-listen-to-events-emitted-from-server)

**4. What happens when a server emits an event?**

The event is passed from the server to the client 

**5. What happens if a client “misses” an event?**

The event is lost

**6. How can we mitigate this?**

You can add systems to replay, retry, or resend the event. 

**Term** | **Definition**
-----|-----
Socket | Software structure within a network node of a computer network that serves as an endpoint for sending and receiving data across the network [wiki](https://en.wikipedia.org/wiki/Network_socket)
Web Socket | A WebSocket is a persistent connection between a client and server. WebSockets provide a bidirectional, full-duplex communications channel that operates over HTTP through a single TCP/IP socket connection [Kevin Sookocheff](https://sookocheff.com/post/networking/how-do-websockets-work/)
Socket.io | Socket.IO is a JavaScript library for realtime web applications. It enables realtime, bi-directional communication between web clients and servers. [Wiki](https://en.wikipedia.org/wiki/Socket.IO)
Client | Something making a web request
Server | Something sending a web response
OSI Model | The OSI Model (Open Systems Interconnection Model) is a conceptual framework used to describe the functions of a networking system. It's made up of seven different abstraction layers: Physical, Data Link, Network, Transport, Session, Presentation, and Application. [CYBER EDU](https://www.forcepoint.com/cyber-edu/osi-model) 
TCP Model |  Concise version of the OSI model. It contains four layers: Process/Application Layer, Host-to-Host/Transport Layer, Internet Layer, Network Access/Link Layer [GeeksForGeeks](https://www.geeksforgeeks.org/tcp-ip-model/)
TCP | Transmission Control Protocol. Standard that defines how to establish and maintain a network conversation through which application programs can exchange data [TechTarget](https://searchnetworking.techtarget.com/definition/TCP)
UDP | User Datagram Protocol is one of the core members of the Internet protocol suite. With UDP, computer applications can send messages, in this case referred to as datagrams, to other hosts on an Internet Protocol (IP) network [Wiki](https://en.wikipedia.org/wiki/User_Datagram_Protocol)
Packets | In networking, a packet is a small segment of a larger message. Data sent over computer networks*, such as the Internet, is divided into packets. These packets are then recombined by the computer or device that receives them. [CloudFlare](https://www.cloudflare.com/learning/network-layer/what-is-a-packet/)


### Preview
- [Socket.io Chat Example](https://socket.io/get-started/chat/)
- [Rooms and Namespaces](https://socket.io/docs/v3/rooms/index.html)
- [Socket.io Emit Cheatsheet](https://socket.io/docs/v3/emit-cheatsheet/index.html)

1. Which 3 things had you heard about previously and now have better clarity on?

sockets, emitted events, socket.io

1. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?

TCP, UDP, OSI

1. What are you most excited about trying to implement or see how it works?

More practice with events

[⬅ Back to README Home](README.md)
