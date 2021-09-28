
 ## <Login /> and <Auth />



**Why is the Context API useful?**

- It enables you to exchange unique details and assists in solving prop-drilling from all levels of your application.

**Can a component outside of a provider get its context?**

- Yes we can call useContext in each component to pull out the values we need. It doesn’t matter how far apart the components are as long as they’re wrapped in a provider.

**What are some common use cases for using the Context API?**
 
- Some sample use cases where the Context API proves helpful are: Theming — Pass down app theme. i18n — Pass down translation messages. Authentication — Pass down current authenticated user. 

**Describe “Context Hell”**

- The React Context hell is the nasty code you get taking advantage of the React Context API.

-------------------

### Term


**global state :** Global state is the data that is shared between all the components within a React application.


**global context :** is about how concerned we are worldwide, how we make decisions about global issues and how we can act in a responsible way to make the world a better place. … The opportunities and tensions provided by world- interconnectedness; The impact of decision- making on humankind and the environment.Apr 29, 2021


**provider :** Every Context object comes with a Provider React component that allows consuming components to subscribe to context changes. The Provider component accepts a value prop to be passed to consuming components that are descendants of this Provider. One Provider can be connected to many consumers.


**consumer :** A React component that subscribes to context changes. Using this component lets you subscribe to a context within a function component. Requires a function as a child. The function receives the current context value and returns a React node.