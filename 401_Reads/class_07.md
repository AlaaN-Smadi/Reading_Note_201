
## Class 07

### Write the following steps in the correct order:

- Register your application to get a client_id and client_secret
- Ask the client if they want to sign in via a third party
- Make a request to a third-party API endpoint
- Redirect to a third party authentication endpoint
- Receive authorization code
- Make a request to the access token endpoint
- Receive access token

### What can you do with an authorization code?

=> An authorization code is an alphanumeric password that authorizes its user to purchase, sell or transfer items, or to enter information into a security-protected space.

### What can you do with an access token?

=> Access tokens are the thing that applications use to make API requests on behalf of a user,The access token represents the authorization of a specific application to access specific parts of a user’s data.


### What’s a benefit of using OAuth instead of your own basic authentication?

=> It enables apps to obtain limited access (scopes) to a user’s data without giving away a user’s password. It decouples authentication from authorization and supports multiple use cases addressing different device capabilities. It supports server-to-server apps, browser-based apps, mobile/native apps, and consoles/TVs.

### Terms:

- **Client ID** :  The client_id is a public identifier for apps. Even though it’s public, it’s best that it isn’t guessable by third parties, so many implementations use something like a 32-character hex string. It must also be unique across all clients that the authorization server handles. If the client ID is guessable, it makes it slightly easier to craft phishing attacks against arbitrary applications.

- **Client Secret**: is a secret known only to the application and the authorization server. It must be sufficiently random to not be guessable, which means you should avoid using common UUID libraries which often take into account the timestamp or MAC address of the server generating it. A great way to generate a secure secret is to use a cryptographically-secure library to generate a 256-bit value and converting it to a hexadecimal representation.

- **Authentication Endpoint** :  is a security mechanism designed to ensure that only authorized devices can connect to a given network, site or service.The approach is also known as device authentication. In this context, the endpoint most often considered is a mobile computing device, like a laptop, smart phone or tablet but it could be any connected hardware device on a TCP/IP network. The possibilities include desktop computers, printers, servers and specialized hardware such as POS terminals, smart meters and other smart devices.


- **Access Token Endpoint**:  Access tokens are the thing that applications use to make API requests on behalf of a user. The access token represents the authorization of a specific application to access specific parts of a user’s data.

- **API Endpoint** : an endpoint is one end of a communication channel. When an API interacts with another system, the touchpoints of this communication are considered endpoints. For APIs, an endpoint can include a URL of a server or service. Each endpoint is the location from which APIs can access the resources they need to carry out their function.

- **Authorization Code** :  is a temporary code that the client will exchange for an access token. The code itself is obtained from the authorization server where the user gets a chance to see what the information the client is requesting, and approve or deny the request.

- **Access Token** :  is an object encapsulating the security identity of a process or thread.[1] A token is used to make security decisions and to store tamper-proof information about some system entity. While a token is generally used to represent only security information, it is capable of holding additional free-form data that can be attached while the token is being created.