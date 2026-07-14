# Millwork Desk

> **Products · Dictionary · AWI Standard** — A single-page reference tool for architectural woodwork professionals.

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen?logo=github)](https://juliogb01.github.io/Millwork_Desk/)

---

## Overview

**Millwork Desk** is a lightweight, zero-dependency reference app that puts three essential resources at your fingertips:

| Tab | Contents |
|-----|----------|
| 📦 **Products** | Every product type covered by the AWI/AWS standard, grouped by section, with drafting briefs and image-search links. |
| 📖 **Dictionary** | 500 + millwork and drafting terms with definitions, an A–Z filter, and an abbreviations table. |
| 📋 **Standard** | All 12 sections of the AWS 2nd Edition (2014) summarised with includes/excludes per section. |

---

## Live Demo

👉 [https://juliogb01.github.io/Millwork_Desk/](https://juliogb01.github.io/Millwork_Desk/)

---

## File Structure

```
Millwork_Desk/
├── index.html          # Main HTML shell
├── style.css           # All styles (design tokens, layout, components, responsive)
├── script.js           # All data (DATA object) + UI logic
└── README.md           # This file
```

---

## Features

- **Instant search** — filter products, terms, or standard sections in real time.
- **A–Z letter filter** in the Dictionary view.
- **Sticky table of contents** for the Standard section.
- **No build step, no framework** — open `index.html` directly in any browser or deploy to any static host.
- **Responsive** — works on desktop, tablet and mobile.
- **Accessibility** — ARIA roles on tabs and buttons, `:focus-visible` outlines, `prefers-reduced-motion` respected.

---

## Deployment (GitHub Pages)

This repo is configured for **GitHub Pages** from the `main` branch root.

1. Go to **Settings → Pages**.
2. Source: **Deploy from a branch** → `main` → `/ (root)`.
3. Save. The site will be live at `https://juliogb01.github.io/Millwork_Desk/` within a minute.

---

## Local Development

No build tools required. Just open the file:

```bash
# Clone
git clone https://github.com/JulioGB01/Millwork_Desk.git
cd Millwork_Desk

# Open in browser (any of these work)
start index.html          # Windows
open index.html           # macOS
xdg-open index.html       # Linux
```

Or serve with any static server to avoid CORS issues with local `file://` paths:

```bash
# Python 3
python -m http.server 8080

# Node (npx)
npx serve .
```

Then visit `http://localhost:8080`.

---

## Standards Reference

Content is based on the **Architectural Woodwork Standards (AWS), 2nd Edition, 2014** published by:

- [Architectural Woodwork Institute (AWI)](https://www.awinet.org/)
- [Architectural Woodwork Manufacturers Association of Canada (AWMAC)](https://www.awmac.com/)
- [Woodwork Institute (WI)](https://www.woodworkinstitute.com/)

---

## License

This project is for educational and professional reference purposes.  
All AWS/AWI content belongs to their respective copyright holders.
