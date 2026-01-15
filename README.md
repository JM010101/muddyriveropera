# Muddy River Opera Company Website

A modern, responsive website for Muddy River Opera Company, featuring a clean design, improved usability, and optimized performance.

## 🎯 Project Overview

This website provides a complete online presence for Muddy River Opera Company with all essential pages and functionality:
- Home page with hero section and featured performances
- About page with mission, history, and values
- Season/Performances page with current and past seasons
- Individual show pages for each production
- Tickets page with pricing and purchase options
- Donate page with donation widget integration
- Contact page with contact form
- Media gallery with photos and videos
- Sponsors page with sponsor logos and information

## 📁 File Structure

```
muddyriveropera/
├── index.html                  # Home page
├── about.html                  # About page
├── performances.html           # Season/Performances listing
├── tickets.html                # Tickets page
├── donate.html                 # Donation page
├── contact.html                # Contact page
├── media.html                  # Media gallery
├── sponsors.html               # Sponsors page
├── show-la-traviata.html       # Example show page
├── show-magic-flute.html       # Example show page
├── show-carmen.html            # Example show page
├── css/
│   └── style.css              # Main stylesheet
├── js/
│   └── main.js                # Main JavaScript file
├── images/                     # Image assets (placeholders included)
│   ├── performance-placeholder.jpg
│   ├── gallery-placeholder.jpg
│   ├── about-placeholder.jpg
│   ├── sponsor-placeholder.png
│   └── hero-background.jpg
└── README.md                   # This file
```

## ✨ Features

### Design & UX
- **Modern, clean design** with elegant typography (Playfair Display for headings, Inter for body)
- **Fully responsive** - works perfectly on desktop, tablet, and mobile devices
- **Professional color scheme** - sophisticated dark blues with warm gold accents
- **Intuitive navigation** with sticky header and mobile menu
- **Clear call-to-action buttons** prominently displayed throughout

### Performance
- **Optimized loading** with lazy loading for images
- **Minimal dependencies** - uses only Google Fonts (can be self-hosted)
- **Fast page loads** with optimized CSS and JavaScript
- **SEO-friendly** structure with proper meta tags and semantic HTML

### Functionality
- **Mobile-responsive navigation** with hamburger menu
- **Gallery filtering** on media page
- **Contact form** ready for integration with form services
- **Newsletter signup** ready for integration with email services
- **Smooth scrolling** and interactive elements

## 🚀 Getting Started

### Local Development

1. **Clone or download** this repository
2. **Open `index.html`** in a web browser, or
3. **Use a local server** (recommended):
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```
4. **Navigate to** `http://localhost:8000` in your browser

### Deployment

This website can be deployed to any static hosting service:

#### Options:
- **GitHub Pages** - Free hosting for static sites
- **Netlify** - Free tier with continuous deployment
- **Vercel** - Free hosting with great performance
- **AWS S3 + CloudFront** - Scalable cloud hosting
- **Traditional web hosting** - Upload files via FTP/SFTP

#### Steps for Deployment:
1. **Compress all files** (or use Git for version control)
2. **Upload to your hosting service**
3. **Update configuration** as needed (see Configuration section below)
4. **Test all pages** after deployment

## ⚙️ Configuration & Customization

### 1. Update Contact Information

Search for these placeholders throughout the HTML files and replace with actual information:
- `info@muddyriveropera.org` - Update email addresses
- `(555) 123-4567` - Update phone numbers
- `123 Opera Street, City, State 12345` - Update address (in contact.html)

### 2. Integrate Donation Widget

Edit `donate.html` and replace the donation widget placeholder with your actual donation platform code:

**Options:**
- **PayPal Donate Button** - Generate button code from PayPal
- **Network for Good** - Embed their donation form
- **GiveLively / Every.org** - Use their embed code
- **Custom Form** - Integrate with your payment processor

**Location:** Look for `.donation-widget-placeholder` section in `donate.html`

### 3. Integrate Contact Form

Edit `contact.html` and update the form action in the JavaScript (`js/main.js`):

**Options:**
- **Formspree** - Simple form handling service
- **EmailJS** - Client-side email service
- **Netlify Forms** - If hosting on Netlify
- **Custom Backend API** - PHP, Node.js, etc.

**Location:** See `contactForm` handler in `js/main.js`

### 4. Integrate Newsletter Signup

Edit `js/main.js` and update the newsletter form handler:

**Options:**
- **Mailchimp** - Popular email marketing service
- **ConvertKit** - Creator-friendly email service
- **EmailOctopus** - Affordable alternative
- **Custom API** - Your own newsletter service

**Location:** See `newsletterForm` handler in `js/main.js`

### 5. Update Ticket Links

Edit `tickets.html` and update the "Buy Tickets Online" link to point to your actual ticketing platform:
- Ticketmaster
- Eventbrite
- Your venue's ticketing system
- Custom ticketing solution

**Location:** Look for `.tickets-cta` section in `tickets.html`

### 6. Add Images

Replace placeholder images in the `images/` folder:
- `performance-placeholder.jpg` - Production photos
- `gallery-placeholder.jpg` - Gallery images
- `about-placeholder.jpg` - About page image
- `sponsor-placeholder.png` - Sponsor logos
- `hero-background.jpg` - Hero section background (optional)

**Recommended image sizes:**
- Performance images: 1200x800px
- Gallery images: 1000x750px
- Sponsor logos: 400x200px (or maintain aspect ratio)
- Hero background: 1920x1080px

**Image optimization tips:**
- Use WebP format for better compression
- Compress images with tools like TinyPNG or ImageOptim
- Maintain reasonable file sizes (under 500KB per image)

### 7. Update Show Information

Edit individual show pages (`show-*.html`) and update:
- Cast members
- Creative team members
- Performance dates and times
- Synopsis text
- Images

### 8. Update Sponsor Logos

Edit `sponsors.html` and replace placeholder sponsor logos with actual sponsor images. Update the sponsor tiers (Major, Supporting, Community Partners) as needed.

### 9. Customize Colors

Edit CSS variables in `css/style.css` (lines at the top):

```css
:root {
    --primary-color: #1a1a2e;      /* Main dark color */
    --secondary-color: #16213e;    /* Secondary dark color */
    --accent-color: #c49b6a;       /* Gold/accent color */
    /* ... other variables */
}
```

### 10. Update Social Media Links

Search for social media links in the footer and navigation, and update with your actual social media URLs.

## 📝 Content Updates Guide

### Adding a New Show

1. **Create a new show page:**
   - Copy `show-la-traviata.html` as a template
   - Rename to `show-[show-name].html`
   - Update all show-specific information

2. **Add to performances page:**
   - Edit `performances.html`
   - Add a new `.performance-item` or `.performance-card`
   - Update performance listing

3. **Update homepage:**
   - Edit `index.html`
   - Add to `.performances-grid` section
   - Update featured performances

### Updating Season Information

- Edit `performances.html`
- Update current season shows
- Update past seasons section

### Adding Gallery Images

1. Add images to `images/` folder
2. Edit `media.html`
3. Add new `.gallery-item` elements with proper `data-category` attributes

### Updating Bios

If you add a team/bios section:
1. Create `bios.html` or add to `about.html`
2. Follow existing card/listing structure

## 🔧 Maintenance Tasks

### Monthly Tasks
- [ ] Check all links are working
- [ ] Update upcoming performance information
- [ ] Review and update sponsor logos
- [ ] Check contact form submissions
- [ ] Update social media links if changed
- [ ] Review website analytics

### Seasonal Tasks
- [ ] Update season information
- [ ] Create new show pages for upcoming season
- [ ] Archive past season shows
- [ ] Update media gallery with new photos
- [ ] Review and optimize images
- [ ] Update copyright year in footer

### Technical Maintenance
- [ ] Test website on different browsers
- [ ] Test mobile responsiveness
- [ ] Check page load speeds
- [ ] Review and fix any broken links
- [ ] Update meta descriptions for SEO
- [ ] Backup website files

## 🔍 SEO Optimization

The website includes basic SEO optimization:
- Meta descriptions on all pages
- Semantic HTML structure
- Proper heading hierarchy (H1, H2, H3)
- Alt text placeholders for images (update with actual descriptions)

### Additional SEO Recommendations:
1. **Update all image alt text** with descriptive text
2. **Submit sitemap** to Google Search Console (create XML sitemap)
3. **Set up Google Analytics** for tracking
4. **Add Open Graph tags** for social media sharing
5. **Create robots.txt** file if needed
6. **Add structured data** (JSON-LD) for events/performances

## 📱 Browser Support

The website is tested and works on:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🐛 Troubleshooting

### Images not loading
- Check image file paths
- Ensure images are in the `images/` folder
- Check file names match exactly (case-sensitive)

### Forms not working
- Ensure form service is properly integrated
- Check JavaScript console for errors
- Verify API endpoints are correct

### Navigation menu not working on mobile
- Check JavaScript file is loaded
- Verify `js/main.js` is in the correct location
- Check browser console for JavaScript errors

### Styles not applying
- Clear browser cache
- Check CSS file path is correct
- Verify `css/style.css` is in the correct location

## 📞 Support & Questions

For questions about the website or assistance with updates:
- Review this README for common tasks
- Check the code comments in HTML/CSS/JS files
- Contact your web developer/freelancer for custom modifications

## 📄 License

This website was created for Muddy River Opera Company. All rights reserved.

---

**Version:** 1.0.0  
**Last Updated:** 2024  
**Maintained by:** Muddy River Opera Company
