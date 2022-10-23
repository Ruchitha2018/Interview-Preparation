# React Basics

### What is React?
- Open-Source, JS Frontend library 
- Used for building user interfaces for SPA
- Used for handling mobile and web views
- Created by Jordan walke, software engineer - Facebook

### Major Features for React?
- Uses Virtual DOM 
- Server-side rendering 
- Composable/Reusuable UI components
- Unidirectional Data Flow

### What is JSX?
- Javascript XML
- Syntactic Sugar of React.createElement()
- JS along with HTML like template syntax.

### Element vs Component?

### How to create components in React?
- Class Component
- Function Component

### When to use Class Component over a Function Component?
- Class Component: Before React 16, if the component need state and lifecycle methods.
- Function Component: After React 16, we can use state and lifecycle methods using Hooks
- Error boundaries is not present in Function Component.

### What is State in React?
- It is an object
- Holds some information about the component that may change over the lifetime of the component.
- private 
- fully controlled by the component

### What are props?
- input to Components
- contain single value or object
- data passed data from parent to child component
- using naming conventions like HTML-tag attribute

### State vs Props?
- Props - Similar to Function Parameters
- State - Managed within the component similar to variables declared within a function

### Why should we not update the state directly?
- wont re-render the component

### HTML and React Event Handling 
- HTML - represents in lowercase - activateUsers()
- React - camelCase - activateUsers

- HTML - returns false; to prevent default behaviour
- React - event.preventDefault()

- HTML - invoke the function by appending ()
- React - should not append ()

### How to add Event Handlers?
- onClick = {() => setCounter(2)}
- onClick = {setCount}

### Inline Conditional Expressions
{&&}

### What is 'key' prop ?
- special String attribute include when creating an array of elements.
- helps identify which items have changed, added or removed
- gives us a warning message, if the key prop is not present.

### What are refs?
- returns a reference to the element
- direct access to the DOM element or an instance of a component.
- should be avoided in most cases.

### How to create refs?
- attach a ref attribute to the element
- useRef() hook

### Virtual DOM?
- in-memory representation of Real-DOM
- Representation of UI is kept in memory and sync with the Real-DOM

### How Virtual DOM Works?
- When the data gets change, the entire UI is re-rendered in Virtual DOM
- Difference between previous Virtual DOM and new Virtual DOM is calculated.
- Once the calculations are done, then Real-DOM will be updated with only the things that have actually changed.

### Shadow DOM 
- Scoping variables

### Controlled Components
- Form data is handled by the Components State.
- Makes changes through callbacks like onClick, onChange.
- Recommended Way

### UnControlled Components
- Form data is handled by the DOM
- We use ref attributes to get the instance of the DOM.
- During the lifecycle of the component, the form elements can lose their reference and may   be changed/affected by other sources.

### How to make Ajax call?
- Ajax libraries using Axios, Jquery, Ajax and browser built-in fetch method
- Call Api in useEffect Hook

### Popular Packages for animation
- React Motion
- React Transition Group

### Common Folder structure for React?
- Group by Features or routes
- Group by File Type

### Approaches to include polyfills in create-react-app
- Manual import from core-js
- Polyfill CDN