# Manikanta's Inline CSS Portfolio Website

A **modern, mobile-friendly single-page portfolio** built entirely using **HTML5 and inline CSS**. No external stylesheets or JavaScript — just pure semantic HTML with embedded styles. Font Awesome icons are loaded via CDN to enhance visual appeal.

## Features

- **Single-page layout** with clean, readable structure
- **Responsive design** using inline styles (mobile-friendly)
- **Font Awesome CDN** for social media icons
- Inline-only CSS — demonstrates direct use of style attributes
- Sections include:
  - **Header** – Name and title
  - **Profile Image**
  - **About Me**
  - **Skills & Experience**
  - **Contact Information**
  - **My Other web Pages**
  - **Footer**

## Purpose

This project was created as:
- A **personal developer portfolio**
- A demonstration of **inline CSS styling**
- A submission for the **NexGenEduTech internship**
- To showcase all the Projects done by me for the **NexGenEduTech internship**

## Technologies Used

- **HTML5**
- **Inline CSS**
- **Font Awesome (via CDN)**

## How to Use

1. Download or clone this repository.
2. Open the `index.html` file in any modern web browser.
3. Edit the HTML file to customize content and styles.

## Preview

![Preview Screenshot](https://i.ibb.co/s9gqNS1f/Screenshot-2025-05-05-180353.png)

**Total Lines of Code:** `100+`  

---


# Terry A. Davis Tribute Website  
  
This is a tribute website dedicated to **Terry A. Davis**, the creator of **TempleOS** — a unique, single-handedly developed operating system with a divine mission. This site honors his work, beliefs, and technical achievements by offering an immersive, interactive, and respectful digital memorial.  
  
---  
  
## Table of Contents  
- [Features](#features)    
- [Technologies Used](#technologies-used)    
- [Setup and Installation](#setup-and-installation)    
- [Project Structure](#project-structure)    
- [Customization](#customization)    
- [Accessibility](#accessibility)    
- [Performance Optimizations](#performance-optimizations)    
- [Browser Compatibility](#browser-compatibility)    
- [Contributing](#contributing)    
- [Credits and Acknowledgments](#credits-and-acknowledgments)    
- [License](#license)    
  
---  
  
## Features  
  
### 1. Responsive Design    
The entire site is built with mobile-first responsiveness in mind, ensuring optimal viewing across phones, tablets, and desktops.  
  
### 2. Starfield Background    
A dynamic, animated starfield using the HTML5 `<canvas>` element to provide a cosmic, nostalgic backdrop reminiscent of TempleOS aesthetics.  
  
### 3. Oracle of ASCII    
An interactive section inspired by Terry’s divine communication system, featuring random, spiritually themed ASCII messages revealed on button click.  
  
### 4. Section-Based Navigation    
Sticky navigation bar with smooth scrolling and anchor-based links to major sections like Biography, TempleOS, HolyC, and Legacy.  
  
### 5. Interactive Modals    
Each section includes "Learn More" or "View Game" buttons that open fullscreen modal dialogs with extended information and visuals.  
  
### 6. Expandable Content Sections    
Uses checkboxes and labels to create accessible, expandable sections that reveal deeper content about Terry’s life, mental health, and beliefs.  
  
### 7. Timeline Layout    
A chronological visual representation of key milestones in Terry’s life — education, development phases, and TempleOS releases.  
  
### 8. Image Gallery    
Horizontally scrollable gallery containing rare TempleOS screenshots, code editors, and moments from Terry's journey.  
  
### 9. HolyC Code Comparison    
Tabbed interface comparing **HolyC** to standard **C**, including syntax highlights and examples of each.  
  
### 10. Final CTA Button    
A “Go To Main Portfolio” button at the end of the page invites visitors to explore the developer's broader work.  
  
---  
  
## Technologies Used  
  
- **HTML5:** Semantic layout and structural elements for accessibility and SEO.  
- **CSS3:** Uses CSS Grid, Flexbox, animations, transitions, and CSS variables for consistent color themes.  
- **JavaScript (Vanilla):** Oracle interactions, modal handling, gallery logic, and canvas animation.  
- **Canvas API:** Starfield animation simulates movement of stars in the background.  
- **ARIA & Semantic Tags:** For screen readers, focus management, and keyboard users.  
  
---  






# Foodie Website Project Layout 

A responsive food delivery website showcasing different layout variations of the "About Us" section, enhanced menu cards with interactive elements, and a humorous "No Food" page.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Project Structure](#project-structure)
3. [Design System](#design-system)
4. [Layout Variations](#layout-variations)
5. [Grid System Implementation](#grid-system-implementation)
6. [Responsive Design](#responsive-design)
7. [Interactive Elements](#interactive-elements)
8. [Menu Card System](#menu-card-system)
9. [No Food Page](#no-food-page)
10. [Browser Compatibility](#browser-compatibility)
11. [Performance Optimizations](#performance-optimizations)
12. [Accessibility Considerations](#accessibility-considerations)
13. [Future Enhancements](#future-enhancements)
14. [Running the Project](#running-the-project)
15. [Development Decisions](#development-decisions)

## Project Overview

The Foodie Website is a demonstration project that showcases different layout techniques and responsive design principles. The primary focus is on displaying the same content with four different layout variations, particularly in the "About Us" section. The project also includes enhanced menu cards with pricing and interactive "Order Now" buttons, as well as a humorous "No Food" page that appears when users attempt to order food.

### Key Features

- Four different layout variations of the "About Us" section
- 12-column grid system for precise layout control
- Responsive design that adapts to all screen sizes
- Interactive menu cards with pricing and "Order Now" buttons
- Modal confirmation system for orders
- Humorous "No Food" page with animations
- Consistent styling and user experience across all pages

## Project Structure

```
foodie-website/
├── page1.html        # Layout 1: Image left, text right
├── page2.html        # Layout 2: Image right, text left
├── page3.html        # Layout 3: Image top, text bottom
├── page4.html        # Layout 4: Text top, image bottom
├── no-food.html      # Humorous page for non-existent food items
└── README.md         # Project documentation
```

## Design System

### Color Palette

- **Primary Color**: #d83a3a (Red) - Used for buttons, headings, and accents
- **Secondary Color**: #333333 (Dark Gray) - Used for text and secondary buttons
- **Background Color**: #f8f8f8 (Light Gray) - Used for page backgrounds
- **Card Background**: #ffffff (White) - Used for cards and content areas
- **Border Color**: #cccccc (Light Gray) - Used for borders and dividers

### Typography

- **Font Family**: Sans-serif
- **Heading Sizes**:
  - H1: 2.5em
  - H2: 2em
  - H3: 1.2em
- **Body Text**: 1em
- **Small Text**: 0.9em

### Spacing System

- **Container Max Width**: 1200px
- **Grid Gap**: 20px
- **Section Margin**: 40px
- **Component Padding**: 15px
- **Button Padding**: 8px 16px

### Component Styles

- **Buttons**: 
  - Background color: #d83a3a
  - Text color: white
  - Border radius: 5px
  - Hover effect: Darker background (#b73131)
  
- **Cards**:
  - Border: 1px solid #ccc
  - Border radius: 8px
  - Box shadow on hover
  - Transition effects for hover states

## Layout Variations

### Layout 1: Image Left, Text Right (page1.html)

The original layout places the image on the left side (spanning 4 columns) and the text content on the right side (spanning 8 columns). This is a common layout pattern that works well for introducing a topic with supporting visuals.

**Implementation**:
```css
.grid-container {
  display: grid;
  grid-template-columns: repeat(12, 1fr);
  gap: 20px;
}

.about-image {
  grid-column: span 4;
}

.monkey5 {
  grid-column: span 8;
}
```

### Layout 2: Image Right, Text Left (page2.html)

This layout reverses the original pattern, placing the text on the left side (spanning 8 columns) and the image on the right side (spanning 4 columns). This variation can be useful for creating visual interest and breaking up the monotony of a page.

**Implementation**:
```css
.layout2 {
  grid-template-areas: "text text text text text text text text img img img img";
}

.layout2 .monkey5 {
  grid-area: text;
}

.layout2 .about-image {
  grid-area: img;
}
```

### Layout 3: Image Top, Text Bottom (page3.html)

This layout stacks the elements vertically, with the image at the top and the text content below it. This arrangement works well for mobile devices and can be more effective when the image needs to be the primary focus.

**Implementation**:
```css
.layout3 {
  grid-template-areas: 
    "img img img img img img img img img img img img"
    "text text text text text text text text text text text text";
}

.layout3 .about-image {
  grid-area: img;
}

.layout3 .monkey5 {
  grid-area: text;
}
```

### Layout 4: Text Top, Image Bottom (page4.html)

This layout also stacks the elements vertically, but with the text content at the top and the image below it. This arrangement can be useful when the text needs to introduce the image or when the image serves as a supporting visual.

**Implementation**:
```css
.layout4 {
  grid-template-areas: 
    "text text text text text text text text text text text text"
    "img img img img img img img img img img img img";
}

.layout4 .monkey5 {
  grid-area: text;
}

.layout4 .about-image {
  grid-area: img;
}
```

## Grid System Implementation

The project uses a 12-column grid system implemented with CSS Grid. This provides precise control over the layout and ensures consistency across different screen sizes.

### Base Grid Container

```css
.grid-container {
  display: grid;
  grid-template-columns: repeat(12, 1fr);
  gap: 20px;
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px;
  align-items: center;
}
```

### Grid Areas for Complex Layouts

For more complex layouts, grid template areas are used to create a visual representation of the layout in the CSS:

```css
.layout2 {
  grid-template-areas: "text text text text text text text text img img img img";
}

.layout2 .monkey5 {
  grid-area: text;
}

.layout2 .about-image {
  grid-area: img;
}
```

This approach makes it easier to understand and maintain the layout, especially when dealing with responsive adjustments.

## Responsive Design

The website is fully responsive and adapts to different screen sizes using a combination of CSS Grid, media queries, and flexible units.

### Breakpoints

- **Large Desktop**: > 992px
- **Small Desktop/Tablet**: 768px - 992px
- **Tablet**: 576px - 768px
- **Mobile**: ≤ 576px

### Responsive Strategies

1. **Fluid Grid**: The 12-column grid system adjusts proportionally to the screen width.
2. **Responsive Typography**: Font sizes are reduced on smaller screens for better readability.
3. **Flexible Images**: Images use max-width constraints and aspect ratios to maintain proportions.
4. **Media Queries**: Different layouts and styles are applied at specific breakpoints.

### Example Media Query

```css
@media (max-width: 768px) {
  .about-image {
    grid-column: span 5;
  }
  .monkey5 {
    grid-column: span 7;
    font-size: 0.95em;
  }
  .about-image img {
    max-width: 100%;
  }
}
```

## Interactive Elements

### Order Buttons

Each menu card includes an "Order Now" button that triggers a modal confirmation dialog when clicked. The button is styled to match the site's design system and includes hover effects for better user feedback.

```css
.order-button {
  background: #d83a3a;
  color: white;
  border: none;
  padding: 8px 16px;
  border-radius: 5px;
  cursor: pointer;
  font-size: 0.9em;
  transition: background-color 0.3s ease;
  width: 100%;
}

.order-button:hover {
  background: #b73131;
}
```

### Modal Confirmation

When a user clicks an "Order Now" button, a modal dialog appears to confirm the order. The modal includes:

- The name of the selected food item
- Confirmation and cancellation buttons
- A close button (X) in the top-right corner
- Click-outside-to-close functionality

```javascript
// Add click event to all order buttons
orderButtons.forEach(button => {
  button.addEventListener('click', function() {
    const itemName = this.getAttribute('data-item');
    orderItemName.textContent = itemName;
    modal.style.display = 'block';
  });
});
```

## Menu Card System

The menu section uses a card-based layout with CSS Grid to create a responsive, visually appealing display of food items.

### Card Structure

Each menu card includes:

1. An image of the food item
2. A title (food name)
3. A description
4. A price
5. An "Order Now" button

```html
<div class="menu-card">
  <img src="image-url.jpg" alt="Food Name">
  <div class="menu-card-content">
    <h3 class="menu-card-title">Food Name</h3>
    <p class="menu-card-description">Description of the food item.</p>
    <p class="menu-card-price">₹249</p>
    <button class="order-button" data-item="Food Name">Order Now</button>
  </div>
</div>
```

### Card Layout

The cards are arranged in a responsive grid that adjusts the number of columns based on the available space:

```css
.menu-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 25px;
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px 40px;
}
```

### Card Interactions

Each card includes hover effects to provide visual feedback to the user:

```css
.menu-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 20px rgba(0,0,0,0.1);
}
```

## No Food Page

The "No Food" page is a humorous error page that appears when a user attempts to order food. It's designed to be lighthearted and engaging while providing clear navigation back to the main site.

### Design Elements

1. **Hungry Cat**: An image of the cat from the main site, with a thought bubble showing a pizza
2. **Animated Food Emojis**: Bouncing food emojis to add visual interest
3. **Humorous Message**: A lighthearted explanation of why the food isn't available
4. **Clear Navigation**: Buttons to return to the homepage or go back to the previous page

### Animations

The page includes several CSS animations to make it more engaging:

```css
@keyframes bounce {
  0%, 20%, 50%, 80%, 100% {
    transform: translateY(0);
  }
  40% {
    transform: translateY(-20px);
  }
  60% {
    transform: translateY(-10px);
  }
}

@keyframes pulse {
  0% {
    transform: scale(1);
  }
  50% {
    transform: scale(1.1);
  }
  100% {
    transform: scale(1);
  }
}
```

## Browser Compatibility

The website has been tested and works well on:

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Mobile browsers (iOS Safari, Android Chrome)

### Compatibility Considerations

1. **CSS Grid**: The layout relies heavily on CSS Grid, which is supported in all modern browsers but may require fallbacks for very old browsers.
2. **Flexbox**: Used for alignment and smaller layout components, with good browser support.
3. **CSS Variables**: Not used in this project to ensure maximum compatibility.
4. **JavaScript**: Uses standard DOM manipulation methods that work across all modern browsers.

## Performance Optimizations

Several optimizations have been implemented to ensure good performance:

### Image Optimization

1. **Aspect Ratio**: Predefined aspect ratios prevent layout shifts during loading.
2. **Object Fit**: Ensures consistent image display regardless of actual dimensions.
3. **Responsive Sizing**: Images scale appropriately for different screen sizes.

### CSS Efficiency

1. **Shared Styles**: Common styles are defined once and reused.
2. **Specific Overrides**: Layout-specific styles only override what's necessary.
3. **Minimal Selectors**: CSS selectors are kept simple to improve rendering performance.

### JavaScript Optimization

1. **Event Delegation**: Not implemented but could be added for better performance with many buttons.
2. **Minimal DOM Manipulation**: The JavaScript code makes minimal changes to the DOM.
3. **Efficient Event Handling**: Event listeners are added only once per element.

## Accessibility Considerations

The website includes several accessibility features:

1. **Semantic HTML**: Proper use of HTML5 semantic elements like `<header>`, `<footer>`, and `<button>`.
2. **Alt Text**: All images include descriptive alt text.
3. **Color Contrast**: Text colors maintain sufficient contrast with backgrounds.
4. **Keyboard Navigation**: Interactive elements are accessible via keyboard.
5. **Focus States**: Not explicitly styled but rely on browser defaults.

## Future Enhancements

Potential improvements for the project:

1. **Dark Mode**: Implement a toggle for dark/light theme.
2. **Cart System**: Create a simple cart to collect multiple orders.
3. **Form Validation**: Add validation to the contact form.
4. **More Menu Items**: Expand the menu with additional food categories.
5. **Image Lazy Loading**: Implement lazy loading for better performance.
6. **Animation Improvements**: Add smoother transitions between states.
7. **Accessibility Enhancements**: Improve focus states and ARIA attributes.

## Running the Project

Since these are static HTML pages, you can run them in any modern web browser:

1. Download all the HTML files to a local directory
2. Open any of the HTML files in a web browser by double-clicking on them or using File > Open in your browser
3. Navigate between the different layouts using the navigation links at the top or bottom of each page

Alternatively, you can use a local development server:

```bash
# Using Python 3
python -m http.server

# Using Node.js with http-server (install with: npm install -g http-server)
http-server
```

Then open your browser and navigate to `http://localhost:8000` (or the port specified by your server).

## Development Decisions

### Why CSS Grid for Layout?

CSS Grid was chosen for the layout system because it provides:

1. **Two-dimensional Control**: Unlike Flexbox, Grid allows control over both rows and columns simultaneously.
2. **Named Areas**: Grid template areas provide a visual representation of the layout in the CSS.
3. **Responsive Flexibility**: Grid makes it easy to redefine layouts at different breakpoints.
4. **Precise Alignment**: Grid allows for precise alignment and spacing of elements.

### Why JavaScript for Interactivity?

Vanilla JavaScript was used for interactivity because:

1. **No Dependencies**: No need for external libraries or frameworks.
2. **Performance**: Direct DOM manipulation is efficient for simple interactions.
3. **Compatibility**: Basic JavaScript works across all modern browsers.
4. **Simplicity**: The interactive elements are straightforward and don't require complex state management.

### Design System Choices

The design system was created with these principles in mind:

1. **Consistency**: Using the same colors, spacing, and typography throughout the site.
2. **Simplicity**: A limited color palette and straightforward typography for clarity.
3. **Hierarchy**: Clear visual hierarchy through size, color, and spacing.
4. **Feedback**: Interactive elements provide visual feedback through hover and active states.

### Mobile-First vs. Desktop-First

The project uses a desktop-first approach with responsive breakpoints for smaller screens. This decision was made because:

1. **Content Priority**: The desktop layout better showcases the different layout variations.
2. **Complexity**: The desktop layouts are more complex and benefit from being defined first.
3. **Target Audience**: The primary purpose is to demonstrate layout techniques, which are more visible on larger screens.

However, a mobile-first approach would be recommended for production websites.


## Key Changes and Improvements

### 1. Fixed Spacing Issues on the "No Food" Page

I've completely eliminated any left spacing issues on the "No Food" page by:

1. Adding a CSS reset with `* { margin: 0; padding: 0; box-sizing: border-box; }` to ensure consistent spacing
2. Setting `width: 100%` and `overflow-x: hidden` on the body to prevent horizontal scrolling
3. Ensuring the container has proper centering with `width: 100%; max-width: 800px; margin: 0 auto;`
4. Removing any unnecessary margins or padding from elements

### 2. Made Button Sizes Consistent

I've adjusted the button styles on the "No Food" page to match the rest of the site:

```css
.button {
  padding: 8px 16px;
  background-color: #d83a3a;
  color: white;
  text-decoration: none;
  border-radius: 5px;
  font-weight: bold;
  transition: background-color 0.3s ease, transform 0.2s ease;
  font-size: 0.9em;
  border: none;
  cursor: pointer;
  display: inline-block;
}

```







  ## Contact

- **LinkedIn**: [linkedin.com/in/kvsmanikanta](https://www.linkedin.com/in/kvsmanikanta)
- **GitHub**: [github.com/monkey9-Cyber-cat-Spidy](https://github.com/monkey9-Cyber-cat-Spidy)
- **Email**: [mk1343093@gmail.com](mailto:mk1343093@gmail.com)

**Total Lines of Code:** `1500+`  
© 2025 Manikanta | Built with HTML & Inline CSS only
