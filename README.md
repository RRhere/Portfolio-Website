# 🔥 My Portfolio

A modern, responsive, red-and-black themed developer portfolio built using HTML, CSS, and JavaScript.

Designed to showcase projects, skills, experience, and contact information with smooth animations, glassmorphism UI, and EmailJS integration.

---

## 🚀 Live Features

- Modern Red & Black UI
- Fully Responsive Design
- Glassmorphism Cards
- Smooth Scroll Animations
- Animated Typing Hero Section
- Interactive Hover Effects
- EmailJS Contact Form Integration
- Custom Cursor Glow
- Project Showcase Section
- Skills / Education / Work Tabs
- Mobile Friendly Layout

---

## 🛠️ Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript

### Libraries & Services
- Font Awesome
- Google Fonts
- EmailJS

---

## 📂 Project Structure

```bash
portfolio/
│
├── index.html
├── style.css
├── icon.ico
├── README.md
│
├── cv/
│   └── cv.pdf
│
└── assets/
```
---

## ⚡ Getting Started
1. Clone Repository
git clone https://github.com/RRhere/RRhere.git
2. Open Project
Open the folder in VS Code or any editor.
3. Run Locally

You can simply open:
index.html

OR use Live Server extension in VS Code.

## 📧 EmailJS Setup

This portfolio uses EmailJS for the contact form.

Step 1 — Create EmailJS Account

Visit:

https://www.emailjs.com/

Step 2 — Create Email Service
Connect Gmail
Create Email Service

Example:

service_portfolio
Step 3 — Create Email Template

Template variables:

{{from_name}}
{{email}}
{{title}}

Example template:

New Portfolio Message

Name: {{from_name}}

Email: {{email}}

Message:
{{title}}
Step 4 — Add Public Key

Inside index.html:

emailjs.init("YOUR_PUBLIC_KEY");
Step 5 — Update JavaScript

Replace:

service_portfolio
template_portfolio

with your actual EmailJS values.

## 🎨 UI Features
Hero Section
Animated typing effect
Gradient glow background
Smooth CTA buttons
About Section
Skills
Education
Work Experience tabs
Projects Section
Interactive project cards
Hover animations
Contact Section
EmailJS integration
Real-time message status
📱 Responsive Design

Optimized for:

Desktop
Laptop
Tablet
Mobile Devices

## ✨ Customization
Change Accent Color

Inside style.css:

:root{
    --accent:#ff2b2b;
}
Update Typing Text

Inside index.html:

const words = [
    "Ragav",
    "a Full Stack Developer",
    "a Tech Enthusiast",
    "a Problem Solver"
];
Add Projects

Duplicate this block:

<div class="work glass hidden">
</div>

## 🌐 Deployment

You can deploy using:

GitHub Pages
Netlify
Vercel

## 📸 Preview

Features a modern developer-focused design inspired by:

SaaS Landing Pages
Modern Portfolio Websites
Glassmorphism UI Trends

## 👨‍💻 Author
Ragav Radhesh

Connect With Me
GitHub: https://github.com/RRhere
LinkedIn: https://www.linkedin.com/in/ragavradhesh/

## 📄 License

This project is open-source and available under the MIT License.

## ⭐ Support

If you like this project:

Star the repository
Fork the project
Share it with others

---

**Last Updated**: May 2026