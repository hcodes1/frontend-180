
-----

# Day 05: HTML Lists - Ordered, Unordered, and Description Lists

**Date:** July 11, 2025

## 📚 Topic Covered:

  * Unordered Lists (`<ul>` and `<li>`)
  * Ordered Lists (`<ol>` and `<li>`)
  * Description Lists (`<dl>`, `<dt>`, and `<dd>`)
  * Nesting Lists for complex structures

## 📝 Key Learnings:

  * **Unordered lists** (`<ul>`) are used for items where the order doesn't matter (e.g., a shopping list). Each item is marked with a bullet point by default. List items are defined by `<li>` tags.
  * **Ordered lists** (`<ol>`) are for items where the sequence is important (e.g., steps in a recipe). Each item is numbered by default. Again, `<li>` tags define the list items.
  * **Description lists** (`<dl>`) are used for terms and their descriptions. Each term is defined by a `<dt>` (description term) tag, and its description by a `<dd>` (description detail) tag. This is great for glossaries or Q\&A sections.
  * All list types can be **nested** within each other. This means you can put an entire list inside an `<li>` or `dd` tag to create sub-lists, which is powerful for organizing hierarchical information.
  * Using the correct list type semantically helps with accessibility and makes your HTML more meaningful.

## 💡 Task/Mini-Project:

  * **Task:** Create a web page featuring a "Daily Routine" and a "Glossary of HTML Terms." The daily routine will use an ordered list, and the glossary will use a description list. Incorporate at least one nested unordered list within your daily routine.

  * **Project:** Located in `Day05-Lists/lists-example.html`

      * This project showcases the practical application of ordered, unordered, and description lists to structure diverse content like steps and definitions. The inclusion of a nested list demonstrates how to manage hierarchical information effectively using HTML lists.

    <!-- end list -->

    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Day 5 Project: HTML Lists</title>
    </head>
    <body>

        <h1>My Daily Routine</h1>
        <ol>
            <li>Wake up and prepare for the day.</li>
            <li>Morning learning session:
                <ul>
                    <li>Review previous day's notes.</li>
                    <li>Read new HTML concepts.</li>
                    <li>Complete coding exercise.</li>
                </ul>
            </li>
            <li>Break for lunch and exercise.</li>
            <li>Afternoon coding practice.</li>
            <li>Evening review and plan for tomorrow.</li>
        </ol>

        <hr>

        <h1>HTML Glossary</h1>
        <dl>
            <dt>HTML</dt>
            <dd>HyperText Markup Language. The standard markup language for creating web pages.</dd>

            <dt>Element</dt>
            <dd>A fundamental component of an HTML document, typically consisting of a start tag, content, and an end tag.</dd>

            <dt>Attribute</dt>
            <dd>A modifier of an HTML element, providing additional information or characteristics.</dd>

            <dt>Semantic HTML</dt>
            <dd>Using HTML elements according to their meaning, rather than just their visual presentation.</dd>
        </dl>

    </body>
    </html>
    ```

## 🔗 Resources:

  * [MDN Web Docs: The Unordered List element (`<ul>`)](https://www.google.com/search?q=%5Bhttps://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul%5D\(https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul\))
  * [MDN Web Docs: The Ordered List element (`<ol>`)](https://www.google.com/search?q=%5Bhttps://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol%5D\(https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol\))
  * [MDN Web Docs: The Description List element (`<dl>`)](https://www.google.com/search?q=%5Bhttps://developer.mozilla.org/en-US/docs/Web/HTML/Element/dl%5D\(https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dl\))
  * [W3Schools: HTML Lists](https://www.w3schools.com/html/html_lists.asp)

-----

[← Back to Main Table of Contents](../README.md)