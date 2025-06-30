# Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Perfect for showcasing your projects, skills, and professional experience.

## Features

- 🎨 Modern and clean design
- 📱 Fully responsive (mobile, tablet, desktop)
- ⚡ Fast loading and optimized
- 🎯 SEO friendly
- 📧 Contact form with validation
- 🌟 Smooth animations and transitions
- 🎨 CSS Grid and Flexbox layouts
- 📍 Sticky navigation with active states

## Sections

- **Hero**: Eye-catching introduction with call-to-action buttons
- **About**: Personal information and statistics
- **Skills**: Technical skills organized by categories
- **Projects**: Featured projects with live demos and GitHub links
- **Contact**: Contact form and social media links

## Getting Started

1. **Clone or download** this repository
2. **Customize** the content in `index.html`:
   - Replace "Your Name" with your actual name
   - Update the hero section with your information
   - Add your projects, skills, and experience
   - Update contact information and social media links
3. **Replace images**:
   - Add your profile photo
   - Add project screenshots
   - Update placeholder images with your own
4. **Deploy** to GitHub Pages (see deployment instructions below)

## Customization

### Colors
The main color scheme uses CSS custom properties. You can easily change colors by modifying the CSS variables or the color values in `styles.css`.

### Content
- Update personal information in the HTML file
- Add your own projects with live demos and GitHub links
- Customize skills and technologies
- Update social media links

### Images
Replace the placeholder images with your own:
- Profile photo (recommended: 300x300px, square)
- Project screenshots (recommended: 400x250px)
- About section image (recommended: 400x500px)

## Deployment to GitHub Pages

1. **Create a new repository** on GitHub
2. **Push your code** to the repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/your-repo-name.git
   git push -u origin main
   ```
3. **Enable GitHub Pages**:
   - Go to your repository settings
   - Scroll down to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

Your site will be available at: `https://yourusername.github.io/your-repo-name`

## Custom Domain Setup

To use your own domain name:

1. **Purchase a domain** from a domain registrar
2. **Add a CNAME file** to your repository root (this is already included)
3. **Configure DNS** with your domain provider:
   - Add a CNAME record pointing to `yourusername.github.io`
   - Or add A records pointing to GitHub's IP addresses:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153
4. **Update GitHub Pages settings**:
   - Go to repository Settings > Pages
   - Enter your custom domain in the "Custom domain" field
   - Enable "Enforce HTTPS"

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── CNAME              # Custom domain configuration
├── README.md          # This file
└── .gitignore         # Git ignore file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available under the [MIT License](LICENSE).

## Contributing

Feel free to fork this project and customize it for your own use. If you make improvements, pull requests are welcome!

## Contact

If you have any questions or need help with customization, feel free to reach out!
