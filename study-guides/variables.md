# Variables

**Example**: `index.html`

```html
<html>
    <head>
        <title>My Document</title>
    </head>
    <body>
        <h1>Header</h1>
        <p>Paragraph</p>
    </body>
</html>
```

Let's say we want to store a reference to the `p` element.
- Since there are no attributes attached to this element, no `id` or `class` name, this eliminates the use of the `getElementById` method.
- We can only use the `querySelector` or `querySelectorAll` method. However, since there is only a single instance of a `p` element, we will elect to use the `querySelector` method with the **element selector** associated with its tag name `p`.
