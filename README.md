<div align="center">

# ✍️ Willowstration

### *Where Writing Embraces Simplicity*

**A clean, modern marketing landing page for the Willowstration writing platform — built with pure HTML, CSS, and JavaScript.**

[![HTML](https://img.shields.io/badge/HTML-42.7%25-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS-34.5%25-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-22.8%25-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](#license)

</div>

---

## 📖 Table of Contents

- [Demo / Screenshots](#-demo--screenshots)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Project Structure](#-project-structure)
- [Deployment](#-deployment)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)

---

## 🌐 Demo / Screenshots

> 🔗 **Live Demo:** [View on GitHub Pages](https://faneeshh.github.io/Willowstration/) *(update link once deployed)*

| Hero Section | Features Section | Testimonials |
|---|---|---|
| *(screenshot placeholder)* | *(screenshot placeholder)* | *(screenshot placeholder)* |

The page showcases:
- A full-viewport hero with a compelling headline and a smooth scroll CTA
- An animated features grid with lazy-loaded images
- An interactive tabbed operations panel
- A testimonial carousel with dot navigation
- A sign-up modal with form validation
- A sticky, fade-on-hover navigation bar

---

## ✨ Features

| Feature | Description |
|---|---|
| 🖊️ **Distraction-Free Mode** | A minimalist interface that hides toolbars and notifications so you can focus purely on writing |
| 📈 **Progress Tracking** | Monitor word count, set writing goals, and view detailed statistics to stay motivated |
| 📄 **Content Templates** | Customisable templates for blog posts, essays, novels, and more — providing a structured starting point |
| 📤 **Flexible Export** | Export documents in PDF, DOCX, and EPUB formats while preserving formatting across all platforms |
| 🌍 **Multi-Platform Access** | Seamlessly sync documents across desktop, tablet, and smartphone |
| 📚 **Built-in Dictionary & Thesaurus** | Instantly look up definitions and synonyms without leaving your document |

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 (semantic, accessible) |
| Styling | CSS3 — Custom Properties, CSS Grid, Flexbox, animations |
| Scripting | Vanilla JavaScript (ES6+) — Intersection Observer API, event delegation, modal, slider |
| Fonts | [Poppins](https://fonts.google.com/specimen/Poppins) via Google Fonts |
| Icons | Inline SVG sprite (`img/icons.svg`) |

No frameworks, no build tools, no dependencies — just the open web platform.

---

## 🚀 Getting Started

### Prerequisites

All you need is a modern web browser. No Node.js, package managers, or build steps are required.

### Run Locally

1. **Clone the repository**

   ```bash
   git clone https://github.com/faneeshh/Willowstration.git
   cd Willowstration
   ```

2. **Open in browser**

   Simply open `index.html` directly:

   ```bash
   # macOS
   open index.html

   # Linux
   xdg-open index.html

   # Windows
   start index.html
   ```

   Or use the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension in VS Code for hot-reload during development:

   ```
   Right-click index.html → Open with Live Server
   ```

---

## 📁 Project Structure

```
Willowstration/
├── index.html        # Main HTML document — all page sections
├── style.css         # Global styles, layout, animations, responsive design
├── script.js         # All interactive behaviour (modal, slider, lazy-load, sticky nav)
└── img/
    ├── logo.png          # Navigation & footer logo
    ├── icon.png          # Browser favicon
    ├── hero.png          # Hero section illustration
    ├── digital.jpg       # Features section — full-quality image
    ├── digital-lazy.jpg  # Features section — low-quality placeholder (lazy load)
    ├── grow.jpg          # Features section — full-quality image
    ├── grow-lazy.jpg     # Features section — low-quality placeholder (lazy load)
    ├── card.jpg          # Features section — full-quality image
    ├── card-lazy.jpg     # Features section — low-quality placeholder (lazy load)
    ├── icons.svg         # SVG icon sprite used throughout the page
    ├── user-1.jpg        # Testimonial avatar — Donna Tartt
    ├── user-2.jpg        # Testimonial avatar — Haruki Murakami
    └── user-3.jpg        # Testimonial avatar — Sylvia Path
```

---

## ☁️ Deployment

Because this is a static site (no server-side code), it can be deployed for free on several platforms in just a few clicks.

### GitHub Pages

1. Go to **Settings → Pages** in your repository.
2. Under *Source*, select the `main` branch and root (`/`) folder.
3. Click **Save** — your site will be live at `https://<username>.github.io/Willowstration/`.

### Netlify

```bash
# Drag & drop the project folder onto https://app.netlify.com/drop
# — or —
# Connect your GitHub repo and Netlify will deploy on every push to main.
```

### Vercel

```bash
npm install -g vercel   # install CLI (one-time)
vercel                  # deploy from the project root
```

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. **Fork** the repository
2. **Create** a feature branch
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Commit** your changes
   ```bash
   git commit -m "feat: add your feature"
   ```
4. **Push** to your fork
   ```bash
   git push origin feature/your-feature-name
   ```
5. **Open a Pull Request** against the `main` branch

Please keep changes focused and describe what you changed and why in the PR description.

---

## 📄 License

This project is licensed under the **MIT License**.
> ⚠️ *The exact license file has not been added to the repository yet. A `LICENSE` file with the MIT License text should be added — see [choosealicense.com](https://choosealicense.com/licenses/mit/) for the full template.*

---

## 📬 Contact

**Faneeshh** — [@faneeshh](https://github.com/faneeshh)

Project link: [https://github.com/faneeshh/Willowstration](https://github.com/faneeshh/Willowstration)

---

<div align="center">
  <sub>Built with ❤️ and pure vanilla web technologies · <em>Precision in every paragraph</em></sub>
</div>
