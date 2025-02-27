# LFP Battery Pack - Premium Blogger Template

A professional, SEO-optimized Blogger template designed for electric vehicle battery products. Features a modern, responsive design with optimized user experience and conversion-focused layout.

![LFP Battery Pack Template Preview](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjwTJr9eCH9LdUKN3p1Dt7TRbsTl-S-XWB3SShz4YdwRE2wydFRfv8lb50x6TeSn2cSwga2fRJZm7jO3TM2hGJNXUC8w6fvdQdeZJxk5l9-Q5cYjhKdzZvDFCKPE8XzCS9kqAJJKYhjXsWcK9o6NgX3AashQr_clU9AFUi7gdnGX5yB6808ViKeYXilpXUS/s1600/logo-header.png)

## Table of Contents
1. [Features](#features)
2. [Installation](#installation)
3. [Configuration](#configuration)
4. [Content Management](#content-management)
5. [SEO Optimization](#seo-optimization)
6. [Customization](#customization)
7. [Video Management](#video-management)
8. [FAQ Management](#faq-management)
9. [Troubleshooting](#troubleshooting)
10. [Support](#support)

## Features
- 🎨 Modern, responsive design
- 📱 Mobile-first approach
- 🚀 SEO optimized structure
- 🎥 YouTube video integration
- 📊 Product specifications section
- ❓ FAQ section with accordion
- 🖼️ Image gallery with lightbox
- 📞 Contact form integration
- 🔍 Schema.org markup
- 🎯 Conversion-optimized layout

## Installation
1. **Create New Blog**
   - Go to [Blogger.com](https://www.blogger.com)
   - Sign in with your Google account
   - Click "New Blog"
   - Enter blog name and address

2. **Install Template**
   - In Blogger Dashboard, go to "Theme"
   - Click "⋮" (three dots) > "Edit HTML"
   - Delete all existing code
   - Copy all content from template.xml
   - Click "Save theme"
   - Confirm when prompted

3. **Initial Setup**
   - Replace default logo
   - Update contact information
   - Configure social media links
   - Set up product images

## Configuration

### Domain Setup
1. **Custom Domain Configuration**
   - Go to Settings > "Custom domain"
   - Enter your domain
   - Follow DNS verification steps
   - Wait 24-48 hours for DNS propagation

2. **SSL Configuration**
   - Enable HTTPS in Blogger settings
   - Ensure all assets use HTTPS URLs

### Social Media Links
```html
<div class='social-links'>
    <a href='YOUR_FACEBOOK_URL' class='social-link'>
        <span class='material-icons'>facebook</span>
    </a>
    <!-- Add more social links -->
</div>
```

## Content Management

### Product Information
1. **Update Hero Section**
```html
<h1 class='hero-title'>Your Product Name</h1>
<p class='hero-subtitle'>Your product description...</p>
```

2. **Technical Specifications**
```html
<div class='spec-item'>
    <span class='material-icons'>battery_charging_full</span>
    <div class='spec-content'>
        <h3>Voltage</h3>
        <p>70.4V</p>
    </div>
</div>
```

3. **Product Images**
- Upload images to Blogger
- Get image URL
- Replace in template:
```html
<img src='YOUR_IMAGE_URL' alt='Description'/>
```

## SEO Optimization

### Meta Tags
1. **Basic Meta Tags**
```html
<meta name='description' content='Your description'/>
<meta name='keywords' content='your, keywords'/>
```

2. **Open Graph Tags**
```html
<meta property='og:title' content='Your Title'/>
<meta property='og:description' content='Your Description'/>
```

### Schema.org Markup
```html
<script type='application/ld+json'>
{
  "@context": "https://schema.org/",
  "@type": "Product",
  "name": "Your Product Name"
}
</script>
```

## Video Management

### Adding New Videos
1. Create new post
2. Add label "Video"
3. Use format:
```
Video title: [Your Video Title]
Video: [YouTube URL]
```

### Video Rules
- Regular videos: Use youtube.com/watch?v=VIDEO_ID
- YouTube Shorts: 
  1. Click "Share" button on the Shorts video
  2. Click "Copy link"
  3. Use the full URL format: https://youtube.com/shorts/VIDEO_ID?si=PARAMETER
  4. Example: https://youtube.com/shorts/w91XiOTWK3U?si=yzbPi7N5vcLZtHYG
- Ensure videos are public
- Thumbnails auto-fetch from YouTube

**Note**: Always use the complete Shorts URL from the share button to ensure proper video embedding and tracking.

## FAQ Management

### Adding FAQ Items
```html
<div class='faq-item'>
    <div class='faq-question' onclick='toggleFaq(this)'>
        <h3>Your Question</h3>
        <span class='material-icons'>expand_more</span>
    </div>
    <div class='faq-answer'>
        <p>Your Answer</p>
    </div>
</div>
```

## Customization

### Color Scheme
Modify in template CSS:
```css
:root {
    --primary-color: #your-color;
    --secondary-color: #your-color;
}
```

### Typography
```css
:root {
    --font-primary: 'Your-Font', sans-serif;
    --font-secondary: 'Your-Font', sans-serif;
}
```

## Troubleshooting

### Common Issues

1. **Images Not Loading**
   - Ensure image URLs are correct
   - Check if images are public
   - Verify HTTPS URLs

2. **Videos Not Playing**
   - Check video privacy settings
   - Verify video ID format
   - Ensure proper embedding permissions

3. **Mobile Menu Issues**
   - Clear browser cache
   - Check JavaScript console
   - Verify touch events

### Performance Optimization

1. **Image Optimization**
   - Use WebP format
   - Implement lazy loading
   - Optimize image dimensions

2. **Code Optimization**
   - Minify CSS/JS
   - Remove unused code
   - Implement caching

## Support
For technical support:

### GitHub Issues
1. Visit our GitHub repository: [LFP Battery Pack Template](https://github.com/hacong86/lfp-battery-template)
2. Click on "Issues" tab
3. Click "New Issue" button
4. Fill in:
   - Title: Brief description of your issue
   - Description: Detailed explanation with screenshots if possible
   - Labels: Choose appropriate label (bug, enhancement, question)
5. Click "Submit new issue"

### Direct Contact
- Email: support@yourdomain.com
- Documentation: [GitHub Wiki](https://github.com/hacong86/lfp-battery-template/wiki)

### Quick Support Links
- [Report a Bug](https://github.com/hacong86/lfp-battery-template/issues/new?labels=bug)
- [Request a Feature](https://github.com/hacong86/lfp-battery-template/issues/new?labels=enhancement)
- [Ask a Question](https://github.com/hacong86/lfp-battery-template/issues/new?labels=question)

## License
This template is licensed under ThemeForest Standard License.

---
© 2024 LFP Battery Pack Template. All rights reserved. 