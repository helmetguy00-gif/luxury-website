# Luxe - Luxury Website

A premium luxury website inspired by Apple's minimalist design aesthetic, featuring smooth animations, elegant typography, and a sophisticated user experience.

## Features

- **Apple-Inspired Design**: Clean, minimalist interface with premium aesthetics
- **Responsive Layout**: Fully responsive design that works on all devices
- **Smooth Animations**: Elegant fade-in effects and hover transitions
- **Modern CSS**: Uses CSS Grid, Flexbox, and modern styling techniques
- **Interactive Elements**: Smooth scrolling, navigation effects, and button interactions
- **Glass Morphism**: Frosted glass effect on navigation bar

## Technologies Used

- HTML5
- CSS3 (with modern features like Grid, Flexbox, backdrop-filter)
- Vanilla JavaScript (ES6+)
- No frameworks or dependencies required

## Getting Started

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/helmetguy00-gif/luxury-website.git
cd luxury-website
```

2. Open `index.html` in your browser:
   - Simply double-click the `index.html` file, or
   - Use a local server (recommended):
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (http-server)
   npx http-server
   ```

3. Visit `http://localhost:8000` in your browser

### GitHub Pages Deployment

To deploy this website on GitHub Pages:

1. Go to your repository settings
2. Navigate to "Pages" section
3. Under "Source", select "main" branch
4. Click "Save"
5. Your site will be live at `https://helmetguy00-gif.github.io/luxury-website/`

## Project Structure

```
luxury-website/
│
├── index.html          # Main HTML file
├── styles.css          # All styling and animations
├── script.js           # Interactive functionality
└── README.md          # Project documentation
```

## Design Features

### Color Palette
- Primary: Gradient Purple (#667eea to #764ba2)
- Background: White (#fff) and Light Gray (#f5f5f7)
- Text: Dark Gray (#1d1d1f) and Medium Gray (#6e6e73)

### Typography
- Font Family: SF Pro Display (Apple's system font stack)
- Responsive font sizes with modern scaling
- Careful letter-spacing for premium feel

### Sections
1. **Navigation**: Fixed glass-morphism navbar
2. **Hero**: Full-screen gradient background with CTA buttons
3. **Feature**: Split layout showcasing product details
4. **Products**: Grid layout with hover effects
5. **Experience**: Dark section with emphasis on luxury
6. **Footer**: Multi-column layout with links

## Customization

### Changing Colors
Edit the CSS custom properties in `styles.css`:
- Hero gradient: `.hero` background
- Accent colors: `.btn-primary`, `.link-arrow`

### Adding Content
- Update text in `index.html`
- Add more product cards by duplicating `.product-card` elements
- Modify animations in `script.js`

### Adding Images
Replace placeholder backgrounds in CSS:
```css
.feature-image {
    background: url('your-image.jpg');
    background-size: cover;
}
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance

- No external dependencies
- Minimal JavaScript
- Optimized CSS animations
- Fast loading times

## License

MIT License - feel free to use this template for your projects

## Credits

Design inspiration: Apple Inc.
Created with ❤️ for luxury brands

---

**Note**: This is a template website. Replace placeholder content with your actual brand content and images.