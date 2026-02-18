# 👨‍💻 Raj Kumawat (RK Logix) - MERN Stack Developer Portfolio

![Portfolio Banner](https://img.shields.io/badge/version-2.0.0-blue)
![Status](https://img.shields.io/badge/status-live-success)
![License](https://img.shields.io/badge/license-MIT-green)

<div align="center">
  <img src="assets/images/preview.gif" alt="Portfolio Preview" width="600">
  <br>
  <a href="https://rklogix.dev"><strong>🔗 Live Demo</strong></a> •
  <a href="https://github.com/rklogixtech/portfolio"><strong>📦 GitHub Repo</strong></a>
</div>

---

## 📋 **Table of Contents**
- [About](#-about)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Live Demo](#-live-demo)
- [Screenshots](#-screenshots)
- [Installation](#-installation)
- [Configuration](#-configuration)
- [Usage](#-usage)
- [Folder Structure](#-folder-structure)
- [Customization](#-customization)
- [Deployment](#-deployment)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)

---

## 🎯 **About**

A modern, responsive portfolio website for **Raj Kumawat** - MERN Stack Developer and Founder of RK Logix. This portfolio showcases my journey from Web Designer to MERN Stack Developer after completing intensive training at **Groot Academy, Jaipur**.

**What makes this portfolio special?**
- ✨ Dark theme with beautiful gradients
- 📱 Fully responsive on all devices
- 📧 Working contact form with EmailJS
- 🚀 Fast and lightweight
- 🎨 Modern UI/UX design

---

## ✨ **Features**

### ✅ Core Features
| Feature | Description |
|---------|-------------|
| **Responsive Design** | Works perfectly on mobile, tablet, and desktop |
| **Dark Theme** | Modern gradient-based UI with smooth animations |
| **Contact Form** | EmailJS integration - no backend needed |
| **Project Filtering** | Filter projects by category (HTML, MERN, E-commerce) |
| **Skills Animation** | Circular progress indicators with percentages |
| **Testimonials Carousel** | Swiper.js powered client reviews |
| **WhatsApp Integration** | Floating chat button for instant contact |
| **CV Download** | Multiple download options (PDF, DOCX) |
| **Smooth Scroll** | Navigation between sections |
| **AOS Animations** | Scroll-based reveal animations |

### 🎯 Project Categories
- ✅ 4+ HTML/CSS/JS Projects
- ✅ 3+ MERN Stack Applications
- ✅ 1+ E-commerce Platform

---

## 💻 **Tech Stack**

### Frontend
```
├── HTML5          - Structure & semantics
├── CSS3           - Styling with custom properties
├── JavaScript     - ES6+ functionality
├── Font Awesome 6 - Icons & graphics
├── Google Fonts   - Inter & Playfair Display
```

### Libraries & Plugins
```
├── EmailJS        - Email functionality (free tier)
├── AOS            - Animate on Scroll
├── Swiper.js      - Testimonials carousel
├── Font Awesome   - Icon library
```

---

## 🌐 **Live Demo**

Check out the live version here:
- 🔗 **Live URL:** [https://rklogix.dev](https://rklogix.dev)
- 🔗 **GitHub:** [https://github.com/rklogixtech/portfolio](https://github.com/rklogixtech/portfolio)

---

## 📸 **Screenshots**

<div align="center">
  <table>
    <tr>
      <td><img src="assets/screenshots/hero-section.png" alt="Hero Section" width="400"></td>
      <td><img src="assets/screenshots/portfolio-section.png" alt="Portfolio" width="400"></td>
    </tr>
    <tr>
      <td align="center"><strong>Hero Section</strong></td>
      <td align="center"><strong>Portfolio Grid</strong></td>
    </tr>
    <tr>
      <td><img src="assets/screenshots/skills-section.png" alt="Skills" width="400"></td>
      <td><img src="assets/screenshots/contact-form.png" alt="Contact" width="400"></td>
    </tr>
    <tr>
      <td align="center"><strong>Skills Animation</strong></td>
      <td align="center"><strong>Contact Form</strong></td>
    </tr>
  </table>
</div>

---

## ⚙️ **Installation**

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Code editor (VS Code recommended)
- Git (optional)

### Step-by-Step Setup

1. **Clone the repository**
```bash
git clone https://github.com/rklogixtech/portfolio.git
cd portfolio
```

2. **Or download ZIP**
   - Download from GitHub
   - Extract to your desired folder

3. **Open with Live Server** (VS Code)
```bash
# Install Live Server extension
# Right-click index.html → Open with Live Server
```

4. **Or directly open in browser**
```bash
# Double-click index.html
# File will open in default browser
```

---

## 🔧 **Configuration**

### 1️⃣ **EmailJS Setup** (Free)

#### Step 1: Create Account
- Go to [EmailJS.com](https://www.emailjs.com/)
- Sign up for free account (200 emails/month)

#### Step 2: Connect Email Service
```
Dashboard → Email Services → Add New Service
→ Choose Gmail/Outlook → Connect Account
→ Copy Service ID (e.g., service_6qom5ml)
```


### 2️⃣ **WhatsApp Number**
Update floating button:
```html
<a href="https://wa.me/919876543210?text=Hi%20Raj..." class="whatsapp-float">
```

### 3️⃣ **Social Media Links**
Update these links:
```html
<a href="https://github.com/yourusername">
<a href="https://linkedin.com/in/yourprofile">
```

### 4️⃣ **CV Files**
Place your CV files in `cv/` folder:
```
cv/
├── Raj_Kumawat_MERN_Stack_CV.pdf
├── raj-kumawat-cv.pdf
└── raj-kumawat-resume.docx
```

---

## 📁 **Folder Structure**

```
RK-Logix-Portfolio/
│
├── 📄 index.html                 # Main HTML file
├── 📄 README.md                  # Documentation
├── 📄 LICENSE                    # MIT License
│
├── 📁 assets/
│   ├── 📁 images/                # Project images
│   │   ├── project-1.jpeg
│   │   ├── project-2.jpeg
│   │   ├── project-3.png
│   │   ├── project-4.png
│   │   ├── project-5.png
│   │   ├── project-6.png
│   │   ├── Blog Space.webp
│   │   └── EcoMart.webp
│   │
│   └── 📁 screenshots/           # README screenshots
│       ├── hero-section.png
│       ├── portfolio-section.png
│       ├── skills-section.png
│       └── contact-form.png
│
├── 📁 cv/                         # Resume/CV files
│   ├── Raj_Kumawat_MERN_Stack_CV.pdf
│   ├── raj-kumawat-cv.pdf
│   └── raj-kumawat-resume.docx
│
└── 📁 email-templates/            # Email templates
    └── email-template.html
```

---

## 🎨 **Customization Guide**

### Colors
Change CSS variables in `:root`:
```css
:root {
    --primary: #00ced1;     /* Teal */
    --secondary: #9d4edd;    /* Purple */
    --accent-1: #ff6b6b;     /* Red */
    --accent-2: #ffe66d;      /* Yellow */
}
```

### Personal Info
Update throughout `index.html`:
```html
<title>Your Name</title>
<h1 class="hero-name">Your Name</h1>
<div class="brand-name">Your Brand</div>
<p>raj@yourdomain.com</p>
```

### Projects
Edit project cards in portfolio section:
```html
<div class="project-card" data-category="mern">
    <h3 class="project-title">Your Project</h3>
    <p class="project-desc">Description here</p>
    <a href="live-link">Live Demo</a>
    <a href="github-link">GitHub</a>
</div>
```

---

## 🚀 **Deployment**

### Option 1: **GitHub Pages** (Free)

```bash
# 1. Create repository on GitHub
# 2. Push your code
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/yourusername/portfolio.git
git push -u origin main

# 3. Enable GitHub Pages
# Settings → Pages → Branch: main → Save
# Your site will be live at: https://yourusername.github.io/portfolio
```

### Option 2: **Vercel** (Recommended)

```bash
# 1. Install Vercel CLI
npm install -g vercel

# 2. Deploy
vercel

# Or visit vercel.com and import your repository
```

### Option 3: **Netlify**
- Drag & drop your folder to [Netlify Drop](https://app.netlify.com/drop)
- Or connect GitHub repository

---

## 📊 **Performance**

| Metric | Score |
|--------|-------|
| Lighthouse Performance | 95+ |
| Lighthouse Accessibility | 98+ |
| Lighthouse Best Practices | 100 |
| SEO | 100 |
| Load Time | < 2s |

---

## 🤝 **Contributing**

Contributions are welcome! Here's how:

1. **Fork** the repository
2. **Create** feature branch
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Commit** changes
   ```bash
   git commit -m 'Add AmazingFeature'
   ```
4. **Push** to branch
   ```bash
   git push origin feature/AmazingFeature
   ```
5. **Open** a Pull Request

---

## 📝 **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2025 Raj Kumawat (RK Logix)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files...
```

---

## 📞 **Contact**

### Raj Kumawat
**MERN Stack Developer & Founder @ RK Logix**

<div align="center">
  
[![Email](https://img.shields.io/badge/Email-raj@rklogix.dev-red?style=for-the-badge&logo=gmail)](mailto:raj@rklogix.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/raj-kumawat-702503218/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?style=for-the-badge&logo=github)](https://github.com/rklogixtech)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-Chat-green?style=for-the-badge&logo=whatsapp)](https://wa.me/919876543210)

</div>

---

## 🙏 **Acknowledgments**

- **Groot Academy, Jaipur** - MERN Stack Training
- **EmailJS** - Free email service
- **Font Awesome** - Icons
- **Google Fonts** - Typography
- **Swiper.js** - Carousel
- **AOS** - Scroll animations

---

## 📈 **GitHub Stats**

<div align="center">
  
![GitHub stars](https://img.shields.io/github/stars/rklogixtech/portfolio?style=social)
![GitHub forks](https://img.shields.io/github/forks/rklogixtech/portfolio?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/rklogixtech/portfolio?style=social)
![GitHub followers](https://img.shields.io/github/followers/rklogixtech?style=social)

</div>

---

### ⭐ **Show your support**

Give a ⭐ if you like this project!

---

<div align="center">
  <strong>Made with ❤️ in Jaipur, Rajasthan</strong>
  <br>
  <sub>© 2025 Raj Kumawat (RK Logix). All rights reserved.</sub>
</div>
