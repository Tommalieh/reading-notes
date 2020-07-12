## The combineReducers 
- The combineReducers helper function turns an object whose values are different reducing functions into a single reducing function you can pass to createStore.
- The resulting reducer calls every child reducer, and gathers their results into a single state object. The state produced by combineReducers() namespaces the states of each reducer under their keys as passed to combineReducers()

## The actions
- Each reducer technically has it’s own actions and creators.

## Using combineReducers
The most common state shape for a Redux app is a plain Javascript object containing "slices" of domain-specific data at each top-level key. Similarly, the most common approach to writing reducer logic for that state shape is to have "slice reducer" functions, each with the same (state, action) signature, and each responsible for managing all updates to that specific slice of state. Multiple slice reducers can respond to the same action, independently update their own slice as needed, and the updated slices are combined into the new state object.

![image](https://image.slidesharecdn.com/reduxdataflowwithangular2-161118085712/95/redux-data-flow-with-angular-2-20-638.jpg?cb=1479459463)