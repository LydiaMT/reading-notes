## Read: Class 06 - Authentication

### Review, Research, and Discussion

**1. Explain what a “Singleton” is (in Computer Science terms)**

Singleton limits the number of instances of a particular object to just one. They are useful when system-wide actions need to be coordinated from a central place [dofactory](https://www.dofactory.com/javascript/design-patterns/singleton#:~:text=Summary,from%20a%20single%20central%20place.)

**2. Explain how the Singleton pattern can be used with Node modules, specifically with classes** When we want to make sure there is only one object instantiated. So rather than creating new objects we ensure the constructor is called only once and then we reuse the instance [Arek Jaworski](https://medium.com/swlh/node-js-and-singleton-pattern-7b08d11c726a)

**3. If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?** I would first determine what I'm trying to manipulate or output with the middleware. I would then write a function and then pass it in as a dependency to another function like a callback. 

**Term** | **Definition**
-----|-----
Router Middleware | Take a request, and forwards it to a handler based on it's path and then sends a response to the client on the behalf of the original handler [Stack Overflow](https://stackoverflow.com/questions/63106648/what-is-router-middleware-in-express)
Dynamic Module Loading | a mechanism by which a computer program can, at run time, load a library (or other binary) into memory, retrieve the addresses of functions and variables contained in the library, execute those functions or access those variables, and unload the library from memory. [Wiki](https://en.wikipedia.org/wiki/Dynamic_loading)
Singleton Pattern | limits the number of instances of a particular object to just one [dofactory](https://www.dofactory.com/javascript/design-patterns/singleton#:~:text=Summary,from%20a%20single%20central%20place.)
CRUD -> REST Method Matches | CREATE <-> POST, READ <-> GET, UPDATE <-> PUT, DELETE <-> DELETE
Mock Testing | Mock testing is an approach to unit testing that lets you make assertions about how the code under test is interacting with other system modules. In mock testing, the dependencies are replaced with objects that simulate the behaviour of the real ones. [devopedia](https://devopedia.org/mock-testing#qst-ans-0)

### Preparation Materials

- [Securing Passwords](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)
- [Basic Auth](https://en.wikipedia.org/wiki/Basic_access_authentication)
- [OWASP auth cheatsheet](https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html)
- [bcrypt docs](https://www.npmjs.com/package/bcrypt)

**1. Which 3 things had you heard about previously and now have better clarity on?**

Authorization, authentication, bcrypt/hashing

**2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**

I'm excited to continue learning about authorization and authentication, and I want to learn more about middleware and testing

**3. What are you most excited about trying to implement or see how it works?**

0Auth

[⬅ Back to README Home](README.md)
