# Personal Profile Website

A modern, responsive personal profile website built with HTML, CSS, and JavaScript. This website includes all the sections you requested: About, Skills, Projects, and Contact.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional design with smooth animations
- **Interactive Elements**: Hover effects, smooth scrolling, and dynamic content
- **Contact Form**: Functional contact form with validation
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Smooth Animations**: Skill bars, typing effects, and scroll animations

## Sections Included

### 1. Hero Section
- Eye-catching introduction with your name and title
- Call-to-action buttons
- Professional gradient background

### 2. About Section
- Personal description and background
- Statistics showcase (experience, projects, clients)
- Professional image placeholder

### 3. Skills Section
- Frontend and Backend development skills
- Visual skill bars with percentages
- Technology icons and hover effects

### 4. Projects Section
- Project cards with descriptions
- Technology tags
- Live demo and code links

### 5. Contact Section
- Contact information with icons
- Social media links
- Functional contact form

## How to Customize

### 1. Personal Information
Edit the `index.html` file to update your personal information:

```html
<!-- Update your name -->
<h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>

<!-- Update your title -->
<p class="hero-subtitle">Web Developer & Designer</p>

<!-- Update your description -->
<p class="hero-description">
    I create beautiful, functional, and user-centered digital experiences.
    Passionate about clean code and innovative solutions.
</p>
```

### 2. About Section
Update the about section with your personal story:

```html
<p>
    Hello! I'm a passionate web developer with a strong foundation in modern web technologies. 
    I love creating digital experiences that are not only visually appealing but also functional 
    and user-friendly.
</p>
```

### 3. Skills
Modify the skills section to match your expertise:

```html
<div class="skill-item">
    <div class="skill-icon">
        <i class="fab fa-html5"></i>
    </div>
    <h4>HTML5</h4>
    <div class="skill-bar">
        <div class="skill-progress" style="width: 95%"></div>
    </div>
</div>
```

### 4. Projects
Add your own projects by duplicating the project card structure:

```html
<div class="project-card">
    <div class="project-image">
        <div class="project-placeholder">
            <i class="fas fa-laptop-code"></i>
        </div>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Your project description here.</p>
        <div class="project-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
        <div class="project-links">
            <a href="#" class="project-link"><i class="fas fa-external-link-alt"></i> Live Demo</a>
            <a href="#" class="project-link"><i class="fab fa-github"></i> Code</a>
        </div>
    </div>
</div>
```

### 5. Contact Information
Update your contact details:

```html
<div class="contact-item">
    <div class="contact-icon">
        <i class="fas fa-envelope"></i>
    </div>
    <div class="contact-text">
        <h4>Email</h4>
        <p>your.email@example.com</p>
    </div>
</div>
```

### 6. Social Media Links
Update the social media links with your profiles:

```html
<div class="social-links">
    <a href="https://github.com/yourusername" class="social-link"><i class="fab fa-github"></i></a>
    <a href="https://linkedin.com/in/yourusername" class="social-link"><i class="fab fa-linkedin"></i></a>
    <a href="https://twitter.com/yourusername" class="social-link"><i class="fab fa-twitter"></i></a>
    <a href="https://instagram.com/yourusername" class="social-link"><i class="fab fa-instagram"></i></a>
</div>
```

## Customization Tips

### Colors
The website uses a modern color scheme. You can customize it by editing the CSS variables in `styles.css`:

- Primary Blue: `#2563eb`
- Gradient: `linear-gradient(135deg, #667eea 0%, #764ba2 100%)`
- Accent Yellow: `#fbbf24`

### Fonts
The website uses Google Fonts (Poppins). You can change it by updating the font import in the HTML head section.

### Images
Replace the placeholder icons with your actual images:
- Profile photo in the hero section
- About section image
- Project screenshots

### Adding New Sections
To add new sections, follow the existing structure:

```html
<section id="new-section" class="new-section">
    <div class="container">
        <h2 class="section-title">New Section</h2>
        <!-- Your content here -->
    </div>
</section>
```

## File Structure

```
profile/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## Performance Features

- Optimized CSS with efficient selectors
- Smooth scrolling and animations
- Responsive images and icons
- Minimal JavaScript for better performance

## Deployment

You can deploy this website to any web hosting service:

1. **GitHub Pages**: Upload to a GitHub repository and enable GitHub Pages
2. **Netlify**: Drag and drop the folder to Netlify
3. **Vercel**: Connect your GitHub repository
4. **Traditional hosting**: Upload files via FTP

## Support

If you need help customizing your website or have questions, feel free to ask! The code is well-commented and structured for easy modification.

## License

This project is open source and available under the MIT License. 