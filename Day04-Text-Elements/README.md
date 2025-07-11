
-----

# Day 04: HTML Text Elements: Headings, Paragraphs, and Dividers

**Date:** July 11, 2025

## 📚 Topic Covered:

  * HTML Headings (`<h1>` to `<h6>`)
  * HTML Paragraphs (`<p>`)
  * Line Breaks (`<br>`) and Horizontal Rules (`<hr>`)
  * Semantic vs. Presentational Use of Text Elements

## 📝 Key Learnings:

  * **Headings** (`<h1>` to `<h6>`) define the hierarchy and structure of content. `<h1>` is the most important (main title, usually one per page), and the numbers decrease in importance. They're crucial for SEO and accessibility.
  * **Paragraphs** (`<p>`) are used for blocks of text. Browsers automatically add vertical spacing around them, making content more readable.
  * **Line Breaks** (`<br>`) force a new line *within* a block of text, like in an address or a poem. It's an empty tag and should not be used for spacing between different blocks.
  * **Horizontal Rules** (`<hr>`) represent a thematic break or change in topic within the content, visually often appearing as a horizontal line. It's also an empty tag.
  * A key insight is always to use these tags for their **semantic meaning** (what the content *is*) rather than just for their default visual appearance (what it *looks like*). Styling should be handled with CSS.

## 💡 Task/Mini-Project:

  * **Task:** Create a simple "About Me" page that effectively utilizes headings to structure personal information, paragraphs for descriptions, and incorporates line breaks for formatting details, along with horizontal rules for thematic separation.

  * **Project:** Located in `Day04-Text-Elements/text-formating.html`

      * This project demonstrates how these core HTML text elements work together to build a well-structured, readable, and semantically correct web page without any styling. It includes sections for professional background, hobbies, and contact information.

    <!-- end list -->

    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>About John Doe - Day 4 Practice</title>
    </head>
    <body>

        <h1>About John Doe</h1>
        <hr>

        <h2>Professional Background</h2>
        <p>John is a passionate frontend developer with 5 years of experience crafting user-friendly and responsive web applications. He specializes in modern JavaScript frameworks and clean, maintainable HTML/CSS.</p>
        <p>His expertise includes:<br>
        - Responsive Web Design<br>
        - JavaScript (React, Vue)<br>
        - HTML5 & CSS3<br>
        - Version Control (Git)</p>

        <h2>Hobbies & Interests</h2>
        <p>Outside of coding, John enjoys a variety of activities:</p>
        <ul>
            <li>**Photography:** Capturing the beauty of nature and urban landscapes.</li>
            <li>**Hiking:** Exploring new trails and enjoying the outdoors.</li>
            <li>**Reading Sci-Fi Novels:** Delving into imaginative worlds and thought-provoking concepts.</li>
        </ul>

        <hr>
        <p>Feel free to connect with John at: <a href="mailto:doe@myemail.com">doe@example.com</a></p>

    </body>
    </html>
    ```

## 🔗 Resources:

  * [MDN Web Docs: The Headings element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements)
  * [MDN Web Docs: The Paragraph element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/p)
  * [MDN Web Docs: The Line Break element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/br)
  * [MDN Web Docs: The Thematic Break (Horizontal Rule) element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/hr)

-----

[← Back to Main Table of Contents](../README.md)