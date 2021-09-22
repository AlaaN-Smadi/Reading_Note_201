# Reading: useState() Hook
**How does React differ from vanilla JS/HTML/CSS?**
- React breaks down the UI into smaller and reusable components that can move around data amongst each other. This breaking down of the UI is what gives React an edge over Vanilla JS. … This is where React comes in with a great feature i.e its own virtual DOM. The virtual DOM is a shortcut to bypass the manual work.
Vanilla JS initially renders the UI anywhere from 5-10x faster than Preact, and about 30x faster than React! Handling UI state changes with vanilla JS is also orders of magnitude faster than using Preact or React
**What is the primary difference between a function component and a class component?**
**Functional components**
- Functional components are basic JavaScript functions. These are typically arrow functions but can also be created with the regular function keyword.
- React lifecycle methods (for example, componentDidMount) cannot be used in functional components.
- There is no render method used in functional components.
- Functional components can accept and use props.
- Functional components should be favored if you do not need to make use of React state.
**Class components**
- Class components make use of ES6 class and extend the Component class in React.
- Sometimes called “smart” or “stateful” components as they tend to implement logic and state.
- React lifecycle methods can be used inside class components (for example, componentDidMount).
- You pass props down to class components and access them with this.props.
## Terms
- Functional Components: a function that takes props and returns JSX. They do not have state or lifecycle methods. Functional components are easier to read, debug, and test. They offer performance benefits, decreased coupling, and greater reusability.
- Children / Child Components: Children allow to pass components as data to other components