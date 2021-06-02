## Read: Class 32 - Custom Hooks

### Review, Research, and Discussion

**1. What does a component’s lifecycle refer to?**

The processes of components render and commit phases through the cycle of Mounting, Updating, Unmounting [lifecycle cheatsheet](https://projects.wojtekmaj.pl/react-lifecycle-methods-diagram/)

**2. Why do you sometimes need to “wrap” functions in `useCallback` when called from within `useEffect`?**

So the functions aren't recreated over and over again because useEffect runs every time an action takes place. 

**3. Why are functional components preferred over class components?**

You can pass information more easily across functional component siblings and ancestors than with class components. You also don't need to write as much code with functional components

**4. What is wrong with the following code?**

```js
import React, {useState, useEffect} from 'react';

function MyComponent(props) {
  const [count, setCount] = useState(0);

  function changeCount(e) {
    setCount(e.target.value);
  }

  let renderedItems = []

  for (let i = 0; i < count; i++) {
    useEffect( () => {
      console.log('component mount/update');
    }, [count]);

    renderedItems.push(<div key={i}>Item</div>);
  }

  return (<div>
     <input type='number' value={count} onChange={changeCount}/>
      {renderedItems}
    </div>);
}
```
- Wrapping the for loop around the useEffect is not a best practice

**Term** | **Definition**
-----|-----
state hook | Hook uses useState() functional component for setting and retrieving state. i.e. `const [count, setCount] = useState(0)` [javatpoint](https://www.javatpoint.com/react-hooks)
effect hook | useEffect(). The Effect Hook allows us to perform side effects (an action) in the function components. It does not use components lifecycle methods which are available in class components. In other words, Effects Hooks are equivalent to componentDidMount(), componentDidUpdate(), and componentWillUnmount() lifecycle methods. [javatpoint](https://www.javatpoint.com/react-hooks)
reducer hook | An alternative to useState. Accepts a reducer of type (state, action) => newState, and returns the current state paired with a dispatch method. [React](https://reactjs.org/docs/hooks-reference.html)

### Preview
- [custom hooks - all you need to know](https://www.telerik.com/kendo-react-ui/react-hooks-guide/#toc-custom-react-hooks)
- [async hooks](https://dev.to/vinodchauhan7/react-hooks-with-async-await-1n9g)
- [useReducer Hook](https://reactjs.org/docs/hooks-reference.html#usereducer)
- [react custom hooks](https://reactjs.org/docs/hooks-custom.html)
- [use hooks](https://usehooks.com/)
- [hooks list](https://github.com/rehooks/awesome-react-hooks)
- [10 essential react hooks](https://blog.bitsrc.io/10-react-custom-hooks-you-should-have-in-your-toolbox-aa27d3f5564d)

1. Which 3 things had you heard about previously and now have better clarity on?

useEffect, state hooks, effect hooks

1. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?

async hooks, useCallback, reducer hooks

1. What are you most excited about trying to implement or see how it works?

More practice with hooks and bootstrap

[⬅ Back to README Home](README.md)
