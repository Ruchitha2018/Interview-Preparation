# Redux

#### What is Redux?
- pattern and library for managing and updating the application state
- serves as centralized store for state that need to be accessed accross the entire application 
---
#### What is Action?
- Plain JS object 
- type field and payload

```
return {
    type: 'COUNT',
    payload: num
}
```
---
#### What is Action Creator?
- pure function which creates the action.
```
export const incNumber = (num) => {
    return {
    type: 'COUNT',
    payload: num
}
}
```
---
#### What is Reducers?
- Are functions
- take the current state and action as arguments
- return a new state result.