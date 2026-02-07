# Mahek Fatima - Portfolio Website

A modern, animated portfolio website showcasing backend engineering projects and skills.

## Features

- **Transparent Background**: Clean, gradient background with particle animations
- **Interactive Particle System**: Mouse-responsive particle network (inspired by openjkai.dev)
- **Smooth Animations**: Scroll-triggered animations and hover effects
- **Clean Design**: Beginner-friendly layout with professional aesthetics (inspired by disam.dev)
- **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern Tech Stack**: Pure HTML, CSS, and JavaScript (no frameworks needed)

## Structure

```
portfolio/
├── index.html          # Main HTML structure
├── styles.css          # All styling and animations
├── script.js           # Particle effects and interactions
└── README.md          # This file
```

## Customization

### Update Contact Information

Edit `index.html` and replace placeholder links:

```html
<!-- Line ~239 -->
<a href="mailto:your.email@example.com" class="contact-btn">
<!-- Line ~246 -->
<a href="https://github.com/yourusername" class="contact-btn">
<!-- Line ~253 -->
<a href="https://linkedin.com/in/yourprofile" class="contact-btn">
```

### Customize Colors

Edit `styles.css` variables:

```css
:root {
    --primary-color: #00ff88;      /* Main accent color */
    --secondary-color: #0088ff;    /* Secondary accent */
    --text-color: #e0e0e0;         /* Main text */
    --text-dark: #a0a0a0;          /* Secondary text */
}
```

### Adjust Particle Count

Edit `script.js`:

```javascript
this.particleCount = 100;  // Change particle density
```

## Deployment

### GitHub Pages

1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to Settings > Pages
4. Select "Deploy from main branch"
5. Your site will be live at `https://yourusername.github.io/repository-name`

### Netlify

1. Drag and drop the folder to [Netlify Drop](https://app.netlify.com/drop)
2. Your site is instantly deployed

### Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in the project directory
3. Follow the prompts

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Performance

- Lightweight: ~15KB total (uncompressed)
- No external dependencies
- Optimized animations using requestAnimationFrame
- GPU-accelerated transforms

## License

Feel free to use this template for your own portfolio. Attribution appreciated but not required.

## Contact

For questions or feedback, reach out via the contact links on the website.
