### Linking CSS Files

**Line 6**  `<link href="style.css" rel="stylesheet" type="text/css" />`  connects the CSS style sheet to our HTML file.

Let’s break down the syntax used to do this action. Learn more on the [MDN Web Docs about the `link` element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/link).

- `<link>`: This element specifies relationships between the current document (the HTML file) and an external resource (the CSS file).
- `href`: This attribute specifies the file path, or location, of our external resource. In this particular example, the CSS file is named `style.css` but you can name your stylesheet anything. Take note that the file path is surrounded by double quotes, `""`.
- `rel`: `rel` stands for relationship. This lets the document know how the resource will interact with the current document

, in this case we are linking to a `stylesheet`. Learn more on the MDN Web Docs about link types.
- `type`: Similar to the `rel` attribute, the `type` attribute lets the document know the specific type of file that is being linked.
