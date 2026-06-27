<div align="center">

# 🚀 ElevateX 4.0 — Interactive Web Trailer

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![IEEE JUSB](https://img.shields.io/badge/IEEE-JUSB-00629B?style=for-the-badge)](https://ieeejusb.in)

An immersive, cinematic DOM-based web experience built for **ElevateX 4.0**, the ultimate mentoring summit presented by IEEE JUSB. 

[Explore the Live Demo]([https://your-demo-link-here.com](https://vercel.com/apurbasamanta322-4600s-projects/elevate-x-4-0)) </div>

---

## 📖 Table of Contents
- [About the Project](#-about-the-project)
- [Key Features](#-key-features)
- [Project Structure](#-project-structure)

---

## 📌 About the Project
This project replaces a traditional MP4 video trailer with a dynamic, browser-native presentation. It features a custom particle engine, interactive HUD elements, and a timeline-based slide progression system designed with a futuristic, cyberpunk aesthetic. It is engineered to command attention and drive registrations for the upcoming ElevateX 4.0 technical summit.

## ✨ Key Features
- **Custom Particle Engine:** A dynamic background built with the HTML5 `<canvas>` API, featuring floating nodes that calculate proximity to draw connecting vectors in real-time.
- **Cinematic Slide Engine:** A vanilla JavaScript timeline that handles sequential slide rendering with precise timing and automatic progression.
- **Sci-Fi HUD Overlays:** - Real-time session clock and "energy bar" progress indicators.
  - SVG-based circular countdown timers synchronized with slide durations.
  - CRT-style scanline overlays and corner-bracket targeting UI.
- **Advanced CSS Animations:** Utilizes `@keyframes` for glitch text effects, pulsing rings, fluid `clip-path` reveals, and smooth typography fades.
- **Custom Interactive Cursor:** Replaces the default OS cursor with a screen-blended targeting dot and trailing ring for an immersive user feel.

## 🗂 Project Structure
Because this is a highly optimized, single-load experience, the core logic is contained within a unified structure:

```text
elevatex-trailer/
├── index.html        # Core structure, CSS styles, and JS logic
├── README.md         # Project documentation
