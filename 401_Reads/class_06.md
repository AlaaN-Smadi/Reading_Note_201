
## Class 06

### Authentication


#### Q1 : Explain what a “Singleton” is (in Computer Science terms)

A singleton is a class that allows only a single instance of itself to be created and gives access to that created instance. It contains static variables that can accommodate unique and private instances of itself. It is used in scenarios when a user wants to restrict instantiation of a class to only one object. This is helpful usually when a single object is required to coordinate actions across a system.


#### Q2 : Explain how the Singleton pattern can be used with Node modules, specifically with classes

- Creating singleton in Node.JS is very easy. When we take advantage of Node.JS caching then this is trivial. In this article we showed two ways of achieving the same results and I strongly recommend to use the latter one.

- The singleton pattern is used in programming languages such as Java and .NET to define a global variable.


#### Q3 : If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?

Bind application-level middleware to an instance of the app object by using the app.use() and app.METHOD() functions, where METHOD is the HTTP method of the request that the middleware function handles such as GET, PUT, or POST in lowercase.


--------------------------

## Document the following Vocabulary Terms

- **Router Middleware** : The term is composed of 2 words router and middleware ; 
**middleware** => It is a piece of code that comes in the middle of request and response. It kind of hijacks your request so that you can do anything that you want with your request or response eg: Modify the data or call the next middleware. Middleware functions are functions that have access to the request object (req), the response object (res), and the next middleware function in the application’s request-response cycle
**Router** => In Express, usually, we make end-points that uses HTTP verbs to denote a GET POST DELETE PUT etc requests. Router is used to manage these incoming requests. It kind of routes your requests to correct handler/code


- **Dynamic Module Loading** : Dynamic loading is a mechanism by which a computer program can, at run time, load a library (or other binary) into memory, retrieve the addresses of functions and variables contained in the library, execute those functions or access those variables, and unload the library from memory. ...

- **Singleton Pattern** : In software engineering, the singleton pattern is a software design pattern that restricts the instantiation of a class to one "single" instance. This is useful when exactly one object is needed to coordinate actions across the system. The term comes from the mathematical concept of a singleton.

- **CRUD -> REST Method Matches** :  CRUD stands for Create, Read, Update, and Delete, which are four primitive database operations. At first glance, these operations map well to the HTTP verbs most frequently used in REST POST , GET , PUT ,DELETE

- **Mock Testing** : In object-oriented programming, mock objects are simulated objects that mimic the behavior of real objects in controlled ways, most often as part of a software testing initiative.