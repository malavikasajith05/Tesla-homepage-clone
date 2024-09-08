# Tesla Landing Page Clone

This project is a responsive landing page clone for Tesla's website. It showcases various Tesla models and features dynamic animations and interactive elements.

## Table of Contents

- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Features](#features)
- [How to Use](#how-to-use)

## Technologies Used

- HTML5
- CSS3 (with Flexbox and animations)
- JavaScript (for dynamic content and interactivity)
- Font Awesome (for icons)
- External Images from Tesla's website

## Project Structure

The project consists of three main files:
1. `tesla.html` – The main HTML file containing the structure of the Tesla landing page.
2. `tesla.css` – The CSS file providing styling for the page, including animations, layouts, and hover effects.
3. `tesla.js` – The JavaScript file handling the interactivity of the menu and scroll-based animations.

## Features

### 1. Responsive Header with Navigation
- A fixed header with the Tesla logo and navigation links for different Tesla models (Model S, Model 3, Model X, Model Y, Solar Roof, Solar Panels).
- Hover effects on navigation links with smooth transitions.

### 2. Side Menu
- A hidden side menu that slides in when the "Menu" link is clicked.
- The side menu contains additional options like "Existing Inventory", "Used Inventory", "Test Drive", and more.
- The menu can be closed by clicking the close button (`fa-xmark`).

### 3. Main Content Sections
- Multiple sections showcasing different Tesla models (Model S, Model 3, Model X, Model Y) and Tesla's solar products (Solar Panels, Solar Roof).
- Each section includes a title, an image of the product, and two buttons for "Custom Order" and "Existing Inventory".

### 4. Scroll-Based Animations
- As the user scrolls through the page, different sections become visible using animations.
- The text and buttons for each section appear dynamically as the user scrolls, creating a smooth user experience.

### 5. Button Animations
- The buttons for ordering or viewing the existing inventory are animated, with subtle transitions when hovered over.

## How to Use

1. Clone or download the project files.
2. Open the `tesla.html` file in your browser to view the Tesla landing page.
3. Scroll through the page to see the animations, or click the "Menu" link to open the side menu.

### JavaScript (tesla.js)
The JavaScript file controls:
- The toggling of the side menu and blur effect.
- The scroll-based animations that trigger when certain scroll positions are reached, controlling the visibility of each section and its content.

### CSS (tesla.css)
The CSS file includes:
- Layout and styling for the header, navigation links, buttons, and images.
- Keyframes for the animations used to display content dynamically as the user scrolls.
- Styling for the side menu, including hover effects for each option in the list.
