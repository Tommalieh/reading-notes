## Charts

* Charts are far better for **displaying data** visually than tables. They’re easier to look at and convey data quickly, but they’re not always easy to create.

* **Chart.js**, a **JavaScript plugin** that uses **HTML5’s** canvas element to draw the graph onto the page. It’s a well documented plugin that makes using all kinds of bar charts, line charts, pie charts and more, incredibly easy.


## Canvas API

* A `<canvas>` looks like the `<img>` element, with the only clear difference being that it doesn't have the src and alt attributes. The `<canvas>` element has only two attributes, width and height.

* The canvas will **initially** be *300 pixels wide and 150 pixels high*. The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted.

* The canvas is initially blank. To display something, a script first needs to access the rendering context and draw on it.

* As a consequence of the way fallback is provided, unlike the <img> element, the <canvas> element requires the closing tag (`</canvas>`). If this tag is not present, the rest of the document would be considered the fallback content and wouldn't be displayed.

* The fallback content is displayed in browsers which do not support <canvas>. Scripts can also check for support programmatically by simply testing for the presence of the getContext() method.

* Unlike SVG, <canvas> only supports two primitive shapes: rectangles and paths (lists of points connected by lines). All other shapes must be created by combining one or more paths. Luckily.
