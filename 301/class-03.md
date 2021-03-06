## Javascript Templating - Mustache.js

* Javascript templating is a fast and efficient technique to **render client-side view templates** with Javascript by using a **JSON data source**. 

* The template is HTML markup, with added templating tags that will either insert variables or run programming logic.

* The **template** engine then replaces variables and instances declared in a template file with actual values at runtime, and convert the template into an HTML file sent to the client.

* **Mustache** is a logic-less template syntax. It **can be used for HTML, config files, source code — anything**. It works by **expanding tags in a template using values provided in a hash or object**.

* It is often referred to as **“logic-less”** because there are no if statements, else clauses, or for loops. Instead, there are only tags. Some tags are replaced with a value, some nothing, and others a series of values.

* Example:
```
Mustache.render(“Hello, {{name}}”, { name: “Sherlynn” });
// returns: Hello, Sherlynn

```

* In the above, **we see two braces around** `{{ name }}`. This is **Mustache syntax** to show that it is a **placeholder**. When Mustache compiles this, it will look for the ‘name’ property in the object we pass in, and replace {{ name }} with the actual value, e,g, “Sherlynn”.


## Flexbox

* The Flexbox Layout **(Flexible Box)** module aims at providing a more efficient way to lay out, align and distribute space among items in a container, even when their size is unknown and/or dynamic **(thus the word “flex”)**.

*  A flex container expands items to fill available free space or shrinks them to prevent overflow.

* Flexbox layout is most appropriate to the components of an application, and small-scale layouts, while the Grid layout is intended for larger scale layouts.

* If “regular” layout is based on both block and inline flow directions, the flex layout is based on **“flex-flow directions”**. 