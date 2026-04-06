<div align="center">

<br/>

```
███████╗██╗     ██╗      █████╗
██╔════╝██║     ██║     ██╔══██╗
█████╗  ██║     ██║     ███████║
██╔══╝  ██║     ██║     ██╔══██║
███████╗███████╗███████╗██║  ██║
╚══════╝╚══════╝╚══════╝╚═╝  ╚═╝
```

# Ella Homestay — Kuttikanam, Kerala

### A premium, single-file website for a nature homestay in the Western Ghats

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![SEO](https://img.shields.io/badge/SEO-Optimised-4CAF50?style=flat-square&logo=google&logoColor=white)](https://developers.google.com/search)
[![Mobile](https://img.shields.io/badge/Mobile-Responsive-0078D4?style=flat-square&logo=googlechrome&logoColor=white)](https://web.dev/responsive-web-design-basics/)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)](LICENSE)

<br/>

> *"A quiet retreat in the Western Ghats. Tradition, nature, and genuine warmth — 900 metres above the ordinary."*

<br/>

**[🌐 View Live Site](#)** &nbsp;·&nbsp; **[📸 Screenshots](#-screenshots)** &nbsp;·&nbsp; **[⚙️ Features](#-features)** &nbsp;·&nbsp; **[🛠️ Tech Stack](#-tech-stack)**

<br/>

---

</div>

## 📌 About the Project

This is a **fully custom, zero-dependency website** built for **Ella Homestay**, a nature retreat near Kuttikanam and Wagamon in Kerala's Western Ghats.

The client's existing site was running on a generic hotel template with placeholder content, outdated branding, and no mobile optimisation. This redesign was built from scratch as a single `index.html` file — no frameworks, no build tools, no dependencies — delivering an **Awwwards-inspired editorial aesthetic** with production-grade code quality.

The design draws inspiration from premium hospitality websites, prioritising:
- Full-bleed cinematic atmosphere over stock-photo clutter
- Editorial typography and generous whitespace
- High-converting layout with clear calls-to-action
- Lightweight performance (single file, system + Google Font only)

<br/>

---

## ✨ Features

### 🎨 Design & UX
- **Custom cursor** with smooth trailing ring animation
- **Full-screen cinematic hero** — layered CSS gradients simulating mist, depth, and atmospheric lighting
- **Scroll-triggered reveal animations** — elements fade up as they enter the viewport via `IntersectionObserver`
- **Grain texture overlay** — subtle noise layer for tactile, editorial depth
- **Alternating light/dark section rhythm** — cream, parchment, dark soil, ink backgrounds for visual pacing
- **Asymmetric two-column hero layout** — headline left, description + CTAs right
- **Hover micro-interactions** — room cards lift, gallery items scale, nav links draw underlines from left

### 📐 Layout & Sections
| Section | Description |
|---|---|
| 🏔️ **Hero** | Full viewport, cinematic, animated mist, asymmetric copy layout |
| 📊 **Stats Strip** | Altitude · Rooms · Google Rating · Years hosting |
| 🏡 **About** | Story, Kerala heritage, property features grid |
| 🛏️ **Rooms** | 3 cards (Deluxe / Premium / Family Suite) with pricing, amenities |
| 🖼️ **Gallery** | Asymmetric mosaic grid, 5 photo slots |
| 🥾 **Activities** | Trekking · Fire Camp · Camp Stay · Sunrise Views |
| ⭐ **Reviews** | 4.8★ Google Reviews, 3 testimonials |
| 📋 **Booking Form** | Date pickers, room selector, success state |
| 🗺️ **Map** | Google Maps embed + location facts bar |
| 💬 **WhatsApp CTA** | Floating button + inline form CTA |

### 🔧 Technical
- **Zero dependencies** — pure HTML, CSS, JavaScript
- **Single file** — entire site in one `index.html`
- **CSS custom properties** — full design token system (`--ink`, `--gold`, `--fog`, etc.)
- **Mobile-first responsive** — fluid breakpoints at 1024px and 640px
- **Sticky nav with scroll detection** — transparent → frosted glass on scroll
- **IntersectionObserver** — performant scroll reveal, no layout jank
- **Semantic HTML5** — `<nav>`, `<section>`, `<footer>`, ARIA-friendly
- **SEO meta tags** — title, description, keywords, Open Graph

### 📱 WhatsApp & Conversion
- Pre-filled WhatsApp deep link (`wa.me`) with booking message
- Floating persistent WhatsApp button (bottom-right)
- Dual CTA strategy: form enquiry + instant WhatsApp
- Room cards with individual enquiry links

<br/>

---

## 🛠️ Tech Stack

```
┌─────────────────────────────────────────────┐
│  HTML5          Semantic structure & SEO     │
│  CSS3           Variables · Grid · Keyframes │
│  Vanilla JS     Cursor · Observer · Nav      │
│  Google Fonts   Cormorant Garamond · Jost    │
│  Google Maps    Embedded iframe              │
│  WhatsApp API   wa.me deep link              │
└─────────────────────────────────────────────┘
```

**No React. No Tailwind. No bundler. No npm.** Just clean, handcrafted code.

<br/>

---

## 📸 Screenshots

> *Add screenshots here once the site is live. Use browser dev tools to capture desktop (1440px) and mobile (375px) views.*

| Desktop — Hero | Desktop — Rooms |
|---|---|
| `[screenshot]` | `[screenshot]` |

| Mobile — Hero | Mobile — Booking |
|---|---|
| `[screenshot]` | `[screenshot]` |

> 💡 **Tip:** Use [Screely](https://screely.com) or [Shots.so](https://shots.so) to wrap screenshots in beautiful browser mockups before adding them here.

<br/>

---

## 🚀 Getting Started

This is a static single-file site. No installation required.

```bash
# Clone the repository
git clone https://github.com/Acnalroj/ella-homestay.git

# Open directly in browser
open index.html

# Or serve locally
npx serve .
# → http://localhost:3000
```

<br/>

---

## 📁 Project Structure

```
ella-homestay/
│
├── index.html          # Entire site — HTML + CSS + JS in one file
├── README.md           # This file
└── .gitattributes      # Git config
```

> All styles are in a `<style>` block inside `index.html`.
> All scripts are in a `<script>` block at the bottom of `index.html`.
> No external CSS/JS files needed.

<br/>

---

## 🌐 Deployment

This site can be deployed anywhere that serves static HTML.

### GitHub Pages (Free — Recommended)
1. Go to repo **Settings → Pages**
2. Branch: `main` → Folder: `/ (root)`
3. Click **Save**
4. Live at: `https://acnalroj.github.io/ella-homestay/`

### Other options
| Platform | Method | Cost |
|---|---|---|
| **Netlify** | Drag & drop `index.html` | Free |
| **Vercel** | `vercel deploy` | Free |
| **cPanel / Hosting** | Upload via File Manager | Varies |
| **Custom Domain** | Point domain to GitHub Pages | Domain cost only |

<br/>

---

## 🎯 Design Decisions

### Why single-file?
The client needs a fast, maintainable site they can hand off to any developer or upload directly to shared hosting — no build steps, no node_modules, no framework lock-in.

### Why Cormorant Garamond?
Premium hospitality sites use refined serif display typefaces to evoke luxury, nature, and timelessness. Cormorant Garamond's thin weight and high contrast echo the editorial quality of sites like Duyvenvoorde (Awwwards HM).

### Why CSS gradient "photography"?
Placeholder visuals are built with layered `radial-gradient` and `linear-gradient` to simulate depth and forest atmosphere — so the layout reads correctly even before real photos are added.

### Why no JavaScript framework?
Performance. A vanilla site loads instantly with zero JS overhead. The only JS used is ~40 lines for: custom cursor, scroll-based nav, IntersectionObserver reveals, and form submit state.

<br/>

---

## 📋 Customisation Guide

| What to change | Where | Notes |
|---|---|---|
| Room names & prices | `index.html` → Rooms section | Search `₹3,500` |
| WhatsApp number | `index.html` → Search `919633289830` | Replace all instances |
| Google Maps location | `iframe src` in Map section | Replace embed URL |
| Real photos | `.room-img-bg`, `.g-bg`, `.about-img` | Add `background-image: url(...)` |
| Colour palette | `:root` CSS variables | Top of `<style>` block |
| Google Reviews | Reviews section | Replace sample quotes |

<br/>

---

## 📞 About Ella Homestay

**Ella Homestay** is located in Kuttikanam, Peermade, Kerala — nestled between Wagamon and Thekkady in the Western Ghats at approximately 900 metres altitude.

- 📍 Kuttikanam, Peermade, Kerala 685531
- 📞 +91 96332 89830
- 💬 [WhatsApp Direct](https://wa.me/919633289830)
- 🌐 [ellahomestay.com](http://www.ellahomestay.com)

<br/>

---

## 👨‍💻 Built by

**Acnal Roj** — Data Analytics professional & freelance web developer based in Kerala, India.

[![GitHub](https://img.shields.io/badge/GitHub-Acnalroj-181717?style=flat-square&logo=github)](https://github.com/Acnalroj)

> Interested in a website for your business? Feel free to reach out.

<br/>

---

<div align="center">

Made with 🌿 for the hills of Kerala

*© 2025 Ella Homestay. Built by Acnal Roj.*

</div>
