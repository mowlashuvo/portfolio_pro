# Portfolio Website README

This README describes the structure, features, and setup instructions for the **Arfatul Mowla Shuvo – Portfolio Website**, built with HTML, CSS, and JavaScript.

---

## 🚀 Overview

This is a modern, responsive personal portfolio website showcasing:

* Hero section with introduction
* About section
* Work experience timeline
* Skills categorized visually
* Projects grid with images & descriptions
* Contact information and form UI
* Light/Dark theme toggle
* Mobile-friendly drawer navigation

The design uses:

* **HTML5**
* **CSS3** (modular styles)
* **JavaScript** for interactions
* **Font Awesome** icons
* **Google Fonts (Inter)**

---

## 📂 Project Structure

```
project-folder/
│
├── index.html
├── styles/
│   ├── main.css
│   ├── navigation.css
│   ├── sections.css
│   ├── theme.css
│
├── scripts/
│   ├── main.js
│   ├── animations.js
│   ├── theme.js
│
├── assets/
│   ├── images/
│   │   ├── profile.png
│   │   ├── favicon.ico
│   │   ├── companies/
│   │   ├── skills/
│   │   └── projects/
│   └── documents/
│       └── resume.pdf
```

---

## ✨ Features

### 🌗 Theme Toggle

* Switches between light and dark mode
* Works on both desktop & mobile
* Saves preference in local storage

### 📱 Mobile Navigation

* Smooth slide-in drawer
* Overlay click to close
* Accessible menu icons

### 🎨 Modern UI Components

* Gradient headings
* Cards for profile, skills, projects
* Animated hero section
* Timeline-style experience layout

### 📧 Contact Form (Frontend)

* Name, Email, Subject, Message
* Ready for backend integration

---

## 🛠️ Setup & Usage

1. Download or clone the project:

```
git clone https://github.com/your-repo/portfolio.git
```

2. Open `index.html` in any browser.
3. Replace images & content under `assets/`.
4. Update your resume at:

```
assets/documents/resume.pdf
```

---

## 🔧 Customization Guide

### Update Name & Titles

Modify in the **Hero section** inside `index.html`:

```html
<h1>Arfatul Mowla <span class="gradient-text">Shuvo</span></h1>
<h2>Mobile App Developer</h2>
```

### Update Social Links

Search for icons in `hero`, `footer`, and `profile-card` sections.

### Replace Images

Drop new images inside:

```
assets/images/
```

Use the same file names or update the HTML references.

### Add New Projects

Copy an existing project card and replace details:

```html
<div class="project-card">
   ...
</div>
```

---

## 🧪 Known Enhancements (Optional)

* Connect contact form to backend (Node.js/PHP/Firebase)
* Add animations on scroll
* Add blogs section
* Use a CSS framework (Tailwind/Bootstrap) if needed

---

## 📄 License

This project is free for personal and professional use.

---

## 💬 Contact

If you'd like help improving the website, feel free to reach out:
**Email:** [mowlashuvo2@gmail.com](mailto:mowlashuvo2@gmail.com)

---

Thank you for using this portfolio template! 🚀
