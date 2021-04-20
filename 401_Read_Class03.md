## Read: Class 03 -  Express REST API

### Review, Research, and Discussion

**1. Name 3 real world use cases where you’d want to change the request with custom middleware**

- For authentication or login. If you have routes that require authentication you would add auth middleware with authentication logic. That way, if at any step in the route handling the user is not able to authenticate and the auth fails, an error response will be thrown. [Selvaganesh](https://medium.com/@selvaganesh93/how-node-js-middleware-works-d8e02a936113)
- When you want to record how long each requests takes to be sent back to the browser [Jamis Charles](https://medium.com/@jamischarles/what-is-middleware-a-simple-explanation-bb22d6b41d01)
- To see if a user is already logged in. If a user was not logged in you could have the server tell the browser to redirect the user to the login route [Jamis Charles](https://medium.com/@jamischarles/what-is-middleware-a-simple-explanation-bb22d6b41d01)

**2. True or false: The route handler is middleware?**

True. All callback functions that use app.method() can be defined as middleware. Frequently if you're not specifically using `next` as an argument in your function, people will refer to these as route handlers rather than middleware, but they are technically middleware. [github](https://github.com/expressjs/express/issues/4089)

**3. In what ways can a middleware function end the process and send data to the browser?**

If a 'check' occurs, such as a user is trying to modify something they don't have the credentials to modify on the front end, a middleware function can send data to the browser. Say a user is trying to edit someone else's post on a webpage, a middleware function could send data in the form of a message such as 'You must be the author of this post to make edits". [Ian Schoonover](https://www.youtube.com/watch?v=zPYmM9K8-g8)

**4. At what point in the request lifecycle can you “inject” middleware?**

You can use dependency injections to support scalable modules.
[Adam Polak](https://tsh.io/blog/dependency-injection-in-node-js/)

**5. What can cause express to error with “Request headers sent twice, cannot start a second response”**

- Calling res.writeHead to early
- Calling res.redirect then setting more data
- Calling next after response has been returned

*Source: [endyourif.com](https://www.endyourif.com/cant-set-headers-after-they-are-sent/)*


### Document the following Vocabulary Terms

**Term** | **Definition**
-----|-----
Middleware | software that provides services to software applications beyond those available from the operating system ([wiki](https://en.wikipedia.org/wiki/Middleware))
Request Object | Retrieves the values that the client browser passed to the server during an HTTP request ([Microsoft](https://docs.microsoft.com/en-us/previous-versions/iis/6.0-sdk/ms524948(v=vs.90)))
Response Object | Sends output from a request back to the client ([Microsoft](https://docs.microsoft.com/en-us/previous-versions/iis/6.0-sdk/ms525405(v=vs.90)))
Application Middleware | Bind application-level middleware to an instance of the app object by using the app.use() and app.METHOD() functions, where METHOD is the HTTP method of the request that the middleware function handles (such as GET, PUT, or POST) in lowercase. ([Express](https://expressjs.com/en/guide/using-middleware.html#middleware.router))
Routing Middleware | Router-level middleware works in the same way as application-level middleware, except it is bound to an instance of express.Router(). ([Express](https://expressjs.com/en/guide/using-middleware.html#middleware.router))
Test Driven Development | Software development process relying on software requirements being converted to test cases before software is fully developed, and tracking all software development by repeatedly testing the software against all test cases. ([wiki](https://en.wikipedia.org/wiki/Test-driven_development))
Behavioral Testing | Agile software development process that encourages collaboration among developers, QA, and non-technical or business participants in a software project. It encourages teams to use conversation and concrete examples to formalize a shared understanding of how the application should behave. ([wiki](https://en.wikipedia.org/wiki/Behavior-driven_development))

### Preview

- [Review: ES6 Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)
- [Using Express Routing](https://expressjs.com/en/guide/routing.html)
- [Express Routing](https://scotch.io/tutorials/learn-to-use-the-new-router-in-expressjs-4)

**1. Which 3 things had you heard about previously and now have better clarity on?**

TDD, Request Objects, and Response Objects. 

**2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**

- Injecting middleware, as I could not find a great article explaining that. Lots of info for ASP.net, but not so much for node.js or javascript
- I'm looking forward to better understanding middleware
- Understanding, in practice, the pros and cons of TDD vs BDD

**3. What are you most excited about trying to implement or see how it works?**

I'm excited to code more with ES6 classes and middleware


[⬅ Back to README Home](README.md)
