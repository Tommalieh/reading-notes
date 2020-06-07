# OAuth

## OAUTH2.0

* OAuth is “an open standard for access delegation” … In other words, OAuth serves as a way to give users the ability to grant application access to services, without giving the application their password.

* But if they’ve asked for it (and you agreed to it), the application can also do things such as create or delete documents or access other services “as you”. When you “Login with Google” the application that requested that, for all intents and purposes, Is You … which means it can effectively do things at Google (or facebook, or wherever) as though it was you at the keyboard.

### What are some of the benefits as a client/user to using OAuth?

* It allows limited access to the user's data and allows accessing when authorization tokens expire.

* It has ability to share data for users without having to release personal information.

* It is easier to implement and provides stronger authentication.

### As an application developer, why would you choose this over creating your own login system?

* More simple and less time consuming while providing a good layer of security.

## How does OAuth work?

* An application such as an Express Web Server asks the user if it’s ok to login as them at some remote service, and then begins the process of authentication and access.
