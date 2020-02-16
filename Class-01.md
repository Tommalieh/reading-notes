## HTML  


### Structure



* The HTML code is made up of characters that live inside angled brackets — these are called HTML elements. Elements are usually made up of two tags: an opening tag and a closing tag. (The closing tag has an extra forward slash in it.) Each HTML element tells the browser something about the information that sits between its opening and closing tags.

* Tags act like containers. They tell you something about the information that lies between their opening and closing tags.

* The characters in the brackets indicate the tag's purpose. 

* Attributes provide additional information about the contents of an element. They appear on the opening tag of the element and are made up of two parts: a name and a value, separated by an equals sign.

* Example: `<p lang="en-us">Paragraph in English</p>`

* Here an attribute called lang is used to indicate the language used in this element. The value of this attribute on this page specifies it is in US English.

* The attribute name indicates what kind of extra information you are supplying about the element's content. It should be written in lowercase.

* The value is the information or setting for the attribute. It should be placed in double quotes. Different attributes can have different values.

* The majority of attributes can only be used on certain elements, although a few attributes (such as lang) can appear on any element.
 
* Most attribute values are either pre-defined or follow a stipulated format. 

* The standard layout of an HTML page consists of 3 main elements, which are:

1. The `<head></head>`  element: This contains information about the page (rather than information that is shown within the main part of the browser window).

2. The `<title></title>` element: The contents of the `<title>` element are either shown in the top of the browser, above where you usually type in the URL of the page you want to visit, or on the tab for that page (if your browser uses tabs to allow you to view multiple pages at the same time).

3. The `<body></body>` element: Everything inside this element is shown inside the main browser window.  



### Extra Markup



* Block elements: Some elements will always appear to start on a new line in the browser window. These are known as block level elements. Examples of block elements are `<h1>`, `<p>`, `<ul>`, and `<li>`.

* Inline elements: Some elements will always appear to continue on the same line as their neighbouring elements. These are known as inline elements. Examples of inline elements are `<a>`, `<b>`, `<em>`, and `<img>`.

* The `<div>` element allows you to group a set of elements together in one block-level box. It can also make it easier to follow your code if you have used <div> elements to hold each section of the page.

* The `<span>` element acts like an inline equivalent of the `<div>` element. It is used to either:  Contain a section of text where there is no other suitable element to differentiate it from its surrounding text. Or to contain a number of inline elements.

* An `<iframe>` is like a little window that has been cut into your page — and in that window you can see another page. The term iframe is an abbreviation of inline frame. There are a few attributes that you will need to know to use it:
  1. `src= ""`: The src attribute specifies the URL of the page to show in the frame.
  2.  `height= ""` The height attribute specifies the height of the iframe in pixels.
  3. `width= ""` The width attribute specifies the width of the iframe in pixels.
and few other attributes.

* The `<meta>` element lives inside the `<head>` element and contains information about that web page.It is not visible to users but fulfills a number of purposes such as telling search engines about your page, who created it, and whether or not it is time sensitive. (If the page is time sensitive, it can be set to expire.)

* The `<meta>` element is an empty element so it does not have a closing tag. It uses attributes to carry the information. The most common attributes are the `name` and `content` attributes, The value of the `name` attribute can be anything you want it to be. The value of the `name` attribute is the property you are setting, and the value of the `content` attribute is the value that you want to give to this property.
Some defined values for this attribute that are commonly used are:
 
   1. `name= "description"` This contains a description of the page. This description is commonly used by search engines to understand what the page is about and should be a maximum of 155 characters. Sometimes it is also displayed in search engine results.

   2. `name= "keywords"` This contains a list of commaseparated words that a user might search on to find the page. In practice, this no longer has any noticeable effect on how search engines index your site.

   3. `name= "robots"` This indicates whether search engines should add this page to their search results or not. A value of noindex can be used if this page should not be added. A value of nofollow can be used if search engines should add this page in their results but not any pages that it links to.

* The `<meta>` element also uses the `http-equiv` and `content` attributes in pairs. In our example, you can see three instances of the `httpequiv` attribute. Each one has a different purpose:

   1. `http-equiv= "aurhor"` This defines the author of the web page.

   2. `http-equiv= "progma"` This prevents the browser from caching the page. (That is, storing it locally to save time downloading it on subsequent visits.)

   3. `http-equiv= "expires"` Because browsers often cache the content of a page, the expires option can be used to indicate when the page should expire (and no longer be cached). Note that the date must be specified in the format shown.

* There are some characters that are used in and reserved by HTML code. (For example, the left and right angled brackets.), therefore, if you want these characters to appear on your page you need to use what are termed "escape" characters (also known as escape codes or entity references). 

*  For example, to write a left angled bracket, you can use either `&lt;` or `&#60;`. For an ampersand, you can use either `&amp;` or `&#38;`.

* There are also special codes that can be used to show symbols such as copyright and trademark, currency symbols, mathematical characters, and some punctuation marks, if you want to include a copyright symbol on a web page you can use either `&copy;` or `&#169;`.

* You can add comments to your code between the  `<!-- and -->` markers.  



### HTML5 Layout



* HTML5 is introducing a new set of elements that help define the structure of a page, the names of these elements indicate the kind of content you will find in them. 

* The new elements provide clearer code (compared with using multiple `<div>` elements).

* The point of creating these new elements is so that web page authors can use them to help describe the structure of the page. For example, screen reader software might allow users to ignore headers and footers and get straight to the content. 

*  Similarly, search engines might place more weight on the content in an `<article>` element than that in the `<header>` or `<footer>` elements. it also makes the code easier to follow.

* Older browsers that do not understand HTML5  elements need to be told which elements are block-level elements.

* To make HTML5 elements work in Internet Explorer 8 (and older versions of IE), extra JavaScript is needed, which is available free from Google.  



### Process & Design 



* We can write in HTML using any text editor but it will only be executed as an HTML page only if our file has _.html_ as the extension.

* When we are creating a website we should keep in mind who's going to be vising the site and what type of demographic they are.

* It's always helpful to create a fake audience to test your approach on them before hand.

* There are questions to ask ourselfs that will help us decide our target audience and some of these questions are:
   1. Who is the site For?
      * Individuals or companies

   2. Why people visit your website?
      * Key motivations and Specific goals

   3. How often people will visit your site?
      * For goods, services and information

* Create your site map to organize the information you collected, A site map will usually begin with the homepage. Additionally, if the site is large and is compartmentalized into sections, each section might require its own section homepage to link to all of the information within it.

* Always try to create a wireframe of the website before you start coding as it helps stay focused on what to do and in order.

* Always be creative and try things you didn't try before. The primary aim of any kind of visual design is to communicate. Organizing and prioritizing information on a page helps users understand its importance and what order to read it in.  




## JavaScript



### The ABCs of Programming

* JavaScript can be used to select any **element**, **attribute**, text from an HTML page. To **_add_ elements**, **attributes**, and **text** to the page, or **remove them**.


* Also it could be used to **specify a set of steps for the browser to follow** *(like a recipe)*, which **allows it to access or change the content of a page**.

* Browser compatibility is very important for the code to work so make sure to use a modern browser like Chrome or FireFox

* JavaScript is a programming langauge using **"Script"** as it's core principle, A script is a *series of instructions* that a computer can follow to achieve a goal. To **write** a script, you need to first **state** your **goal** and then **list** the tasks that need to be completed in order to achieve it.

* Start with the **big picture** of what you want to achieve, and **break** that down into **smaller steps**. Once you know the goal of your script, you can work out the individual tasks needed to be acheived. This can be **represented** using a **flowchart**, and translate these steps into code.

* Always think like you were the computer and it will be easier to find the right approch to write the code.

* An expression **evaluates** into *(results in)* a single value, Broadly speaking there are two types of expressions:

   1. Expressions that just assign a value to a variable
   2. Expressions that use two or more values to return a single value
