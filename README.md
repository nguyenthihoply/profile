# Nguyen Thi Hop Ly - Marketing Professional Portfolio

A modern, responsive portfolio website for marketing professional Nguyen Thi Hop Ly. This website showcases skills, services, portfolio projects, and contact information with a professional design optimized for GitHub Pages deployment.

## 🌟 Features

- **Multi-Page Structure**: Professional website with dedicated pages for different sections
- **Responsive Design**: Fully responsive layout that works on all devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, portfolio filtering, FAQ accordions, and dynamic content
- **Professional Sections**:
  - **Home**: Hero section with professional introduction
  - **About**: Detailed background, experience timeline, education, and skills
  - **Services**: Comprehensive service offerings with process overview and pricing
  - **Portfolio**: Filterable project showcase with case studies and testimonials
  - **Contact**: Contact form, FAQ section, and contact information
- **SEO Optimized**: Proper meta tags and semantic HTML structure
- **Performance Optimized**: Lightweight and fast-loading

## 🌐 Website Structure

The website consists of five main pages:

1. **index.html** - Home page with hero section and introduction
2. **about.html** - Professional background, experience, and education
3. **services.html** - Service offerings, process, and pricing packages
4. **portfolio.html** - Project portfolio with filtering and testimonials
5. **contact.html** - Contact form, information, and FAQ section

## 🚀 Live Demo

Visit the live website at: `https://nguyenthihoply.github.io/profile`

## 📁 Project Structure

```
profile/
├── index.html          # Home page with hero section
├── about.html          # About page with experience and education
├── services.html       # Services page with offerings and pricing
├── portfolio.html      # Portfolio page with projects and testimonials
├── contact.html        # Contact page with form and FAQ
├── favicon.svg         # Website favicon (marketing megaphone icon)
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality and animations
└── README.md          # Project documentation
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript**: Interactive functionality and animations
- **Font Awesome**: Professional icons
- **Google Fonts**: Poppins font family for modern typography

## 📦 Deployment on GitHub Pages

### Prerequisites
- GitHub account
- Git installed on your computer

### Steps to Deploy

1. **Create a GitHub Repository**
   ```bash
   # If you haven't already, initialize git in your project folder
   git init
   git add .
   git commit -m "Initial commit: Add portfolio website"
   ```

2. **Connect to GitHub Repository**
   ```bash
   # Replace 'nguyenthihoply' with your GitHub username
   git remote add origin https://github.com/nguyenthihoply/profile.git
   git branch -M main
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Click on "Settings" tab
   - Scroll down to "Pages" section in the left sidebar
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

4. **Access Your Website**
   - GitHub will provide you with a URL like: `https://nguyenthihoply.github.io/profile`
   - It may take a few minutes for the site to be available

### Alternative Deployment Method

If you prefer to use the `gh-pages` branch:

```bash
# Create a gh-pages branch
git checkout -b gh-pages
git push origin gh-pages

# In GitHub repository settings, select gh-pages as the source branch
```

## 🎨 Customization

### Personal Information
Edit the following in `index.html`:
- Name and title in the hero section
- Professional description and bio
- Skills and competencies
- Service offerings
- Portfolio projects
- Contact information
- Social media links

### Styling
Modify `styles.css` to customize:
- Color scheme (current: gradient from #667eea to #764ba2)
- Typography and fonts
- Layout and spacing
- Animation effects

### Functionality
Update `script.js` to modify:
- Navigation behavior
- Form submission handling
- Animation effects
- Interactive elements

## 📱 Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Local Development

To run the website locally:

1. Clone the repository
   ```bash
   git clone https://github.com/nguyenthihoply/profile.git
   cd profile
   ```

2. Open `index.html` in your browser or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have it installed)
   npx http-server
   ```

3. Visit `http://localhost:8000` in your browser

## 📧 Contact Form

The contact form is currently set up with client-side validation. For a fully functional form, you may want to:

- Integrate with a form service like Formspree, Netlify Forms, or EmailJS
- Add backend processing if you have server capabilities
- Update the form submission handler in `script.js`

## 🤝 Contributing

This is a personal portfolio website. If you'd like to suggest improvements:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Support

For questions or support regarding this portfolio website:
- Email: nguyen.hoply@email.com
- LinkedIn: [Add LinkedIn profile URL]

---

**Note**: Remember to update all placeholder information (email, phone number, social media links) with actual contact details before deploying to production.
