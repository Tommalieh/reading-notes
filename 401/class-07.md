## Routing

* Routing refers to how an application’s endpoints (URIs) respond to client requests. For an introduction to routing.

## Route methods
* A route method is derived from one of the HTTP methods, and is attached to an instance of the express class.

## Route paths

* Route paths, in combination with a request method, define the endpoints at which requests can be made. Route paths can be strings, string patterns, or regular expressions.

## Route handlers

* Route handlers You can provide multiple callback functions that behave like middleware to handle a request. The only exception is that these callbacks might invoke next(‘route’) to bypass the remaining route callbacks.

* You can provide multiple callback functions that behave like middleware to handle a request. The only exception is that these callbacks might invoke next(‘route’) to bypass the remaining route callbacks. You can use this mechanism to impose pre-conditions on a route, then pass control to subsequent routes if there’s no reason to proceed with the current route.

## express.Router

* Use the express.Router class to create modular, mountable route handlers. A Router instance is a complete middleware and routing system.