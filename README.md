# Asiko Hydrocarbon Company Limited - Website

A modern, responsive website for Asiko Hydrocarbon Company Limited, a leading provider of comprehensive hydrocarbon and energy solutions.

## 🌐 Overview

This is a professional website showcasing Asiko Hydrocarbon Company Limited's core services, mission, and commitment to delivering sustainable energy solutions. The site is built with clean HTML, modern CSS, and vanilla JavaScript for optimal performance and accessibility.

## 📋 Features

- **Responsive Design** - Mobile-first approach with seamless adaptation across all device sizes
- **Modern UI** - Clean, professional interface with gradient accents and smooth animations
- **Navigation** - Desktop and mobile-optimized navigation menus
- **Hero Section** - Eye-catching banner with call-to-action buttons
- **Stats Display** - Key metrics showcasing company achievements
- **Services Preview** - Overview of core service offerings
- **Mission Statement** - Clear articulation of company values and purpose
- **Footer** - Comprehensive footer with links and contact information
- **Accessibility** - Semantic HTML and WCAG-compliant markup

## 📁 Project Structure

```
.
├── index.html          # Homepage with hero section and services preview
├── about.html          # About page with company history and values (referenced)
├── services.html       # Detailed services page (referenced)
├── styles.css          # Main stylesheet with responsive design
├── script.js           # JavaScript functionality
└── README.md          # This file
```

## 🎯 Pages

### Home (index.html)
- Hero section with company branding
- Statistics showcase (15+ years experience, 50+ projects completed, 100% safety record)
- Core services preview cards
- Mission statement section
- Navigation and footer

### About (about.html)
- Company history and background
- Vision and mission
- Core values
- Team information

### Services (services.html)
- Detailed service offerings
- Gas Processing
- LNG Solutions
- Tri-Fuel Terminal Operations

## 🎨 Design System

### Color Palette
- **Primary**: `#1e3a8a` (Deep Blue)
- **Secondary**: `#3b82f6` (Bright Blue)
- **Accent**: `#f59e0b` (Amber)
- **Light**: `#dbeafe` (Light Blue)
- **Dark**: `#1e293b` (Slate)
- **Gray**: Various shades for text and backgrounds

### Typography
- **Headings**: Poppins (700 weight)
- **Body**: Inter (300-700 weights)
- **Fallback**: system-ui, sans-serif

### Responsive Breakpoints
- Mobile: < 640px
- Tablet: ≥ 640px
- Desktop: ≥ 768px
- Large Desktop: ≥ 1024px

## 🚀 Getting Started

### Prerequisites
- No build tools or dependencies required
- Works in any modern browser

### Installation
1. Clone the repository
```bash
git clone https://github.com/Charles-C4/Asikohydrocarbon.git
```

2. Navigate to the project directory
```bash
cd Asikohydrocarbon
```

3. Open in a browser
```bash
# Simply open index.html in your browser
open index.html

# Or use a local server (Python)
python -m http.server 8000

# Or use Live Server extension in VS Code
```

## 📱 Responsive Features

- **Mobile Menu** - Hamburger menu that toggles on small screens
- **Flexible Grids** - CSS Grid layouts that adapt to screen size
- **Touch-Friendly** - Proper spacing and sizing for touch interactions
- **Optimized Images** - SVG icons for scalability

## 🔧 Customization

### Updating Company Information
Edit `index.html` to update:
- Company name and tagline
- Contact information (footer section)
- Service descriptions

### Modifying Colors
Update CSS variables in `styles.css`:
```css
:root {
    --primary: #1e3a8a;
    --secondary: #3b82f6;
    --accent: #f59e0b;
    /* ... other variables ... */
}
```

### Adding New Sections
1. Add new HTML in the appropriate page file
2. Create corresponding CSS classes in `styles.css`
3. Ensure responsive design with media queries

## 🎬 JavaScript Functionality

The `script.js` file handles:
- Mobile menu toggle functionality
- Navigation state management
- Smooth interactions

## 📊 Statistics

The homepage displays key company metrics:
- **15+** Years of Experience
- **50+** Projects Completed
- **100%** Safety Record
- **24/7** Operations

## 🔐 Services Offered

1. **Gas Processing** - Natural gas processing and purification technologies
2. **LNG Solutions** - Liquefied natural gas production, storage, and distribution
3. **Tri-Fuel Terminal** - Multi-fuel terminal operations and distribution networks

## ♿ Accessibility

- Semantic HTML5 structure
- Proper heading hierarchy
- Alt text for images (SVG icons with descriptions)
- Sufficient color contrast ratios
- Keyboard navigation support

## 📞 Contact Information

**Asiko Hydrocarbon Company Limited**
- Email: info@asikohydrocarbon.com
- Website: [Company Website]
- Services: Energy Solutions, Gas Processing, LNG, Tri-Fuel Terminals

## 📝 License

© 2024 Asiko Hydrocarbon Company Limited. All rights reserved.

## 🤝 Contributing

For contributions or suggestions, please contact the development team or submit issues through the repository.

## 📈 Future Enhancements

Potential improvements:
- Contact form implementation
- Blog section for news and updates
- Team member profiles
- Case studies and testimonials
- Multi-language support
- CMS integration

## 🐛 Troubleshooting

### Mobile menu not working
- Ensure `script.js` is properly linked in HTML
- Check browser console for JavaScript errors

### Styling issues
- Clear browser cache (Ctrl+Shift+Delete)
- Verify all CSS classes match between HTML and CSS files

### Responsive layout problems
- Test with browser DevTools (F12)
- Check media queries in `styles.css`

---

**Last Updated**: 2024
**Version**: 1.0
**Status**: Active
