## Error Handling & Debugging

#### To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run .

![JS_Error](https://www.oreilly.com/library/view/javascript-and-jquery/9781118531648/images/p452-001.jpg)

#### This script above creates a greeting message, then writes it to an alert box (see right-hand page). In order to create that greeting, two functions are used: greetUser() and getName() .

#### You might think that the order of execution (the order in which statements are processed) would be as numbered: one through to four. However, it is a little more complicated

### EXECUTION CONTEXTS

#### The JavaScript interpreter uses the concept of execution contexts. There is one global execution context; plus, each function creates a new execution context. They correspond to variable scope.


### UNDERSTANDING ERRORS

#### If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handling code.

#### Error objects can help you find where your mistakes are and browsers have tools to help you read them.

#### When an Er ror object is created, it will contain the following properties:

PROPERTY | DESCRIPTION
------- | -------
name | Type of execution
message |  Description
fileNumber | Name of the JavaScript file
lineNumber | Line number of error


#### There are seven types of built-in error objects in JavaScript. You'll see them on the next two pages:

![image error](https://i.stack.imgur.com/QnUPb.png)

Object | Description 
-------- | --------
Error | Generic error - the other errors are all based upon this error
SyntaxError | Syntax has not been followed
ReferenceError | Tried to reference a variable that is not declared/within scope
TypeError | An unexpected data type that cannot be coerced
RangeError | Numbers not in acceptable range
URIError | encodeURI ().decodeURI(),and similar methods used incorrectly
EvalError | eval () function used incorrectly

----------


## HOW TO DEAL WITH ERRORS

- DEBUG THE SCRIPT TO FIX ERRORS
- HANDLE ERRORS GRACEFULLY

#### If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements. Use them to give your users helpful feedback .

#### If you understand execution contexts (which have two stages) and stacks, you are more likely to find the error in your code.

