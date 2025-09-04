# Anmol Chopra - Portfolio Website

A clean, modern, and responsive portfolio website for Anmol Chopra, a first-year Computer Science and Engineering student at JECRC University, Jaipur.

## Features

- **Responsive Design**: Looks great on all devices
- **Modern UI**: Clean and professional design
- **Interactive Elements**: Smooth scrolling, animations, and form handling
- **Sections**:
  - Home with introduction
  - About Me
  - Education timeline
  - Skills showcase
  - Projects gallery
  - Contact form

## Technologies Used

- HTML5
- CSS3 (with CSS Variables for theming)
- JavaScript (Vanilla JS, no frameworks)
- Font Awesome Icons
- Google Fonts (via CDN)

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (for development)

### Running Locally

1. **Using a local server (recommended):**
   - Python 3:
     ```
     python -m http.server 8000
     ```
     Then open `http://localhost:8000` in your browser.

   - Node.js with `http-server`:
     ```
     npx http-server
     ```
     Then open the provided local URL in your browser.

2. **Direct file access:**
   - Simply open the `index.html` file in your browser (note: some features may be limited due to browser security restrictions).

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Customization

### Changing Colors

You can easily change the color scheme by updating the CSS variables in the `:root` selector in `styles.css`:

```css
:root {
    --primary-color: #2563eb;    /* Main brand color */
    --secondary-color: #1e40af;  /* Darker shade for hover states */
    --text-color: #1f2937;       /* Main text color */
    --light-text: #6b7280;       /* Secondary text color */
    --bg-color: #ffffff;         /* Background color */
    --light-bg: #f3f4f6;        /* Light background for sections */
    --border-color: #e5e7eb;     /* Border color */
}
```

### Adding Projects

To add a new project, add a new `.project-card` div in the projects section of `index.html`:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-project-icon"></i> <!-- Replace with appropriate icon -->
    </div>
    <h3>Project Title</h3>
    <p>Project description goes here. Keep it concise and highlight the key features.</p>
    <div class="project-links">
        <a href="#" class="btn btn-small">Live Demo</a>
        <a href="#" class="btn btn-small">View Code</a>
    </div>
</div>
```

### Updating Skills

Update the skills section in `index.html` by modifying the `.skills-container` section.

## Browser Support

This website is tested and works on:
- Google Chrome (latest)
- Mozilla Firefox (latest)
- Microsoft Edge (latest)
- Safari (latest)

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

- **Name:** Anmol Chopra
- **Email:** anmolchopra342@gmail.com
- **Phone:** +91 7717504438
- **GitHub:** [Your GitHub Profile]()
- **LinkedIn:** [Your LinkedIn Profile]()

---

Feel free to fork this project and customize it for your own portfolio!
