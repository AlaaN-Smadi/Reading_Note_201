## Authorization and Authentication flows
### What is the difference between authorization and authentication?

- Authentication confirms that users are who they say they are. Authorization gives those users permission to access a resource.


### What is Authorization Code Flow?

- It's is used to obtain an access token to authorize API requests. And the Access tokens, obtained using authorization code flow, provide permissions for your application to manipulate documents and other resources on behalf of a Mendeley user and make requests for all API resources.
### What is Authorization Code Flow with Proof Key for Code Exchange PKCE?

- The Authorization Code Flow PKCE is an OpenId Connect flow specifically designed to authenticate native or mobile application users.
### What is Implicit Flow with Form Post?

- It's means that the web app requests and obtains tokens through the front channel, without the need for secrets or extra backend calls.
### What is Client Credentials Flow?

- The Client Credentials flow is a server to server flow. There is no user authentication involved in the process.
### What is Device Authorization Flow?

- It's an OAuth 2.0 extension that enables devices with no browser or limited input capability to obtain an access token.
### What is Resource Owner Password Flow?

- It's a requests that users provide credentials username and password, typically using an interactive form.


## OAuth


## What is OAuth?
- OAuth allows websites and services to share assets among users. It is widely accepted, but be aware of its vulnerabilities.

## Give an example of what using OAuth would look like.
- The simplest example of OAuth is when you go to log onto a website and it offers one or more opportunities to log on using another website’s/service’s logon. You then click on the button linked to the other website, the other website authenticates you, and the website you were originally connecting to logs you on itself afterward using permission gained from the second website.

### * How does OAuth work? What are the steps that it takes to authenticate the user? *
### The User Shows Intent
### The Consumer Gets Permission
### The User Is Redirected to the Service Provider
### The User Gives Permission
### The Consumer Obtains an Access Token
### The Consumer Accesses the Protected Resource


## What is OpenID?
### is a simple identity layer on top of the OAuth 2.0 protocol. It allows Clients to verify the identity of the End-User based on the authentication performed by an Authorization Server, as well as to obtain basic profile information about the End-User in an interoperable and REST-like manner.
