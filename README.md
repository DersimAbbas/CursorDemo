# Cafe Habibi - Middle Eastern Cafe Website made with CURSOR AI 100% 

A beautiful responsive website for Cafe Habibi, a fictional Middle Eastern cafe specializing in authentic treats and beverages.

## Features

- **Responsive Design**: Works seamlessly on all device sizes
- **Modern UI**: Beautiful Middle Eastern themed design with custom animations
- **Interactive Menu**: Tab-based menu displaying various categories of food and beverages
- **Image Gallery**: Showcasing the cafe ambiance and offerings
- **Contact Information**: Easy access to the cafe's details

## Technologies Used

- HTML5
- CSS3 (with CSS Variables for theming)
- JavaScript (Vanilla JS)
- Font Awesome for icons
- Google Fonts (Amiri and Raleway)

## Getting Started

1. Clone this repository or download the files
2. Open the `index.html` file in any modern web browser

No build steps or installations required!

## Project Structure

- `index.html` - Main HTML file with the structure of the website
- `styles.css` - All styling for the website with responsive breakpoints
- `script.js` - JavaScript functionality for interactive elements

## Customization

### Colors
You can easily change the color scheme by modifying the CSS variables in the `:root` section of the `styles.css` file:

```css
:root {
    --primary-color: #c8894e;
    --secondary-color: #b2485b;
    --accent-color: #386641;
    --dark-color: #413026;
    --light-color: #f8eee2;
    --transition: all 0.3s ease;
}
```

### Content
To update the menu items, modify the relevant sections in the `index.html` file. Each menu item follows this structure:

```html
<div class="menu-item">
    <div class="menu-item-image">
        <img src="IMAGE_URL" alt="ITEM_NAME">
    </div>
    <div class="menu-item-info">
        <h3>ITEM_NAME</h3>
        <p>ITEM_DESCRIPTION</p>
        <span class="price">$PRICE</span>
    </div>
</div>
```
