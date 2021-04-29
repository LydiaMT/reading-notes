## Read: Class 08 - Access Control (ACL)

### Review, Research, and Discussion

**1. When is Basic Authorization used vs. Bearer Authorization?**

Basic auth encodes and decodes your passwords, whereas bearer auth generates a token for your account based on your credentials so you can navigate to certain areas on a website. 

**2. What does the JSON Web Token package do?**

Verifies that you are in fact you. From there, based on your token settings, you are allowed to take certain actions or access certain areas of a site. 

**3. What considerations should we make when creating and storing a SECRET?**

The should be very secure. For development they should be hidden in your .env . 

**Term** | **Definition**
-----|-----
encryption | Encryption is the method by which information is converted into secret code that hides the information's true meaning. [TechTarget](https://searchsecurity.techtarget.com/definition/encryption)
token | A security token is a peripheral device used to gain access to an electronically restricted resource. The token is used in addition to or in place of a password. It acts like an electronic key to access something [Wiki](https://en.wikipedia.org/wiki/Security_token)
bearer | The bearer  middleware verifies a Bearer Token using OpenID Connect on a Web API without modifying the application. [Dapr Docs](https://docs.dapr.io/developing-applications/middleware/supported-middleware/middleware-bearer/)
secret | Basically a digital signature to decode tokens
JSON Web Token | JSON Web Token defines a compact and self-contained way for securely transmitting information between parties as a JSON object. [JWT](https://jwt.io/introduction)

### Preview

- [RBAC tutorial](https://www.youtube.com/watch?v=C4NP8Eon3cA)
- [5 steps to RBAC](https://www.csoonline.com/article/3060780/5-steps-to-simple-role-based-access-control.html)
- [wiki - RBAC](https://en.wikipedia.org/wiki/Role-based_access_control)


**1. Which 3 things had you heard about previously and now have better clarity on?**

bearer, tokens, secrets

**2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**

JWT, encryption, how to implement RBAC

**3. What are you most excited about trying to implement or see how it works?**

I'm excited to learn more about ACL and user access permissions


[⬅ Back to README Home](README.md)
