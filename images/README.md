# Images Directory

This directory should contain the following images for the Muddy River Opera website:

## Required Images

### Performance Images
- `performance-placeholder.jpg` - Production photos for shows
  - Recommended size: 1200x800px
  - Used on: Home page, Performances page, Individual show pages

### Gallery Images
- `gallery-placeholder.jpg` - Photos for the media gallery
  - Recommended size: 1000x750px
  - Used on: Media gallery page

### About Page Image
- `about-placeholder.jpg` - Image for the About page
  - Recommended size: 800x600px
  - Used on: About page, Home page (about preview section)

### Sponsor Logos
- `sponsor-placeholder.png` - Logo images for sponsors
  - Recommended size: Varies (maintain aspect ratio, max 400x200px)
  - Used on: Sponsors page
  - Note: Add multiple sponsor logo files as needed (sponsor-1.png, sponsor-2.png, etc.)

### Hero Background (Optional)
- `hero-background.jpg` - Background image for hero section
  - Recommended size: 1920x1080px
  - Used on: Home page hero section
  - Note: This is optional - the hero section works without it

## Image Optimization Tips

1. **Format**: Use JPEG for photos, PNG for logos with transparency
2. **Compression**: Optimize images to reduce file size (aim for under 500KB per image)
3. **Tools**: Use tools like:
   - TinyPNG / TinyJPG (online)
   - ImageOptim (Mac)
   - Squoosh (online)
   - Photoshop "Save for Web"

4. **WebP Format**: For better performance, consider using WebP format and updating HTML accordingly

## Adding Images

1. Add your actual image files to this directory
2. Replace the placeholder filenames in the HTML files with your actual image filenames
3. Update alt text in HTML for accessibility and SEO

## Example

If you have a photo called `la-traviata-2024.jpg`:
- Upload it to this `images/` directory
- Update the HTML: `<img src="images/la-traviata-2024.jpg" alt="La Traviata 2024 Production">`
