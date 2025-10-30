# Basic Restaurant Menu

A simple, elegant restaurant menu built with pure HTML and CSS. No JavaScript or external dependencies required.

## Features

- 🎨 **Pure HTML & CSS** - No JavaScript required
- 📱 **Fully Responsive** - Works on desktop, tablet, and mobile devices
- 🎯 **Semantic HTML** - Proper HTML5 structure for accessibility
- 🎭 **Professional Design** - Gradient header, card-based menu items, smooth hover effects
- 🖨️ **Print Friendly** - Optimized for printing physical menus
- ⚡ **Lightweight** - Fast loading with minimal code

## Menu Sections

- **Appetizers** - 4 items
- **Main Courses** - 5 items
- **Desserts** - 4 items
- **Beverages** - 5 items

## How to Use

1. Clone or download this repository
2. Open `index.html` in your web browser
3. That's it! No build process or dependencies needed

## File Structure

```
Basic-Restaurant-menu/
├── index.html      # Main HTML file with menu structure
├── styles.css      # CSS styling for the menu
└── README.md       # This file
```

## Customization

### Change Restaurant Name
Edit the `<h1>` tag in `index.html`:
```html
<h1 class="restaurant-name">Your Restaurant Name</h1>
```

### Change Colors
Modify the CSS variables in `styles.css`:
- Header gradient: `.header` background
- Accent color: Blue (#3498db)
- Price color: Red (#e74c3c)

### Add/Remove Menu Items
Follow the existing HTML structure for menu items:
```html
<div class="menu-item">
    <div class="item-header">
        <h3 class="item-name">Item Name</h3>
        <span class="item-price">$0.00</span>
    </div>
    <p class="item-description">Item description</p>
</div>
```

## Browser Compatibility

Works on all modern browsers:
- Chrome
- Firefox
- Safari
- Edge
- Opera

## License

Free to use and modify for personal and commercial projects.

## Preview

The menu features:
- An elegant header with restaurant name and tagline
- Clean, organized menu sections
- Professional typography
- Responsive design that adapts to any screen size
- Hover effects for interactive feedback