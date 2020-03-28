## HTML

### Forms

* Whenever you want to **collect information** from visitors you will need a form, which lives inside a `<form>` element.

* Information from a form is sent in **name/value** pairs.

* Each **form control** is given a **name**, and the text the user types in or the values of the options they select are sent to the **server**.

* There are several **types of form controls** that you can use to **collect information** from visitors to your site. Such as:

  1. Adding text
  2. Making choices
  3. Submitting forms
  4. Uploading files

* So how does forms work?!

  * A user fills in a form and then presses a button to submit the information to the server.

  * The name of each form control is sent to the server along with the value the user enters or selects.

  * The server processes the information using a programming language such as PHP, C#, VB.net, or Java. It may also store the information in a database.

  * The server creates a new page to send back to the browser based on the information received.

* A form may have several form controls, each gathering different information. The server needs to know which piece of inputted data corresponds with which form element.

* Form controls live inside a `<form>` element. This element **should always carry** the **action attribute** and will usually have a method and id attribute too.

* Every `<form>` element requires an `action` attribute. It's value is the URL for the page on the server that will recive the information in the form when it is submitted.

* Forms can be sent using one of two methods: **get** or **post**.

  * With the **get** method, the **values** from the form are **added** to the end of the **URL** specified in the action attribute. Mostly used for:
    * Short forms (such as search boxes)
    * When you are just **retrieving** data from the web server *(not sending information that should be added to or deleted from a database)*.

  * With the **post** method the **values** are **sent** in what are known as **HTTP headers**. As a rule of thumb you should use the post method if your form. Mostly used for:
    * To upload a file 
    * Very long forms
    * Contains sensetive data *(e.g. passwords)*
    * adds information to, or deletes information from a database.

* The `<input>` element is used to **create several different form controls**. The **value** of the `type` attribute determines what kind of input they will be creating.

* Each form control **requires** a `name` attribute. The **value** of this attribute **identifies** the form control and is **sent** along with the information they enter to the **server**.

## CSS

* Forms are **easier** to use if the form controls are **vertically aligned** using CSS.

* Forms **benefit** from styles that make them feel more **interactive**.


## JavaScript

### Events

* Events are the browser's way of **indicating** when something has happened (such as when a page has finished loading or a button has been clicked). 

* Binding is the **process** of **stating** which event you are waiting to happen, and which element you are waiting for that event to happen upon. 

* When an event **occurs** on an element, it can **trigger** a JavaScript **function**. this **function** then **changes** the web page in some way, it feels **interactive** because it has responded to the user. 

* You can use event **delegation** to **monitor** for **events** that happen on all of the children of an element. 

* The most commonly used events are **W3C DOM** events, although there are others in the HTMLS specification as well as browser-specific events. 






