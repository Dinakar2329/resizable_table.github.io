# Resizable Table CDN

## Overview

The Resizable Table CDN provides a simple and efficient solution for creating resizable table columns in web projects. This CDN includes CSS and JavaScript files that allow users to adjust the width of table columns by dragging the column borders. The resizable table is designed to be easy to integrate and customize, providing a seamless user experience.

## Features

- Easily resizable table columns by dragging the column borders.
- Lightweight and efficient implementation.
- Accessibility enhancements for keyboard navigation.
- Compatible with various table structures and designs.
- Customizable CSS styles to match your project's design.

## Usage

### 1. Include CSS Styles

Include the resizable_table.css file in the `<head>` section of your HTML file to apply the necessary styles:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/Dinakar2329/resizable_table.github.io/resizable_table.css?version=0">
```

### 2. Create HTML Table

Create the HTML table structure in the `<body>` section of your HTML file. Add the `resizable` class to the table headers (`<th>`) that you want to make resizable.

```html
<table class="resizable">
    <thead>
        <tr>
            <th class="rs-column">Column 1</th>
            <th class="rs-column">Column 2</th>
            <th class="rs-column">Column 3</th>
            <!-- Add more columns as needed -->
        </tr>
    </thead>
    <tbody>
        <!-- Table data rows go here -->
    </tbody>
</table>
```

### 3. Include JavaScript

Include the resizable_table.js file just before the closing `</body>` tag of your HTML file to add resizing functionality to the table:

```html
<script src="https://cdn.jsdelivr.net/gh/Dinakar2329/resizable_table.github.io/resizable_table.js"></script>
```

### 4. Customize and Populate Table Data

Customize the table structure and populate it with your data as needed.

### 5. Test and Integrate

Save your HTML file and open it in a web browser to test the resizable table functionality. Adjust the column widths by dragging the column borders. Customize the CSS styles and table structure to integrate it seamlessly into your web project.

## Note

For avoiding conflicts with other `::before` or `::after` effects in the table, the `rs-column` class has been added to multiple columns.

## Example

Here's a basic example of how to use the resizable table in your HTML file:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Resizable Table Example</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/Dinakar2329/resizable_table.github.io/resizable_table.css"> 
    <style>
        /* Custom styles can be added here */
    </style>
</head>
<body>

    <!-- Place your resizable table HTML code here -->

    <script src="https://cdn.jsdelivr.net/gh/Dinakar2329/resizable_table.github.io/resizable_table.js"></script>
</body>
</html>
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
