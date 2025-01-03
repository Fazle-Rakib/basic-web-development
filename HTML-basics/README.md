
# HTML and CSS Basics Documentation

## **HTML Basics**

### **What is HTML?**

HTML (HyperText Markup Language) is the standard language for creating web pages. It defines the structure of web content using a system of tags.

- Official Documentation: [MDN Web Docs - HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)

---

### **HTML Structure**

Every HTML document follows a basic structure:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <!-- Page Content Goes Here -->
</body>
</html>
```

#### **Tags and Elements**

- **Tags** are used to mark the start and end of an element, e.g., `<p>` and `</p>`.
- **Elements** include both the tags and the content, e.g., `<p>This is a paragraph.</p>`.

#### **Common Tags**

| Tag                    | Description |
| ---------------------- | ----------- |
| `<h1>`-`<h6>`          | Headings    |
| `<p>`                  | Paragraphs  |
| `<a>`                  | Hyperlinks  |
| `<img>`                | Images      |
| `<ul>`, `<ol>`, `<li>` | Lists       |

- Reference: [W3Schools - HTML Elements](https://www.w3schools.com/html/html_elements.asp)

---

### **HTML Attributes**

Attributes provide additional information about an element. They are defined inside the opening tag.

```html
<a href="https://example.com" target="_blank">Visit Example</a>
```

- **`href`**: Specifies the URL.
- **`target`**: Defines how the link opens.

More attributes: [MDN - HTML Attribute Reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes)

---

### **HTML Media**

#### **Images**

```html
<img src="image.jpg" alt="Description of the image">
```
<!--
#### **Videos**

```html
<video controls>
    <source src="video.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>
```

- Learn more: [MDN - HTML Multimedia](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/video)
-->
---

### **Forms**

HTML forms collect user input.

```html
<form action="/submit" method="post">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required>
    <button type="submit">Submit</button>
</form>
```

- Explore: [HTML Forms - W3Schools](https://www.w3schools.com/html/html_forms.asp)

---

## **CSS Basics**

### **What is CSS?**

CSS (Cascading Style Sheets) is used to style and layout web pages. It controls color, fonts, spacing, and more.

- Official Documentation: [MDN Web Docs - CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)

---

### **CSS Syntax**

```css
selector {
    property: value;
}
```

- **Selector**: Targets an HTML element.
- **Property**: Defines the style to apply.
- **Value**: Specifies the property value.

Example:

```css
h1 {
    color: blue;
    font-size: 24px;
}
```

---

### **CSS Inclusion Methods**

1. **Inline Styles** (Inside HTML elements):

   ```html
   <p style="color: red;">This is red text.</p>
   ```

2. **Internal Styles** (Inside `<style>` tag):

   ```html
   <style>
       body {
           background-color: lightgray;
       }
   </style>
   ```

3. **External Stylesheets** (Linked file):

   ```html
   <link rel="stylesheet" href="styles.css">
   ```

---
<!--
### **Selectors**

| Selector  | Description                       |
| --------- | --------------------------------- |
| `*`       | Selects all elements              |
| `element` | Selects all `<element>` elements  |
| `#id`     | Selects element with the given ID |
| `.class`  | Selects elements with a class     |

More details: [MDN - CSS Selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Selectors)

---

### **Box Model**

Every element in CSS is a box consisting of:

- **Content**: The actual content (text, image, etc.)
- **Padding**: Space between content and border
- **Border**: Surrounds the padding
- **Margin**: Space outside the border

Learn more: [MDN - Box Model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)
---
-->

### **CSS Example: Basic Styling**

```css
body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    color: #333;
}

h1 {
    text-align: center;
    color: #0056b3;
}

p {
    line-height: 1.5;
}
```

---

### **Further Reading**

- [CSS Basics - W3Schools](https://www.w3schools.com/css/default.asp)
- [CSS Tricks - A Complete Guide](https://css-tricks.com/)
- [MDN - Getting Started with CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps)
