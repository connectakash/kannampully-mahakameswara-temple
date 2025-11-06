# 🕉️ KANNAMPULLY MAHAKAMESWARA TEMPLE Website

A beautiful, modern, and responsive website template for temples and religious institutions.

## ✨ Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean and elegant design with smooth animations
- **Multiple Sections**:
  - Hero section with captivating background
  - About section with temple history and features
  - Services section with daily prayer timings
  - Events calendar for upcoming celebrations
  - Photo gallery
  - Donation form
  - Contact form with temple information
- **Interactive Elements**:
  - Smooth scrolling navigation
  - Mobile-friendly hamburger menu
  - Scroll-to-top button
  - Active navigation highlighting
  - Scroll animations for content
  - Interactive forms

## 🚀 Quick Start

1. **Download or Clone the Repository**
   ```bash
   git clone <repository-url>
   cd SampleWebsite
   ```

2. **Open the Website**
   - Simply open `index.html` in your web browser
   - No build process or dependencies required!

3. **Customize the Content**
   - Edit `index.html` to update text, timings, events, and contact information
   - Modify `styles.css` to change colors, fonts, and styling
   - Adjust `script.js` for custom interactions

## 📁 File Structure

```
SampleWebsite/
├── index.html          # Main HTML file
├── styles.css          # All styling and responsive design
├── script.js           # Interactive functionality
└── README.md          # Documentation (this file)
```

## 🎨 Customization Guide

### Changing Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #dc143c;      /* Main red color (Crimson) */
    --secondary-color: #8b0000;     /* Dark red accent */
    --accent-color: #ff4444;        /* Bright red highlights */
    /* ... modify as needed */
}
```

### Updating Temple Information

1. **Temple Name**: Update in `index.html` (search for "KANNAMPULLY MAHAKAMESWARA TEMPLE")
2. **Contact Details**: Edit the Contact section in `index.html`
3. **Prayer Timings**: Modify the Services section
4. **Events**: Update the Events section with your temple's calendar

### Adding Real Images

Replace the placeholder emojis with actual images:

1. Add your images to an `images/` folder
2. In `index.html`, update the gallery items:
   ```html
   <div class="gallery-item">
       <img src="images/your-image.jpg" alt="Description">
   </div>
   ```
3. Update the hero background in `styles.css`:
   ```css
   .hero {
       background: url('images/hero-image.jpg') center/cover;
   }
   ```

### Setting Up Forms

The forms currently show demo alerts. To make them functional:

1. **Using a Form Service** (Easy):
   - Sign up for services like Formspree, Netlify Forms, or Google Forms
   - Update the form `action` attribute
   - Example with Formspree:
     ```html
     <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
     ```

2. **Using Backend Server** (Advanced):
   - Set up a backend server (Node.js, PHP, etc.)
   - Send form data via AJAX to your server
   - Process donations through payment gateways (Stripe, PayPal, etc.)

## 🌐 Deployment

### Option 1: GitHub Pages (Free)
1. Create a GitHub repository
2. Push your code
3. Enable GitHub Pages in repository settings
4. Your site will be live at `https://yourusername.github.io/repository-name`

### Option 2: Netlify (Free)
1. Create account at [Netlify](https://netlify.com)
2. Drag and drop your folder
3. Your site is live instantly!

### Option 3: Vercel (Free)
1. Create account at [Vercel](https://vercel.com)
2. Import your repository
3. Deploy with one click

### Option 4: Traditional Web Hosting
1. Purchase hosting from providers like Bluehost, HostGator, etc.
2. Upload files via FTP
3. Access through your domain

## 🔧 Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📱 Responsive Breakpoints

- Desktop: > 968px
- Tablet: 768px - 968px
- Mobile: < 768px
- Small Mobile: < 480px

## ⚡ Performance Tips

1. **Optimize Images**:
   - Use WebP format for better compression
   - Resize images to appropriate dimensions
   - Use lazy loading for images below the fold

2. **Minify Files**:
   - Use tools to minify CSS and JavaScript for production
   - Consider using a CDN for faster loading

3. **Add Caching**:
   - Configure browser caching in your hosting settings

## 🙏 Donation Integration

To accept real donations, integrate with:

- **Stripe**: [https://stripe.com](https://stripe.com)
- **PayPal**: [https://paypal.com](https://paypal.com)
- **Razorpay** (India): [https://razorpay.com](https://razorpay.com)
- **Square**: [https://squareup.com](https://squareup.com)

## 📧 Contact Form Integration

Free form services:
- **Formspree**: [https://formspree.io](https://formspree.io)
- **Netlify Forms**: Built-in with Netlify hosting
- **EmailJS**: [https://emailjs.com](https://emailjs.com)

## 🎯 SEO Optimization

1. **Update Meta Tags** in `index.html`:
   ```html
   <meta name="description" content="Your temple description">
   <meta name="keywords" content="temple, worship, prayers">
   ```

2. **Add Open Graph Tags** for social sharing:
   ```html
   <meta property="og:title" content="KANNAMPULLY MAHAKAMESWARA TEMPLE">
   <meta property="og:description" content="Your description">
   <meta property="og:image" content="link-to-image.jpg">
   ```

3. **Create sitemap.xml** and submit to Google Search Console

## 📝 License

This template is free to use for religious and non-profit organizations. Feel free to customize it for your temple's needs.

## 🤝 Support

For questions or customization help, you can:
- Modify the code to suit your needs
- Hire a web developer for advanced customizations
- Use online resources and tutorials for web development

## 🌟 Features to Add (Optional)

Consider adding these features for enhanced functionality:

- [ ] Event registration system
- [ ] Online booking for special pujas
- [ ] Member login/portal
- [ ] Blog/News section
- [ ] Multilingual support
- [ ] Live streaming integration
- [ ] Newsletter subscription
- [ ] Social media feeds
- [ ] Google Maps integration
- [ ] Calendar with iCal support

## 📍 Updating Google Maps Location

The website includes a Google Maps section in the footer (4th column)! To update it with your temple's actual location:

### Step 1: Get Your Embed Code
1. Go to [Google Maps](https://www.google.com/maps)
2. Search for your temple: "Kannampully Mahakameswara Temple"
3. Click the **Share** button
4. Select the **Embed a map** tab
5. Choose your preferred size (Medium recommended)
6. Copy the iframe code

### Step 2: Update the Website
1. Open `index.html`
2. Find the `<iframe>` tag in the footer (around line 375-383)
3. Replace the entire `src="..."` URL with your copied embed URL
4. Save and refresh!

**Example:**
```html
<iframe 
    src="YOUR_GOOGLE_MAPS_EMBED_URL_HERE"
    width="100%" 
    height="250" 
    style="border:0; border-radius: 8px;" 
    allowfullscreen="" 
    loading="lazy">
</iframe>
```

The footer is designed with 4 columns on desktop:
1. Temple info & logo
2. Quick links
3. Social media
4. Google Maps location

---

**May this website serve your temple community well! 🙏**

For technical assistance or custom development, consider consulting with a web developer familiar with modern web technologies.

