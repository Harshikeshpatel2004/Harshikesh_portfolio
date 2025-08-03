# Personal Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript. This portfolio is designed to work seamlessly on both desktop and mobile devices.

## Features

- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Navigation**: Smooth scrolling and mobile-friendly hamburger menu
- **Contact Form**: Functional contact form with validation
- **Skills Section**: Organized display of technical skills with icons
- **Projects Showcase**: Beautiful project cards with descriptions and links
- **Smooth Animations**: Scroll-triggered animations and hover effects
- **SEO Friendly**: Proper meta tags and semantic HTML structure

## Sections Included

1. **Hero Section**: Introduction with your name, photo, and call-to-action buttons
2. **About Section**: Personal description and statistics
3. **Skills Section**: Technical skills organized by category
4. **Projects Section**: Featured projects with descriptions and links
5. **Contact Section**: Contact information and contact form
6. **Footer**: Copyright information

## Getting Started

### Prerequisites

- A modern web browser
- Basic knowledge of HTML, CSS, and JavaScript (for customization)

### Installation

1. Download or clone this repository
2. Open `index.html` in your web browser
3. Start customizing the content

## Customization Guide

### 1. Personal Information

Edit the following in `index.html`:

```html
<!-- Update your name -->
<h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>

<!-- Update your title/role -->
<p class="hero-subtitle">Full Stack Developer & Designer</p>

<!-- Update your description -->
<p class="hero-description">
    I create beautiful, functional, and user-friendly digital experiences. 
    Passionate about turning ideas into reality through code and design.
</p>
```

### 2. Profile Photo

Replace the placeholder image URL with your actual photo:

```html
<img src="path/to/your/photo.jpg" alt="Your Name">
```

### 3. About Section

Update the about section content:

```html
<div class="about-text">
    <p>
        Your personal description here...
    </p>
    <p>
        Additional information about yourself...
    </p>
</div>
```

### 4. Skills

Modify the skills section to match your expertise:

```html
<div class="skill-category">
    <h3>Frontend</h3>
    <div class="skill-items">
        <div class="skill-item">
            <i class="fab fa-html5"></i>
            <span>HTML5</span>
        </div>
        <!-- Add more skills as needed -->
    </div>
</div>
```

### 5. Projects

Update the projects section with your actual projects:

```html
<div class="project-card">
    <div class="project-image">
        <img src="path/to/project-image.jpg" alt="Project Name">
    </div>
    <div class="project-content">
        <h3>Project Name</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
        <div class="project-links">
            <a href="live-demo-url" class="btn btn-small">Live Demo</a>
            <a href="github-url" class="btn btn-small btn-outline">GitHub</a>
        </div>
    </div>
</div>
```

### 6. Contact Information

Update your contact details:

```html
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <span>your.email@example.com</span>
</div>
<div class="contact-item">
    <i class="fas fa-phone"></i>
    <span>+1 (555) 123-4567</span>
</div>
<div class="contact-item">
    <i class="fas fa-map-marker-alt"></i>
    <span>Your City, Country</span>
</div>
```

### 7. Social Media Links

Update the social media links:

```html
<div class="social-links">
    <a href="your-github-url" class="social-link"><i class="fab fa-github"></i></a>
    <a href="your-linkedin-url" class="social-link"><i class="fab fa-linkedin"></i></a>
    <a href="your-twitter-url" class="social-link"><i class="fab fa-twitter"></i></a>
    <a href="your-instagram-url" class="social-link"><i class="fab fa-instagram"></i></a>
</div>
```

### 8. Colors and Styling

To customize the color scheme, edit the CSS variables in `styles.css`:

```css
/* Primary colors */
--primary-color: #4F46E5;
--primary-dark: #3730A3;
--secondary-color: #7C3AED;
--accent-color: #FCD34D;

/* Background colors */
--bg-light: #F9FAFB;
--bg-dark: #1F2937;
```

## Deployment

### Option 1: GitHub Pages (Free)

1. Create a GitHub repository
2. Upload your portfolio files
3. Go to Settings > Pages
4. Select source branch (usually `main`)
5. Your portfolio will be available at `https://username.github.io/repository-name`

### Option 2: Netlify (Free)

1. Create a Netlify account
2. Drag and drop your portfolio folder to Netlify
3. Your portfolio will be deployed instantly
4. You can set up a custom domain later

### Option 3: Vercel (Free)

1. Create a Vercel account
2. Connect your GitHub repository
3. Deploy automatically on every push

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Tips

1. **Optimize Images**: Compress your images before uploading
2. **Minimize HTTP Requests**: Combine CSS and JS files if possible
3. **Use CDN**: The Font Awesome and Google Fonts are already loaded from CDN
4. **Enable Compression**: If hosting on a server, enable gzip compression

## Customization Tips

1. **Add More Sections**: You can easily add new sections by following the existing pattern
2. **Change Fonts**: Update the Google Fonts link in the HTML head
3. **Add Animations**: The CSS includes animation classes you can reuse
4. **Modify Layout**: The grid system is flexible and can be adjusted in CSS

## Troubleshooting

### Common Issues

1. **Images not loading**: Check file paths and ensure images are in the correct directory
2. **Fonts not loading**: Ensure internet connection for Google Fonts
3. **Mobile menu not working**: Check if JavaScript is enabled
4. **Contact form not working**: The form currently shows a success message. To make it functional, you'll need to add backend processing.

### Contact Form Backend

To make the contact form functional, you can:

1. Use a service like Formspree or Netlify Forms
2. Set up a backend server (Node.js, PHP, etc.)
3. Use email services like SendGrid or AWS SES

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you need help customizing your portfolio or have questions, feel free to:

1. Check the code comments for guidance
2. Review the HTML structure for examples
3. Modify the CSS variables for styling changes

## Contributing

Feel free to fork this project and submit pull requests for improvements!

---

**Happy coding! 🚀** 