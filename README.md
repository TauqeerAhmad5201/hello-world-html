# hello-world-html

## HTML Documentation

### What is HTML?

HTML (HyperText Markup Language) is the standard markup language for creating web pages. It describes the structure of a web page using markup tags.

### Basic HTML Structure

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document Title</title>
</head>
<body>
    <!-- Your content goes here -->
</body>
</html>
```

### Common HTML Tags

#### Text Formatting
- `<h1>` to `<h6>` - Headings (h1 is largest, h6 is smallest)
- `<p>` - Paragraph
- `<br>` - Line break
- `<strong>` or `<b>` - Bold text
- `<em>` or `<i>` - Italic text
- `<mark>` - Highlighted text
- `<small>` - Smaller text
- `<del>` - Deleted text
- `<ins>` - Inserted text
- `<sub>` - Subscript text
- `<sup>` - Superscript text

#### Links and Media
- `<a href="url">` - Hyperlink
- `<img src="image.jpg" alt="description">` - Image
- `<audio>` - Audio content
- `<video>` - Video content

#### Lists
- `<ul>` - Unordered list
- `<ol>` - Ordered list
- `<li>` - List item
- `<dl>` - Description list
- `<dt>` - Description term
- `<dd>` - Description definition

#### Tables
- `<table>` - Table
- `<thead>` - Table header
- `<tbody>` - Table body
- `<tr>` - Table row
- `<th>` - Table header cell
- `<td>` - Table data cell

#### Forms
- `<form>` - Form container
- `<input>` - Input field
- `<textarea>` - Multi-line text input
- `<button>` - Clickable button
- `<select>` - Dropdown list
- `<option>` - Dropdown option
- `<label>` - Form label

#### Semantic Elements
- `<header>` - Header section
- `<nav>` - Navigation links
- `<main>` - Main content
- `<section>` - Section
- `<article>` - Article
- `<aside>` - Sidebar content
- `<footer>` - Footer section

#### Containers
- `<div>` - Division/container (block-level)
- `<span>` - Inline container

### HTML Attributes

Common attributes used with HTML tags:

- `id` - Unique identifier for an element
- `class` - One or more class names for styling
- `style` - Inline CSS styles
- `title` - Additional information (tooltip)
- `src` - Source URL (for images, videos, etc.)
- `href` - Hyperlink reference (for links)
- `alt` - Alternative text (for images)
- `width` and `height` - Dimensions
- `disabled` - Disables an input element
- `required` - Makes an input field required
- `placeholder` - Hint text in input fields

### Example: Simple HTML Page

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hello World</title>
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <main>
        <section id="home">
            <h2>Hello World!</h2>
            <p>This is a simple HTML page example.</p>
        </section>
        
        <section id="about">
            <h2>About</h2>
            <p>HTML is the foundation of web development.</p>
            <img src="example.jpg" alt="Example image" width="300">
        </section>
        
        <section id="contact">
            <h2>Contact</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="4"></textarea>
                
                <button type="submit">Send</button>
            </form>
        </section>
    </main>
    
    <footer>
        <p>&copy; 2025 My Website. All rights reserved.</p>
    </footer>
</body>
</html>
```

### Resources

- [MDN Web Docs - HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [W3Schools HTML Tutorial](https://www.w3schools.com/html/)
- [HTML Living Standard](https://html.spec.whatwg.org/)