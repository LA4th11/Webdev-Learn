# HTML Learn Project

This project demonstrates various HTML elements and their uses, providing a simple webpage layout that includes headings, paragraphs, lists, tables, semantic elements, and more.

## Project Structure

### 1. **Meta Tags**

- `meta charset="UTF-8"`: Ensures the webpage uses UTF-8 character encoding.
- `meta name="viewport" content="width=device-width, initial-scale=1.0"`: Makes the webpage responsive to different screen sizes (important for mobile).

### 2. **Favicon**

- The page uses a favicon located at `./Assets/html-icon.png`, which is a small icon that appears on the browser tab when visiting the site.

### 3. **Styles**

- There is basic CSS styling applied directly in the `<head>` section of the document to create a border for tables and center the text in table cells.
- Example of CSS:
  ```css
  table,
  th,
  td {
    border: 2px solid black;
    text-align: center;
  }
  ```

### 4. **HTML Content**

#### **Headings**

- Demonstrates all heading levels from `<h1>` to `<h6>`, showcasing how HTML headings differ in size and semantic importance.

#### **Paragraphs**

- A block of text is provided using the `<p>` tag, demonstrating how paragraphs are used in HTML.

#### **Links**

- A clickable hyperlink using the `<a>` tag links to an external YouTube video.

#### **Images**

- An image is embedded using the `<img>` tag, showing how to include external images in a webpage.

#### **Horizontal Rule**

- A horizontal line `<hr>` is used to visually divide content sections.

#### **Line Break**

- A line break `<br>` is used to insert blank lines between content.

#### **Preformatted Text**

- A block of text inside the `<pre>` tag, demonstrating preformatted text.

#### **Inline Styling**

- Inline CSS is applied directly to an HTML element to change the background color of a specific heading.

#### **Text Formatting**

- Demonstrates text formatting with:
  - `<b>`: Bold text
  - `<strong>`: Strong importance text
  - `<i>`: Italic text
  - `<mark>`: Highlighted text
  - `<sub>` and `<sup>`: Subscript and superscript
  - `<del>` and `<ins>`: Deleted and inserted text

### 5. **Tables**

- Shows a simple table with a border around the table, its rows, and cells.
- Demonstrates colspan with another table.

### 6. **Lists**

- **Unordered List**: Using the `<ul>` tag with list items (`<li>`) for a bulleted list.
- **Ordered List**: Using the `<ol>` tag for a numbered list.
- **Description List**: Using the `<dl>`, `<dt>`, and `<dd>` tags for a term-description pair.

### 7. **Semantic HTML**

- **Header**: Using `<header>` to contain navigation buttons (`<button>` elements).
- **Section**: Two sections created using the `<section>` tag, each containing paragraphs of text.
- **Main**: The `<main>` tag wraps the core content of the webpage, which in this case contains the title of the webpage and some descriptive text.
- **Footer**: A footer created using the `<footer>` tag contains copyright information.

## Running the Project

To view the webpage:

1. Open the `index.html` file in your browser.
2. Ensure the image and favicon paths are correct if they do not load properly.

## Additional Notes

- This project uses basic inline CSS for styling. To expand on this, consider moving the styles to an external stylesheet for better scalability.
- The page uses **semantic HTML elements** such as `<header>`, `<section>`, `<main>`, and `<footer>`, which improve the accessibility and structure of the document.
- Explore and modify the HTML to learn more about the flexibility of different elements.
