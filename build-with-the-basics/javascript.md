---
icon: js
---

# JavaScript

JavaScript is a programming language used to make websites interactive. While HTML creates the structure of the webpage and CSS styles it, JavaScript allows the page to **respond to user actions** like clicking buttons, typing in forms, or moving the mouse.

### Example of JavaScript:

Here’s a simple example where JavaScript is used to display an alert message when a button is clicked:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First JavaScript</title>
  </head>
  <body>
    <h1>Click the Button</h1>
    <button onclick="sayHello()">Click Me!</button>

    <script>
      function sayHello() {
        alert("Hello, world!");
      }
    </script>

  </body>
</html>
```

#### Breaking It Down:

* **`<button onclick="sayHello()">Click Me!</button>`**: This creates a button. When you click the button, it triggers the `sayHello` function.
* **`<script>`**: The JavaScript code is placed inside the `<script>` tag.
* **`function sayHello() { alert("Hello, world!"); }`**: This is the JavaScript function. When called, it shows an alert box with the message **"Hello, world!"**.

#### What Happens:

When you open this HTML file in a browser and click the button, a pop-up alert box will appear with the message “Hello, world!”

#### More Examples of JavaScript Features:

1.  **Changing HTML Content**: You can use JavaScript to change the content of an HTML element.

    ```html
    <p id="demo">This is a paragraph.</p>
    <button onclick="document.getElementById('demo').innerHTML = 'Paragraph changed!'">Change Text</button>
    ```
2.  **Showing and Hiding Content**: You can use JavaScript to hide or show elements on the page.

    ```html
    <p id="myText">This is some text that can be hidden.</p>
    <button onclick="document.getElementById('myText').style.display = 'none'">Hide</button>
    <button onclick="document.getElementById('myText').style.display = 'block'">Show</button>
    ```

#### What JavaScript Can Do:

* **Respond to user actions**: Like clicking buttons or submitting forms.
* **Change the content of a page**: Modify text, images, or other elements.
* **Validate forms**: Check if someone has entered correct information in a form before submitting it.
* **Create animations**: Move or animate elements on the page.
* **Interact with web APIs**: Communicate with external data sources, like fetching data from a server.

JavaScript adds life to a web page, making it dynamic and interactive!
