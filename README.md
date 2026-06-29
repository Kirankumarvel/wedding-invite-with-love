# Emma & James · Wedding Invitation

A premium, fully responsive wedding invitation website designed with love, elegance, and a touch of modern interactivity. This single‑page HTML site serves as a digital save‑the‑date and invitation, featuring a countdown timer, scroll‑reveal animations, a visual timeline, and a beautiful gallery—all built with pure HTML, CSS, and JavaScript.

![Screenshot](https://github.com/user-attachments/assets/bb023734-1b1f-47ee-a6b4-9ce1171776a3)

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
  ```
- Modify the time zone offset (`GMT+0100`) and date/time accordingly.

### 4. Edit the Timeline & Story
- Timeline items are inside `.timeline` – add or remove events as needed.
- The “Our Story” text is in the `.story-text` div – rewrite it with your own love story.

### 5. RSVP Button
- Replace the `<a href="#" class="rsvp-btn">` with a link to your preferred form (e.g., Google Forms, RSVPify, or a mailto link).

---

## 📁 Project Structure

```text
.
├── index.html          # Main file (all HTML, CSS, and JavaScript)
└── screenshot.png      # (optional) Add a preview image for your repo
```

---

## 🎨 Design Credits

- **Fonts**: [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) & [Inter](https://fonts.google.com/specimen/Inter) – provided by Google Fonts.
- **Images**: All placeholder images sourced from [Unsplash](https://unsplash.com) under the free-to-use license.
- **Icons**: Emoji‑based icons (📅, ⏰, 📍, ♥) used throughout for a light and friendly touch.

---

## 🤝 Contributing

This is a personal project, but if you spot a bug or have an improvement suggestion, feel free to open an issue or submit a pull request. Contributions that maintain the design elegance are welcome.

---

## 📄 License

This project is open‑source and available under the [MIT License](LICENSE). You are free to use, modify, and distribute it for personal or commercial purposes.

---

## 💌 Support

If you find this useful, please consider giving it a ⭐ on GitHub – it means a lot!

Made with ♥ by [Your Name] – inspired by love stories everywhere.
