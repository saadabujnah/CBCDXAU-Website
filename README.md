# CBCD - Central Blockchain Digital Coin Website

A professional, modern cryptocurrency website with neon theme and bilingual support (English/Arabic).

## Features

- **Modern Neon Design**: Futuristic FDML style with neon gradients and glowing effects
- **Bilingual Support**: English (default) and Arabic language switching
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Interactive Elements**: Animated charts, scroll effects, and smooth transitions
- **Professional Sections**: Hero, About, Whitepaper, Tokenomics, Roadmap, Team, Contact

## Files Structure

```
/
├── index.html          # Main HTML file
├── styles.css          # All styling and responsive design
├── script.js           # JavaScript functionality
├── logo.png           # Custom logo image (needs to be added)
└── README.md          # This file
```

## Setup Instructions

### 1. Add Your Custom Logo

1. Save your custom logo image as `logo.png` in the root directory
2. Recommended dimensions: 200x200 pixels (will be automatically resized)
3. The logo should have a transparent background for best results
4. Supported formats: PNG, JPG, JPEG, SVG

### 2. Serve the Website

**Option 1: Python Server (Recommended)**
```bash
python -m http.server 8000
```
Then open `http://localhost:8000` in your browser.

**Option 2: Live Server (VS Code Extension)**
1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html` and select "Open with Live Server"

**Option 3: Direct File Opening**
Simply double-click `index.html` to open in your browser (some features may not work)

## Features Overview

### Language Support
- Click the language switcher in the top-right corner to toggle between English and Arabic
- All content is translated and direction changes automatically for Arabic (RTL)

### Interactive Elements
- **Tokenomics Chart**: Interactive doughnut chart showing token distribution
- **Animated Roadmap**: Timeline with hover effects and progress indicators
- **Contact Form**: Functional form with validation and notifications
- **Whitepaper Download**: Click to download the whitepaper
- **Smooth Scrolling**: Navigation links scroll smoothly to sections

### Responsive Design
- Mobile-first approach
- Hamburger menu for mobile navigation
- Optimized layouts for all screen sizes
- Touch-friendly buttons and interactions

## Customization

### Colors
The neon color scheme can be customized in `styles.css` by modifying the CSS custom properties:

```css
:root {
  --neon-purple: #a855f7;
  --neon-blue: #3b82f6;
  --neon-cyan: #06b6d4;
  --neon-green: #10b981;
  --neon-pink: #ec4899;
}
```

### Content
All text content can be modified in both `index.html` and the language objects in `script.js`.

### Animations
Scroll animations and effects can be adjusted in the CSS file.

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## Performance

- Optimized CSS with efficient animations
- Responsive images and layouts
- Minimal JavaScript for fast loading
- Modern web standards for better performance

## Support

For issues or questions:
1. Check browser console for errors
2. Ensure all files are in the same directory
3. Verify logo.png exists for custom logo
4. Test in different browsers if issues persist

---

**Created with ❤️ for CBCD - Central Blockchain Digital Coin**