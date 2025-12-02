# Navigator Academy Website

A modern, responsive website for Navigator Academy - Business Valuation Training Program.

## Features

- **Modern Design**: Clean, professional design with gradient accents and smooth animations
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Smooth Scrolling**: Enhanced navigation with smooth scroll behavior
- **Interactive Elements**: Hover effects, animations, and mobile menu
- **SEO Friendly**: Semantic HTML structure

## Getting Started

### Prerequisites

No special prerequisites needed - this is a static website that can be opened directly in a browser.

### Installation

1. Clone or download this repository
2. Open `index.html` in your web browser

That's it! The website is ready to use.

### Local Development Server (Optional)

For a better development experience, you can use a local server:

#### Using Python 3:
```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

#### Using Node.js (http-server):
```bash
npx http-server -p 8000
```

#### Using PHP:
```bash
php -S localhost:8000
```

## File Structure

```
navigator-academy/
├── index.html      # Main HTML file
├── styles.css      # Stylesheet with all styling
├── script.js       # JavaScript for interactivity
└── README.md       # This file
```

## Customization

### Colors

The website uses CSS custom properties (variables) defined in `styles.css`. You can easily change the color scheme by modifying these variables:

```css
:root {
    --primary-color: #2563eb;
    --primary-dark: #1e40af;
    --secondary-color: #0f172a;
    --accent-color: #3b82f6;
    /* ... */
}
```

### Content

All content is in `index.html`. Simply edit the HTML to update text, add sections, or modify the structure.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

© 2024 Navigator Academy. All rights reserved.

