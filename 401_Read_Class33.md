## Read: Class 33 - Context API

### Review, Research, and Discussion

**1. Describe use cases for `useMemo()` and `useReducer()`?**

useMemo is similar to useCallback except that instead of memoizing a function, it memoizes a value. useReducer returns state and a dispatch function. You can pass the dispatch function down to other components which should call it with a type. [medium](https://binyamin.medium.com/react-hooks-usereducer-usecallback-usememo-5e5af9b0257a)

**2. Why do custom hooks need the use prefix?**

It's mostly just industry standard

**3. What do custom hooks usually do?**

The turn things like functions into components so you can use those functions across different parts of your app

**4. Using any list of custom hooks, research and name one that you think will be useful in your applications?**

useContext: Accepts a context object (the value returned from React.createContext) and returns the current context value for that context. 

**5. Describe how a hook that fetches API data might work**

Wish I knew but I couldn't get this to work in my lab :). Jokes aside I imagine they all would have a similar structure but have slight variations based on the route and the method you're using. 

**Term** | **Definition**
-----|-----
reducer | A reducer is a function that determines changes to an application's state. [CSS Tricks](https://css-tricks.com/understanding-how-reducers-are-used-in-redux/)


### Preview
- [context api](https://reactjs.org/docs/context.html)
- [hooks and context example](https://medium.com/swlh/snackbars-in-react-an-exercise-in-hooks-and-context-299b43fd2a2b)
- [react context links](https://github.com/diegohaz/awesome-react-context)

1. Which 3 things had you heard about previously and now have better clarity on?

hooks, reducers, custom hooks for APIs

1. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?

custom hooks, hooks, useEffect

1. What are you most excited about trying to implement or see how it works?

I'm excited to create custom hooks for the API calls we had in our lab. I'm also excited about using more of reacts custom hooks

[⬅ Back to README Home](README.md)
