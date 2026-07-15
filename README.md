<p align="center">
  <img src="https://img.shields.io/badge/Status-Live-brightgreen?style=for-the-badge" alt="Status">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white" alt="Three.js">
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
</p>

<h1 align="center">🌌 Cosmic View</h1>

<p align="center">
  <strong>An interactive educational website exploring the wonders of astronomy and space exploration.</strong>
</p>

<p align="center">
  Discover galaxies, nebulae, black holes, and exoplanets through stunning visuals, interactive 3D models, and curated scientific data — all in your browser.
</p>

---

## 📖 About

**Cosmic View** is a multi-page static website designed to make astronomy accessible, engaging, and visually immersive. It combines high-quality space imagery, real astronomical data, and interactive Three.js visualizations to create an educational experience for students, enthusiasts, and curious minds alike.

> Developed by **Anson Saju**

---

## ✨ Features

| Feature | Description |
|---|---|
| **🏠 Home Page** | Full-screen hero with auto-rotating background slideshow, featured cosmic objects grid, galaxy & planetary data tables, and a call-to-action section |
| **🖼️ Cosmic Gallery** | Curated gallery of 15+ celestial objects — from the Andromeda Galaxy and Pillars of Creation to TON 618 and theoretical Wormholes |
| **🔭 Astronomy & Space Exploration** | Deep-dive educational articles on neutron stars, black holes, kilonovae, exoplanets (Kepler-22b, Proxima Centauri b), the JWST, and NASA's contributions |
| **ℹ️ About Page** | Project objectives, technologies used, data sources, and development process |
| **🌀 3D Galaxy Visualization** | Interactive Three.js spiral galaxy model with realistic star colors, drag-to-rotate, and scroll-to-zoom |
| **☀️ 3D Solar System Simulator** | All 8 planets orbiting the Sun with Saturn's rings, planet tooltips on hover, and full orbit animation |
| **📱 Responsive Design** | Mobile-first navigation with hamburger menu, adaptive grids, and fluid typography |
| **🎬 Embedded Media** | YouTube video integration covering NASA landing technology |

---

## 🗂️ Project Structure

```
cosmic-view/
├── index.html                              # Home page — hero, featured objects, data sections, 3D visualizations
├── gallery.html                            # Cosmic gallery — image grid with descriptions
├── Astronomy and Space Exploration.html    # Educational articles with scientific data tables
├── about.html                              # About the project, tech stack, and sources
└── README.md                               # This file
```

> **Note:** This is a purely front-end project — no build tools, bundlers, or server-side dependencies required.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **HTML5** | Semantic page structure and content |
| **CSS3** | Custom styling, gradients, glassmorphism effects, and animations |
| **JavaScript (ES6+)** | DOM manipulation, slideshow logic, modal controls, and 3D scene management |
| **[Three.js](https://threejs.org/)** | WebGL-powered 3D galaxy and solar system visualizations |
| **[Tailwind CSS](https://tailwindcss.com/)** | Utility-first responsive styling via CDN |
| **[Font Awesome](https://fontawesome.com/)** | Icon library for UI elements |
| **[Google Fonts (Inter)](https://fonts.google.com/specimen/Inter)** | Modern typography |
| **[Unsplash](https://unsplash.com/)** | High-resolution space imagery |
| **[Sketchfab API](https://sketchfab.com/)** | 3D model integration support |

---

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, Safari) with **WebGL** support
- No installation, dependencies, or build steps required

### Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/cosmic-view.git
   cd cosmic-view
   ```

2. **Open in your browser**
   ```bash
   # Option 1: Simply double-click index.html

   # Option 2: Use a local server (recommended for best experience)
   npx serve .
   # or
   python -m http.server 8000
   ```

3. **Navigate** using the top navigation bar to explore all pages.

---

## 📸 Pages Overview

### 🏠 Home (`index.html`)
The landing page features a cinematic hero section with four rotating space backgrounds, a grid of six featured cosmic objects (Andromeda Galaxy, Orion Nebula, Black Hole M87, Pillars of Creation, Jupiter's Great Red Spot, Saturn's Rings), comprehensive data sections on galaxies, planets, and black holes, interactive 3D visualizations, latest astronomical discoveries, user reviews, and a detailed footer.

### 🖼️ Gallery (`gallery.html`)
A responsive grid showcasing 15+ celestial objects with high-resolution imagery and educational descriptions. Objects include galaxies, nebulae, exoplanets, pulsars, comets, magnetars, wormholes, and quasars.

### 🔭 Astronomy & Space Exploration (`Astronomy and Space Exploration.html`)
In-depth educational content divided into two major sections:
- **Astronomy** — History, structure, recent news, and detailed articles on neutron stars, black holes, and kilonovae with scientific data tables and references.
- **Space Exploration** — From Sputnik to Artemis, covering Kepler-22b, Proxima Centauri b, the James Webb Space Telescope, and NASA's contributions. Includes an embedded YouTube video.

### ℹ️ About (`about.html`)
Project background, objectives, technologies used, data sources (NASA, ESA, Hubble, Wikipedia), and the development process.

---

## 📚 Data Sources

All astronomical data is sourced from reputable scientific organizations:

- [NASA](https://www.nasa.gov/) — Planetary data, mission information, and space imagery
- [ESA (European Space Agency)](https://www.esa.int/) — European space missions and astronomical data
- [Hubble Space Telescope](https://hubblesite.org/) — High-resolution imagery and discoveries
- [NASA Exoplanet Archive](https://exoplanets.nasa.gov/) — Exoplanet catalog and data
- [Event Horizon Telescope](https://eventhorizontelescope.org/) — Black hole imaging
- [Wikipedia Astronomy Portal](https://en.wikipedia.org/wiki/Portal:Astronomy) — General information (cross-verified)

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/add-new-object`)
3. **Commit** your changes (`git commit -m "Add new gallery object"`)
4. **Push** to the branch (`git push origin feature/add-new-object`)
5. **Open** a Pull Request

### Adding a New Gallery Item

The gallery page includes a built-in template. Simply copy and paste this block into `gallery.html`:

```html
<div class="gallery-item">
    <img src="YOUR_IMAGE_URL_HERE" alt="YOUR_ALT_TEXT" class="gallery-image">
    <div class="gallery-content">
        <h3>YOUR TITLE HERE</h3>
        <p>YOUR DESCRIPTION HERE</p>
    </div>
</div>
```

---

## 📄 License

This project is open source and available for educational purposes.

---

<p align="center">
  <strong>🌟 If you find this project useful, please consider giving it a star! 🌟</strong>
</p>

<p align="center">
  <sub>© 2025 Cosmic View — Educational Astronomy and Space Discoveries</sub>
</p>
