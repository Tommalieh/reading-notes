## Context

### Context provides a means of passing state down the component tree through a Provider/Consumer relationship.

### In a functional component, you can use the useContext() hook to tap right in.Returns and provides access to whatever your context provider exports

### In a typical React application, data is passed top-down (parent to child) via props, but this can be cumbersome for certain types of props (e.g. locale preference, UI theme) that are required by many components within an application. Context provides a way to share values like these between components without having to explicitly pass a prop through every level of the tree.

## When to Use Context

### Context is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language.

![IMG](https://camo.githubusercontent.com/7105a3291d846f93bc05ae0a972b98b191b9c7ea/68747470733a2f2f75706c6f6164732e746f7074616c2e696f2f626c6f672f696d6167652f3132393037312f746f7074616c2d626c6f672d696d6167652d313534393332333331343837352d64366263396337353361346339616332393131653861663137373332303233642e706e67)