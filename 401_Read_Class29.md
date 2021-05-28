## Read: Class 29 - Routing

### Review, Research, and Discussion

**1. Do child components have direct access to props/state from the parent?**

Yes. Props/state can be passed down to the children from the parent

**2. When a component “wraps” another component, how does the child component’s output get rendered?**

```js
<Main>
  <Content />
</Main>
```

Content is a child of main and will be rendered anywhere Main is rendered

**3. Can a component, such as `<Content />`, which is a child also be used as a standalone component elsewhere in the application?**

Yes

**4. What trick can a parent use to share all `props` with it’s children**

The spread operator ...

**Term** | **Definition**
-----|-----
props.children | it is used to display whatever you include between the opening and closing tags when invoking a component. [codeburst.io](https://codeburst.io/a-quick-intro-to-reacts-props-children-cb3d2fce4891)
composition | Composition is one of the fundamental concepts in object-oriented programming. It describes a class that references one or more objects of other classes in instance variables [stackify](https://stackify.com/oop-concepts-composition/)

### Preview
- [browser router tutorial](https://blog.pshrmn.com/simple-react-router-v4-tutorial/)
- [browser router api docs](https://reactrouter.com/web/api)
- [react-if component](https://www.npmjs.com/package/react-if)
- [react testing library queries](https://testing-library.com/docs/queries/about/)
- [aria roles](https://www.w3.org/TR/html-aria/)

1. Which 3 things had you heard about previously and now have better clarity on?

components, spread operator, parent children relationship

1. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?

props.children, react testing

1. What are you most excited about trying to implement or see how it works?

react hooks and usestate

[⬅ Back to README Home](README.md)
