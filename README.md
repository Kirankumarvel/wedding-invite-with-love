# · Wedding Invitation

A premium, fully responsive wedding invitation website designed with love, elegance, and a touch of modern interactivity. This single‑page HTML site serves as a digital save‑the‑date and invitation, featuring a countdown timer, scroll‑reveal animations, a visual timeline, and a beautiful gallery—all built with pure HTML, CSS, and JavaScript.

![Screenshot](screenshot.png)

---

## ✨ Features

- **Timeless Design** – A warm, earthy palette with gold accents, serif typography, and soft shadows.
- **Fully Responsive** – Seamlessly adapts to desktops, tablets, and mobile devices.
- **Scroll‑Reveal Animations** – Elements fade and slide in as you scroll, creating a narrative flow.
- **Live Countdown Timer** – Counts down to the wedding day (September 12, 2026) with days, hours, minutes, and seconds.
- **Dynamic Gallery** – Hover effects and a clean grid to showcase your favourite memories.
- **Accessibility Ready** – Respects `prefers‑reduced‑motion` for a considerate user experience.
- **No Dependencies** – Pure vanilla code, easy to host or modify.

---

## 🚀 Quick Start

1. **Clone or download** this repository.
2. Open `index.html` in your browser.
3. That’s it! The site is self‑contained and ready to use.

To deploy, simply upload the `index.html` file to any static hosting service (Netlify, Vercel, GitHub Pages, etc.).

---

## 🛠️ Customization

Make it yours in just a few steps:

### 1. Update the Couple’s Names & Date
- Locate the `hero-date-badge` and the `invitation-card` sections.
- Change the text inside the `<h1 class="names">`, `<div class="names-invite">`, and the date/location in the badge.

### 2. Replace the Images
- All stock images are from [Unsplash](https://unsplash.com). Swap the `src` attributes in the gallery, couple cards, and story section with your own photos.
- Recommended image sizes:  
  - Hero background: `1600x900`  
  - Couple portraits: `400x400` (square)  
  - Gallery: `600x400` (landscape)

### 3. Adjust the Countdown Date
- In the JavaScript section, update the `targetDate` variable:
  ```js
  const targetDate = new Date('September 12, 2026 15:00:00 GMT+0100').getTime();
