QR Menu - README

Overview

This project is a digital QR-based restaurant menu designed for Başgan Köfte. The menu is accessible via a QR code, allowing customers to view menu items, prices, and images of food and beverages on their mobile devices.

Project Structure

The project consists of the following main files:

main.html - The core HTML file that contains the structure of the menu.

main.js - The JavaScript file that enables interactivity, such as expanding and collapsing menu sections.

style.css - The CSS file that defines the visual styling of the menu.

Features

Interactive menu sections: Users can click on menu categories to expand or collapse them.

Responsive design: The menu adapts to different screen sizes, making it accessible on mobile devices.

Image display for beverages: Each drink option includes a small image for better visualization.

Price placeholders: Prices are displayed in a highlighted box for easy readability.

File Details

1. main.html

Defines the menu structure.

Includes different sections such as Sandwiches, Mixed Sandwiches, Menus, Toasts, Plates, Breakfast Items, and Beverages.

Uses onclick attributes to allow users to toggle sections.

References external CSS (style.css) and JavaScript (main.js).

2. main.js

Contains a single function:

function toggleVisibility(element) {
    const table = element.nextElementSibling;
    if (table.style.display === "none" || !table.style.display) {
        table.style.display = "table";
    } else {
        table.style.display = "none";
    }
}

This function allows users to click on a menu category title to show or hide its content dynamically.

3. style.css

Provides styling for a clean and elegant look.

Implements responsive design for mobile optimization.

Enhances user experience with:

Hover effects on menu titles

Box shadows for a modern look

Readable font styles and structured spacing

How to Use

Upload the project files to a web server or a local directory.

Generate a QR code pointing to the hosted HTML file.

Customers scan the QR code with their smartphones to access the digital menu.

Future Enhancements

Multi-language support: Add a language selection option.

Dark mode: Provide a night-friendly interface.

Backend integration: Connect to a database for dynamic price updates.

Ordering system: Enable users to place orders directly from the menu.

License

This project is free to use and modify for Başgan Köfte or similar restaurant implementations.

For further modifications or enhancements, feel free to update the HTML, CSS, and JavaScript files accordingly.

