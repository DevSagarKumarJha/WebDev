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

## Tags in HTML
HTML tags are the building blocks of an HTML document. They define the structure and content of a webpage. Each tag consists of an opening tag (e.g., `<p>`) and a closing tag (e.g., `</p>`), and the content goes in between the tags. Some tags are self-closing (e.g., `<img />`).

Here's an overview of some commonly used HTML tags:

1. **Document Structure Tags**:
    - `<html>`: The root element of an HTML document. Wraps all the content of the page.
    - `<head>`: Contains metadata and links to scripts and stylesheets.
    - `<title>`: Defines the title of the document, which appears in the browser's title bar or tab.
    - `<body>`: Contains the main content of the webpage.

2. **Text Formatting Tags**:
    - `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>`: Heading tags for structuring content. `<h1>` is the highest level, while `<h6>` is the lowest.
    - `<p>`: Defines a paragraph of text.
    - `<b>`: Makes text bold.
    - `<i>`: Makes text italic.
    - `<strong>`: Similar to `<b>`, emphasizes text.
    - `<em>`: Similar to `<i>`, emphasizes text.
    - `<br>`: Creates a line break (self-closing tag).

3. **Links and Media Tags**:
    - `<a>`: Creates a hyperlink. Requires the `href` attribute to specify the link destination.
    - `<img>`: Displays an image. Requires the `src` attribute to specify the image source.
    - `<audio>` and `<video>`: Used for embedding audio and video files.
    - `<source>`: Specifies the source of audio or video media.

4. **Lists**:
    - `<ul>`: Unordered list, creates a list with bullet points.
    - `<ol>`: Ordered list, creates a numbered list.
    - `<li>`: List item, used within `<ul>` or `<ol>` tags.

5. **Tables**:
    - `<table>`: Defines a table.
    - `<tr>`: Table row, used within `<table>`.
    - `<td>`: Table cell (data), used within `<tr>`.
    - `<th>`: Table header cell, used within `<tr>`.

6. **Forms**:
    - `<form>`: Encapsulates a form element.
    - `<input>`: Creates an input field. Various types include `text`, `password`, `submit`, and more.
    - `<button>`: Creates a button, either for form submission or other purposes.
    - `<textarea>`: Creates a multi-line text input field.

7. **Semantic Tags**:
    - `<header>`: Represents the header of a section or the whole document.
    - `<footer>`: Represents the footer of a section or the whole document.
    - `<nav>`: Represents navigation links.
    - `<article>`: Defines independent content, like a blog post.
    - `<section>`: Represents a section of a document.
    - `<aside>`: Represents content aside from the main content.

These are just some of the most common HTML tags. HTML has many more tags that serve various purposes, including structuring content, embedding multimedia, and building forms. You can refer to the [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/HTML/Element) for a complete list of HTML elements and attributes.