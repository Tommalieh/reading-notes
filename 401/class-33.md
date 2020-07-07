## Role-based access control:
Role-based access control (RBAC) restricts network access based on a person's role within an organization and has become one of the main methods for advanced access control. The roles in RBAC refer to the levels of access that employees have to the network.

### Benefits  of RBAC
- Reducing administrative work and IT support.
- Maximizing operational efficiency.
- Improving compliance.

### Isomorphic cookies
To be able to access user cookies while doing server-rendering, you can use plugToRequest or setRawCookie.

```<CookiesProvider />```
Set the user cookies
On the server, the ```cookies``` props must be set using ```req.universalCookies``` or ```new Cookie(cookieHeader)```