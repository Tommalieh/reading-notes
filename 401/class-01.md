# Classes, Inheritance, Functional Programming

### 3 advantages to Test Driven Development:

 * TDD creates code that is maintainable, flexible, and easily extensible.

 * The resulting unit tests are simple and act as documentation for the code. Since TDD use cases are written as tests, other programmers can view the tests as usage examples of how the code is intended to work.

 * The programmer’s productivity is increased.

###  What case would you need to use beforeEach() or afterEach() in a test suite?

 * It should be run before/after every `describe/it` block in the current context completes. However, the behavior noticed was that `beforeEach` and `afterEach` are run before/after every `it` block in the current context and all nested contexts.

### Downside of Test Driven Development

 * **No silver bullet**: Tests help to find bugs, but they can't find bugs that you introduce in the test code and in implementation code. If you haven't understood the problem you need to solve, writing tests most probably doesn't help.

### Primary difference between ES6 Classes and Constructor/Prototype Classes

 * The most important difference between class- and prototype-based inheritance is that a class defines a type which can be instantiated at runtime, whereas a prototype is itself an object instance.

### Static properties and methods

 * Static methods are used to assign a method to the class function itself, not to its "prototype".

### Higher Order Functions

 * For example, we can have functions that create new functions.
```

function greaterThan(n) {
  return m => m > n;
}
let greaterThan10 = greaterThan(10);
console.log(greaterThan10(11));
// → true

```

 * And we can have functions that change other functions.

```
function noisy(f) {
  return (...args) => {
    console.log("calling with", args);
    let result = f(...args);
    console.log("called with", args, ", returned", result);
    return result;
  };
}
noisy(Math.min)(3, 2, 1);
// → calling with [3, 2, 1]
// → called with [3, 2, 1] , returned 1

```

## Vocabulary Terms


| Term  | Defenition  |
|---|---|
| Functional Programming  | The process of building software by composing pure functions, avoiding shared state, mutable data, and side-effects.  |
| Pure Function  | A function which given the same input, will always return the same output.
Produces no side effects.  |
| Higher-Order Function  | Functions that operate on other functions, either by taking them as arguments or by returning them  |
| Immutable State  | Immutable state is state that cannot be changed. Immutable objects (for which none of the state can be changed) become important when you are dealing with concurrency, the ability for more than one processor in your computer to operate on that object at the same time.
  |
| Object  | An object, in object-oriented programming (OOP), is an abstract data type created by a developer. It can include multiple properties and methods and may even contain other objects. In most programming languages, objects are defined as classes.  |
| Object Oriented Programming  | a programming paradigm based on the concept of "objects", which can contain data, in the form of fields (often known as attributes or properties), and code, in the form of procedures (often known as methods). Programs are designed by making them out of objects that interact with one another.  |
| Class  | an extensible program-code-template for creating objects, providing initial values for state (member variables) and implementations of behavior (member functions or methods).  |
| Prototype  | Is an object that is associated with every functions and objects by default in JavaScript, where function's prototype property is accessible and modifiable and object's prototype property (aka attribute) is not visible  |
| Super  | Keyword is used to access and call functions on an object's parent.  |
| Inheritance  | Inheritance refers to an object's ability to access methods and other properties from another object. Objects can inherit things from other objects. Inheritance in JavaScript works through something called prototypes and this form of inheritance is often called prototypal inheritance.  |
| Constructor   | A constructor is a function that creates an instance of a class which is typically called an “object”. In JavaScript, a constructor gets called when you declare an object using the new keyword. The purpose of a constructor is to create an object and set values if there are any object properties present  |
| Instance  | An “instance” means a reference to an “object” created by “new” or the equivalent.What's special about JavaScript, and other scripting languages, is that an “instance” is just a regular object; it's not what it is, but how it's made that is different.  |
| Context  | Context is always the value of the this keyword which is a reference to the object that “owns” the currently executing code  |
| This  | Keyword refers to the object it belongs to.And It has different values depending on where it is used  |
| Test Drivin Development  | Test-driven development is a programming methodology with which one can tackle the design, implementation, and testing of units of code, and to some extent the expected functionality of a program.  |
|  Jest | Jest is a JavaScript test runner, that is, a JavaScript library for creating, running, and structuring tests. Jest is distributed as an NPM package, you can install it in any JavaScript project. Jest is one of the most popular test runner these days and the default choice for Create React App.  |
| Continuous Integration (CI)  | Practices used by developers all over the world to increase the quality of their software, and decrease the time to market for features and bug fixes.  |
| Unit testing  | Unit testing is the process of testing the implemented code at a module level. Unit testing allows you to ensure that your developed modules are meeting the requirements specified by the business document. These tests are written for every module as they are created. After every new module development, the entire suite of test cases is run to ensure that no existing modules are affected by the developed module.
  |
|   |   |

