# 💍 Engagement Invitation Website

A beautiful, minimal yet classy one-page website for engagement invitations with **Modern Royal Indian Elegance** theme. Features traditional Indian wedding motifs combined with modern, clean web design.

## ✨ Features

- 🎨 **Rich Color Palette**: Deep maroon, antique gold, ivory backgrounds
- 🌸 **Traditional Motifs**: Mandala decorations, lotus flowers, diya animations
- 📱 **Fully Responsive**: Beautiful on all devices (mobile, tablet, desktop)
- ⚡ **Smooth Animations**: Floating rose petals, golden glow effects, entrance animations
- ♿ **Accessible**: Keyboard navigation, screen reader friendly, reduced motion support
- 🎯 **Easy to Customize**: Clear placeholder markers for all content

## 🚀 Quick Start

1. **Open the website**: Simply open `index.html` in your web browser
2. **Customize content**: Follow the customization guide below
3. **Deploy**: Upload to any web hosting service

## 📝 Customization Guide

### 1. Update Couple's Names

Open `index.html` and search for these placeholders:

```html
<!-- CUSTOMIZE: Bride Name -->
<h1 class="bride-name">[BRIDE NAME]</h1>

<!-- CUSTOMIZE: Groom Name -->
<h1 class="groom-name">[GROOM NAME]</h1>
```

Replace `[BRIDE NAME]` and `[GROOM NAME]` with actual names.

**Also update in footer:**
```html
<p class="footer-names">[BRIDE NAME] & [GROOM NAME]</p>
```

### 2. Update Engagement Date

Search for:
```html
<!-- CUSTOMIZE: Engagement Date -->
<p class="engagement-date">[ENGAGEMENT DATE]</p>
```

Replace with your date (e.g., "December 25, 2024")

### 3. Update Event Details

Find the Event Details section and update:

```html
<!-- CUSTOMIZE: Event Date -->
<p class="event-detail"><span class="icon">📅</span> <strong>[EVENT DATE]</strong></p>

<!-- CUSTOMIZE: Event Time -->
<p class="event-detail"><span class="icon">🕐</span> <strong>[EVENT TIME]</strong></p>

<!-- CUSTOMIZE: Venue Name and Address -->
<p class="event-detail"><span class="icon">📍</span> <strong>[VENUE NAME]</strong></p>
<p class="venue-address">[VENUE ADDRESS]</p>
```

### 4. Replace QR Code

**Important**: Replace the QR code image with your venue's location QR code.

1. Generate a QR code for your venue (use Google Maps link or any QR generator)
2. Save it as `qr-code.png` (250x250px recommended)
3. Replace the file at: `assets/images/qr-code.png`

### 5. Update Google Maps Link

Find:
```html
<!-- CUSTOMIZE: Google Maps Link -->
<a href="[GOOGLE MAPS URL]" target="_blank" class="btn-primary btn-directions">Get Directions</a>
```

Replace `[GOOGLE MAPS URL]` with your venue's Google Maps link.

### 6. Update Invitation Message

Find:
```html
<!-- CUSTOMIZE: Invitation Message -->
<p class="invitation-accent">Your presence would be</p>
<p class="invitation-main">an honor and a blessing</p>
<p class="invitation-closing">We hope to see you there!</p>
```

Customize the message to your preference.

### 7. Update Footer Details

```html
<!-- CUSTOMIZE: Wedding Hashtag -->
<p class="footer-hashtag">#[WEDDINGTAG]</p>

<!-- CUSTOMIZE: Contact Email (optional) -->
<p class="footer-contact">[EMAIL]</p>
```

### 8. Replace Hero Background

Replace `assets/images/hero-bg.jpg` with your couple's photo or a beautiful cultural image.
- Recommended size: 1920x1080px
- The image will have a golden tint overlay automatically

## 📁 File Structure

```
engagement-invitation/
├── index.html              # Main HTML file (customize here)
├── css/
│   ├── styles.css         # Main styles
│   └── animations.css     # Animation definitions
├── js/
│   └── main.js            # Interactive behaviors
├── netlify.toml           # Netlify deployment config
├── _redirects             # Netlify redirects
├── assets/
│   ├── images/
│   │   ├── hero-bg.jpg    # Hero background (REPLACE)
│   │   ├── qr-code.png    # QR code (REPLACE)
│   │   └── decorative/    # SVG decorations (optional)
└── README.md              # This file
```

## 🎨 Color Palette

The website uses these colors (defined in `css/styles.css`):

- **Primary**: `#800020` (Deep Maroon)
- **Secondary**: `#D4AF37` (Antique Gold)
- **Background**: `#FAF6F0` (Ivory)
- **Text**: `#3E2723` (Charcoal)
- **Highlights**: `#C8BCA8` (Sage Green), `#F8D7DA` (Blush Pink)

## 🌐 Deployment Options

### Option 1: GitHub Pages (Free)
1. Create a GitHub repository
2. Upload all files
3. Go to Settings → Pages
4. Select main branch and save
5. Your site will be live at `https://yourusername.github.io/repo-name`

### Option 2: Netlify (Free) - Recommended ⭐
1. Sign up at [netlify.com](https://netlify.com)
2. Click "Add new site" → "Deploy manually"
3. Drag and drop your project folder
4. Get instant deployment with custom domain support
5. The included `netlify.toml` file will automatically configure everything

**Or use Netlify CLI:**
```bash
npm install -g netlify-cli
netlify deploy --prod
```

### Option 3: Vercel (Free)
1. Sign up at [vercel.com](https://vercel.com)
2. Import your project
3. Deploy with one click

### Option 4: Traditional Web Hosting
Upload all files via FTP to your web hosting provider.

## 🔧 Troubleshooting

### Images not showing?
- Check file paths are correct
- Ensure images are in the right folders
- File names are case-sensitive on some servers

### Fonts not loading?
- Check internet connection (fonts load from Google Fonts)
- Fallback fonts will be used if Google Fonts fails

### Animations not working?
- Check if browser supports CSS animations
- Some users may have "reduced motion" enabled (animations will be minimal)

### Layout broken on mobile?
- Clear browser cache
- Test in different browsers
- Ensure viewport meta tag is present in HTML

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 💡 Tips

1. **Image Optimization**: Compress images before uploading to improve load times
2. **Test on Mobile**: Always test on actual mobile devices
3. **Backup**: Keep a copy of original files before making changes
4. **Preview**: Open `index.html` locally to preview changes before deploying

## 🎯 Sections Overview

1. **Hero Section**: Full-screen opening with names and date
2. **Event Details**: Date, time, venue, and QR code
3. **Invitation**: Warm message to guests
4. **Footer**: Closing message and contact info

## 📞 Need Help?

If you encounter any issues:
1. Check this README thoroughly
2. Verify all placeholder text has been replaced
3. Ensure file paths are correct
4. Test in different browsers

---

**Made with ❤️ for your special day**

Enjoy your beautiful engagement invitation website! 🎉
