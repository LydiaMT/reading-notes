## Read: Class 34 - `<Login />` and `<Auth />`

### Review, Research, and Discussion

**1. Why is the Context API useful?**

It can house top level settings, context, and themes that are used across your entire application.

**2. Can a component outside of a provider get its context?**

I'm sure there's a way for it to do this, but it's not best practice and should be avoided. In short, no. 

**3. What are some common use cases for using the Context API??**

Top level UI themes like dark and light toggle modes. 

**4. Describe “Context Hell”**

When multiple providers are nested within other consumers and you have layers of providers within other provider within consumers. 

**Term** | **Definition**
-----|-----
global state | State that's managed at your top level components
global context | Context managed at your top level components, or Provider components. Context provides a way to pass data through the component tree without having to pass props down manually at every level.
provider | A component that is providing the context or state. Sort of like a parent. 
consumer | A component that is receiving the context or state from a parent provider component. Sort of like a child. 


### Preview
- [what is role based access control?](https://digitalguardian.com/blog/what-role-based-access-control-rbac-examples-benefits-and-more)
- [react-cookies component](https://www.npmjs.com/package/react-cookies)
- [react-cookie library](https://www.npmjs.com/package/react-cookie)

1. Which 3 things had you heard about previously and now have better clarity on?

RBAC, components, providers/consumers

1. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?

Context, react-cookies, 

1. What are you most excited about trying to implement or see how it works?

I'm excited to work with Context more

[⬅ Back to README Home](README.md)
