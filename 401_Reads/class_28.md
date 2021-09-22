# Reading: Component Lifecycle / useEffect() Hook
- Using this Hook, we tell React that the component needs to do something after render.
**Why do we not need more .html pages in a multi-page React app?**
- A single-page application is an application that loads a single HTML page and all the necessary assets (such as JavaScript and CSS) required for the application to run. Any interactions with the page or subsequent pages do not require a round trip to the server which means the page is not reloaded.
**If we wanted a component to show up on every page, where would we put it and why:question:**
- Inside a <Route />
**What does routing do with the components that were rendered when a new route is requested**
- React Router uses component structure to call components, which display the appropriate information, every time a route is requested we call the components and render it
**What does props.children contain?**
- use props.children on components that represent ‘generic boxes’ and that ‘don’t know their children ahead of time’, and it is used to display whatever that include between the opening and closing tags when invoking a component.
**How do useState() and this.setState() differ?**
- The setState function is used to handle the state object in a React class component.
- SetState is merging the previous state with the new one, it means that you dont have to pass the full state object every time you want to change some part of the state. React will update given properties and won’t touch the rest. The useState’s updater rewrites a previous state with a new one and it does not perform any merging. Its just replacement instead of merging.
## Terms
- State Hook built in function in react that allows you to add and update states to your stateless components.
- Mounting and Un-Mounting “mounting” (adding nodes to the DOM) or render the component, “unmounting” (removing them from the DOM) stop render or unrender the component , and “updating” (making changes to nodes already in the DOM) or edit the exist render of component