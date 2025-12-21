# 🚀 Vijay Aditya R V - Personal Portfolio

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-success?style=flat&logo=github)](https://VIJAYADITYARV.github.io/portfolio)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

> A modern, responsive portfolio website showcasing my projects, skills, and professional journey in Computer Science and Software Development.

## 🌐 Live Demo

**🔗 Visit:** [https://VIJAYADITYARV.github.io/portfolio](https://vijayadityarv.github.io/VIJAY-PORTFOLIO/)

---

## ✨ Features

- 🎨 **Modern Design**: Clean, professional UI with smooth animations
- 🌓 **Dark/Light Mode**: Toggle between themes for comfortable viewing
- 📱 **Fully Responsive**: Optimized for all devices (mobile, tablet, desktop)
- ⚡ **Fast & Lightweight**: Vanilla JavaScript, no heavy frameworks
- 🎭 **Interactive Animations**: Scroll-based reveals, particle effects, gradient animations
- 📧 **Contact Form**: Integrated with EmailJS for direct communication
- 🔗 **Multi-page Navigation**: Organized content across dedicated pages

---

## 📂 Project Structure

```
portfolio/
├── index.html              # Home page (Hero + Tech Stack)
├── about.html              # About me, stats, and interests
├── education.html          # Academic background & certifications
├── skills.html             # Technical skills & learning progress
├── projects.html           # Featured projects showcase
├── testimonials.html       # Testimonials & GitHub activity
├── contact.html            # Contact form with EmailJS
├── styles.css              # All styling (CSS3 with custom properties)
├── script.js               # Interactive functionality
├── profile.jpg             # Profile picture
└── README.md               # Project documentation
```

---

## 🛠️ Technologies Used

### Frontend
- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS Grid, Flexbox, and Custom Properties
- **JavaScript (ES6+)** - Dynamic content rendering and interactivity

### Libraries & Tools
- **Font Awesome** - Icons
- **Google Fonts** - Typography (Inter, Space Grotesk)
- **EmailJS** - Contact form integration
- **GitHub Pages** - Hosting

### Design Features
- CSS Variables for theming
- Intersection Observer API for scroll animations
- LocalStorage for theme persistence
- Responsive Grid & Flexbox layouts

---

## 🚀 Quick Start

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/VIJAYADITYARV/portfolio.git
   cd portfolio
   ```

2. **Open in browser**
   ```bash
   # Simply open index.html in your browser
   # Or use a local server (recommended)
   
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (with http-server)
   npx http-server
   
   # Using VS Code Live Server extension
   # Right-click on index.html -> "Open with Live Server"
   ```

3. **View the site**
   ```
   http://localhost:8000
   ```

---

## ⚙️ Configuration

### EmailJS Setup (Contact Form)

To enable the contact form, update `script.js` with your EmailJS credentials:

```javascript
// In script.js, find the EmailJS initialization section:
emailjs.init("YOUR_PUBLIC_KEY");

// Update the service and template IDs:
emailjs.send("YOUR_SERVICE_ID", "YOUR_TEMPLATE_ID", {
    name: document.getElementById("name").value,
    email: document.getElementById("email").value,
    message: document.getElementById("message").value,
});
```

**Get your credentials:**
1. Sign up at [EmailJS](https://www.emailjs.com/)
2. Create a service (Gmail, Outlook, etc.)
3. Create an email template
4. Copy your Public Key, Service ID, and Template ID

---

## 🎨 Customization

### Update Personal Information

**Edit `script.js` to customize:**

```javascript
// Tech Stack
const techStackData = [
    { icon: '⚛', name: 'React' },
    // Add or modify technologies
];

// Projects
const projectData = [
    {
        title: "Your Project Name",
        tags: ['Tech1', 'Tech2'],
        description: "Project description...",
        // ...
    }
];

// Skills, testimonials, and learning data
// All located in script.js
```

### Change Theme Colors

Edit CSS variables in `styles.css`:

```css
:root[data-theme="dark"] {
    --color-bg: #0a0a0f;
    --color-accent: #3b82f6;
    /* Customize colors */
}
```

### Replace Profile Picture

Replace `profile.jpg` with your own image (recommended: 800x800px or similar aspect ratio)

---

## 📦 Deployment

### GitHub Pages

1. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

2. **Enable GitHub Pages**
   - Go to repository Settings
   - Navigate to "Pages" section
   - Source: Deploy from branch `main`
   - Folder: `/ (root)`
   - Click Save

3. **Access your site**
   ```
   https://YOURUSERNAME.github.io/REPO-NAME
   ```

### Custom Domain (Optional)

1. Add a `CNAME` file with your domain:
   ```
   yourdomain.com
   ```

2. Update DNS settings with your domain provider

---

## 📊 Portfolio Sections

### 🏠 Home
- Hero section with introduction
- Tech stack showcase
- Quick links to social profiles

### 👨‍💻 About
- Professional summary
- Key statistics
- Areas of interest
- Currently learning

### 🎓 Education
- Academic qualifications
- Relevant coursework
- Industry certifications (AWS)

### 💪 Skills
- Technical skills categorized by domain
- Learning progress tracker

### 🚀 Projects
- 6 featured projects with:
  - Tech stack tags
  - Detailed descriptions
  - Key metrics
  - Live demo & GitHub links

### 💬 Testimonials
- Peer reviews
- GitHub activity stats

### 📧 Contact
- Contact form with EmailJS
- Social media links
- Professional information

---

## 🎯 Performance

- **Lighthouse Score**: 95+ (Performance, Accessibility, Best Practices, SEO)
- **Load Time**: < 2 seconds
- **Mobile-First**: Optimized for mobile devices
- **SEO Ready**: Meta tags, semantic HTML, alt attributes

---

## 🤝 Contributing

This is a personal portfolio project, but suggestions are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

You're free to use this template for your own portfolio! Just remember to:
- Update all personal information
- Replace profile picture
- Update EmailJS credentials
- Customize colors and content

---

## 📬 Contact

**Vijay Aditya R V**

- 📧 Email: [vijayadityarv@gmail.com](mailto:vijayadityarv@gmail.com)
- 💼 LinkedIn: [linkedin.com/in/vijay-aditya-r-v](https://in.linkedin.com/in/vijay-aditya-r-v)
- 🐙 GitHub: [github.com/VIJAYADITYARV](https://github.com/VIJAYADITYARV)
- 📄 Resume: [View PDF](https://drive.google.com/file/d/1psRnezARcynav-tT-mXkNaRBN_8jjrmR/view?usp=sharing)

---

## 🙏 Acknowledgments

- **Font Awesome** for icons
- **Google Fonts** for typography
- **EmailJS** for contact form functionality
- **GitHub Pages** for free hosting

---

## 📸 Screenshots

### Desktop View
![Desktop Screenshot](screenshots/desktop.png)

### Mobile View
![Mobile Screenshot](screenshots/mobile.png)

### Dark Mode
![Dark Mode](screenshots/dark-mode.png)

---

<div align="center">

### ⭐ Star this repo if you find it helpful!

**Made with ❤️ by Vijay Aditya R V**

[🔝 Back to Top](#-vijay-aditya-r-v---personal-portfolio)

</div>
