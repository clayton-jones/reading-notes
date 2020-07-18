**[Back](https://clayton-jones.github.io/reading-notes/)**

# Class 32 Reading - Async Actions

## What is an async action?  
Sometimes you want to retrieve information from an API before you dispatch your action, so you need to wait for the API to respond with an asynchronous function.
  
## Thunk?  
Using special redux middleware called `thunk` we can inspect our dispatched actions and handle them accordingly, by either letting them through if it's a standard action, or by processing the given function and then dispatching the action with those results.

## What does it look like?  
``` JavaScript
export default store => next => action =>
  typeof action === 'function'
    ? action(store.dispatch, store.getState)
    : next(action);
```