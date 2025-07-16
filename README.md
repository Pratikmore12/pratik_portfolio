# Pratik's Portfolio Website 🚀

A modern, responsive portfolio website with a coding theme, beautiful animations, and interactive features.

## ✨ Features

- **Modern Design**: Clean, professional design with a coding theme
- **Responsive**: Works perfectly on all devices (desktop, tablet, mobile)
- **Interactive Animations**: Smooth scroll animations, typing effects, and particle systems
- **Code Editor Theme**: Visual code editor in the hero section
- **Smooth Navigation**: Sticky navigation with active section highlighting
- **Contact Form**: Functional contact form with validation
- **Performance Optimized**: Fast loading with optimized animations
- **SEO Friendly**: Proper meta tags and semantic HTML

## 🎨 Design Highlights

- **Terminal-inspired header** with macOS-style buttons
- **Code syntax highlighting** in the hero section
- **Particle effects** for visual appeal
- **Gradient backgrounds** and modern color scheme
- **Smooth hover effects** and transitions
- **Professional typography** with Fira Code and Inter fonts

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid, Flexbox, and animations
- **JavaScript (ES6+)**: Interactive features and animations
- **Font Awesome**: Icons
- **Google Fonts**: Typography

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🚀 Getting Started

1. **Clone or download** the portfolio files
2. **Open `index.html`** in your web browser
3. **Customize** the content to match your information
4. **Deploy** to your preferred hosting service

## 🎯 Customization Guide

### Personal Information

Update the following sections in `index.html`:

#### Hero Section
```html
<!-- Update your name and role -->
<span class="typing-text">Hello, I'm [Your Name]</span>
<span class="code-string">"[Your Name]"</span>
<span class="code-string">"[Your Role]"</span>
```

#### About Section
```html
<!-- Update your description -->
<p class="about-description">
    [Your personal description here]
</p>

<!-- Update statistics -->
<div class="stat-number" data-target="[Your Years]">0</div>
<div class="stat-number" data-target="[Your Projects]">0</div>
<div class="stat-number" data-target="[Your Clients]">0</div>
```

#### Skills Section
```html
<!-- Update your skills -->
<div class="skill-item" data-skill="[Skill Name]">
    <i class="[Icon Class]"></i>
    <span>[Skill Name]</span>
</div>
```

#### Projects Section
```html
<!-- Update your projects -->
<h3 class="project-title">[Project Name]</h3>
<p class="project-description">[Project description]</p>
<div class="project-tech">
    <span class="tech-tag">[Technology]</span>
</div>
```

#### Contact Section
```html
<!-- Update contact information -->
<p>[your.email@example.com]</p>
<p>[Your Phone Number]</p>
<p>[Your Location]</p>
```

### Styling Customization

#### Colors
Update the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #00d4ff;      /* Main brand color */
    --secondary-color: #ff6b6b;    /* Accent color */
    --accent-color: #4ecdc4;       /* Additional accent */
    --dark-bg: #0a0a0a;            /* Background color */
    /* ... other variables */
}
```

#### Typography
Change fonts by updating the Google Fonts link in `index.html`:

```html
<link href="https://fonts.googleapis.com/css2?family=[Font+Name]:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

#### Animations
Modify animation speeds and effects in `styles.css`:

```css
/* Typing animation speed */
@keyframes typing {
    /* Adjust timing here */
}

/* Scroll animation duration */
.fade-in {
    transition: all 0.6s ease-out; /* Change duration */
}
```

### JavaScript Customization

#### Typing Animation Text
Update the typing animation text in `script.js`:

```javascript
const texts = [
    "Hello, I'm [Your Name]",
    "I'm a [Your Role]",
    "[Your Tagline]",
    "[Call to Action]"
];
```

#### Particle Effects
Customize particle effects in `script.js`:

```javascript
// Number of particles
for (let i = 0; i < 50; i++) { // Change number here
    createParticle(hero);
}

// Particle colors
background: ${Math.random() > 0.5 ? '#00d4ff' : '#ff6b6b'}; // Change colors
```

## 🌐 Deployment

### GitHub Pages
1. Create a new repository on GitHub
2. Upload your portfolio files
3. Go to Settings > Pages
4. Select source branch and save

### Netlify
1. Drag and drop your portfolio folder to Netlify
2. Your site will be live instantly
3. Customize domain if needed

### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your portfolio directory
3. Follow the prompts

## 📱 Mobile Optimization

The portfolio is fully responsive and optimized for mobile devices:

- **Touch-friendly** navigation
- **Optimized animations** for mobile performance
- **Readable typography** on small screens
- **Proper spacing** for touch interactions

## 🔧 Performance Tips

1. **Optimize images** before adding them
2. **Minify CSS and JS** for production
3. **Use a CDN** for external resources
4. **Enable compression** on your hosting service
5. **Cache static assets** for faster loading

## 🎨 Adding Your Own Projects

1. **Duplicate** an existing project card
2. **Update** the project information
3. **Add** your project images (recommended size: 350x200px)
4. **Update** the technology tags
5. **Add** links to live demo and GitHub repository

## 📧 Contact Form Setup

The contact form is currently set up for demonstration. To make it functional:

1. **Add a backend service** (Netlify Forms, Formspree, etc.)
2. **Update the form action** in `index.html`
3. **Configure email notifications**
4. **Add spam protection** if needed

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio. If you make improvements, consider sharing them with the community!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **Font Awesome** for the beautiful icons
- **Google Fonts** for the typography
- **CSS Grid and Flexbox** for the responsive layout
- **Intersection Observer API** for scroll animations

## 📞 Support

If you need help customizing your portfolio or have questions, feel free to reach out!

---

**Built with ❤️ and ☕ by Pratik**

*Happy coding! 🚀* 