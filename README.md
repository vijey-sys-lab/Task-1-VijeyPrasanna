# DevCraft — Responsive Frontend Interface
### DecodeLabs Full Stack Internship · Project 1 · Batch 2026

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)

---

## 📌 Project Overview

**DevCraft** is a fully responsive frontend web interface built as **Project 1** of the DecodeLabs Full Stack Development Internship Program (Batch 2026). The goal was to master the fundamentals of responsive web design using only **HTML5, CSS3, and Vanilla JavaScript** — no frameworks, no shortcuts.

> "The absolute best way to master Full Stack Development is through hands-on practice, not just theory." — DecodeLabs

---

## 🔗 Live Demo

🌐 **[View Live →](https://your-live-link.netlify.app)**  
📂 **[GitHub Repository →](https://github.com/your-username/decodelabs-project1)**

---

## 🎯 Project Requirements

| Requirement | Status |
|---|---|
| Pure HTML, CSS, JS — No Frameworks | ✅ Complete |
| Responsive layout for different screen sizes | ✅ Complete |
| Clean and user-friendly UI | ✅ Complete |
| Semantic HTML5 landmarks | ✅ Complete |
| Mobile-first approach | ✅ Complete |
| WCAG Accessibility compliance | ✅ Complete |

---

## 🏛️ The Three Pillars (DecodeLabs Framework)

### Pillar 1 — Strategy & Blueprint
- User research approach using Empathy Maps
- Low-fidelity wireframing focused on hierarchy and flow
- Golden Rule applied: designed in grayscale first

### Pillar 2 — Visual Design & 2025 Aesthetics
| Color | Hex | Role |
|---|---|---|
| Mocha Mousse | `#A5856F` | Stability / Primary |
| Ethereal Blue | `#A0D4E0` | Trust / Accent |
| Moonlit Grey | `#F2F0EA` | Refinement / Background |

**Typography:**
- Headlines — `Montserrat` (Geometric, 800/600 weight)
- Body — `Roboto` (Readable, 400/300 weight)
- Constraint: Max 2 font families, 3 weights

### Pillar 3 — Implementation
- **HTML5:** `<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, `<footer>`
- **CSS:** Grid (macro layouts) + Flexbox (micro components) + `clamp()` fluid typography
- **JS:** Mobile menu state, scroll reveal, counter animations, active nav highlighting

---

## 📐 Responsive Architecture

```
Mobile (< 768px)     →  Single column, hamburger menu
Tablet (≥ 768px)     →  2-column grid, expanded nav
Desktop (≥ 1024px)   →  3-column grid, full navigation
```

Built **mobile-first** using `min-width` media queries as specified in the DecodeLabs blueprint.

---

## ⚙️ The 6-Phase Execution Roadmap

```
Phase 1 — Discovery      Define "How Might We" — user problem first
Phase 2 — Wireframe      Grayscale, mobile-first layout planning
Phase 3 — Semantics      HTML5 landmark structure
Phase 4 — Style          CSS Grid/Flex + 2025 colour palette
Phase 5 — Logic          Vanilla JS interactivity & state
Phase 6 — Audit          LCP/CLS checks + accessibility pass
```

---

## 🗂️ Project Structure

```
decodelabs-project1/
│
└── index.html          # Complete single-file application
                        # (HTML + CSS + JavaScript)
```

> Single-file architecture as per the project scope — all CSS is in `<style>` and all JS is in `<script>` within `index.html`.

---

## ✨ Features Built

- **Sticky navigation header** with smooth scroll links
- **Mobile hamburger menu** with animated open/close state
- **Hero section** with blueprint grid background and browser mockup
- **Stats band** with count-up animation on scroll
- **Features grid** — 3-column on desktop, 2 on tablet, 1 on mobile
- **How It Works** section with numbered steps
- **Testimonials** card grid
- **CTA section** with gradient background
- **Footer** with 4-column layout collapsing to 2 on mobile
- **Scroll reveal animations** with IntersectionObserver (staggered)
- **Active nav link** highlighting on scroll
- **Skip-to-content** accessibility link
- **ARIA labels, roles, and focus-visible** indicators throughout
- **`prefers-reduced-motion`** media query support

---

## ♿ Accessibility (WCAG Compliance)

- Semantic HTML5 landmark roles (`role="banner"`, `role="main"`, etc.)
- Skip navigation link for keyboard users
- All interactive elements have `aria-label` or `aria-expanded`
- `focus-visible` outlines on all focusable elements
- Color contrast meets WCAG AA standards
- `prefers-reduced-motion` respected — animations disabled for users who opt out
- Screen-reader-only text via `.sr-only` utility class

---

## 🚀 How to Run Locally

No build tools needed. Just open the file:

```bash
# Clone the repository
git clone https://github.com/your-username/decodelabs-project1.git

# Navigate into the folder
cd decodelabs-project1

# Open in browser
open index.html
# or just double-click index.html
```

---

## 🌐 Deployment (Netlify)

1. Go to [netlify.com](https://netlify.com)
2. Drag and drop the project folder into the deploy area
3. Your site is live instantly

---

## 👤 Author

**Vijey Prasanna**  
Full Stack Development Intern — DecodeLabs Batch 2026  
📧 vjysupermacy@gmail.com  
🌐 [devverse1.in](https://devverse1.in)  
📷 [@vjysupermacy](https://instagram.com/vjysupermacy)

---

## 🏢 About DecodeLabs

DecodeLabs is an industrial training program that bridges the gap between learning code and building real-world projects. Project 1 is the mandatory starting point for all interns — mastering responsive frontend fundamentals before progressing to backend and full-stack development.

📞 +91 89330 06408  
✉️ decodelabs.tech@gmail.com  
🌐 [www.decodelabs.tech](https://www.decodelabs.tech)  
📍 Greater Lucknow, India

---

*Built with zero frameworks. Mastered with 100% fundamentals.*
