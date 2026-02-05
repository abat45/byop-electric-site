# BYOP Electric Website

A clean, modern one-page business card website for BYOP Electric - Energy Independence Solutions.

## Brand Colors
- **Primary (Yellow):** #FCCE08
- **Secondary (Dark Charcoal):** #2B292A
- **White:** #FFFFFF

## Font
- **Display/Headers:** Rajdhani Bold (via Google Fonts) - similar to Agency FB Bold Extended
- **Body:** Inter

## Features
- ✅ One-page scroll design
- ✅ Fully responsive (mobile, tablet, desktop)
- ✅ Smooth scroll navigation
- ✅ Mobile menu
- ✅ Service showcase (6 core services)
- ✅ Contact form
- ✅ Social media links
- ✅ Brand colors integrated throughout
- ✅ Image placeholders for easy customization

## Easy Updates

### Update Phone Number
Search for `3852837904` in `index.html` and replace with your number.

### Update Email
Search for `contact@byopelectric.com` in `index.html` and replace with your email.

### Update Social Media Links
In `index.html`, find the social links section and replace:
- `https://facebook.com/YOUR_HANDLE`
- `https://instagram.com/YOUR_HANDLE`
- `https://linkedin.com/company/YOUR_HANDLE`

### Add Your Logo
1. Add your logo file to the project folder (e.g., `logo.png`)
2. In `index.html`, find `<img src="logo-placeholder.png"` and change to your logo filename

### Add Project Photos
Replace the placeholder divs in the gallery section with actual images:
```html
<div class="gallery-item">
    <img src="project1.jpg" alt="Project description">
</div>
```

### Add Hero Image
Replace the hero image placeholder with your actual image:
```html
<div class="hero-image">
    <img src="hero-image.jpg" alt="BYOP Electric">
</div>
```

## File Structure
```
byop-electric/
├── index.html          # Main HTML file
├── styles.css          # All styling
├── README.md           # This file
└── (your images here)  # Logo, photos, etc.
```

## Deployment Options

### Option 1: GoHighLevel (GHL)
1. Open GHL Sites
2. Create new page
3. Use "Custom Code" option
4. Paste `index.html` content
5. Add `styles.css` in the CSS section

### Option 2: Netlify (Recommended)
1. Create GitHub repository
2. Push these files to GitHub
3. Connect Netlify to your repo
4. Auto-deploy on every commit
5. Get free SSL certificate

### Option 3: Simple Hosting
Upload files to any web host via FTP.

## Testing Locally
1. Open `index.html` in a web browser
2. Or use VS Code Live Server extension

## Git Setup

### Initialize Repository
```bash
git init
git add .
git commit -m "Initial commit: BYOP Electric website"
```

### Push to GitHub
```bash
git remote add origin https://github.com/YOUR_USERNAME/byop-electric-site.git
git branch -M main
git push -u origin main
```

## Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance
- Lightweight design (~10KB HTML, ~8KB CSS)
- Fast loading
- Mobile-optimized
- No external dependencies except Google Fonts

## License
© 2024 BYOP Electric. All rights reserved.

## Contact
For website updates or questions, contact: [Your contact info]
