
# QR Menu - Başgan Köfte

## Overview

This project is a **QR-based digital menu** for the restaurant **Başgan Köfte**. It provides an interactive and user-friendly way for customers to browse the menu using their smartphones. The menu is structured into sections, each containing food items with different portion sizes and prices.

---

## Features

- **Interactive Sections:** Customers can click on menu categories to expand/collapse them.
- **Mobile-Friendly Design:** The menu adapts to different screen sizes for seamless viewing.
- **Easy-to-Update Prices:** Prices are displayed dynamically using placeholders.
- **Image Support:** Beverages include images for easy recognition.
- **Lightweight & Fast:** The menu is built using **HTML, CSS, and JavaScript** without requiring a backend.

---

## File Structure

```
/project-root
│── assets/
│   │── style.css      # Styling for the menu layout
│   │── main.js        # JavaScript functions for toggling menu sections
│   │── pictures/      # Images used in the menu (e.g., drinks)
│── main.html          # Main HTML file (restaurant menu)
```

---

## Installation & Usage

1. **Upload the files** to your web hosting provider.
2. **Generate a QR code** linking to the hosted `main.html` file.
3. **Print and place the QR code** on tables or the restaurant entrance.
4. **Customers scan the QR code** to access the menu instantly.

---

## Technologies Used

- **HTML5:** Structure of the menu.
- **CSS3:** Styling and responsiveness.
- **JavaScript:** Interactive menu sections.

---

## JavaScript Functionality

The script (`main.js`) allows users to show or hide menu sections by clicking on headings.

```js
function toggleVisibility(element) {
    const table = element.nextElementSibling;
    if (table.style.display === "none" || !table.style.display) {
        table.style.display = "table";
    } else {
        table.style.display = "none";
    }
}
```

This makes the menu compact and easier to navigate on mobile devices.

---

## Customization

- **Modify `style.css`** to adjust colors, fonts, and layout.
- **Update `main.html`** to add, remove, or edit menu items.
- **Replace images** in the `pictures/` folder for drinks or branding.

---

## Future Improvements

- Implement a **backend system** for dynamic price updates.
- Add **multi-language support**.
- Enable **ordering functionality** directly from the menu.

---

### License

This project is open for modification and customization based on your restaurant’s needs.

---
