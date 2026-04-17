# 💰 Mutual Fund Landing Page — PPFAS-Style UI

A production-quality mutual fund landing page built as a portfolio project for a Junior Web Designer role in fintech.
**Created by Prateek Chaudhari.**

---

## 🎯 Key Highlights
- Built a responsive fintech landing page aligned with real mutual fund platforms
- Converted UI design concepts into structured HTML/CSS layouts
- Developed cross-client compatible HTML email template using table-based design
- Ensured consistency in spacing, typography, and component-based UI

---

## 🚀 Live Demo
[View Live Project](https://prateekchaudhari.github.io/ppfas-landing-page/)

## 🎨 Figma Design
[View Figma Design](#)

---

## 🛠️ Tech Stack
- **HTML5 & CSS3**
- **Bootstrap 5** (Layout, responsiveness)
- **CSS Custom Properties** (Theming, component modularity)
- **Table-based HTML** (For cross-client email compatibility)

---

## 📁 Project Structure

```text
/ppfas-landing-page
│
├── /css
│   └── styles.css          # Custom CSS (overriding/augmenting Bootstrap)
│
├── index.html              # The main Landing Page (Home)
├── fund-details.html       # Secondary page (Deep dive into fund metrics - coming soon)
├── email-template.html     # The standalone HTML Email Campaign (Table-based)
└── README.md               # Project documentation
```

## 📐 Design System

- **Color Palette:** Trust Blue (`#1A3C6E`), Growth Green (`#2ECC71`), Clean Whites/Greys.
- **Typography:** `Inter` for exceptional legibility with financial data.
- **Spacing:** Strict 8px grid system.

## 📱 Responsive Implementation

Built with a mobile-first approach. Uses Bootstrap's grid system combined with custom media queries to ensure the Hero section, Trust Stats, and Fund Cards degrade gracefully on tablet and mobile devices. Touch targets are optimized for mobile accessibility.

## ✉️ Email Template

Includes a standalone `email-template.html` specifically designed for email clients. Built entirely using 1999-era `<table>` layouts and inline CSS to ensure perfect rendering across Gmail, Outlook, and Apple Mail, bypassing their CSS stripping behaviors.
