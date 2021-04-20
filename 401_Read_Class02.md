## Read: Class 02 - Express

### Review, Research, and Discussion

**1. What’s the difference between `PUT` and `PATCH`?**

PUT and PATCH are both part of the Update in CRUD. However, they make these updated in different ways. PUT uses the request URI to supply a modified version of the requested resource which replaces the original version of the resource. PUT updates the entire resource, or creates a resource if it doesn't exist yet. Because of this, make sure to define the entire resource when making PUT requests. PATCH supplies a set of instructions to modify the resource. PATCH partially updates the resource rather than fully replacing the original. Because of this, if you call PATCH on a resource that doesn't exist yet your request will fail. *Source [Wiki Patch Verb](https://en.wikipedia.org/wiki/Patch_verb#:~:text=The%20main%20difference%20between%20the,instructions%20to%20modify%20the%20resource.) [RapidAPI](https://rapidapi.com/blog/put-vs-patch/)*

**2. Provide links to 3 services or tools that allow you to “mock” an API for development like `json-server`**

- [No API? No Problem! Rapid Development via Mock APIs](https://www.freecodecamp.org/news/rapid-development-via-mock-apis-e559087be066/#:~:text=A%20mock%20API%20allows%20you,they%20work%20with%20your%20app.)
- [Design and Mock APIs with Postman](https://www.postman.com/features/mock-api/)
- [Creating a Mock API in React](https://www.pluralsight.com/guides/react-mock-api)

**3. Compare and contrast Swagger and APIDoc.js** 

Swagger and apiDoc.js are API tools that create documentation for API annotation in your source code. Swagger is formatted with YALM and JSON. apiDoc is formatted with JSON (?). For apidocjs you’ll have to modify documentation for each affected method/endpoints if the service changes. In swagger we can limit changes ([Source](https://www.asptricks.net/2019/04/apidoc-vs-swagger-for-node-app.html)). Also: [See comparison table](https://npmcompare.com/compare/apidoc,documentation,esdoc,jsdoc,swagger)

Swagger: [Documentation](https://swagger.io/docs/specification/about/) 

APIDoc.js: [Documentation](https://apidocjs.com/#example-basic)


**4.  Which HTTP status codes should be sent with each type of (un)successful API call?**

Status Classes:
- 100-199: Informational status codes
- 200-299: Success codes
- 300-399: Redirection codes
- 400-499: Client error codes
- 500-599: Server error codes

*Source [Moesif](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/#400---499)*

[Find a full list here](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status)

**5. Compare and contrast SOAP and ReST**

- SOAP: Simple Access Object Protocol. Best for web service access. Language, Platform & Transport Independent. Built in Error handling. Harder to use.

- REST: REpresentative State Transfer. Rest requires the use of HTTP. Assumes point to point communication. Fast. Easier to use. 

*Source [SoapUI](https://www.soapui.org/learn/api/soap-vs-rest-api/)*

### Document the following Vocabulary Terms

**Term** | **Definition**
-----|-----
Web Server | Computer software or hardware that accepts requests via HTTP or HTTPS. A user agent (web browser or web crawler), initiates communication by making a request for a specific resource using HTTP and the server responds with content of that resource or an error message ([wiki](https://en.wikipedia.org/wiki/Web_server))
Express | Back end web application framework for Node.js that's designed for building web applications and APIs ([wiki](https://en.wikipedia.org/wiki/Express.js))
Routing | The process of selecting a path for traffic in a network or between or across multiple networks ([wiki](https://en.wikipedia.org/wiki/Routing))
WRRC | web request-response cycle. The cycle of requests and responses that flow between clients and a server ([Jen Strong](https://medium.com/@jen_strong/the-request-response-cycle-of-the-web-1b7e206e9047))

### Preview

- [An introduction to NodeJS and Express](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction)
- [What is NPM?](https://docs.npmjs.com/about-npm)
- [What is TDD?](https://www.agilealliance.org/glossary/tdd/#q=~(infinite~false~filters~(postType~(~'page~'post~'aa_book~'aa_event_session~'aa_experience_report~'aa_glossary~'aa_research_paper~'aa_video)~tags~(~'tdd))~searchTerm~'~sort~false~sortDirection~'asc~page~1))
- [CI/CD](https://www.youtube.com/watch?v=xSv_m3KhUO8)

**1. Which 3 things had you heard about previously and now have better clarity on?**

 - NodeJS: nodeJS' runtime is used outside of the browser (hadn't specifically made that connection in the past).
 - Express: a node framework that writes handlers for requests with different HTTP verbs at different URL routes ([MDN](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction))
 - npm: essentially an open source software registry for developers to share and borrow packages

**2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**

- TDD, supertest, http status codes

**3. What are you most excited about trying to implement or see how it works?**

- I'm very excited to implement TDD because I want to learn more about how to write tests. This seems like a pillar in writing clean, quality code. I also imagine that it makes you more intentional in your code writing process.

### Bookmark

- [nodeJS docs](https://nodejs.org/en/docs/)
- [npm docs](https://docs.npmjs.com/)
- [express docs](https://expressjs.com/en/4x/api.html)
- [http status codes](https://www.restapitutorial.com/httpstatuscodes.html)
- [supertest](https://github.com/visionmedia/supertest)

[⬅ Back to README Home](README.md)
