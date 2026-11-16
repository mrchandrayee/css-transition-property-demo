# CSS Transition Property with & without

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://mrchandrayee.github.io/css-transition-property-demo/)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org) [![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](./LICENSE)

A standalone recreation of the uploaded 17.23-second screen recording.

## What the video shows

The heading reads **CSS Transition Property with & without**. Two cards are shown side by side:

- **❌ Without Transition** — “Beautiful Mountains”; copy: “Hover this card. Everything changes immediately without animation.”
- **✅ With Transition** — “Beautiful Mountains”; copy: “Hover this card. Every property animates smoothly.”

Both cards use the same mountain-road photograph and an **Explore** button. The video compares immediate hover changes with smooth CSS transitions.

## Visible CSS source

The left code panel shows the hover rule:

```css
.card:hover {
  transform: translateY(-18px);
  box-shadow: 0 30px 60px rgba(0,0,0,...
}
```

The right code panel shows:

```css
.card {
  transition: transform 0.45s ease,
              box-shadow 0.45s ease;
}

.card:hover {
  transform: translateY(-18px);
  box-shadow: 0 30px 60px rgba(0,0,0,...
}
```

The source video is low-resolution and the right edge of the shadow declarations is clipped/blurred. For the working demo, the completed shadow value is reconstructed as `rgba(0,0,0,.35)`. The visible transform and transition timings are transcribed as displayed.

## Run

1. Extract the ZIP.
2. Open `index.html` in a modern browser.
3. Hover over each mountain card and its Explore button.
4. Compare the instant response on the left with the smooth transition on the right.

No npm install, build step, JavaScript, or server is required.

## Files

- `index.html` — two comparison cards and visible CSS code panels
- `style.css` — responsive layout, card styling, hover states and transitions
- `assets/mountain-road.jpg` — mountain image cropped from the uploaded video frame
- `README.md` — transcription notes and run instructions

## Fidelity note

The mountain image is extracted from the supplied recording. The labels, card copy, transition duration, transform and visible code structure are based on the screen. The clipped shadow alpha value and surrounding page styles are reconstructed for a complete runnable demo, not claimed as exact hidden original source.

## 👨‍💻 Author

**mrchandrayee** · [GitHub](https://github.com/mrchandrayee)

## 📄 License

[MIT License](./LICENSE)
