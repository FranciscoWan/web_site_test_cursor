# MawCare - Cat Care Service Landing Page

A modern, responsive landing page for MawCare cat care services. Built with HTML, CSS, and JavaScript, featuring a clean design with smooth animations and mobile-first responsive layout.

## Features

- **Modern Design**: Clean, minimalist design with soft shadows and rounded elements
- **Responsive Layout**: Fully responsive design that works on desktop, tablet, and mobile devices
- **Interactive Elements**: Smooth animations, hover effects, and interactive components
- **Mobile Navigation**: Hamburger menu for mobile devices with smooth transitions
- **Performance Optimized**: Fast loading with optimized images and efficient CSS
- **Accessibility**: Semantic HTML structure and keyboard navigation support

## Design Specifications

### Color Palette
- **Background**: Light gray (#f4f4f4)
- **Text**: Dark gray (#1a1a1a)
- **Accent**: Orange (#ff7f32)
- **White**: Pure white for cards and sections

### Typography
- **Font Family**: Inter (Google Fonts)
- **Weights**: 400 (Regular), 500 (Medium), 600 (Semi-bold), 700 (Bold)

### Layout Structure
1. **Header**: Fixed navigation with logo and menu
2. **Hero Section**: Three-column layout with content, cat image, and join card
3. **Trust Section**: Social proof with ratings and user count

## File Structure

```
├── index.html          # Main HTML structure
├── styles.css          # All CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## Setup Instructions

1. **Clone or download** the project files
2. **Open** `index.html` in a web browser
3. **No build process required** - the page works immediately

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Responsive Breakpoints

- **Desktop**: 1024px and above
- **Tablet**: 768px - 1023px
- **Mobile**: Below 768px

## Features in Detail

### Header
- Fixed position with glassmorphic effect
- Responsive navigation menu
- Hamburger menu for mobile devices
- Smooth scroll behavior

### Hero Section
- Three-column grid layout
- Large cat image with glassmorphic shadow effect
- Call-to-action button with hover animations
- Join card with overlay and badge

### Trust Section
- Social proof elements
- Animated counter for user count
- Paw icon with ratings information
- Link to external reviews

### Animations
- Fade-in animations on page load
- Smooth hover effects on buttons and links
- Counter animation in trust section
- Mobile menu slide-in animation

## Customization

### Colors
Update the CSS custom properties in `styles.css`:
```css
:root {
    --primary-color: #ff7f32;
    --text-color: #1a1a1a;
    --background-color: #f4f4f4;
}
```

### Images
Replace the Unsplash image URLs in `index.html` with your own images:
- Hero cat image
- Join card image

### Content
Update the text content in `index.html` to match your business needs.

## Performance Tips

- Images are loaded from Unsplash CDN for optimal performance
- CSS and JavaScript are minified-ready
- Font loading is optimized with preconnect links
- Smooth animations use CSS transforms for better performance

## License

This project is open source and available under the MIT License.

## Support

For questions or issues, please refer to the code comments or create an issue in the repository.
