<!-- @format -->

### Hooks

1. Hooks allow function components to have access to state and other React features. Because of this, class components are generally no longer needed.
2. Hooks generally replace class components, there are no plans to remove classes from React.
3. Hooks allow us to "hook" into React features such as state and lifecycle methods.
   There are 3 rules for hooks:

- Hooks can only be called inside React function components.
- Hooks can only be called at the top level of a component.
- Hooks cannot be conditional.
- Note: Hooks will not work in React class components.

---

The React useState Hook allows us to track state in a function component.
State generally refers to data or properties that need to be tracking in an application.

`useState` accepts an initial state and returns two values:

- The current state.
- A function that updates the state.

`useState` Hook can be used to keep track of strings, numbers, booleans, arrays, objects, and any combination of these.
