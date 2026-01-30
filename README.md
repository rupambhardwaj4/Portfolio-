# 🚀 Rupam Bhardwaj - Creative Developer Portfolio

A modern, visually striking, and fully responsive personal portfolio website showcasing web development expertise, projects, and professional experience.

![Live](https://img.shields.io/badge/Live-Portfolio-success)
![Portfolio Preview](https://img.shields.io/badge/Status-Live-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Responsive](https://img.shields.io/badge/Responsive-Yes-success)

🔗 **Live Preview:** 👉 **https://bhardwajportfolio.netlify.app/**

---

## ✨ Features

### 🎨 Design & UX
- **Modern Glassmorphism UI** with gradient accents
- **Orbital Tech Stack Animation** - Unique rotating technology display
- **Smooth Page Transitions** with intersection observer
- **Micro-interactions** on all interactive elements
- **Dark Theme** with gradient highlights
- **Mobile-First Responsive Design**

### 🔥 Sections

#### 1. **Hero Section**
- Animated gradient background with floating orbs
- Circular profile image with pulse animation
- Call-to-action buttons (View Projects, Contact, Download Resume)
- Direct social links (GitHub, LinkedIn)
- Interactive orbital tech stack display

#### 2. **About Me**
- Personal bio and introduction
- Animated education timeline
- Visual timeline with hover effects

#### 3. **Skills & Expertise**
- **6 Skill Categories:**
  - Languages (JavaScript, Python, HTML5, CSS3, TypeScript, etc.)
  - Frontend (React, Next.js, Flutter, Tailwind CSS, etc.)
  - Backend & Database (Node.js, MongoDB, MySQL, Firebase, etc.)
  - Tools & Platforms (Git, Figma, Docker, VS Code, etc.)
  - Core Competencies (UI/UX, Performance, Agile, etc.)
  - AI & Emerging Tech (AI Integration, OpenAI APIs, etc.)
- **Color-Coded Status Indicators:**
  - 🟢 Green = Proficient
  - 🟠 Orange = Learning
- Animated skill tags with hover effects

#### 4. **Experience**
- **4 Professional Experiences:**
  - Frontend Developer Intern - QUALITHAR CONSULTANCY (2025)
  - Android Developer Intern - EduSkills & Google (2025)
  - Frontend Developer - Hackspire Hackathon (2024)
  - Web Development Intern - NASSCOM (2025)
- Glassmorphic cards with detailed responsibilities
- Hover animations and gradient effects

#### 5. **Projects**
- **Featured Projects:**
  - CampusCode (Ongoing - with live badge)
  - Yum Maker
  - Interactive Portfolio
- Live demo and GitHub repository links
- Technology tags and descriptions
- Gradient backgrounds with shimmer effects

#### 6. **Services**
- 6 Professional service cards
- Icons with rotation animations
- Comprehensive service descriptions

#### 7. **Training & Certifications**
- **Horizontal scrollable design**
- **9 Certifications:**
  - Unstop Talent Park
  - NASSCOM PBEL Internship
  - GUVI Python Certification
  - Cisco Cybersecurity
  - Microsoft Learn
  - MongoDB Certifications
  - IBM Web Development
  - Google Android Developer
- Clickable certificate links
- Custom scrollbar design

#### 8. **Contact**
- Email link with icon
- Social media links (LinkedIn, GitHub)
- Contact form with gradient submit button
- Glassmorphic form design

---

## 🛠️ Technologies Used

### Frontend
- **HTML5** - Semantic markup
- **CSS3** - Custom properties, animations, glassmorphism
- **JavaScript** - Vanilla JS for interactions
- **Font Awesome 6.5.1** - Icon library
- **Google Fonts** - Poppins typography
- **Tailwind CSS CDN** - Utility classes

### Design Principles
- Mobile-first responsive design
- CSS Grid & Flexbox layouts
- CSS Custom Properties (variables)
- Smooth scroll behavior
- Intersection Observer API
- CSS animations & keyframes

### Performance
- Optimized animations (60fps)
- Lazy loading considerations
- Minimal dependencies
- Pure CSS effects
- Efficient DOM manipulation

---

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic text editor (VS Code recommended)

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/rupam-bhardwaj/portfolio.git
cd portfolio
```

2. **Open the portfolio**
```bash
# Use Live Server in VS Code for development
```

3. **Customize (Optional)**
- Update personal information in the HTML
- Modify colors in CSS variables
- Add your own projects and experiences
- Replace placeholder links with actual URLs

---

## 📱 Responsive Breakpoints

```css
/* Desktop */
Default: 1440px max-width

/* Tablet */
@media (max-width: 1024px)

/* Mobile */
@media (max-width: 768px)

/* Small Mobile */
@media (max-width: 480px)
```

---

## 🎨 Color Palette

```css
/* Primary Colors */
--bg-dark: #0a0a0f
--text-primary: #ffffff
--text-secondary: #a0a0b8

/* Gradients */
--gradient-accent: linear-gradient(135deg, #667eea 0%, #764ba2 50%, #f093fb 100%)
--gradient-1: linear-gradient(135deg, #667eea 0%, #764ba2 100%)
--gradient-2: linear-gradient(135deg, #f093fb 0%, #f5576c 100%)
--gradient-3: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%)

/* Status Colors */
Proficient: #10b981 (Green)
Learning: #f59e0b (Orange)

/* Glassmorphism */
--glass-bg: rgba(255, 255, 255, 0.05)
--glass-border: rgba(255, 255, 255, 0.1)
```

---

## ⚙️ Customization Guide

### Update Personal Information

1. **Profile Image**
   - Replace the SVG placeholder in the hero section
   - Recommended size: 140x140px (mobile), 180x180px (desktop)

2. **Resume Download**
   - Update the `href` attribute in the Download Resume button
   - Add your resume PDF to the project

3. **Project Links**
   - Update `href` attributes in project cards
   - Add actual GitHub repository URLs
   - Update live demo links

4. **Social Media**
   - Update LinkedIn and GitHub URLs in hero and footer
   - Add additional social links if needed

5. **Contact Email**
   - Replace `rupambhardwaj4@gmail.com` with your email
   - Update form submission handler if needed

### Modify Colors

Edit CSS variables in the `:root` selector:
```css
:root {
    --bg-dark: #your-color;
    --gradient-accent: your-gradient;
    /* etc. */
}
```

### Add/Remove Sections

Each section is wrapped in `<section id="section-name">` tags. Simply add or remove sections as needed, and update the navigation links accordingly.

---

## 📊 Key Features Breakdown

### Orbital Tech Stack Animation
```javascript
// Continuous orbital rotation with counter-rotation
// Inner orbit: 30s clockwise
// Outer orbit: 40s counter-clockwise
// Icons remain upright while orbiting
```

### Intersection Observer
```javascript
// Sections fade in when scrolled into view
// Smooth animations triggered on visibility
// Performance optimized with threshold settings
```

### Scroll Progress Indicator
```javascript
// Visual progress bar at top of page
// Shows reading progress as user scrolls
// Gradient colored for brand consistency
```

---

## 🎯 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

---

## 📈 Performance

- **Lighthouse Scores:**
  - Performance: 95+
  - Accessibility: 90+
  - Best Practices: 95+
  - SEO: 100

- **Optimization Techniques:**
  - CSS-only animations (no JavaScript animation libraries)
  - Efficient DOM queries
  - Minimal external dependencies
  - Optimized images and icons
  - Smooth 60fps animations

---

## 🤝 Contributing

While this is a personal portfolio, suggestions and improvements are welcome!

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👤 Author

**Rupam Bhardwaj**

- Email: rupambhardwaj4@gmail.com
- LinkedIn: [linkedin.com/in/rupam-bhardwaj](https://www.linkedin.com/in/rupam-bhardwaj)
- GitHub: [github.com/rupam-bhardwaj](https://github.com/rupam-bhardwaj)
- Portfolio: [Your Portfolio URL]

---

## 🎓 Education

**B.Tech in Computer Science & Engineering**  
2023 – 2027 (Ongoing) | SGPA: 7.8

---

## 🏆 Certifications

- Certificate of Excellence - Unstop Talent Park (2025)
- PBEL Virtual Internship - NASSCOM (2025)
- Python Zero to Hero - GUVI (2024)
- Cybersecurity Essentials - Cisco (2023)
- Microsoft Learn Certifications (2024)
- MongoDB Certifications (2023)
- Web Development Training - IBM (2025)
- Android Developer - Google For Developer (2025)

---

## 📞 Contact

For any queries or collaboration opportunities, feel free to reach out:

- 📧 Email: rupambhardwaj4@gmail.com
- 💼 LinkedIn: [Rupam Bhardwaj](https://www.linkedin.com/in/rupam-bhardwaj-260b61319/)
- 🐱 GitHub: [rupam-bhardwaj](https://github.com/rupambhardwaj4)

---

## 🌟 Acknowledgments

- Font Awesome for icon library
- Google Fonts for Poppins typography
- Inspiration from modern portfolio designs
- Community feedback and suggestions

---

<div align="center">

**⭐ If you like this portfolio, please give it a star!**

Made with ❤️ by Rupam Bhardwaj

</div>
