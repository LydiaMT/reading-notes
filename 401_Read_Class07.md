## Read: Class 07 - Bearer Authorization

### Review, Research, and Discussion

**1. Write the following steps in the correct order:**

- Register your application to get a client_id and client_secret
- Ask the client if they want to sign in via a third party
- Redirect to a third party authentication endpoint
- Make a request to a third-party API endpoint
- Receive authorization code
- Make a request to the access token endpoint
- Receive access token

**2. What can you do with an authorization code?**
An access token allows you to access secure pages or spaces online, as well as take certain actions within those spaces

**3. What can you do with an access token?**
An access token allows you to access secure pages or spaces online. 

**4. What’s a benefit of using OAuth instead of your own basic authentication?**
The benefits of OAuth is it's limited access to the users data, it's ability to share data for users without having to release PII, and it's easy to implement [Tutorials Point](https://www.tutorialspoint.com/oauth2.0/oauth2.0_overview.htm)

**Term** | **Definition**
-----|-----
Client ID | A public identifier for applications. Many applications use 32-character hex string [okta](https://www.oauth.com/oauth2-servers/client-registration/client-id-secret/)
Client Secret | A client secret is a secret known only to your application and the authorization server. It protects your resources by only granting tokens to authorized requestors. [Auth0](https://auth0.com/docs/applications)
Authentication Endpoint | Authentication mechanism used to verify the identity of a network's external or remote connecting device [iotone](https://www.iotone.com/term/end-point-authentication/t219)
Access Token Endpoint | Used to interact with the resource owner and get the authorization to access the protected resource [OAuth](https://auth0.com/docs/protocols/protocol-oauth2)
API Endpoint | In simple terms, an API endpoint is the point of entry in a communication channel when two systems are interacting. It refers to touchpoints of the communication between an API and a server. [rapidAPI](https://rapidapi.com/blog/api-glossary/endpoint/)
Authorization Code | An authorization code is an alphanumeric password that authorizes its user to purchase, sell or transfer items, or to enter information into a security-protected space. [Investopedia](https://www.investopedia.com/terms/a/authorization-code.asp)
Access Token | An object encapsulating the security identity of a process or thread. A token is used to make security decisions and to store tamper-proof information about some system entity. [Wiki](https://en.wikipedia.org/wiki/Access_token)

### Preview

-[JWTs Explained](https://www.youtube.com/watch?v=926mknSW9Lo)
-[Intro to JWT](https://jwt.io/introduction/)
-[Are JWTs Secure?](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)

**1. Which 3 things had you heard about previously and now have better clarity on?**

Web Tokens, access token, authorization codes

**2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**

Oauth, API endpoints, client secrets

**3. What are you most excited about trying to implement or see how it works?**

Honestly all of this! There's so much cross over will all of these topics, I'm excited to see how they all integrate and work together. I want to learn more about how to build secure and safe applications. 

[⬅ Back to README Home](README.md)
