## API server

* The API Server is a lightweight Web application that allows users to create and expose data APIs from data, without the need for custom development.
router.param(name, callback)

* Adds callback triggers to route parameters, where name is the name of the parameter and callback is the callback function. Although name is technically optional, using this method without it is deprecated starting with Express v4.11.0.

### router.route(path)

* Returns an instance of a single route which you can then use to handle HTTP verbs with optional middleware. Use router.route() to avoid duplicate route naming and thus typing errors.

### router.use([path], [function, ...] function)

* Uses the specified middleware function or functions, with optional mount path path, that defaults to “/”.

### Types of Middleware
1. Document middleware.
2. Model middleware.
3. Query middleware.
4. Aggregate middleware.

### Subdocument

* Are similar to normal documents. Nested schemas can have middleware, custom validation logic, virtuals, and any other feature top-level schemas can use.