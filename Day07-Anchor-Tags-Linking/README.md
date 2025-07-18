# Day 07: Anchor tags and linking between pages

**Date:** July 18, 2025

## 📚 Topic Covered:

  * Anchor tags (`<a>`) for creating hyperlinks
  * `href` attribute for specifying link destinations
  * Linking to external websites (`target="_blank"`, `rel="noopener noreferrer"`)
  * Linking to internal pages (relative paths)
  * Linking to specific sections within the same page (anchor links)
  * Email contact links (`mailto:`)

## 📝 Key Learnings:

  * The **anchor tag (`<a>`)** is the fundamental HTML element for creating hyperlinks, allowing users to navigate between web pages or to different sections within the same page.
  * The **`href` attribute** is essential for the `<a>` tag, as it specifies the URL or path that the hyperlink points to.
  * To open an external link in a **new browser tab**, the `target="_blank"` attribute is used.
  * When `target="_blank"` is used, it's a best practice and security measure to also include **`rel="noopener noreferrer"`**. `noopener` prevents the new page from accessing the original page's `window.opener` property, and `noreferrer` prevents the new page from knowing which page referred it.
  * **Internal links** use relative paths (e.g., `about.html` or `../images/pic.jpg`) to navigate within the same website, making the site structure more flexible.
  * **Anchor links** (e.g., `<a href="#section-id">`) allow users to jump to specific sections within the *same* HTML page. This requires the target element to have a matching `id` attribute (e.g., `<section id="section-id">`).
  * The `mailto:` protocol in the `href` attribute (e.g., `<a href="mailto:your.email@example.com">`) creates a link that, when clicked, opens the user's default email client pre-filled with the recipient's address.

## 💡 Task/Mini-Project:

  * **Task:** Build a single HTML page that demonstrates various linking capabilities. This includes a navigation bar with internal links to different sections on the page, an external link that opens in a new tab (with `rel="noopener noreferrer"`), a "Back to top" anchor link, and an email contact link.

  * **Project:** Located in `Day07-Anchor-Tags-Linking/index.html`

      * This project serves as a comprehensive demonstration of HTML linking. It shows how to navigate within a single page, link to external resources securely, and provide direct email contact, all using HTML.

    <!-- end list -->

    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Day 7 Project: Linking Practice</title>
    </head>
    <body>

        <!-- Top of the page anchor -->
        <a id="top"></a> 

        <header>
            <h1>Linking Practice Page</h1>
            <nav>
                <ul>
                    <li><a href="#section1">Go to Section 1</a></li>
                    <li><a href="#section2">Go to Section 2</a></li>
                    <li><a href="#section3">Go to Section 3</a></li>
                    <li><a href="#contact">Contact Us</a></li>
                </ul>
            </nav>
        </header>

        <main>
            <section id="section1">
                <h2>Section 1: Introduction</h2>
                <p>This is the first section of our linking practice page. We will explore different types of links here.</p>
                <p>You can visit an <a href="https://www.google.com" target="_blank" rel="noopener noreferrer">external website (Google)</a> in a new tab.</p>
                <p>This demonstrates how to securely link to external resources.</p>
            </section>

            <hr>

            <section id="section2">
                <h2>Section 2: More Content</h2>
                <p>This section contains more information. The navigation bar above allows you to jump directly to this part of the page.</p>
                <p>Imagine this as a long article where you want to provide quick jumps to different chapters.</p>
            </section>

            <hr>

            <section id="section3">
                <h2>Section 3: Conclusion</h2>
                <p>We've reached the end of our content sections. Linking internally helps users navigate long pages efficiently.</p>
                <p>Remember to always test your links to ensure they work as expected!</p>
            </section>

            <hr>

            <section id="contact">
                <h2>Contact Information</h2>
                <p>If you have any questions, feel free to <a href="mailto:your.email@example.com?subject=Inquiry%20from%20Linking%20Practice">send us an email</a>.</p>
                <p>This link will open your default email client.</p>
            </section>
        </main>

        <footer>
            <p><a href="#top">Back to Top</a></p>
            <p>&copy; 2025 Linking Practice. All rights reserved.</p>
        </footer>

    </body>
    </html>
    ```

## 🔗 Resources:

  * [MDN Web Docs: The Anchor element (`<a>`)](https://www.google.com/search?q=%5Bhttps://developer.mozilla.org/en-US/docs/Web/HTML/Element/a%5D\(https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a\))
  * [MDN Web Docs: `target` attribute](https://www.google.com/search?q=%5Bhttps://developer.mozilla.org/en-US/docs/Web/HTML/Element/a%23attr-target%5D\(https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a%23attr-target\))
  * [MDN Web Docs: `rel` attribute](https://www.google.com/search?q=%5Bhttps://developer.mozilla.org/en-US/docs/Web/HTML/Element/a%23attr-rel%5D\(https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a%23attr-rel\))
  * [W3Schools: HTML Links](https://www.w3schools.com/html/html_links.asp)
  * [W3Schools: HTML `mailto` Link](https://www.google.com/search?q=%5Bhttps://www.w3schools.com/html/html_mailto.asp%5D\(https://www.w3schools.com/html/html_mailto.asp\))

-----

[← Back to Main Table of Contents](https://www.google.com/search?q=../README.md)