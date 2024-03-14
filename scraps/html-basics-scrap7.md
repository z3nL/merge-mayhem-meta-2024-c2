### Linking JavaScript Files

**Line 9**  `<script src="script.js"></script>` links the JavaScript file to our HTML file.

Let’s break down the syntax used to do this action.

- `<script>`: You may be wondering, why do we use the `script` element to connect JavaScript files instead of the `link` element that is used for CSS files. Unlike CSS styling, JavaScript dynamically changes elements in the HTML document. JavaScript may add, delete, or modify HTML elements. CSS styling can only change the appearance of an element, but cannot modify the structure of the HTML element.
- `src`: This attribute specifies the file path, or location, of our external resource. In this particular example, the JS file is named `script.js` but you can name your stylesheet anything. Take note that the file path is surrounded by double quotes, `“”`.

You may have noticed that the `<script>` element is placed inside of the `<body>` element. This is different from the `<link>` element for CSS files which is in the `<head>` element. This is because JavaScript files can often affect the HTML elements within the document. To ensure that the JavaScript file does not run before the HTML elements have been loaded on the page, developers tend to place the `<script>` element towards the bottom of the HTML file to avoid potential errors.
