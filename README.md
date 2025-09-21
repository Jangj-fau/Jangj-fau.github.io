# Research Project Website

A modern, responsive research project website built with HTML, CSS, and JavaScript. This website showcases research activities, team members, publications, and provides a contact form for collaboration opportunities.

## Features

### 🎨 Modern Design
- Clean, professional layout with modern typography
- Beautiful gradient backgrounds and smooth animations
- Responsive design that works on all devices
- Interactive hover effects and transitions

### 📱 Fully Responsive
- Mobile-first approach
- Responsive navigation with hamburger menu
- Optimized layouts for tablets and desktops
- Touch-friendly interface elements

### 🚀 Interactive Elements
- Smooth scrolling navigation
- Animated counters for statistics
- Parallax scrolling effects
- Form validation and submission handling
- Active navigation state tracking

### 📋 Sections Included
- **Hero Section**: Eye-catching introduction with call-to-action buttons
- **About Section**: Research mission and key statistics
- **Research Areas**: Six main research domains with icons
- **Team Section**: Team member profiles and roles
- **Publications**: Recent research publications
- **Contact Section**: Contact information and contact form
- **Footer**: Links and social media connections

## File Structure

```
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## Technologies Used

- **HTML5**: Semantic markup and modern structure
- **CSS3**: Flexbox, Grid, animations, and responsive design
- **JavaScript**: Interactive features and form handling
- **Font Awesome**: Icons for visual elements
- **Google Fonts**: Inter font family for typography

## Getting Started

1. **Clone or download** the project files
2. **Open `index.html`** in your web browser
3. **Customize** the content to match your research project

## Customization Guide

### Content Updates

#### Research Areas
Edit the research cards in the HTML to match your specific research domains:

```html
<div class="research-card">
    <div class="card-icon">
        <i class="fas fa-your-icon"></i>
    </div>
    <h3>Your Research Area</h3>
    <p>Description of your research focus...</p>
</div>
```

#### Team Members
Update team member information in the team section:

```html
<div class="team-member">
    <div class="member-image">
        <i class="fas fa-user"></i>
    </div>
    <h3>Dr. Your Name</h3>
    <p class="member-title">Your Title</p>
    <p class="member-bio">Your research expertise...</p>
</div>
```

#### Publications
Add your research publications:

```html
<div class="publication-item">
    <div class="pub-year">2024</div>
    <div class="pub-content">
        <h3>"Your Publication Title"</h3>
        <p class="pub-authors">Author Names</p>
        <p class="pub-journal">Journal Name</p>
    </div>
</div>
```

### Styling Customization

#### Color Scheme
Update the primary colors in `styles.css`:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #667eea;
    --accent-color: #764ba2;
}
```

#### Typography
Change the font family by updating the Google Fonts link in the HTML head:

```html
<link href="https://fonts.googleapis.com/css2?family=YourFont:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Features

- Optimized CSS with efficient selectors
- Minimal JavaScript for fast loading
- Responsive images and icons
- Smooth animations with hardware acceleration
- Intersection Observer for performance

## Accessibility

- Semantic HTML structure
- Proper heading hierarchy
- Alt text for images
- Keyboard navigation support
- High contrast color scheme
- Screen reader friendly

## Contact Form

The contact form includes:
- Form validation
- Email format checking
- Success/error messages
- Responsive design

Note: The form currently shows a success message but doesn't actually send emails. To enable email functionality, you'll need to integrate with a backend service or email service provider.

## License

This project is open source and available under the [MIT License](LICENSE).

## Contributing

Feel free to submit issues, feature requests, or pull requests to improve this project.

## Support

If you have any questions or need help customizing the website, please open an issue in the project repository.

---

**Built with ❤️ for the research community**



