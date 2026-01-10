# CSS Mini Project - Mango Retail

A responsive sidebar navigation menu with a modern design featuring a hamburger toggle, built using pure HTML, CSS, and Font Awesome icons.

## Project Overview

This project demonstrates a collapsible sidebar navigation menu for a retail business website called "Mango Retail". The sidebar includes navigation links, icons, social media integration, and a responsive design with smooth animations.

## Features

- **Responsive Hamburger Menu**: Toggle sidebar on/off using a checkbox hack (no JavaScript required)
- **Smooth Animations**: CSS transitions for sidebar slide-in/slide-out effects
- **Font Awesome Icons**: Professional icons for menu items and social media links
- **Background Image**: Full-screen background image with cover effect
- **Social Media Links**: Integrated social media icons (Facebook, Twitter, Instagram, YouTube)
- **Modern Typography**: Google Fonts (Montserrat) for enhanced visual appeal
- **Footer**: Copyright information positioned at the bottom of the page

## Project Structure

```
CSS_mini_Project/
├── index.html          # Main HTML file with semantic structure
├── styles.css          # Complete CSS styling and layout
├── readme.md           # Project documentation
└── Resource/           # Assets folder
    ├── mango.jpg       # Background image
    └── cover.jpg       # Additional image resource
```

## Menu Items

The sidebar navigation includes 8 main menu items:
1. **Event Gallery** - Browse event photos and gallery
2. **Shortcuts** - Quick access links
3. **Shop** - Shopping section
4. **Upcoming Events** - Event calendar and announcements
5. **Store** - Store information
6. **Contact** - Contact information
7. **Feedback** - Customer feedback section
8. **Reviews** - Customer reviews

## Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Flexbox, positioning, transitions, and animations
- **Font Awesome 6.4.0**: Icon library for enhanced visuals
- **Google Fonts**: Montserrat font family for typography

## Key CSS Features

- **Checkbox Hack**: Uses hidden checkbox input to toggle menu state without JavaScript
- **Transition Effects**: Smooth 0.5s ease animation for sidebar movement
- **Fixed Positioning**: Sidebar remains fixed while content scrolls
- **Responsive Design**: Adapts to different screen sizes
- **Hover Effects**: Interactive menu items with background color on hover
- **Absolute Positioning**: Strategic placement of buttons, footer, and social icons

## How It Works

The menu toggle uses a CSS checkbox hack:
1. A hidden checkbox (`#check`) controls the menu state
2. Labels with the hamburger/close icons toggle the checkbox
3. CSS `:checked` selector slides the sidebar in/out
4. Button visibility changes based on menu state

## Customization

- **Sidebar Width**: Modify the `width: 250px;` property in `.sidebar_menu`
- **Colors**: Change `#111` (background) and `#fff` (text) values
- **Animation Speed**: Adjust `transition: all 0.5s ease;` timing
- **Background Image**: Replace `/Resource/mango.jpg` path with your image
- **Brand Name**: Update "Mango Retail" text in the logo section

## Browser Compatibility

Works on all modern browsers supporting:
- CSS3 Transitions
- CSS Flexbox
- HTML5 Input elements