## Read: Class 30 - Hooks API

### Review, Research, and Discussion

**1. Why do we not need more .html pages in a multi-page React app?**

Because a react app comes in via one html tag, usually a div with an id of 'root', you only need one html file for your browser view. To make multiple 'pages' in react, you have a main page and you re-render other pages through bringing in or removing different components. 

**2. If we wanted a component to show up on every page, where would we put it and why?**
Inside the `<BrowserRouter />`, outside a `<Route />`. BrowserRouter wraps the whole page, so you would have recurring components like headers and footers in here along with some sort of app or main component that holds your 'subpages'

**3. What does props.children contain?**

Whatever you include between the opening and closing tags when invoking a component.

**Term** | **Definition**
-----|-----
Composition | Composition is one of the fundamental concepts in object-oriented programming. It describes a class that references one or more objects of other classes in instance variables. [stackify](https://stackify.com/oop-concepts-composition/)
Children / Child Components | Child components are basically components within components. Parents can have multiple components, and children components can be parents to their children components. 
Hash Routing | using the anchor part of the URL to simulate different content. For example http://site.com/#/products/list leads to displaying a list of products [krasimirtsonev](https://krasimirtsonev.com/blog/article/deep-dive-into-client-side-routing-navigo-pushstate-hash)
Link Routing | It is a dynamic routing algorithm in which each router shares knowledge of its neighbors with every other router in the network. A router sends its information about its neighbors only to all the routers through flooding. Information sharing takes place only whenever there is a change. [Geeks for Geeks](https://www.geeksforgeeks.org/difference-between-distance-vector-routing-and-link-state-routing/)


### Preview
- [making sense of hooks](https://medium.com/@dan_abramov/making-sense-of-react-hooks-fdbde8803889)
- [the state hook](https://reactjs.org/docs/hooks-state.html)
- [hooks api](https://reactjs.org/docs/hooks-overview.html)
- [hooks api reference](https://reactjs.org/docs/hooks-reference.html)
- [effects hook](https://reactjs.org/docs/hooks-effect.html)

1. Which 3 things had you heard about previously and now have better clarity on?

Components, BrowserRouter, Route

1. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?

Types of routing like Hash vs Link, props.children

1. What are you most excited about trying to implement or see how it works?

I'm excited to start learning about hooks and usestate. 

[⬅ Back to README Home](README.md)
