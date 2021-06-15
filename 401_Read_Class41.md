## Read: Class 41 - React Native

### Review, Research, and Discussion

**1. Compare and Contrast Redux Toolkit with Redux “Ducks”**

- React features:
  - the reusability of modularized components
  - the Virtual DOM
  - native compatibility
  - a relatively quick learning curve
  - helpful developer tools
- Redux Toolkit: 
  - state lives inside the store
  - reducers produce the state
  - Actions let reducers know when to produce the next state
- Redux Ducks: 
  - packages all of your Redux code into redux modules
  - It's a bit easier to read than Redux where you have to look at more files. Everything lives in one file. 

[Start it Up - Lauren Lee](https://medium.com/swlh/the-good-the-bad-of-react-redux-and-why-ducks-might-be-the-solution-1567d5bdc698)

**2. What is the principle advantage of Redux Toolkit?**

It allows us to write more efficient code, speed up the development process, and automatically apply the best-recommended practices. It was mainly created to solve the THREE MAJOR ISSUES with Redux:
- Configuring a Redux store is too complicated
- Have to add a lot of packages to build a large scale application

[Geeks for Geeks](https://www.geeksforgeeks.org/what-is-redux-toolkit-and-why-it-is-more-preferred/)

**Term** | **Definition**
-----|-----
redux toolkit slices | `createSlice()`. A function that accepts an initial state, an object full of reducer functions, and a "slice name", and automatically generates action creators and action types that correspond to the reducers and state. [redux-toolkit](https://redux-toolkit.js.org/api/createSlice)
namespace | In computing, a namespace is a set of signs (names) that are used to identify and refer to objects of various kinds. A namespace ensures that all of a given set of objects have unique names so that they can be easily identified. [wiki](https://en.wikipedia.org/wiki/Namespace)


### Preview
- [getting started with react native](https://reactnative.dev/docs/getting-started)
- [react native basics (Tutorial)](https://reactnative.dev/docs/tutorial)
- [react native](https://reactnative.dev/)
- [expo](https://expo.io/)
- [expo snack](https://snack.expo.io/)
- [ejecting](https://docs.expo.io/expokit/eject/?redirected)

1. Which 3 things had you heard about previously and now have better clarity on?

Redux, redux toolkit, namespace

1. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?

Ducks

1. What are you most excited about trying to implement or see how it works?

Redux Ducks

[⬅ Back to README Home](README.md)
