# UMBA - Digital Banking Website

A modern, responsive replica of the UMBA.com digital banking website. Built with pure HTML, CSS, and JavaScript.

## Features

- 🎨 Modern and clean design
- 📱 Fully responsive (mobile, tablet, desktop)
- ⚡ Smooth animations and transitions
- 🎯 Interactive UI elements
- 🔒 Security-focused messaging
- 💳 Banking features showcase
- 📊 Animated statistics
- 🌟 Customer testimonials

## Sections

1. **Navigation Bar** - Fixed header with smooth scrolling
2. **Hero Section** - Eye-catching landing area with CTA form
3. **Features Section** - Showcase of banking services
4. **How It Works** - Simple 3-step process
5. **Statistics** - Animated counters
6. **Testimonials** - Customer reviews
7. **CTA Section** - Call-to-action with app store links
8. **Footer** - Comprehensive site links

## Getting Started

### Prerequisites

No dependencies required! This is a pure HTML/CSS/JavaScript website.

### Installation

1. Clone or download this repository
2. Open `index.html` in your web browser
3. That's it! The website is ready to use.

### For Development

If you want to serve the files locally with a simple HTTP server:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## File Structure

```
UMBA/
├── index.html      # Main HTML file
├── styles.css      # All styles and responsive design
├── script.js       # JavaScript for interactivity
└── README.md       # This file
```

## Customization

### Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #000000;
    --secondary-color: #10B981;
    --accent-color: #3B82F6;
    /* ... more variables */
}
```

### Content

- Edit text content directly in `index.html`
- Modify sections by editing the corresponding HTML elements
- Update images by replacing the placeholder content

### Styling

- All styles are in `styles.css`
- Responsive breakpoints are set at 968px and 640px
- Animations can be adjusted in the CSS animations section

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Features Implemented

✅ Responsive navigation with mobile menu
✅ Smooth scrolling
✅ Form validation and submission handling
✅ Animated counters for statistics
✅ Intersection Observer for scroll animations
✅ Parallax effects
✅ Hover effects on cards
✅ Mobile-first responsive design

## License

This is a replica project for educational purposes.

## Credits

Inspired by UMBA.com - Digital Banking Platform

---

**Note**: This is a frontend replica. For a production banking website, you would need:
- Backend server
- Database integration
- Payment processing
- Authentication system
- API integrations
- Security measures
- Compliance with financial regulations

