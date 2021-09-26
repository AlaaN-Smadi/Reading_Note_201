# Context API
- Context is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language. Using context, we can avoid passing props through intermediate elements
**Describe use cases useState() vs useReducer()**
- useReducer is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one. useReducer also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks.
- useState does not automatically merge update objects, Another option is useReducer , which is more suited for managing state objects that contain multiple sub-values.
**Why do custom hooks need the use prefix?**
- Custom hooks are normal JS functions, named with the prefix ‘use’, that can use hooks inside of it and contain a common stateful logic to be reused in other components.
**What do custom hooks usually do?**
- Custom hooks allow us to have cleaner functional components, remove logic from the UI layer, and prevent code duplication by bringing common use cases to reusable hooks.
**Using any list of custom hooks, research and name one that you think will be useful in your applications?**
- useContext: Accepts a context object (the value returned from React.createContext) and returns the current context value for that context.
**Describe how a hook that fetches API data might work**
- Put the fetchData function above in the useEffect hook and call it.
## Terms
- reducer: a reducer is a pure function that takes an action and the previous state of the application and returns the new state. The action describes what happened and it is the reducer’s job to return the new state based on that action.

