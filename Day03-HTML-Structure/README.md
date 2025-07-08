# Day 3: Building My First Web Page: HTML Document Structure Explained

**Date:** July 8, 2025

## 📚 Topic Covered:

- HTML Document Structure (`<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`)
- Essential Meta Tags (`charset`, `viewport`)
- Common HTML Elements (`<h1>-<h6>`, `<p>`, `<a>`, `<img>`, `<ul>`/`<ol>`)
- Setting up a basic HTML file in VS Code

## 📝 Key Learnings:

- Understanding the fundamental anatomy of an HTML document is crucial for cross-browser compatibility, maintainability, and SEO.
- The `<!DOCTYPE html>` declaration is essential for defining the HTML version (HTML5).
- The `<html>` tag serves as the root element, with the `lang` attribute for language specification.
- The `<head>` section contains metadata not directly visible on the page, such as character encoding (`charset="UTF-8"`), responsive settings (`viewport`), and the page title (`<title>`).
- The `<body>` section is where all the visible content of the webpage resides.
- I learned how to create a simple `index.html` file and add basic content like headings, paragraphs, and links.
- **Challenge:** Remembering to use self-closing tags for elements like `<img>` versus paired tags for others. Overcame this by practicing and reviewing examples.
- **"Aha!" moment:** Realizing how the `viewport` meta tag makes a webpage adaptable to different screen sizes, which is vital for modern web development.

## 💡 Task/Mini-Project:

- **Task:** Created a complete, well-structured HTML webpage from scratch, incorporating basic content and essential elements.
- **Project:** Located in `Day03-HTML-Structure/first-webpage.html`

  - This project demonstrates the fundamental structure of an HTML5 document, including the `head` and `body` sections, meta tags, and basic content elements like headings, paragraphs, and a link.

  ```html
  <!DOCTYPE html>
  <html lang="en">
    <head>
      <meta charset="UTF-8" />
      <meta name="viewport" content="width=device-width, initial-scale=1.0" />
      <title>My First Complete Webpage</title>
    </head>
    <body>
      <h1>Welcome to My Website</h1>
      <p>
        This is my first properly structured HTML page, created as part of the
        #FrontendDev-Building Your First Web Page challenge.
      </p>
      <p>
        You can click this
        <a href="https://github.com/hcodes1/frontend-180">link</a> to see a
        basic interactive element.
      </p>
    </body>
  </html>
  ```

## 🔗 Resources:

- [MDN Web Docs - HTML document structure](https://developer.mozilla.org/en-US/docs/Web/HTML/HTML_document_structure)
- [W3Schools - HTML Basic](https://www.w3schools.com/html/html_basic.asp)
- [W3Schools - HTML Head](https://www.w3schools.com/html/html_head.asp)

---

[← Back to Main Table of Contents](../README.md)
