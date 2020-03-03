## Local Storage 

* **Persistent local storage** is one of the areas where native client applications have held an advantage over web applications.

* For **native applications**, the operating system typically provides an **abstraction layer** for storing and retrieving application-specific data.

* **Cookies** were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:

  1. Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over.
  2. Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL).
  3. Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful.

* What we really want is:

  1. A lot of storage space
  2. On the client
  3. That persists beyond a page refresh
  4. Aand isn’t transmitted to the server

  *  Before HTML5, all attempts to achieve this were ultimately unsatisfactory in different ways.

* HTML5 set out to solve: to provide a standardized API, implemented natively and consistently in multiple browsers, without having to rely on third-party plugins.

* **HTML5 Storage** is a specification named Web Storage, which was at one time part of the HTML5 specification proper, but was split out into its own specification for uninteresting political reasons. Certain browser vendors also refer to it as **Local Storage** or **DOM Storage.**

* HTML5 storage is a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or etc... Unlike cookies, this data is never transmitted to the remote web server (unless you go out of your way to send it manually). it is implemented natively in web browsers, so it is available even when third-party browser plugins are not.

* HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string. If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.

* Like other JavaScript objects, you can treat the localStorage object as an associative array. Instead of using the getItem() and setItem() methods, you can simply use square brackets. For example, this snippet of code:

```

var foo = localStorage.getItem("bar");
// ...
localStorage.setItem("bar", foo);

```

  * Could be rewritten to use square bracket syntax instead:

```

var foo = localStorage["bar"];
// ...
localStorage["bar"] = foo;

```

* If you call `key()` with an **index** that is not between **0–(length-1)**, the function will return **null**.

* If you want to keep **track** programmatically of **when** the **storage area changes**, you can **trap** the **storage event**. The storage event is **fired** on the **window object** whenever setItem(), removeItem(), or clear() is called and actually changes something. 

*