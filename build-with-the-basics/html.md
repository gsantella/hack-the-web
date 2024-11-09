---
icon: html5
---

# HTML

HTML (HyperText Markup Language) is the basic language used to create web pages. It's like the **blueprint** for a website, telling a browser (like Chrome or Firefox) how to display text, images, links, and more. HTML uses **tags** to define different elements on a webpage.

### How HTML Works

Each HTML file is made up of **elements** that are enclosed in **tags**. Tags are like instructions for the browser, and they usually come in pairs: an opening tag `<tag>` and a closing tag `</tag>`. Everything between the tags is the content that will appear on the webpage.

#### Basic Structure of an HTML Page:

Here’s a very simple example of an HTML page:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First Web Page</title>
  </head>
  <body>
    <h1>Hello, world!</h1>
    <p>This is my first web page.</p>
    <a href="https://www.example.com">Click here to visit a website!</a>
  </body>
</html>
```

#### Breaking It Down:

* **`<!DOCTYPE html>`**: This tells the browser that the document is written in HTML5, the latest version of HTML.
* **`<html>`**: This is the root element of the web page, indicating that everything inside it is part of the webpage.
* **`<head>`**: Contains information about the page, like its title and links to styles or scripts.
* **`<title>`**: This is the title of the webpage, which shows up in the browser tab.
* **`<body>`**: Everything inside this tag is what the user will see on the webpage.
* **`<h1>`**: This tag defines a large, bold heading.
* **`<p>`**: Defines a paragraph of text.
* **`<a>`**: This creates a link. The `href` attribute defines where the link goes.

#### What You See on the Web Page:

When you open the HTML example above in a browser, it will show:

* A large heading: **"Hello, world!"**
* A paragraph: **"This is my first web page."**
* A clickable link: **"Click here to visit a website!"**

This is just the start! HTML can also be used to display images, create tables, lists, and much more. Combined with CSS (which controls the design) and JavaScript (which adds interactivity), HTML forms the backbone of every webpage.
