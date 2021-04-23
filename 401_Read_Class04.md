## Read: Class 04 - Data Modeling

### Review, Research, and Discussion

**1.  Name 3 advantages to Test Driven Development**

- Helps you write very intentional code
- Provides detailed documentation through your test cases
- Avoids big bugs down the road

**2. In what case would you need to use `beforeEach()` or `afterEach()` in a test suite?**

These methods are great when you need to do something repeatedly for lot's of tests. You can invoke other functions inside a beforeEach or afterEach as a callback to test things asynchronously. [jest docs](https://jestjs.io/docs/setup-teardown)

**3. What is one downside of Test Driven Development**

- You can only write tests as good as the edge cases you can think of. You might accidentally leave something out of your test
- You have to continually update your tests and dependencies update
- It can feel slower to code this way before you get the hang of it

**4. What’s the primary difference between ES6 Classes and Constructor/Prototype Classes?**

"The most important difference between class- and prototype-based inheritance is that a class defines a type which can be instantiated at runtime, whereas a prototype is itself an object instance." - [Justen Robertson](https://www.toptal.com/javascript/es6-class-chaos-keeps-js-developer-up#:~:text=Prototypes%20vs.,is%20itself%20an%20object%20instance.&text=A%20constructor%20in%20JavaScript%20is,function%20that%20returns%20an%20object.)

**5. Why REST?**

REST is stateless and the clients data is not saved to the server (can be beneficial in some situations). Separates the front end and back end in an organized way which can help with debugging [Timothy Robards](https://itnext.io/javascript-fundamentals-an-introduction-to-rest-apis-7cbe8a809d3b). Since data is not tied to the method it provides a lot of flexibility, and the routes can handle multiple types of calls, and return different data formats [MuleSoft](https://www.mulesoft.com/resources/api/restful-api)

### Document the following Vocabulary Terms

**Term** | **Definition**
-----|-----
functional programming | Functional programming is a programming paradigm in which we try to bind everything in pure mathematical functions style. It is a declarative type of programming style. Its main focus is on “what to solve” in contrast to an imperative style where the main focus is “how to solve”. [GeeksforGeeks](https://www.geeksforgeeks.org/functional-programming-paradigm/#:~:text=Functional%20programming%20is%20a%20programming,is%20%E2%80%9Chow%20to%20solve%E2%80%9D.)
object-oriented programming (OOP) | Programming technique that accentuates the functional factors required for creating and implementing the programs, or "how to solve" [educba](https://www.educba.com/functional-programming-vs-oop/)
class | Classes are a template for creating objects. They encapsulate data with code to work on that data. [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)
`super` | The super keyword is used to access and call functions on an object's parent. [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/super)
`this` | Within a class constructor, this is a regular object. All non-static methods within the class are added to the prototype of this [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/this)
Test Driven Development (TDD) | Software development process relying on software requirements being converted to test cases before software is fully developed, and tracking all software development by repeatedly testing the software against all test cases. [Wiki](https://en.wikipedia.org/wiki/Test-driven_development)
Jest | A Javascript testing framework [jestjs.io](https://jestjs.io/)
Continuous Integration (CI) | practice of merging all developers' working copies to a shared mainline several times a day [Wiki](https://en.wikipedia.org/wiki/Continuous_integration)
REST | REpresentational State Transfer that uses the following HTTP methods GET, PUT, DELETE, and POST [tutorialspoint.com](https://www.tutorialspoint.com/nodejs/nodejs_restful_api.htm)
Data Model | A model that organizes data description, data semantics, and consistency constraints of data. [guru99](https://www.guru99.com/data-modelling-conceptual-logical.html)

### Preview

- [sql vs nosql (Video)](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)
- [nosql vs sql](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)
- [nosql modeling techniques](https://highlyscalable.wordpress.com/2012/03/01/nosql-data-modeling-techniques/)

**1. Which 3 things had you heard about previously and now have better clarity on?**

REST, TDD, Jest

**2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**

How to actually do TDD, better understanding of super and this and object constructors in general. Functional programming vs OOP

**3. What are you most excited about trying to implement or see how it works?**

Writings tests and working with databases


### Bookmark

- [mongoose api](https://mongoosejs.com/docs/api.html#Model)

[⬅ Back to README Home](README.md)
