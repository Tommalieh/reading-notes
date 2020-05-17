# Node Ecosystem, TDD, CI/CD

### Why would you want to run JavaScript code outside of a browser?

* Running JavaScript without/outside a browser means you are using node.js technology to execute your JavaScript code. This type of usage of javascript typically refers to backend programming where your javascript code will interact with your database and can be used to create RESTful APIs.

### What is the difference between a module and a package?

* Module is a file which contains functions , global variables etc. It is nothing but a file which has executable code / statement.

* Package is namespace which contains a set of modules.

### What does the node package manager do?

* Node Package Manager (NPM) is a command line tool that installs, updates or uninstalls Node.js packages in your application. It is also an online repository for open-source Node.js packages. The node community around the world creates useful modules and publishes them as packages in this repository.

### Code snippets showing 3 different ways to export a function from a node module

1. ```
   module.exports = {
    method: function() {},
    otherMethod: function() {},
   };
   ```

2. ```
   exports.method = function() {};
   exports.otherMethod = function() {};
   ```

3. ```
   module.exports.method = function() {};
   module.exports.othermethod = function() {};
   ```

## Vocabulary Terms



| Term  | Defenition  |
|---|---|
| Ecosystem  | A collection of software projects, which are developed and co-evolve in the same environment  |
| Node.js  | Node.js® is a JavaScript runtime built on Chrome's V8 JavaScript engine, which is an open source development platform for executing JavaScript code server-side.  |
| V8 Engine  | V8 is Google’s open source high-performance JavaScript and WebAssembly engine, written in C++. It is used in Chrome and in Node.js, among others. It implements ECMAScript and WebAssembly, and runs on Windows 7 or later, macOS 10.12+, and Linux systems that use x64, IA-32, ARM, or MIPS processors. V8 can run standalone, or can be embedded into any C++ application.  |
| Module  | A file which contains functions , global variables etc. It is nothing but a file which has executable code / statement.  |
| Package  | Package is namespace which contains a set of modules.  |
| Node Package Manager (NPM)  | Node Package Manager (NPM) is a command line tool that installs, updates or uninstalls Node.js packages in your application. It is also an online repository for open-source Node.js packages.  |
| Server  | A server is a computer program or a device that provides functionality for other programs or devices, called "clients". This architecture is called the client–server model. Servers can provide various functionalities, often called "services", such as sharing data or resources among multiple clients, or performing computation for a client.  |
| Environment  | The set of processes and programming tools used to create the program or software product.  |
| Interpreter  | A computer program that directly executes instructions written in a programming or scripting language, without requiring them previously to have been compiled into a machine language program.  |
| Compiler  | A compiler is a software program that converts computer programming code written by a human programmer into binary code (machine code) that can be understood and executed by a specific CPU. The act of transforming source code into machine code is called "compilation."  |
|   |   |


