# HTTP & REST

## HTTP

* The Hyper Text Transfer Protocol (HTTP) is a stateless request-response application layer protocol.

* Applications built using HTTP subscribe to the client-server computing model. In the client-server computing model a host designed to provide a service is called a server. Clients are hosts that make requests to that service.

* The HTTP specification defines how requests and responses should be formatted, but not what a service should represent

* HTTP is often associated with serving .html files but is also used to transfer images, videos, .json, .xml, binary executables, and much more.

### HTTP Requests

* A HTTP/1.1 request is formatted in text and transferred using TCP. The first line of the request contains the **METHOD**, **URL**, and **HTTP VERSION**. The following lines are the request **HEADERS**.

* A header is a key value pair separated using a colon. Headers containing more than one value separate each value using a semicolon.

*  The header section of the request is terminated with an empty line. An optional body follows the header section.

### HTTP Response

* A HTTP/1.1 response is also formatted in text and transferred using TCP.

* The first line of the response contains the **HTTP VERSION**, **STATUS CODE**, and **STATUS MESSAGE**.

* The following lines are the request headers and are formatted exactly the same way as the request headers.

* The header section of the request is terminated with an empty line. An optional body follows the header section.

## REST

* REST is acronym for REpresentational State Transfer. In layman’s terms, is a means by which we can reference, manipulate, and transfer state.

* Rest uses a common set of methods (called “verbs”) to operate on the state of a resource (“noun”), generally using HTTP as the transfer protocol.

* A “RESTful Endpoint” is a URI that identifies the resource. When addressed with a proper method, you are able to effect state. In normal terms, this means “Performing CRUD operations over HTTP”

* Generally speaking, RESTful endpoints deliver data in JSON format. The best practice is to supply a header with metadata and a collection of results
