# AidanceAI Website

A premium Apple-style website featuring glassmorphism, dark mode, bento grids, and smooth scroll animations.

## Features

- 🎨 **Apple-Style Design**: Clean, minimalist aesthetic with Inter font
- ☀️ **Light Premium Theme**: White backgrounds with soft grey accents
- ✨ **Glassmorphism**: Blur effects on navigation
- 📦 **Bento Grids**: Modern card-based layout with subtle shadows
- 🎬 **Scroll Animations**: Elements fade in as you scroll
- 📱 **Fully Responsive**: Mobile-first design
- 🎯 **Floating Labels**: Premium form inputs
- 💎 **Luxury Feel**: Refined colors and micro-interactions

## Quick Start

1. Simply open `index.html` in your browser
2. No build process required - pure HTML, CSS, and JavaScript

## File Structure

```
Website/
├── index.html      # Main HTML structure
├── styles.css      # Apple-style CSS design system
├── index.js        # Scroll animations & mobile menu
├── assets/         # Place your images here
│   ├── product.png
│   ├── aws.png
│   ├── azure.png
│   ├── ChatGPT.png
│   ├── claude.svg.png
│   ├── deepseek.png
│   ├── fastapi.png
│   ├── react.png
│   └── postgres.png
└── README.md
```

## Adding Your Assets

Place your logo and technology stack images in the `assets/` folder. The website includes fallback placeholders if images are missing.

## Customization

### Colors
Edit CSS variables in `styles.css`:
```css
:root {
    --bg-color: #ffffff;
    --card-bg: #f5f5f7;
    --accent: #0071e3;
}
```

### Content
Edit sections directly in `index.html`:
- Hero section (#intro)
- Services (#services)
- Products (#products)
- Contact form (#contact)

## Contact Form

The form currently logs to console. To connect to a backend:
1. Uncomment the fetch code in `index.js`
2. Replace `/api/contact` with your endpoint

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## Technologies

- Pure HTML5
- CSS3 (Grid, Flexbox, Animations)
- Vanilla JavaScript (ES6+)
- Inter Font (Google Fonts)
- Font Awesome Icons
