# Personal Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript following Apple's design methodology.

## Features

- **Modern Design**: Clean, minimalist interface inspired by Apple's design principles
- **Responsive Layout**: Fully responsive design that works on all devices
- **Smooth Animations**: Fluid transitions and hover effects
- **Interactive Elements**: Dynamic navigation, form validation, and scroll effects
- **Performance Optimized**: Lazy loading, optimized animations, and efficient code
- **Accessibility**: Semantic HTML and keyboard navigation support

## Sections

- **Hero**: Introduction with profile image and call-to-action buttons
- **About**: Personal description and skills showcase
- **Experience**: Professional timeline with work history
- **Projects**: Featured projects with technology tags and links
- **Contact**: Contact information and working contact form

## Technologies Used

- HTML5
- CSS3 (with modern features like Grid, Flexbox, and CSS Variables)
- Vanilla JavaScript (ES6+)
- Font Awesome Icons
- Google Fonts (Inter)

## Deployment

This website is designed to be easily deployed on GitHub Pages or any static hosting service.

### GitHub Pages Deployment

1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to repository Settings > Pages
4. Select "Deploy from a branch" and choose "main" branch
5. Your site will be available at `https://yourusername.github.io/repository-name`

### Local Development

1. Clone or download the repository
2. Open `index.html` in a web browser
3. For development with live reload, use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

## Customization

### Personal Information
Update the following in `index.html`:
- Name and title in the hero section
- About description
- Experience timeline
- Project details
- Contact information

### Profile Image
Replace `WhatsApp Image 2025-09-12 at 12.30.13.jpeg` with your own profile image. Recommended size: 400x400px or larger (square aspect ratio).

### Colors and Styling
The website uses CSS custom properties for easy theming. Main colors can be changed in `styles.css`:
- Primary: `#007aff` (Apple Blue)
- Secondary: `#5856d6` (Purple)
- Text: `#1d1d1f` (Dark Gray)
- Background: `#ffffff` (White)

### Adding Projects
To add new projects, duplicate the project card structure in the projects section and update:
- Project title
- Description
- Technology tags
- Links (GitHub, Live Demo)

## Browser Support

- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+

## Performance

- Optimized images with lazy loading
- Minimal JavaScript footprint
- CSS animations with `prefers-reduced-motion` support
- Efficient scroll event handling

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

For questions or collaboration opportunities, please reach out through the contact form on the website.
