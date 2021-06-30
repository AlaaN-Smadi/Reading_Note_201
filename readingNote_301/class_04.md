# React and Forms
----------------

![Form](https://camo.githubusercontent.com/de335b2394ad6bde6b925dc1c2eda3e348f5e88b84d269d4b8442366aeb75864/68747470733a2f2f7777772e636f6e6372657465706167652e636f6d2f616e67756c61722d322f696d616765732f616e67756c61722d322d666f726d636f6e74726f6c2d6578616d706c652d322e6a7067)

#### well, what is a ‘Controlled Component’?
#### We can combine the two by making the React state be the “single source of truth”. Then the React component that renders a form also controls what happens in that form on subsequent user input. An input form element whose value is controlled by React in this way is called a “controlled component”.

--------------
## The < FormControl >
#### component renders a form control with Bootstrap styling. The < FormGroup > component wraps a form control with proper spacing, along with support for a label, help text, and validation state. To ensure accessibility, set controlId on < FormGroup >, and use < FormLabel > for the label.

#### handleChange runs on every keystroke to update the React state

#### - < textarea > uses a value attribute instead. -

Handling Multiple Inputs
handle multiple controlled input elements, you can add a name attribute to each element and let the handler function choose what to do based on the value of "event. target. name".

-------------------
## The Conditional (Ternary) Operator Explained

#### Why would we use a ternary operator? to decision making in place of longer if and else conditional statements.

#### Rewrite the following statement using a ternary statement if(x===y){ console.log(true); } else { console.log(false); } solution:

### - x===y?console.log(true):console.log(false); -
