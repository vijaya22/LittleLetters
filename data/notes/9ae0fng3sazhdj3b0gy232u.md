
What is Redux ?

Redux is a pattern and library for managing and updating application state, using events called "actions". 

It serves as a centralized store for state that needs to be used across your entire application, with rules ensuring that the state can only be updated in a predictable fashion.

Redux is normally used by installing the Redux packages from NPM, and the UI is created using a library like React.

When should I use Redux?

Redux is more useful when:

- You have large amounts of application state that are needed in many places in the app
- The app state is updated frequently over time
- The logic to update that state may be complex
- The app has a medium or large-sized codebase, and might be worked on by many people

Redux Libraries and Tools

- React-Redux
    React-Redux is the official package that lets React components interact with a Redux store by reading pieces of state and dispatching actions to update the store.

- Redux Toolkit
    Used for writing Redux Logic. It contains packages and functions that are essential for building a Redux app.
    
- Redux DevTools Extension
    This allows to debug applications effectively.


The Redux Store
- The center of every Redux application is the store. 

- A "store" is a container that holds your application's global state.

- A store is a JavaScript object with a few special functions and abilities that make it different than a plain global object


