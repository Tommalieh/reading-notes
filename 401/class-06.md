# Express

## Express Routing

* Event driven system
  * `app.get('/thing', (req,res) => {})`
  * This is the same pattern we see in **Vanilla JS**, **jQuery**
  * ‘When a get event happens in our server, on “/thing”, run this function…’


* Express Middleware
  * What does it do?
    * A series of functions that the request “goes through”
    * Each function receives `request`, `response` and `next` as **parameters**
    * Types of middleware:
      1. Application
         * Error Handling
         * Bringing in other routes
         * Applies Defaults
         * JSON, Body and Form Parsing
         * Runs on every request

      2. Route
         * Dealing with specific things for a route
         * Generally, things many routes would participate in
           * Are you logged in?
           * What is your IP?
           * Have we seen you here before?


## CRUD Operations with REST and Express

 * CREATE
   * `app.post('/resource')`
 * READ
   * `app.get('/resource')`
 * UPDATE
   * `app.put('/resource/:id')`
 * DESTROY
   * `app.get('/resource/:id')`

## Server Testing

* Generally, avoid starting the actual server for testing Instead, export your server as a module in a library. Then, you can use `supertest` to run your tests.

  * This will hit your routes as though your server was running, without actually starting it
  * That’s one less thing to go wrong (eliminate variables when testing!)


## Test Pyramid

* Server Testing crosses boundaries
  * Units: Server Internal Functions
    * Mock any integrations (like data fetching)

* Integration: How it connects to other services
  * Really connect to other services (hard dependencies)

* Acceptance
  * The server might be a dependency of some other test
