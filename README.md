# Chris Deguara - Portfolio Website

A modern, responsive portfolio website showcasing Chris Deguara's profile as a Product & Automation Specialist with over 15 years of experience in software development.

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works seamlessly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations and transitions
- **Single Page Application**: Easy navigation with smooth scrolling between sections
- **Interactive Elements**: Animated statistics, hover effects, and mobile-friendly navigation
- **Performance Optimized**: Fast loading times with optimized assets
- **Accessible**: Built with accessibility best practices

## 📋 Sections

1. **Hero Section**: Eye-catching introduction with key stats (15+ years experience, 100% response rate)
2. **About**: Overview of skills and experience
3. **Services**: Six main service offerings including custom software development and AI automation
4. **Skills**: Categorized display of technical skills and technologies
5. **Experience**: Timeline of professional experience
6. **Education & Certifications**: Academic background and professional certifications
7. **Contact**: Call-to-action with contact information

## 🚀 Getting Started

### Prerequisites

No special prerequisites needed! This is a static website built with vanilla HTML, CSS, and JavaScript.

### Installation

1. Clone the repository:

```bash
git clone https://github.com/chrisdeguara/chrisdeguara.website.git
cd chrisdeguara.website
```

2. Open the website:
   - Simply open `index.html` in your web browser
   - Or use a local development server (recommended)

### Using a Local Development Server

#### Option 1: Python

```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

Then visit `http://localhost:8000`

#### Option 2: Node.js (http-server)

```bash
# Install http-server globally
npm install -g http-server

# Run the server
http-server -p 8000
```

Then visit `http://localhost:8000`

#### Option 3: VS Code Live Server

1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

## 📁 Project Structure

```
chrisdeguara.website/
├── index.html          # Main HTML file
├── styles.css          # CSS styling and responsive design
├── script.js           # JavaScript for interactivity
└── README.md          # This file
```

## 🎨 Customization

### Colors

The website uses CSS variables for easy color customization. Edit the `:root` section in `styles.css`:

```css
:root {
  --primary-color: #6366f1;
  --primary-dark: #4f46e5;
  --secondary-color: #8b5cf6;
  /* ... other variables */
}
```

### Content

To update content:

- **Personal Information**: Edit the hero section in `index.html`
- **Services**: Modify the services grid section
- **Experience**: Update the timeline items
- **Skills**: Add or remove skill tags in the skills section

### Typography

The website uses the Inter font family from Google Fonts. To change the font, update the link in the `<head>` of `index.html` and the `font-family` in `styles.css`.

## 🌐 Deployment

### GitHub Pages

1. Push your code to a GitHub repository
2. Go to repository Settings → Pages
3. Select the branch to deploy (usually `main`)
4. Save and wait a few minutes for deployment

### Netlify

1. Sign up for a free account at [Netlify](https://www.netlify.com)
2. Click "Add new site" → "Import an existing project"
3. Connect your Git repository
4. Deploy!

### Vercel

1. Sign up at [Vercel](https://vercel.com)
2. Import your Git repository
3. Deploy with zero configuration

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript (ES6+)**: Interactive features
- **Google Fonts**: Inter font family
