## Read Class 03

### Questions

**3 real world use cases where you’d want to change the request with custom middleware ==>**

- Make changes to the request and the response objects.
- Adding query params
- Handling errors


**The route handler is middleware? ==>**

False
The route handler is a callback function from the definition, So it's not a middleware


**In what ways can a middleware function end the process and send data to the browser?**

in two ways :
- When the function finished , it will apply the next statement and the request will complete the rout method and send the data to the browser
- When something went wrong in the code , the next will throw with an error and send an error to the browser 


**At what point in the request lifecycle can you “inject” middleware?**

- After the rout and before the call back funtion 
- We can use it in a single line 
**Note :** Middlewares will be called before the call back function of the rout handler 


**What can cause express to error with “Request headers sent twice, cannot start a second response”**

When the server received two or more requests and try to send responses, So the server will make an interupt and break all requests and send back an error 

-----------------------------------------

### Document the following Vocabulary Terms


**Middleware :** is software that lies between an operating system and the applications running on it. Essentially functioning as hidden translation layer, middleware enables communication and data management for distributed applications.



**Request Object :** is the main entry point for an application to issue a request to the Library - all operations on a URL must use a Request object.

**Response Object :** One of the most important objects in ASP is the Response object. It is the object which communicates between the server and the output which is sent to the client. 

**Application Middleware :**  is software that lies between an operating system and the applications running on it. Essentially functioning as hidden translation layer, middleware enables communication and data management for distributed applications.

**Routing Middleware :** the way in which the client requests are handled by the application endpoints. And when you make some routers in separate file, you can use them by using middleware

**Test Driven Development (TDD) :**  is software development approach in which test cases are developed to specify and validate what the code will do. In simple terms, test cases for each functionality are created and tested first and if the test fails then the new code is written in order to pass the test and making code simple and bug-free.

**Behavioral Testing :** Behavioural Testing is a testing of the external behaviour of the program, also known as black box testing. It is usually a functional testing.