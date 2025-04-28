# Agentforce Pitching Selector

Spin the wheel. Select your team. Pitch with power.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Folder Structure](#folder-structure)
- [Customisation](#customisation)
- [Responsive Design](#responsive-design)
- [Preview](#preview)
- [License](#license)
- [Acknowledgements](#acknowledgements)

---

## Overview

**Agentforce Pitching Selector** is an interactive roulette wheel built with HTML5, CSS, and vanilla JavaScript.  
Designed for fun and fair team selection with a polished Salesforce-branded look.

---

## Features

- Animated spinning wheel
- Click sound effects on spin
- Confetti explosion on team selection
- Team selection history
- Brand-themed colours and custom font
- Mobile-responsive design

---

## Getting Started

### Prerequisites
No installations required — just a modern web browser.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/agentforce-pitch-selector.git
   ```

2. Place the following files in the root folder:
   - `index.html`
   - `ITCAvantGardeStd-Demi.otf`
   - `confetti.gif`
   - `click.m4a`
   - `banner.png` (optional)

3. Open `index.html` in your browser.

---

## Folder Structure

```plaintext
/ (root)
 ├── index.html
 ├── ITCAvantGardeStd-Demi.otf
 ├── confetti.gif
 ├── click.m4a
 ├── banner.png
 └── README.md
```

---

## Customisation

| Element                | Where to Change                           |
|-------------------------|-------------------------------------------|
| Team names and colours  | `allTeams` array inside JavaScript        |
| Background image        | `body { background-image: url(...) }`     |
| Font for title          | Linked via `@font-face` in CSS            |
| Wheel size              | `<canvas width="600" height="600">` tag   |
| Spin speed and easing   | `initialVelocity` and `duration` values   |
| Gaps between sections   | Controlled via CSS `gap` property         |

---

## Responsive Design

- Canvas and elements resize below 768px screen width
- Logo scales down
- Wheel remains accessible and usable on mobile

No extra setup needed.

---

## Preview

![Preview Screenshot](preview.png)

---

## License

This project is licensed under the [MIT License](LICENSE).

You are free to use, copy, modify, and distribute.

---

## Acknowledgements

- Salesforce AI Centre branding inspiration
- Mascots featured: Codey, Astro, Appy, Brandy, Cloudy
- Confetti assets and open sounds used under free use licenses

---

# ✨ Happy Spinning!
