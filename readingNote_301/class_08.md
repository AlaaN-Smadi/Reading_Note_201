## RESTful web API design


### designed web API should aim to support:
- Platform independence: Any client should be able to call the API, regardless of how the API is implemented internally. This requires using standard protocols, and having a mechanism whereby the client and the web service can agree on the format of the data to exchange.

- Service evolution: The web API should be able to evolve and add functionality independently from client applications. As the API evolves, existing client applications should continue to function without modification. All functionality should be discoverable so that client applications can fully use it.


### What is REST? In 2000, Roy Fielding proposed Representational State Transfer (REST) as an architectural approach to designing web services. REST is an architectural style for building distributed systems based on hypermedia. EST is independent of any underlying protocol and is not necessarily tied to HTTP.

## some of the main design principles of RESTful APIs using HTTP:

- REST APIs are designed around resources.
- A resource has an identifier, which is a URI that uniquely identifies that resource.
- Clients interact with a service by exchanging representations of resources.
- REST APIs use a uniform interface, which helps to decouple the client and service implementations.
- REST APIs use a stateless request model.
- REST APIs are driven by hypermedia links that are contained in the representation.

![API](https://mostaql.hsoubcdn.com/uploads/739469-UpV68-1593888299-5f00ce2b67fe3.jpg)

### What does it mean to have a ‘chatty’ web API?
- Is this a good or a bad thing? A web API that have more requests, which is bad as it lower the performance.

### What status code does a successful GET request return?
- A successful GET method typically returns HTTP status code 200 (OK).

### What status code does an unsuccessful GET request return?
- If the resource cannot be found, the method should return 404 (Not Found).

### What status code does a successful POST request return?
- If a POST method creates a new resource, it returns HTTP status code 201 (Created).

### What status code does a successful DELETE request return?
- indicating that the process has been successfully handled, but that the response body contains no further information.

