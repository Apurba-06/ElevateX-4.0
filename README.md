ElevateX 4.0 — Interactive Web Trailer 🚀
An immersive, cinematic web experience built for ElevateX 4.0, the ultimate mentoring summit presented by IEEE JUSB. This project serves as an interactive promotional trailer, utilizing modern web technologies to deliver a high-energy, sci-fi-inspired digital environment.

📌 Overview
This project replaces a traditional video trailer with a dynamic, DOM-based presentation. It features a custom particle engine, interactive HUD elements, and a timeline-based slide progression system. The interface is designed with a futuristic, cyberpunk aesthetic, utilizing neon glows, scanlines, and CSS glitch animations to command attention.

✨ Key Features
Custom Particle System: A dynamic background built with the HTML5 <canvas> API, featuring floating nodes that render connecting lines based on proximity calculation.

Cinematic Slide Engine: A vanilla JavaScript timeline that handles sequential slide rendering with precise timing, automatic progression, and manual keyboard navigation overrides.

Sci-Fi HUD & UI Elements: * Real-time session clock and dynamic "energy bar" progress indicators.

SVG-based circular countdown timers synchronized with slide durations.

CRT-style scanline overlays and corner-bracket targeting UI.

Advanced CSS Animations: Utilizes @keyframes for glitch text effects, pulsing rings, fluid clip-path reveals, and smooth typography fades.

Custom Interactive Cursor: Replaces the default OS cursor with a screen-blended targeting dot and trailing ring for an immersive user feel.

🛠️ Tech Stack
HTML5: Semantic structure for the UI layers, slides, and HUD.

CSS3: Vanilla CSS handling complex visual effects (glows, mix-blend-modes, clip-paths) and responsive grid layouts.

JavaScript (ES6): * Canvas rendering loop (requestAnimationFrame).

Asynchronous animation sequencing using Promises and setTimeout.

Event listeners for global keyboard navigation and cursor tracking.

🏗️ Project Architecture
The codebase is structured into a single, highly optimized file for rapid loading and execution:

Intro Sequence: A landing overlay with a glitching logo and a "Skip" mechanism.

The Trailer Container: The primary wrapper containing the HUD overlays and the slide deck.

Slide Modules: * s1: Main Title & Tagline

s2: Number Counter Reveal

s3: 4-Track Grid Selection

s4: Animated Statistics

s5: Finale Call-to-Action

JS Controllers: Divided into Particle Engine, Cursor Logic, HUD Updaters, Timeline Engine, and Keyboard Navigation.

🎮 Navigation & Controls
Auto-Play: The trailer progresses automatically with precise timing for each slide.

Spacebar / Right Arrow (→): Skip to the next slide.

Left Arrow (←): Return to the previous slide.

Enter: Skip the intro sequence.

💡 Use Case
Designed specifically for the IEEE JUSB community to drive engagement and registrations for the ElevateX 4.0 summit. The codebase is highly modular, allowing for easy updates to text, timing, and theme colors for future iterations of the event.
