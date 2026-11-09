# Legal Files — High-Stakes Legal Counsel Landing Page

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Website-brightgreen?style=for-the-badge)](https://priyanshu-onestar.github.io/legal-files-landing-page/)

> 🌐 **Live Website**: [https://priyanshu-onestar.github.io/legal-files-landing-page/](https://priyanshu-onestar.github.io/legal-files-landing-page/)

A modern, responsive, high-converting landing page built for high-stakes corporate law and legal counsel practices. Designed with a clean luxury aesthetic, accessible UI patterns, and lightweight vanilla web technologies.

![Preview](https://images.unsplash.com/photo-1497366216548-37526070297c?auto=format&fit=crop&q=80&w=1200)

## ✨ Features

- **Luxury Editorial Design**: Tailored for high-stakes legal practices using bespoke typography (*Cormorant Garamond* & *Inter*) and refined color palettes.
- **Pure Vanilla Web Tech**: Zero external build dependencies—crafted with pure HTML5, CSS3 custom properties, and modern vanilla JavaScript.
- **Fully Responsive**: Optimized fluid layouts (`clamp()`), mobile slide-out navigation with focus management, and touch-friendly targets.
- **Interactive UI Components**:
  - Sticky glassmorphic navigation with scroll detection.
  - Scroll-triggered reveal animations powered by `IntersectionObserver`.
  - Accessible multi-slide testimonial carousel with screen-reader states (`aria-hidden`).
  - Simulated consultation booking form with HTML5 validation and processing state feedback.
- **Accessibility & Performance First**: Built-in ARIA attributes, semantic landmarks, high-contrast focus rings, and lazy-loaded media assets.

---

## 🎨 Design System

| Element | Specification |
|---|---|
| **Deep Navy** | `#101D2C` (Primary background & high-contrast dark tones) |
| **Warm Ivory** | `#F8F6F1` (Light background & contrast text) |
| **Accent Gold** | `#B99A62` (Interactive highlights & key accents) |
| **Serif Heading** | Cormorant Garamond (Google Fonts) |
| **Sans Body** | Inter (Google Fonts) |

---

## 📂 Project Structure

```text
├── index.html                     # Main entrypoint (ready for GitHub Pages)
├── legal_files_landing_page.html   # Original standalone landing page template
└── README.md                      # Project documentation
```

---

## 🚀 Getting Started

### 1. View Locally
Simply clone the repository and open `index.html` in any modern web browser:

```bash
git clone https://github.com/Priyanshu-onestar/legal-files-landing-page.git
cd legal-files-landing-page
# Open index.html in your default browser:
# On Windows:
start index.html
# On macOS:
open index.html
```

Or serve using Python:
```bash
python -m http.server 8000
```
Then navigate to `http://localhost:8000`.

### 2. Host on GitHub Pages
1. Go to repository **Settings** on GitHub.
2. Select **Pages** from the sidebar.
3. Under **Branch**, select `main` and root folder `/`.
4. Click **Save**. Your site will be live at `https://priyanshu-onestar.github.io/legal-files-landing-page/`!

---

## 📄 License
This project is open source and available under the [MIT License](LICENSE).
