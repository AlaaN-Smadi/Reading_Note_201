
## Class _02

### What’s the difference between PUT and PATCH?


1. PATCH, the enclosed entity boasts a set of instructions that describe how a resource stored on the original server should be partially modified to create a new version.

2. PATCH applies a partial update to the resource.

3. PUT is a method of modifying resource where the client sends data that updates the entire resource.x

4. PATCH is used when you want to apply a partial update to the resource.

5. PUT is a method of modifying resource where the client sends data that updates the entire resource.

6. PUT request, the enclosed entity is viewed as the modified version of the resource saved on the original server, and the client is requesting to replace




### Provide links to 3 services or tools that allow you to “mock” an API for development like json-server.

-  MockServer (and its counterpart service MockServer Proxy) is a multifaceted tool that comes in a variety of builds. It’s available as a Netty web server, a Docker container, a Maven plugin, an npm plugin, and a Grunt plugin. There’s a ton of great options that can be leveraged for a variety of environments. This already makes it a pretty compelling tool given that you can plug it into just about anything you’re running, but its wide range of functionality is the core compelling argument.

-  Beeceptor is a great tool largely because it requires absolutely no code in order to utilize it. Beeceptor is a free online tool for mocking a REST API interaction using any HTTP request. You can customize your responses to simulate pretty much any response or failure situation. Beeceptor also offers some great functionality to simulate latency on downstream APIs – you c

-  Nock is an HTTPS library designed to replicate and mock servers and expectations in Node.js. Functionally, Nock does this by overriding both the http.request and http.ClientRequest functions, intercepting requests and responding with a specific mocked response through the use of Interceptors.
Interceptors are addressed in the order they appear on a list, meaning that you can create multiple interceptors that result in different responses to two or more calls. This is especially useful if you’re testing mocked failures or routing, as you can mimic complex server functionality relatively seamlessly.


### Compare and contrast Swagger and APIDoc.js 1 Which HTTP status codes should be sent with each type of (un)successful API call?

**Swagger status Codes:**

1. 200 : Successful request and response.
2. 400: Bad request
3. 404: Not found
4. 500: Unexpected error


**APIDoc.js HTTP status Codes:**

1. 200 : Successful request and response.
2. 400: Bad request
3. 404: Not found
4. 500: Unexpected error



### Compare and contrast SOAP and ReST

**SOAP**

1. protocol
2. only works with XML formats
3. needs more bandwidth for its usage
4. Simple Object Access Protocol
5. cannot make use of REST

**REST**
1. work with plain text, XML, HTML and JSON
2. Representational State Transfer
3. doesn’t need much bandwidth
4. can make use of SOAP
5. architectural pattern


### Documenting Terms

- Web Server : The term web server can refer to hardware or software, or both of them working together.


- Express : Express.js, or simply Express, is a back end web application framework for Node.js, released as free and open-source software under the MIT License. It is designed for building web applications and APIs.

- Routing : Routing or router in web development is a mechanism where HTTP requests are routed to the code that handles them. To put simply, in the Router you determine what should happen when a user visits a certain page.

