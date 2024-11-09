---
icon: css3-alt
---

# CSS

CSS (Cascading Style Sheets) is a language used to control the appearance and layout of web pages. While HTML defines the structure of a webpage (like headings, paragraphs, and links), CSS is used to make it look nice by controlling things like colors, fonts, and spacing.

#### How CSS Works:

CSS is made up of **rules** that tell the browser how to style elements of the page. Each rule has two parts:

1. **Selector**: The part of the page you want to style (like a heading or paragraph).
2. **Declarations**: The styles you want to apply, written inside curly braces `{}`. Each declaration has a **property** (like color) and a **value** (like red).

#### Example of CSS:

```html
<!DOCTYPE html>
<html>
  <head>
    <style>
      body {
        background-color: lightblue;
      }
      h1 {
        color: navy;
        font-size: 36px;
      }
      p {
        font-family: Arial, sans-serif;
        color: darkgray;
      }
    </style>
  </head>
  <body>
    <h1>Hello, world!</h1>
    <p>This is my first styled web page.</p>
  </body>
</html>
```

#### Breaking It Down:

* **`body { background-color: lightblue; }`**: This changes the background color of the entire webpage to light blue.
* **`h1 { color: navy; font-size: 36px; }`**: This makes the heading (`h1`) text dark blue and larger in size.
* **`p { font-family: Arial, sans-serif; color: darkgray; }`**: This changes the font of the paragraph to Arial and makes the text color dark gray.

#### CSS can be added to a web page in 3 ways:

1. **Inline CSS**: Styles are added directly within HTML tags. Example: `<p style="color: red;">This is a paragraph.</p>`.
2. **Internal CSS**: Styles are included within a `<style>` tag in the `<head>` section of an HTML document (as shown in the example above).
3. **External CSS**: A separate CSS file (e.g., `styles.css`) is linked to the HTML document, making it easier to style multiple pages consistently.

#### Example of External CSS:

In the HTML file:

```html
<head>
  <link rel="stylesheet" href="styles.css">
</head>
```

In the `styles.css` file:

```css
body {
  background-color: lightblue;
}
h1 {
  color: navy;
  font-size: 36px;
}
p {
  font-family: Arial, sans-serif;
  color: darkgray;
}
```

#### Key CSS Properties:

* **Color**: Defines the color of text. Example: `color: red;`
* **Font**: Controls font type and size. Example: `font-size: 20px; font-family: Arial;`
* **Background**: Changes the background color or image. Example: `background-color: yellow;`
* **Margin** and **Padding**: Control spacing around elements. Example: `margin: 10px; padding: 5px;`

CSS helps make websites more visually appealing and user-friendly. By separating content (HTML) from design (CSS), developers can easily update the look of a site without changing its structure.
