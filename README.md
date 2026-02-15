# Soliton Mebel - Premium Furniture Website

A high-converting, conversion-optimized furniture website built with pure HTML and CSS. Designed for GitHub Pages hosting with sales psychology, trust signals, and WhatsApp integration.

## 🎯 Features

- **Conversion-Optimized Design**: Built with sales psychology principles
- **Mobile Responsive**: Fully responsive across all devices
- **WhatsApp Integration**: Floating WhatsApp button and CTA buttons throughout
- **Premium Color Psychology**: Carefully selected colors to increase trust and buying intention
- **Trust Signals**: Multiple trust indicators and urgency badges
- **Clean Code**: Pure HTML and CSS, no frameworks, easy to customize
- **SEO Ready**: Semantic HTML with proper meta tags

## 📁 Project Structure

```
soliton-mebel/
├── index.html              # Homepage
├── css/
│   └── style.css          # Main stylesheet
├── images/                # Image assets (add your product images here)
├── pages/                 # Category pages
│   ├── bedroom-sets.html
│   ├── living-room-sets.html
│   ├── sofa-sets.html
│   ├── corner-sofas.html
│   ├── coffee-tables.html
│   ├── mattresses.html
│   └── chairs.html
└── README.md              # This file
```

## 🚀 Deployment to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and log in
2. Click the "+" icon in the top right and select "New repository"
3. Name your repository (e.g., `soliton-mebel`)
4. Choose "Public" visibility
5. Click "Create repository"

### Step 2: Upload Your Files

**Option A: Using GitHub Web Interface**

1. Click "uploading an existing file"
2. Drag and drop all files and folders from the `soliton-mebel` directory
3. Commit the changes

**Option B: Using Git Command Line**

```bash
cd soliton-mebel
git init
git add .
git commit -m "Initial commit: Soliton Mebel website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/soliton-mebel.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "main" branch
5. Click "Save"
6. Your site will be published at: `https://YOUR-USERNAME.github.io/soliton-mebel/`

## 🎨 Customization Guide

### Adding Real Product Images

1. Add your product images to the `/images/` folder
2. Replace the placeholder `<div class="placeholder-image">` sections with actual images:

```html
<!-- Replace this: -->
<div class="placeholder-image" style="background: linear-gradient(...);">
    <span class="placeholder-text">Product Name</span>
</div>

<!-- With this: -->
<img src="../images/your-product-image.jpg" alt="Product Name">
```

### Changing Colors

Edit the CSS variables in `/css/style.css`:

```css
:root {
    --primary-color: #2C5F2D;      /* Main brand color */
    --accent-color: #C9A961;       /* Accent/CTA color */
    --bg-primary: #FAF8F5;         /* Background color */
    /* ... more variables ... */
}
```

### Updating Contact Information

Replace the WhatsApp number throughout the site:
- Search for `995552309189` in all HTML files
- Replace with your WhatsApp number (without + or spaces)

### Customizing Text Content

- **Homepage**: Edit `index.html`
- **Category Pages**: Edit files in `/pages/` folder
- All text is clearly commented and easy to find

### Adding Social Media Links

In the footer section of each HTML file, update:

```html
<div class="social-links">
    <a href="YOUR_INSTAGRAM_URL" class="social-link">Instagram</a>
    <a href="YOUR_TIKTOK_URL" class="social-link">TikTok</a>
</div>
```

## 📱 WhatsApp Integration

The website includes multiple WhatsApp touchpoints:

1. **Floating Button**: Always visible in bottom-right corner
2. **Hero CTA**: Primary call-to-action in hero section
3. **Product Cards**: Each product has a "Contact for Price" button
4. **Urgency Sections**: Strategic placement throughout pages

All WhatsApp links include pre-filled messages for better conversion.

## 🎯 Conversion Optimization Features

### Sales Psychology Elements

- **Urgency Badges**: "Limited Stock", "Hot Sale", "Best Seller"
- **Trust Indicators**: Quality, delivery, design guarantees
- **Social Proof**: Best seller highlights
- **Emotional Headlines**: Transform-focused messaging
- **Strong CTAs**: Action-oriented button text

### Color Psychology

- **Deep Green**: Trust, stability, growth
- **Elegant Gold**: Luxury, premium quality
- **Warm Beige**: Comfort, warmth
- **Dark Charcoal**: Sophistication, readability

### UX Best Practices

- Large, clickable buttons
- Clear visual hierarchy
- Spacious layout
- Smooth hover effects
- Mobile-first responsive design

## 📊 Category Pages

Each category page includes:

- Hero section with category-specific messaging
- Descriptive introduction
- Product grid with 8+ products
- Urgency/CTA section
- Related categories
- Full navigation and footer

To customize category pages:
1. Open the relevant HTML file in `/pages/`
2. Update the page title and hero text
3. Modify product cards with your actual products
4. Update product descriptions and images

## 🔧 Technical Details

- **Pure HTML5 & CSS3**: No frameworks or dependencies
- **No JavaScript**: Fully functional without JS
- **Mobile Responsive**: Breakpoints at 768px and 480px
- **Cross-browser Compatible**: Works on all modern browsers
- **Fast Loading**: Minimal code, optimized performance
- **SEO Friendly**: Semantic HTML, meta tags included

## 📝 Maintenance Tips

### Regular Updates

- Add new products regularly to keep content fresh
- Update "Best Seller" badges based on actual sales
- Rotate "Limited Stock" items to create urgency
- Keep social media links active

### Performance

- Optimize images before uploading (recommended: 800x600px, under 200KB)
- Use WebP format for better compression
- Keep CSS file organized with comments

### Testing

- Test on multiple devices (mobile, tablet, desktop)
- Check all WhatsApp links work correctly
- Verify all internal links navigate properly
- Test form submissions if you add contact forms

## 🎨 Design Philosophy

This website is designed with furniture buyer psychology in mind:

1. **Premium Feel**: Luxury aesthetic without being pretentious
2. **Trust Building**: Multiple trust signals throughout
3. **Emotional Connection**: Transform-focused messaging
4. **Clear Action**: Every section has a clear next step
5. **Warmth & Comfort**: Color palette creates inviting atmosphere

## 📞 Support

For questions about customization or deployment, refer to:
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [HTML/CSS Resources](https://developer.mozilla.org/en-US/docs/Web)

## 📄 License

This website template is provided as-is for Soliton Mebel. Feel free to customize and modify as needed.

---

**Built with ❤️ for Soliton Mebel**

Transform Your Home Into Luxury 🏡✨
