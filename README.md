# Classic Bags Portfolio Website

A clean, modern portfolio website for showcasing premium bags and accessories brand.

## 🌐 Live Site

**https://dhinakarsivakumar.github.io/cb/**

> 🚀 **Automated Deployment**: This site automatically deploys to GitHub Pages via GitHub Actions whenever changes are pushed to the main branch.

## Features

- **Responsive Design**: Mobile-friendly layout that works on all devices
- **Product Showcase**: Image gallery for handbags, travel bags, and tote bags
- **Design Gallery**: Custom bag designs display
- **Contact Integration**: WhatsApp, phone, and email contact options
- **Smooth Animations**: Professional transitions and scroll effects
- **No Backend Required**: Pure HTML, CSS, and JavaScript
- **Automated Deployment**: GitHub Actions workflow for continuous deployment

## File Structure

```
classic-bags/
├── index.html          # Main HTML file
├── styles.css          # Complete styling with premium color palette
├── script.js           # Interactive JavaScript functionality
└── README.md           # This file
```

## Color Palette

- **Primary Brown**: #8B4513
- **Secondary Brown**: #A0522D
- **Light Brown**: #DEB887
- **Beige**: #F5E6D3
- **Cream**: #FFF8F0

## Sections

1. **Hero Section**: Brand introduction with call-to-action buttons
2. **About Us**: Family business story and craftsmanship details
3. **Product Showcase**: Filterable gallery of bag collections
4. **Design Gallery**: Custom designs and exclusive creations
5. **Contact Section**: Multiple contact methods and contact form
6. **Footer**: Business information and contact details

## Interactive Features

- **Mobile Navigation**: Hamburger menu for mobile devices
- **Product Filtering**: Category-based product filtering
- **Contact Form**: Sends messages directly to WhatsApp
- **Smooth Scrolling**: Navigation links with smooth scroll behavior
- **Scroll Animations**: Elements animate as they come into view
- **WhatsApp Integration**: Floating WhatsApp button for quick contact

## Customization

### Updating Contact Information

Edit the following in `index.html`:

```html
<!-- WhatsApp links -->
<a href="https://wa.me/YOUR_NUMBER" class="whatsapp-float" target="_blank">
<a href="https://wa.me/YOUR_NUMBER" class="contact-link" target="_blank">

<!-- Phone links -->
<a href="tel:+YOUR_PHONE_NUMBER" class="contact-link">

<!-- Email links -->
<a href="mailto:your@email.com" class="contact-link">
```

Update the WhatsApp number in `script.js`:

```javascript
const whatsappNumber = 'YOUR_NUMBER'; // Replace with actual number
```

### Adding Product Images

Replace placeholder divs with actual images:

```html
<div class="product-image">
    <img src="path/to/your/image.jpg" alt="Product Name">
</div>
```

### Updating Brand Information

Edit the brand name, tagline, and descriptions in `index.html` sections.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance

- Optimized CSS with efficient selectors
- Minimal JavaScript for fast loading
- Responsive images ready
- Smooth animations using CSS transforms

## Hosting

This website is currently hosted on:

- **GitHub Pages**: Free static hosting with automated deployment via GitHub Actions

### Current Deployment

This repository includes a GitHub Actions workflow (`.github/workflows/deploy.yml`) that automatically deploys the site to GitHub Pages whenever changes are pushed to the main branch.

**To publish or update the site:**
1. Merge changes to the `main` branch
2. GitHub Actions automatically builds and deploys
3. Site updates appear at `https://dhinakarsivakumar.github.io/cb/` within 1-2 minutes

**First-time setup:**
1. Go to repository Settings > Pages
2. Under "Build and deployment", select "GitHub Actions" as the source
3. The workflow will automatically deploy on the next push to main

See [PUBLISHING.md](PUBLISHING.md) for detailed deployment instructions.

## Fonts Used

- **Playfair Display**: Elegant serif font for headings
- **Inter**: Clean sans-serif font for body text

Both fonts are loaded from Google Fonts for optimal performance.

## SEO Features

- Semantic HTML5 structure
- Meta descriptions and titles
- Proper heading hierarchy
- Alt text ready for images
- Mobile-responsive design

## Security

- No external dependencies except Google Fonts
- HTTPS ready
- No user data storage
- Safe contact form integration

## License

This project is open source and available under the MIT License.

---

**Classic Bags** - Timeless elegance, crafted with love
