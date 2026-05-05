# 🃏 FocusGrid: Dynamic Interaction & State Distortion

> **"An advanced UI interaction experiment exploring focused state amplification and background 'shiver' effects through CSS keyframe orchestration."**

![Repo Size](https://img.shields.io/github/repo-size/Modern-Card-Design?color=cyan&style=flat-square)
![Language Count](https://img.shields.io/github/languages/count/emineugurlu/Modern-Card-Design?color=cyan&style=flat-square)
![Animation Style](https://img.shields.io/badge/Interaction-Dynamic--Focus-blueviolet?style=flat-square)

User focus is a finite resource. This project explores **Selective Attention UI**, where a primary interaction (zooming a card) triggers a secondary "distortion" effect on non-active elements. By utilizing high-frequency CSS shake animations, I created a visual hierarchy that intuitively guides the user's eye toward active content while adding a playful, organic feel to the layout.

---

## 🚀 Engineering Mindset

This experiment focuses on **Contextual State Management**:

*   **State-Driven Distortion:** Implementing a global "hover/active" state where sibling elements receive a rapid, low-amplitude transform animation to simulate an "ant-like" movement.
*   **Scale & Reveal Logic:** Utilizing `transform: scale()` paired with `overflow: hidden` to transition from a compact card to a detailed information view without disrupting the grid flow.
*   **Performance-Optimized Jitter:** Using hardware-accelerated `translate3d` for the shaky effect to ensure high frame rates even when multiple elements are animating simultaneously.
*   **Relative Transition Timing:** Synchronizing the zoom speed of the active card with the jitter frequency of the others to maintain a harmonious visual rhythm.

## 🌟 Key Features

*   **Interactive Zoom:** Smooth expansion of clicked cards to reveal hidden metadata.
*   **Ant-Movement Effect:** A unique "distorted" animation for inactive cards, providing dynamic feedback.
*   **Responsive Grid Architecture:** Fully fluid layout that preserves the interaction logic across mobile and desktop viewports.

## 🔧 Technical Stack

*   **HTML5:** Structured containers for modular card units.
*   **CSS3:** Intensive use of `@keyframes`, `transform-origin`, and transition delays for complex state-dependent styling.

## 📸 Visual Showcase

![Zoom Focus](https://github.com/user-attachments/assets/91d48b02-9d47-4f73-8924-65287aec0b1f)

![Distortion View](https://github.com/user-attachments/assets/25f5f210-1d01-4c2d-82d8-49c2a3366241)

![Mobile Details](https://github.com/user-attachments/assets/aa763253-9747-4b78-9d82-6292865109cd)

---

## 🛠️ Installation & Usage
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/emineugurlu/Modern-Card-Design.git](https://github.com/emineugurlu/Modern-Card-Design.git)
2. **Open the Project:**
   ````bash
   cd Modern-Card-Design
   open index.html

Developed by Emine Uğurlu with a focus on experimental CSS motion and UX psychology.
