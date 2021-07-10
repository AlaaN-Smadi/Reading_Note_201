# In memory storage

## What is a refrence error?

- The call stack is primarily used for function invocation (call).
- The call stack is synchronous.
- A call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).
- the last function that gets pushed into the stack is the first to be pop out .
- The call stack maintains a record of the position of each stack frame.
- A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point.


## What is a ‘syntax error’
- this occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.

## What is a ‘range error’
- Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.

## What is a ‘tyep error’
- These types of errors show up when the types (number, string, ..) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

## What is a breakpoint
- At each breakpoint, JavaScript will stop executing, and let you examine JavaScript values. After examining values, you can resume the execution of code (typically with a play button).

## Debugging >>> open your page with your JS code > (press cmd+o in macOS or Ctrl+o in Windows) > choose your file to debug, click the line you wanna debug > refresh your page again (F5).

## What does the word ‘debugger’ do in your code
- the easiest and maybe the most common way its to simply console.log() the variables you want to check or, by using chrome developer tools

