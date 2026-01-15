# Bryan Walsh - Journalist Portfolio

A clean, professional portfolio website showcasing journalism work and publications.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional design focused on readability
- **Portfolio Showcase**: Display your published articles with categories and descriptions
- **Contact Section**: Multiple contact methods and a contact form
- **Smooth Animations**: Subtle animations and transitions for better user experience

## Structure

- `index.html` - Main HTML file with semantic structure
- `styles.css` - All styling with CSS variables for easy customization
- `script.js` - Interactive features (mobile menu, smooth scrolling, animations)

## Customization Guide

### Update Your Information

1. **About Section** (in `index.html`):
   - Replace the placeholder bio text with your own background
   - Add your profile photo by replacing the SVG placeholder
   - Update your journalism experience and interests

2. **Portfolio Articles** (in `index.html`):
   - Update each article card with your actual published work
   - Change article titles, descriptions, categories, and publication info
   - Add links to your published articles
   - Replace placeholder images with article images or remove them

3. **Contact Information** (in `index.html`):
   - Update email address
   - Update social media links (Twitter, LinkedIn)
   - Add or remove contact methods as needed

### Customize Colors

Edit the CSS variables in `styles.css` (lines 11-21):

```css
--primary-color: #2c3e50;    /* Main dark color */
--secondary-color: #3498db;   /* Accent blue */
--accent-color: #e74c3c;      /* Button/highlight color */
```

### Deploy Your Site

**GitHub Pages:**
1. Push to GitHub
2. Go to Settings > Pages
3. Select branch and save

**Netlify:**
1. Drag and drop the folder to Netlify
2. Your site is live!

**Other Hosting:**
- Upload all files to any web hosting service
- No build process required - it's pure HTML/CSS/JS

## Contact Form

The contact form currently shows an alert. To make it functional, integrate with:
- [Formspree](https://formspree.io/)
- [EmailJS](https://www.emailjs.com/)
- Your own backend API

## Browser Support

Works on all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

## License

Feel free to use and modify this template for your personal portfolio.