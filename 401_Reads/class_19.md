
### Class 19

### AWS: Events



**Describe the similarities between AWS API Gateway + Lambda functions and an ExpressJS Server**

AWS API Gateway and Lambda functions together can work almost exactly like an express server. In an express server, you make routes and then you fire them with functions. In AWS, you make routes in API Gateway and they trigger a Lambda function to run


**List the AWS Database offerings and talk about the pros and cons of each**

Database offerings can be found here (Links to an external site.). There is an excellent table under the Database services section that lists the Database types, their use cases, and the AWS services that offer those database types. Types include Relational, key-value, in memory, Document, Wide column, graph, time series, and ledger


**What’s the difference between a FIFO and a standard queue?**

A FIFO queue is first in, first out. A standard queue is more randomized, but guarantees that an item is only ‘delivered’ once, meaning if an item leaves the queue it is now gone from the queue.


**How can the server be assured a message was properly received?**

It returns a 200 status


--------------------

### Term

**Serverless API** : An API that lives in the cloud and is created using cloud services.


**Triggers** : Essentially a connection between resources. When something happens to a resource, it triggers an action to be taken.


**Dynamo vs Mongo** : Dynamo is like the AWS version of Mongo. Mongo is open source and uses JSON objects, whereas Dynamo uses tables. MongoDB is less restrictive of data types and size.


**Dynamoose vs Mongoose** : Dynamoose is a modeling tool used for dynamo and mongoose is used for mongo.

