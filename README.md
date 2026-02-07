# Cursor-Inspired Landing Page

A desktop-first developer tool landing page inspired by the Cursor website, built with pure HTML and CSS.

## 📋 Project Overview

This project recreates a landing page similar to Cursor's website, focusing on visual and structural accuracy. The page is built without JavaScript, animations, or CSS frameworks, maintaining a clean and minimalist approach.

## 🎯 Features

- **Pure HTML & CSS** - No JavaScript required
- **Desktop-first design** - Optimized for desktop viewing (1200px+)
- **Dark theme** - Modern black background with subtle gray accents
- **10 distinct sections** - Complete landing page structure
- **Image placeholders** - Red div placeholders ready for your images

## 📁 File Structure

```
project/
├── index.html          # Main HTML structure
├── style.css          # All styling
└── README.md          # Documentation (this file)
```

## 🚀 Getting Started

### Prerequisites

- Any modern web browser (Chrome, Firefox, Safari, Edge)
- A text editor (VS Code, Sublime Text, etc.)

### Installation

1. Download or clone the project files
2. Place `index.html` and `style.css` in the same directory
3. Open `index.html` in your web browser

```bash
# If using a local server (optional)
# Using Python 3
python -m http.server 8000

# Using Node.js (http-server)
npx http-server
```

## 📐 Page Sections

The landing page includes the following sections:

### 1. **Navigation Bar**
- Logo
- Navigation links (Features, Changelog, Pricing, Community)
- Sign In link
- Download CTA button

### 2. **Hero Section**
- Main headline
- Description text
- Primary CTA button
- Large product screenshot placeholder
- Trust indicator text

### 3. **Trusted By / Logos**
- 8 company logos in a grid layout
- Includes: Stripe, OpenAI, Instacart, Braintrust, Midjourney, Figma, Perplexity, Adobe

### 4. **Feature Sections (3 blocks)**
- Two-column layouts
- Text and image alternating positions
- Orange accent links
- Feature descriptions

### 5. **Feature Cards**
- Section title
- 3-column grid
- Cards with icons, headings, and descriptions
- Privacy, Context-aware, and IDE integration features

### 6. **Testimonials**
- 6 testimonial cards in 3-column grid
- Profile images
- Quote text
- Author name and role

### 7. **Use Cases / Stories**
- 3 story cards
- Image placeholders
- Titles and descriptions

### 8. **Changelog / Updates**
- Date-based list of updates
- 4 recent updates
- Two-column layout with dates and content

### 9. **Team / About**
- Large team image placeholder
- Company description
- CTA link

### 10. **Final CTA**
- Large heading
- Primary download button

### 11. **Footer**
- 4-column link grid
- Product, Company, Resources, Social links
- Copyright and legal links

## 🎨 Customization Guide

### Adding Images

Replace the red placeholder divs with actual images:

**Before:**
```html
<div class="image-placeholder" style="height: 500px;"></div>
```

**After:**
```html
<img src="images/hero-screenshot.png" alt="Product Screenshot">
```

### Color Scheme

The page uses the following color palette:

- **Background**: `#000000` (Black)
- **Secondary Background**: `#0a0a0a` (Dark gray)
- **Text Primary**: `#ffffff` (White)
- **Text Secondary**: `#999999` (Light gray)
- **Text Tertiary**: `#666666` (Medium gray)
- **Accent Color**: `#ff8c42` (Orange)
- **Borders**: `#1a1a1a` (Very dark gray)

To change colors, search and replace in `style.css`.

### Typography

The page uses system fonts for optimal performance:

```css
font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Roboto', 'Helvetica', 'Arial', sans-serif;
```

To use custom fonts, add Google Fonts or local font files:

```html
<!-- In index.html <head> -->
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
```

```css
/* In style.css */
body {
    font-family: 'Inter', sans-serif;
}
```

### Content Updates

All text content can be edited directly in `index.html`. Key areas:

- Hero headline: Line 31
- Feature headings: Lines 89, 106, 123
- Testimonials: Lines 162-217
- Company logos: Lines 55-62

## 🖼️ Image Recommendations

### Suggested Image Sizes

- **Hero Image**: 1200px × 500px
- **Feature Images**: 600px × 400px
- **Story Cards**: 400px × 250px
- **Team/About Image**: 700px × 450px
- **Profile Icons**: 50px × 50px (circular)
- **Card Icons**: 60px × 60px

### Image Optimization Tips

- Use WebP format for better compression
- Optimize images before upload (use tools like TinyPNG, Squoosh)
- Use appropriate alt text for accessibility
- Consider using lazy loading for below-the-fold images

## 🎯 Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Opera (latest)

## 📝 Best Practices Implemented

- ✅ Semantic HTML5 elements
- ✅ Clean and organized CSS
- ✅ Consistent spacing and typography
- ✅ Hover states for interactive elements
- ✅ Accessible color contrast
- ✅ Organized section structure

## 🔧 Customization Examples

### Changing Button Colors

```css
/* In style.css */
.btn-primary {
    background-color: #your-color;
    color: #text-color;
}
```

### Adjusting Section Spacing

```css
/* In style.css */
.feature-section {
    padding: 120px 0; /* Change these values */
}
```

### Modifying Grid Layouts

```css
/* For testimonials - change from 3 to 2 columns */
.testimonials-grid {
    grid-template-columns: repeat(2, 1fr); /* Change 3 to 2 */
}
```

## 📞 Additional Notes

- No JavaScript means no animations or interactions
- Page is not responsive (desktop-only as requested)
- All placeholder divs use red background (`#ff0000`) for easy identification
- Sticky navigation bar for better UX
- Border separators between major sections

## 🚦 Next Steps

1. **Replace placeholder divs** with actual images
2. **Update text content** with your brand messaging
3. **Customize colors** to match your brand
4. **Add your logo** in the navigation
5. **Update links** in navigation and footer
6. **Test in multiple browsers**
7. **Optimize images** for web performance

## 📄 License

This template is free to use for personal and commercial projects.

## 🤝 Credits

Design inspiration: [Cursor.com](https://cursor.com)

---

**Made with ❤️ for developers**