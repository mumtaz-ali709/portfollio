# Mumtaz Ali - Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Smooth Animations**: Beautiful scroll animations and transitions
- **Modern UI**: Clean and professional design with gradient effects
- **Sections Include**:
  - Hero section with call-to-action buttons
  - About me section
  - Skills showcase with icons
  - Experience timeline
  - Education details
  - Certifications and awards
  - Contact information with social links

## Live Demo

Visit the live portfolio at: [Your GitHub Pages URL]

## How to Use

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/yourusername/portfolio.git
cd portfolio
```

2. Open `index.html` in your web browser or use a local server:
```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (if you have http-server installed)
http-server
```

3. Visit `http://localhost:8000` in your browser

### Customization

To customize the portfolio with your own information:

1. **Edit HTML Content**: Open `index.html` and update:
   - Your name and title in the hero section
   - About me section content
   - Experience and education details
   - Contact information
   - Social media links

2. **Customize Colors**: Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #4a5568;
    --secondary-color: #2d3748;
    --accent-color: #3182ce;
    /* ... other colors */
}
```

3. **Update Information**: Modify skill cards, experience timeline, and education details to match your background.

## Deploying to GitHub Pages

### Steps:

1. **Create a GitHub account** if you don't have one: [github.com](https://github.com)

2. **Create a new repository**:
   - Click the "+" icon in the top-right corner
   - Select "New repository"
   - Name it: `yourusername.github.io` (replace with your GitHub username)
   - Choose "Public"
   - Click "Create repository"

3. **Upload your files**:
   - Click "uploading an existing file" link
   - Select all files from your portfolio folder (index.html, styles.css, script.js)
   - Click "Commit changes"

   OR use Git command line:
   ```bash
   git init
   git add .
   git commit -m "Initial commit - Portfolio website"
   git branch -M main
   git remote add origin https://github.com/yourusername/yourusername.github.io.git
   git push -u origin main
   ```

4. **Access your portfolio**:
   - Your site will be available at: `https://yourusername.github.io`
   - It may take a few minutes to go live

### Alternative: Using a Different Repository Name

If you don't want to name your repository `yourusername.github.io`, you can still host it on GitHub Pages:

1. Create any repository name (e.g., "portfolio")
2. Go to **Settings** → **Pages**
3. Under "Source", select `main` branch and `/root` folder
4. Your site will be available at: `https://yourusername.github.io/portfolio`

## File Structure

```
portfolio/
├── index.html      # Main HTML file
├── styles.css      # CSS stylesheet
├── script.js       # JavaScript for interactivity
└── README.md       # This file
```

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Responsive design with Flexbox and Grid
- **JavaScript**: Smooth scrolling and animations
- **Font Awesome**: Icon library
- **Google Fonts**: Typography

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## License

This project is open source and available under the MIT License.

## Author

Mumtaz Ali
- Email: mumtazalimahar55@gmail.com
- LinkedIn: [linkedin.com/in/mumtaz-ali](https://www.linkedin.com/in/mumtaz-ali)
- Phone: +92 308 3292593

## Getting Help

If you have any issues or questions:
1. Check the GitHub Issues section
2. Review the code comments for guidance
3. Consult the HTML/CSS documentation for specific questions

---

**Happy coding! 🚀**
