## Read: Class 36 - Application State with Redux

### Review, Research, and Discussion

**1. What are the advantages of storing tokens in “Cookies” vs “Local Storage”?**

Local Storage: convenient because it's pure JS. Works with APIs that require you to put your access token in the header.
Cookies: Secure. It’s automatically sent in every HTTP request to your server.

[indepth](https://indepth.dev/posts/1382/localstorage-vs-cookies)

**2. Explain 3rd party cookies.**

Third-party cookies work by embedding JavaScript from one website into another. A website hosts the third-party cookie by incorporating third-party JavaScript. HTTP, the protocol that is used for web browsing, is a stateless protocol meaning information is not saved in between browsing sessions. Cookies remember stateful information in the stateless HTTP environment. [techtarget](https://whatis.techtarget.com/definition/third-party-cookie)

**3. How do pixel tags work?**

Pixel tags are typically single pixel, transparent GIF images that are added to a web page. They allows the ad server to read and record the cookie with the unique ID and the extended information it needs to record. [nielsen](https://resources.marketingeffectiveness.nielsen.com/blog/cookies-tags-pixels-tracking-customer-engagement)

**Term** | **Definition**
-----|-----
cookies | Cookies are text files with small pieces of data — like a username and password — that are used to identify your computer as you use a computer network. Specific cookies known as HTTP cookies are used to identify specific users and improve your web browsing experience. [kasper sky](https://www.kaspersky.com/resource-center/definitions/cookies)
authorization | Authorization is a security mechanism to determine access levels or user/client privileges related to system resources including files, services, computer programs, data and application features.[economic times](https://economictimes.indiatimes.com/definition/authorization)
access control | Access control is a method of guaranteeing that users are who they say they are and that they have the appropriate access to company data. [CSO](https://www.csoonline.com/article/3251714/what-is-access-control-a-key-component-of-data-security.html)
conditional rendering | Conditional rendering in React works the same way conditions work in JavaScript. Use JavaScript operators like if or the conditional operator to create elements representing the current state, and let React update the UI to match them. [conditional rendering](https://reactjs.org/docs/conditional-rendering.html)


### Preview
- [Dan Abramov Redux Tutorials](https://egghead.io/courses/fundamentals-of-redux-course-from-dan-abramov-bd5cc867)
- [worlds easiest guide to redux](https://www.freecodecamp.org/news/understanding-redux-the-worlds-easiest-guide-to-beginning-redux-c695f45546f6/)
- [testing reducers](https://medium.com/@netxm/testing-redux-reducers-with-jest-6653abbfe3e1)
- [Redux Docs](https://redux.js.org/)

1. Which 3 things had you heard about previously and now have better clarity on?

cookies, local storage, authorization

1. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?

pixel tags, conditional rendiner, acces control 

1. What are you most excited about trying to implement or see how it works?

I definitely want more practic with authorization 

[⬅ Back to README Home](README.md)
