# Setting up the environment
1. Editor: VS code, or any other editor
2. Browser: Chrome, MS edge, Firefox, Brave
3. If you are using VSCode then you can use live server extension

# Understanding html
## What is HTML?
HTML, which stands for HyperText Markup Language, is the standard language for creating web pages. HTML structures content on the web in a hierarchical manner using elements or tags that define the different parts of a webpage. Here's an overview of the basic structure of an HTML document:

1. **Doctype**: At the top of an HTML document, there should be a declaration of the document type (`<!DOCTYPE html>`). This helps ensure that the HTML document is parsed in standards mode.

2. **HTML Element**: The root of the HTML document is the `<html>` tag. This tag wraps all other content in the HTML file.

3. **Head Element**: The `<head>` section contains metadata about the webpage, such as the title of the page (`<title>`), links to stylesheets (`<link>`), scripts (`<script>`), and other data such as meta tags (`<meta>`).

4. **Body Element**: The `<body>` section contains the actual content of the webpage, such as headings, paragraphs, lists, images, and other multimedia elements. This is the part that users see when they visit a webpage.

5. **Elements and Attributes**: HTML consists of elements, also known as tags, such as `<h1>`, `<p>`, `<div>`, `<img>`, and more. Elements often contain attributes, such as `id` and `class`, which can be used to style or manipulate elements using CSS and JavaScript. For example, `<img src="image.jpg" alt="A description of the image">`.

6. **Nesting**: HTML elements can be nested inside one another. For example, a `<p>` element might contain an `<a>` element for a hyperlink.

7. **Comments**: HTML allows for comments to be added within the document using the syntax `<!-- comment text -->`. Comments do not appear in the final rendered webpage.

Here's an example of a simple HTML document structure:

### Boilerplate code of HTML
``` html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  
</body>
</html>
```

In this example, the HTML document starts with the `<!DOCTYPE html>` declaration, followed by the `<html>` tag. The head section contains the title, a link to a stylesheet, and the character encoding. The body section contains a heading, a paragraph, and an image.
