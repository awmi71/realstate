# EXP Realty LLC - Professional Real Estate Website

A modern, responsive single-page website for EXP Realty LLC, built with HTML5, Tailwind CSS, and vanilla JavaScript.

## Features

- **Responsive Design**: Perfectly optimized for desktop, tablet, and mobile devices
- **Sticky Navigation**: Header stays visible while scrolling with smooth transitions
- **Mobile Menu**: Three-dot hamburger menu with floating dropdown for mobile devices
- **Animated Logo**: Subtle bounce animation for brand recognition
- **Hero Section**: Eye-catching landing area with recommendation badge and dual CTA buttons
- **Stats Grid**: 4-column responsive grid showcasing company achievements
- **About Section**: Professional company overview with decorative orange underline
- **Smooth Scrolling**: Seamless navigation between sections
- **Interactive Elements**: Hover effects, animations, and micro-interactions

## Technology Stack

- **HTML5**: Semantic markup for accessibility and SEO
- **Tailwind CSS**: Utility-first CSS framework via CDN
- **JavaScript (ES6+)**: Modern vanilla JavaScript for interactions
- **Google Fonts**: Plus Jakarta Sans for typography
- **Google Material Symbols**: Consistent iconography

## Color Palette

- **Primary Orange**: #E67E22
- **Dark Orange**: #D35400
- **White/Off-white**: #FFFFFF, #F9FAFB
- **Gray Scale**: Various shades for text and backgrounds

## File Structure

```
exp-realty-landing/
├── index.html          # Main HTML file
├── style.css           # Custom CSS styles and animations
├── script.js           # JavaScript functionality
├── assets/             # Images and media files
└── README.md           # Project documentation
```

## Deployment

### GitHub Pages

1. Push the code to a GitHub repository
2. Go to repository Settings > Pages
3. Select "Deploy from a branch"
4. Choose the main branch and root folder
5. Your site will be available at `https://username.github.io/repository-name`

### Manual Deployment

1. Upload all files to your web server
2. Ensure the server supports static file hosting
3. Access `index.html` as your main page

## Customization

### Brand Colors
Edit the CSS variables in `style.css` to change the color scheme:

```css
:root {
    --primary-orange: #E67E22;
    --dark-orange: #D35400;
    /* Add more colors as needed */
}
```

### Company Information
Update the following in `index.html`:
- Company name in the header and footer
- Contact information
- Statistics numbers
- About section content

### Adding Images
Place images in the `assets/` folder and reference them in your HTML:

```html
<img src="assets/your-image.jpg" alt="Description" class="responsive-class">
```

## Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Performance

- Optimized for fast loading with CDN resources
- Minimal JavaScript for quick initialization
- Lazy loading support for images
- Debounced scroll events for better performance

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

For questions or support regarding this website:
- Email: info@exprealtywindsurf.com
- Phone: (555) 123-4567

---

**EXP Realty LLC** - Your Trusted Windsurf Real Estate Partner
