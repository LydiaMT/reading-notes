## Read: Class 12 - Socket.io

### Review, Research, and Discussion

**1. What is the benefit of transforming data into packets?**

It improves scalability

**2. UDP is often refereed to as a connectionless protocol. Why is this?**

User Datagram Protocol

**3. Can a socket server application have multiple socket connections?**
Yes. A server can handle 65536 sockets per single IP address [DZone](https://dzone.com/articles/load-balancing-of-websocket-connections)

**4. Can a socket connection application be connected to multiple socket servers?**

Yes because each socket connection application uses a different port

**5. Can an application be both a socket server and a socket connection?**

No. You can't have two client sockets connect to each other in TCP [stackoverflow](https://stackoverflow.com/questions/2578254/connect-two-client-sockets)


**Term** | **Definition**
-----|-----
Observer Pattern | Software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods. [Wiki](https://en.wikipedia.org/wiki/Observer_pattern)
Listener | An event listener is a procedure or function in a computer program that waits for an event to occur.[Computer Hope](https://www.computerhope.com/jargon/e/event-listener.htm)
Event Handler | An event handler is a routine that deals with the event, allowing a programmer to write code that is executed when the event occurs. [Computer Hope](https://www.computerhope.com/jargon/e/event.htm)
Event Driven Programming | In computer programming, event-driven programming is a programming paradigm in which the flow of the program is determined by events such as user actions (mouse clicks, key presses), sensor outputs, or message passing from other programs or threads. [Wiki](https://en.wikipedia.org/wiki/Event-driven_programming)
Event Loop | In computer science, the event loop is a programming construct or design pattern that waits for and dispatches events or messages in a program. [Event Loop](https://en.wikipedia.org/wiki/Event_loop)
Event Queue | An event queue is a repository where events from an application are held prior to being processed by a receiving program or system.[techopedia](https://www.techopedia.com/definition/24963/event-queue)
Call Stack | In computer science, a call stack is a stack data structure that stores information about the active subroutines of a computer program. This kind of stack is also known as an execution stack, program stack, control stack, run-time stack, or machine stack, and is often shortened to just "the stack". [Wiki](https://en.wikipedia.org/wiki/Call_stack)
Emit/Raise/Trigger | Emit allows you to emit an event which causes all callbacks registered to the event to 'fire' [stackoverflow](), the throw statement throws a user-defined exception [mdn](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/throw), and the trigger(https://stackoverflow.com/questions/32246262/what-is-emit-javascript-function) method triggers the specified event and the default behavior of an event [w3school](https://www.w3schools.com/jquery/event_trigger.asp)
Subscribe | A method that can be used on a session[Push Technology Docs](https://docs.pushtechnology.com/cloud/latest/manual/html/developerguide/apis/javascript/getting_started.html)
database | a structured set of data held in a computer

### Preview
Videos
- [OSI Model Explained](https://www.youtube.com/watch?v=vv4y_uOneC0)
- [TCP Handshakes Explained](https://www.youtube.com/watch?v=xMtP5ZB3wSk)

Read
- [Web Sockets](https://en.wikipedia.org/wiki/WebSocket)
- [Socket.io Tutorial](https://www.tutorialspoint.com/socket.io/)
- [Socket.io vs Web Sockets](https://www.educba.com/websocket-vs-socket-io/)

Bookmark
- [Socket.io Documentation](https://socket.io/docs/v4/index.html)
- [Socket.io Server API](https://socket.io/docs/v3/server-api/index.html)
- [Socket.io Client API](https://socket.io/docs/v3/client-api/index.html)
- [Socket Testing Tool](https://amritb.github.io/socketio-client-tool/)

1. Which 3 things had you heard about previously and now have better clarity on?

Call stack, event queue, database

1. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?

sockets servers, socket connections, sockets.io

1. What are you most excited about trying to implement or see how it works?

TCP

[⬅ Back to README Home](README.md)
