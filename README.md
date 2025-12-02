# Navigator Academy Website

A modern, responsive website for Navigator Academy - Business Valuation Training Program.

🌐 **Live Site**: [View on GitHub Pages](https://samjhill.github.io/navigator/)

## Features

- **Modern Design**: Clean, professional design with gradient accents and smooth animations
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Smooth Scrolling**: Enhanced navigation with smooth scroll behavior
- **Interactive Elements**: Hover effects, animations, and mobile menu
- **SEO Friendly**: Complete meta tags, Open Graph, and structured data
- **Accessible**: ARIA labels, focus states, skip links, and keyboard navigation
- **GitHub Pages Ready**: Configured for easy deployment

## Getting Started

### Viewing the Website

The website is live on GitHub Pages: **https://samjhill.github.io/navigator/**

### Local Development

1. Clone the repository:
   ```bash
   git clone git@github.com:samjhill/navigator.git
   cd navigator
   ```

2. Open `index.html` in your web browser, or use a local server (recommended):

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

## GitHub Pages Setup

This repository is configured for GitHub Pages. To enable it:

1. Go to your repository settings on GitHub
2. Navigate to **Pages** in the left sidebar
3. Under **Source**, select **Deploy from a branch**
4. Choose **main** branch and **/ (root)** folder
5. Click **Save**

Your site will be available at `https://samjhill.github.io/navigator/` (or your custom domain if configured)

## File Structure

```
navigator/
├── index.html      # Main HTML file
├── styles.css      # Stylesheet with all styling
├── script.js       # JavaScript for interactivity
├── .nojekyll       # Prevents Jekyll processing
├── .gitignore      # Git ignore rules
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

