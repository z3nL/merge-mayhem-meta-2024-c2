## Common HTML Elements

In this lab, we will introduce you to a few common HTML elements and their syntax, but we highly recommend you check out MDN docs for a [full list of HTML elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Element).

| Element Tag | Description | Syntax Example |
|-------------|-------------|----------------|
| [`h1`,`h2`,...,`h6`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements) | These are **heading tags** that act like text section headers. `h1` is the largest header with a default font size of 2em and `h6` is the smallest header with a default font size of 0.67em. | `<h1>Header 1</h1>` |
| [`p`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/p) | This **paragraph** text defines a paragraph content, or regular text on a page. | `<p>This is a paragraph text</p>` |
| [`a`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a) | An **anchor** tag is used to add **links** to another page. These can be another html file in your project or outside links. We use the `href` attribute to link to the website URL. Be sure to add the URL address in double quotation marks! | `<a href=”https://codepath.org/”>CodePath.org Website</a>` |
| [`br`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/br) | This element create a **line break** on your page.  The `br` element is a void and therefore uses a **self-closing tag**. This means that you do not need a closing tag when adding the `br` element. | `<br>` |
| [`img`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img) | The image tag allows you to add an image on your page. The `src` attribute takes in the image address (either local or online) in double quotation marks. You may add other attributes like `width` and `height` to control the size of the image. | `<img src="./codepathlogo.jpg" width="40px" height="40px">` |
