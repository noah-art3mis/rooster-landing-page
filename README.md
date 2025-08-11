# Rooster - Recycling App Landing Page

A modern, responsive landing page for the Rooster recycling app, designed to showcase the app's features and encourage downloads.

## 🚀 Features

-   **Responsive Design**: Works perfectly on all devices (desktop, tablet, mobile)
-   **Modern UI/UX**: Clean, eco-friendly design with smooth animations
-   **Interactive Elements**: Hover effects, scroll animations, and smooth scrolling
-   **Mobile-First**: Optimized for mobile users with touch-friendly interactions
-   **SEO Ready**: Semantic HTML structure and meta tags
-   **Fast Loading**: Optimized CSS and minimal JavaScript

## 📱 Sections

1. **Navigation Bar**: Fixed header with logo and navigation links
2. **Hero Section**: Main headline with download buttons and phone mockup
3. **Features**: Four key features with icons and descriptions
4. **How It Works**: Step-by-step process explanation
5. **Download**: Call-to-action section with app store buttons
6. **Footer**: Links, social media, and company information

## 🎨 Design Features

-   **Color Scheme**: Eco-friendly greens (#2E7D32, #4CAF50) with neutral grays
-   **Typography**: Inter font family for modern readability
-   **Icons**: Font Awesome icons for consistent visual elements
-   **Animations**: Smooth transitions, hover effects, and scroll-triggered animations
-   **Phone Mockup**: Interactive app interface preview with scanning animation

## 🛠️ Customization

### Colors

Update the color scheme in `styles.css`:

```css
:root {
    --primary-color: #2e7d32;
    --secondary-color: #4caf50;
    --accent-color: #1b5e20;
    --text-color: #333;
    --light-bg: #f8f9fa;
}
```

### Content

-   Update text content in `index.html`
-   Replace placeholder images with your app screenshots
-   Modify feature descriptions to match your app's capabilities
-   Update download links to point to your actual app store listings

### Logo

Replace the recycle icon with your app's logo:

```html
<div class="nav-logo">
    <img src="path/to/your/logo.png" alt="Rooster Logo" />
    <span>Rooster</span>
</div>
```

## 📁 File Structure

```
rooster/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🚀 Getting Started

1. **Open the landing page**:

    - Double-click `index.html` to open in your browser
    - Or serve it locally using a web server

2. **Customize content**:

    - Edit `index.html` to update text and images
    - Modify `styles.css` to change colors and layout
    - Update `script.js` to add custom functionality

3. **Deploy**:
    - Upload files to your web hosting service
    - Or deploy to platforms like Netlify, Vercel, or GitHub Pages

## 🌐 Browser Support

-   Chrome (latest)
-   Firefox (latest)
-   Safari (latest)
-   Edge (latest)
-   Mobile browsers (iOS Safari, Chrome Mobile)

## 📱 Mobile Features

-   Responsive navigation with hamburger menu
-   Touch-friendly buttons and interactions
-   Optimized layouts for small screens
-   Smooth scrolling and animations

## 🎯 Performance Tips

-   Optimize images before adding them
-   Minify CSS and JavaScript for production
-   Use a CDN for external resources
-   Enable gzip compression on your server

## 🔧 Advanced Customization

### Add Analytics

```html
<!-- Google Analytics -->
<script
    async
    src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"
></script>
<script>
    window.dataLayer = window.dataLayer || [];
    function gtag() {
        dataLayer.push(arguments);
    }
    gtag('js', new Date());
    gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

### Add Contact Form

Create a contact section with a form that submits to your backend or email service.

### Add Testimonials

Include user reviews and ratings to build trust and credibility.

## 📞 Support

For questions or customization help:

-   Check the code comments for guidance
-   Modify the CSS variables for easy color changes
-   Use browser developer tools to test responsive design

## 📄 License

This landing page template is free to use and modify for your recycling app project.

---

**Made with ❤️ for a greener planet**
