# Quick Setup Guide

## 🚀 Quick Start

1. **All files are ready to use!** Simply open `index.html` in a web browser to preview.

2. **For local development**, use a local server:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Or use any local server you prefer
   ```

3. **View the site** at `http://localhost:8000`

## ⚡ Immediate Next Steps

### 1. Replace Placeholder Content (5 minutes)
- [ ] Update contact email: `info@muddyriveropera.org`
- [ ] Update phone number: `(555) 123-4567`
- [ ] Update address in `contact.html`

### 2. Add Your Images (15 minutes)
- [ ] Replace `images/performance-placeholder.jpg` with actual production photos
- [ ] Add sponsor logos to `images/` folder
- [ ] Update image references in HTML files
- [ ] Add gallery photos

### 3. Integrate Third-Party Services (30 minutes)

**Contact Form:**
- Choose a service: Formspree, EmailJS, or Netlify Forms
- Update form handler in `js/main.js` (line ~60-90)
- Test form submission

**Donation Widget:**
- Choose a service: PayPal, Network for Good, GiveLively
- Replace donation placeholder in `donate.html`
- Test donation flow

**Newsletter Signup:**
- Choose a service: Mailchimp, ConvertKit, or EmailOctopus
- Update newsletter handler in `js/main.js` (line ~40-55)
- Test signup form

**Ticket Links:**
- Update "Buy Tickets" links in `tickets.html` and show pages
- Point to your actual ticketing platform

### 4. Update Show Information (20 minutes)
- [ ] Update cast members in show pages
- [ ] Update creative team members
- [ ] Verify performance dates and times
- [ ] Update synopsis text if needed

### 5. Customize Branding (optional)
- [ ] Update colors in `css/style.css` (CSS variables at top)
- [ ] Update social media links in footer
- [ ] Add actual hero background image (optional)

## 📋 Deployment Checklist

Before going live:
- [ ] All placeholder content replaced
- [ ] All images uploaded and working
- [ ] Forms tested and working
- [ ] Ticket links point to correct URLs
- [ ] Donation widget integrated and tested
- [ ] Contact information is accurate
- [ ] Mobile responsiveness tested
- [ ] All links working (no broken links)
- [ ] Browser compatibility tested
- [ ] SEO meta descriptions updated

## 🌐 Deployment Options

### Option 1: Netlify (Easiest - Recommended)
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop your project folder
3. Site is live instantly!
4. Add custom domain if needed

### Option 2: GitHub Pages
1. Create a GitHub repository
2. Upload all files
3. Enable GitHub Pages in repository settings
4. Site available at `username.github.io/repository-name`

### Option 3: Traditional Web Hosting
1. Upload all files via FTP/SFTP
2. Ensure `index.html` is in the root directory
3. Test all pages after upload

## 🔧 Common Issues & Solutions

**Issue:** Images not showing
- **Solution:** Check file paths match exactly (case-sensitive)

**Issue:** Form not submitting
- **Solution:** Ensure form service is properly integrated in `js/main.js`

**Issue:** Mobile menu not working
- **Solution:** Check that `js/main.js` is loaded (check browser console)

**Issue:** Styles not applying
- **Solution:** Clear browser cache, check `css/style.css` path

## 📞 Need Help?

Refer to `README.md` for detailed documentation on:
- File structure
- Content updates
- Customization options
- Maintenance tasks
- Troubleshooting

## ✅ Testing Before Launch

Test these key areas:
1. **Navigation** - All menu links work
2. **Mobile Menu** - Opens and closes properly
3. **Forms** - Contact form submits successfully
4. **Donation** - Donation widget loads correctly
5. **Newsletter** - Signup form works
6. **Tickets** - Ticket links go to correct page
7. **Responsive** - Looks good on mobile, tablet, desktop
8. **Links** - No broken links
9. **Images** - All images load correctly
10. **Performance** - Pages load quickly

---

**You're all set!** Follow these steps and your website will be live in no time.
