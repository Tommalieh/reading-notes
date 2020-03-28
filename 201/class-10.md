## JavaScript

### Error Handling and Debugging

* To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run

* The JavaScript interpreter uses the concept of execution contexts. There is one global execution context; plus, each function creates a new execution context. They correspond to variable scope.

* In the interpreter, each execution context has its own variables object. It holds the variables, functions, and parameters available within it. Each execution context can also access its parent’s variables object.

* If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handling code. 

* Error objects can help you find where your mistakes are and browsers have tools to help you read them. 

* Debugging is about deduction: eliminating potential causes of an error.Try to narrow down where the problem might be, then look for clues. 

* You can pause the execution of a script on any line using breakpoints. Then you can check the values stored in variables at that point in time. 

* You can indicate that a breakpoint should be triggered only if a condition that you specify is met. The condition can use existing variables.
