
##  Redux - Combined Reducers



**Why choose Redux instead of the Context API for global state?**

Because it enforces single-source-of-truth, and allows us to standardize how our state is updated across our app. It also allows us to easily modularize our state updates and simplify our interactions with increasingly complex states.

**What is the purpose of a reducer?**

In Redux, a reducer is a pure function that takes an action and the previous state of the application and returns the new state.

**What does an action contain?**

Actions are the only source of information for the store as per Redux official documentation.

**Why do we need to copy the state in a reducer?**

Because it enforces single-source-of-truth, and allows us to standardize how our state is updated across our app. It also allows us to easily modularize our state updates and simplify our interactions with increasingly complex states.


### Terms

**immutable state :**  (unchangeable state) state cannot be modified after it is created. React state should be treated as immutable.


**time travel in redux :**  by tracking state, redux allows devs to “time travel” by reversing state. Because redux is predictable, you can reliably recreate previous states by passing those state objects into the application state.


**action creator :** An action creator is merely a function that returns an action object. Redux includes a utility function called bindActionCreators for binding one or more action creators to the store’s dispatch () function.


**reducer :** A reducer is a function that determines changes to an application’s state.


**dispatch :** the act of passing (or, dispatching) an action from an action creator to a reducer.

