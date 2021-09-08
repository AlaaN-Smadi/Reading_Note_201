
### Class 16


### AWS: Cloud Servers


**Describe the Web-Request-Response-Cycle**

A user opens his browser, types in a URL, and presses Enter. When a user presses Enter, the browser makes a request for that URL. The request hits the Rails router (config/routes.rb). The router maps the URL to the correct controller and action to handle the request. The action receives the request and passes it on to the view. The view renders the page as HTML. The controller sends the HTML back to the browser. The page loads and the user sees it. In this way, the request/response cycle is a useful way to see how a Rails app’s files and folders are for and how they fit together.


**Explain what a “server” is, as it relates to the WRRC**

A server program awaits and fulfills requests from client programs, which might be running in the same, or other computers. A given application in a computer might function as a client with requests for services from other programs and as a server of requests from other programs.


**What does it mean to “deploy” an application?**

It is the process of installing, configuring, and enabling a specific application or set of applications, usually through an application manager app manager or software management system, to a specific URL on a server.

--------------------

### Term

**Server** : is a computer or system that provides resources, data, services, or programs to other computers, known as clients, over a network.

**Pub/Sub** : Publish/subscribe messaging or pub/sub messaging, is a form of asynchronous service-to-service communication used in serverless and microservices architectures.

**WRRC** : the request/response cycle is a useful guide to see how all the app’s files and folders fit together. The request/response cycle traces how a user’s request flows through the app. Understanding the request/response cycle is helpful to figure out which files to edit when developing an app .