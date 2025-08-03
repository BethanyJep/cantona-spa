# Cantona Spa - Landing Page

A beautiful, modern landing page for your salon and spa business specializing in dreadlocks, sister locks, and beauty services.

## Features

Modern Design: Clean, professional layout with spa-inspired aesthetics
Fully Responsive: Works perfectly on desktop, tablet, and mobile devices
WhatsApp Integration: Direct booking through WhatsApp with pre-filled messages
Smooth Animations: Engaging scroll animations and hover effects
Fast Loading: Optimized for performance with lazy loading
Service Showcase: Beautiful grid layout for all your services
Clear Pricing: Organized pricing tables for transparencyProfessional Branding: Cohesive color scheme and typography

## Services Included

### Hair Services
Dreadlocks: Installation, maintenance, and styling
Sister Locks: Precision installation and retightening

### Beauty Services
Manicure & Pedicure: Classic and gel options
Facials: Deep cleansing, hydrating, and anti-aging treatments
Eyebrow Services: Shaping, trimming, and tinting
Additional Services: Hair washing, scalp treatments, makeup

## Customization Guide

### 1. Update Contact Information

In `index.html`, update the following:

```html
<!-- Phone number -->
<p>+1 (555) 123-4567</p>

<!-- Email -->
<p>info@cantonaspa.com</p>

<!-- Address -->
<p>123 Beauty Street<br>Your City, State 12345</p>

<!-- Business Hours -->
<p>Mon-Fri: 9AM-7PM<br>Sat: 9AM-6PM<br>Sun: 10AM-5PM</p>
```

In `script.js`, update the WhatsApp phone number:

```javascript
const phoneNumber = '1234567890'; // Replace with your WhatsApp number (without + or spaces)
```

### 2. Customize Pricing

In `index.html`, update the pricing tables in the `#pricing` section:

```html
<div class="price-item">
    <span>Service Name</span>
    <span>$XX</span>
</div>
```

### 3. Add Your Logo

Replace the text logo in the navigation:

```html
<div class="nav-logo">
    <img src="your-logo.png" alt="Cantona Spa" height="40">
</div>
```

Then update the CSS:

```css
.nav-logo img {
    height: 40px;
    width: auto;
}
```

### 4. Add Real Images

Replace the placeholder images with your actual photos:

1. Add your images to the project folder
2. Update the hero section:

```html
<div class="hero-image">
    <img src="your-hero-image.jpg" alt="Cantona Spa Interior">
</div>
```

3. Add service images to each service card:

```html
<div class="service-image">
    <img src="dreadlocks-image.jpg" alt="Dreadlocks Service">
</div>
```

### 5. Customize Colors

In `styles.css`, update the main brand color:

```css
/* Change #8B5A5A to your brand color */
:root {
    --primary-color: #8B5A5A;
    --primary-hover: #7a4d4d;
    --primary-light: #a67474;
}
```

Then replace all instances of `#8B5A5A` with `var(--primary-color)`.

### 6. Update Business Information

In `index.html`, customize:

- Business name in the title and navigation
- Service descriptions
- About section content
- Contact information

### 7. Social Media Links

Update the social media links in the footer:

```html
<a href="https://facebook.com/your-page" class="social-icon">
    <i class="fab fa-facebook"></i>
</a>
<a href="https://instagram.com/your-profile" class="social-icon">
    <i class="fab fa-instagram"></i>
</a>
```

### 8. SEO Optimization

Update the meta tags in the `<head>` section:

```html
<meta name="description" content="Professional dreadlocks, sister locks, and beauty services at Cantona Spa. Book your appointment today!">
<meta name="keywords" content="dreadlocks, sister locks, manicure, pedicure, facials, beauty salon, spa">
<meta property="og:title" content="Cantona Spa - Expert Hair & Beauty Services">
<meta property="og:description" content="Transform your look with our specialized services">
<meta property="og:image" content="your-og-image.jpg">
```

## WhatsApp Integration

The website includes automatic WhatsApp booking integration. When customers click "Book on WhatsApp":

1Service-specific booking: Sends a pre-filled message with the service name and price
2General booking: Opens a general inquiry message
3Mobile-optimized: Works seamlessly on mobile devices

### WhatsApp Message Format

Each booking button sends a professionally formatted message:

```
Hi Cantona Spa! 👋

I'd like to book an appointment for:
Service: [Service Name]
Price: [Price Range]

Please let me know your available times. Thank you!
```

## File Structure

```
cantona-spa/
├── index.html          # Main HTML file
├── styles.css          # All styling
├── script.js          # JavaScript functionality
└── README.md          # This file
```

## Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## Performance Features

Smooth scrolling: Native CSS scroll behavior
Lazy loading: Images load only when needed
Optimized animations: GPU-accelerated transforms
Minimal JavaScript: Fast loading and execution
Responsive images: Optimized for different screen sizes

## Getting Started

1Download all files to your computer
2Customize the content (see customization guide above)
3Test the website by opening `index.html` in your browser
4Upload to your web hosting service
5Update the WhatsApp phone number to start receiving bookings!

## Support

For questions about customizing this website:

1. Check this README file first
2. Test changes in a web browser
3. Make sure to backup your files before major changes

## License

This website template is created for Cantona Spa. Feel free to modify and use it for your business.

---

Ready to launch your beautiful spa website? Start customizing today! 🌟
