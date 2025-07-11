# Day 06: HTML Attributes and Nesting Elements - The Building Blocks of Web Structure

**Date:** July 11, 2025

## 📚 Topic Covered:

  * Understanding HTML Attributes
  * Importance and Rules of Nesting HTML Elements
  * Common Attributes: `class`, `id`, `href`, `src`

## 📝 Key Learnings:

  * **HTML Attributes** provide additional information about an HTML element or modify its default behavior. They are always specified in the start tag and usually come in name/value pairs (e.g., `<a href="link.html">`).
  * **Nesting HTML Elements** refers to placing one HTML element inside another. This is fundamental for building complex web page structures. For example, `<li>` elements are nested inside `<ul>` or `<ol>` elements.
  * **Correct Nesting** is crucial. Elements must be closed in the reverse order they were opened (e.g., `<div><p>Text</p></div>` is correct, `<div><p>Text</div></p>` is incorrect). Improper nesting can lead to broken layouts, accessibility issues, and validation errors.
  * Common attributes like `href` (for links), `src` (for images/media), `class` (for CSS styling and JavaScript selection), and `id` (for unique identification, often for JavaScript or specific CSS targeting) were reinforced. `id` values must be unique within a document.

## 💡 Task/Mini-Project:

  * **Task:** Create a simple web page that includes a navigation bar and a profile card. The navigation bar should use a `<nav>` element with nested `<ul>` and `<li>` elements. The profile card should be built with nested `<div>`, `<img>`, and `<p>` elements. Add various attributes (`class`, `id`, `href`, `src`) to enhance their structure and potential for interactivity/styling.

  * **Project:** Located in `Day06-HTML-Attributes-Nesting/attributes-nesting.html`

      * This project demonstrates the practical application of HTML attributes and proper element nesting to create common web components like a navigation menu and a user profile card. It highlights how attributes provide crucial metadata and hooks for styling and functionality.

    <!-- end list -->

    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Day 6 Project: Attributes & Nesting</title>
    </head>
    <body>

        <header>
            <nav id="main-nav">
                <ul>
                    <li class="nav-item"><a href="index.html" class="nav-link">Home</a></li>
                    <li class="nav-item"><a href="about.html" class="nav-link">About</a></li>
                    <li class="nav-item"><a href="contact.html" class="nav-link">Contact</a></li>
                </ul>
            </nav>
        </header>

        <main>
            <div class="profile-card" id="user-profile">
                <img src="https://placehold.co/150x150/FF6347/FFFFFF?text=Profile" alt="User Profile Picture" class="profile-img">
                <div class="profile-details">
                    <h2 class="profile-name">John Doe</h2>
                    <p class="profile-title">Frontend Developer</p>
                    <p class="profile-bio">Passionate about creating accessible and user-friendly web experiences.</p>
                </div>
            </div>
        </main>

        <footer>
            <p>&copy; 2025 John Doe. All rights reserved.</p>
        </footer>

    </body>
    </html>
    ```

## 🔗 Resources:

  * [MDN Web Docs: HTML attributes](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes)
  * [MDN Web Docs: HTML element reference (for general nesting examples)](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
  * [W3Schools: HTML Attributes](https://www.w3schools.com/html/html_attributes.asp)
  * [W3C Validator (to check for nesting errors)](https://validator.w3.org/)

-----

[← Back to Main Table of Contents](../README.md)