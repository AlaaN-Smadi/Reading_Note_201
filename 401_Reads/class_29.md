
### Reading Class_29

### Advanced State with Reducers

**How can we ensure that an effect hook runs only once?**

If we pass an empty array [] , it just renders the component only once like componentDidMount .

**Can useState() update more than one state variable at the same time?**

You could combine the state into one state object and then you could do one setState call and there will only be one render. Unlike the setState in class components, the setState returned from useState doesn’t merge objects with existing state, it replaces the object entirely.

**Is useState() synchronous?**

useState and setState both are asynchronous. Even though they are asynchronous, the useState and setState functions do not return promises. Therefore we cannot attach a then handler to it or use async/await to get the updated state values.


**Terms**

-> State Hook: Hook state is the new way of declaring a state in React app. Hook uses useState() functional component for setting and retrieving state.

-> Component Lifecycle: Each component in React has a lifecycle which you can monitor and manipulate during its three main phases. The three phases are: Mounting, Updating, and Unmounting.