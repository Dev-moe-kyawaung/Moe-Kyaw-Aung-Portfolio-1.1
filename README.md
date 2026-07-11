<div align="center">

  <img src="https://res.cloudinary.com/dye5qpwii/image/upload/v1778763535/MKA_25_lbx6fb.webp" alt="Moe Kyaw Aung" width="140" height="140" style="border-radius:50%;" />

  # ⭐ Moe Kyaw Aung — Portfolio 1.1 ⭐
  ### Android Senior Developer | Kotlin · Jetpack Compose · Firebase · Clean Architecture

  [![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-View_Site-6366f1?style=for-the-badge)](https://Dev-moe-kyawaung.github.io/Moe-Kyaw-Aung-Portfolio-1.1/)
  [![License](https://img.shields.io/badge/License-MIT-06b6d4?style=for-the-badge)](LICENSE)
  [![Made with HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
  [![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](#)
  [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#)

  <p align="center">
    <a href="https://github.com/Dev-moe-kyawaung">GitHub</a> ·
    <a href="https://gravatar.com/moekyawaung13721">Gravatar</a> ·
    <a href="https://www.linkedin.com/in/moe-kyaw-aung-2653093a1">LinkedIn</a> ·
    <a href="mailto:moekyawaung@programmer.net">Email</a> ·
    <a href="tel:+95988900889">+95 9 889 000 889</a>
  </p>

</div>

---

## 📖 About This Project

**Moe Kyaw Aung Portfolio 1.1** is a fully responsive, production-ready personal portfolio and SaaS-style landing page built to showcase **nearly 12 years of Android development experience**. The site highlights expertise in **Kotlin, Jetpack Compose, MVVM, Clean Architecture, Firebase, and CI/CD**, alongside a comprehensive collection of real projects, certifications, and professional network links.

Designed with a **glassmorphism aesthetic**, animated interactions, and full **Burmese 🇲🇲 / English 🌐 bilingual support**, this portfolio serves as both a professional showcase and a technical demonstration of front-end craftsmanship using pure HTML, Tailwind CSS, and vanilla JavaScript — no frameworks, no build step, fully portable.

---

## ✨ Key Features

| Category | Highlights |
|---|---|
| 🎨 **Design** | Glassmorphism UI, dark/light mode, custom cursor, particle canvas hero, parallax depth scrolling |
| 🧭 **Navigation** | Fixed glass navbar, responsive hamburger menu, smooth scroll, active-link highlighting |
| 📊 **About / Timeline** | Animated career timeline (2013–Present), SVG progress rings, animated stat counters |
| 🖼️ **Portfolio** | Masonry-style grid of 16+ real Android/web apps with live GitHub links |
| 🎓 **Certificates** | Searchable & filterable certificate gallery (40+ credentials) |
| 🌐 **Network Hub** | 43 GitHub Pages profiles + 30 Lovable WPA prototypes, both searchable |
| 📬 **Contact** | Validated contact form, newsletter signup, Google Maps embed |
| 💬 **Engagement** | Testimonial carousel, pricing table, FAQ accordion, sticky CTA, back-to-top |
| 🇲🇲 **Localization** | Full Burmese/English toggle across hero, about, and FAQ sections |
| ♿ **Accessibility** | Semantic HTML5, ARIA labels, skip-to-content link, keyboard-navigable |

---

## 🛠️ Tech Stack

```

Frontend    : HTML5, Tailwind CSS (CDN), Vanilla JavaScript (ES6+)
Icons       : Font Awesome 6, Lucide Icons
Fonts       : Inter, Space Grotesk, Padauk (Google Fonts)
Media/CDN   : Cloudinary (images & video assets)
Maps        : Google Maps Embed API
Hosting     : GitHub Pages

```

---

## 📂 Project Structure

```

Moe-Kyaw-Aung-Portfolio-1.1/
│
├── index.html              # Main single-file application (HTML + CSS + JS)
├── README.md                # You are here
├── LICENSE                  # MIT License
├── CODE_OF_CONDUCT.md        # Community standards
├── CONTRIBUTING.md           # Contribution guidelines
├── SECURITY.md               # Security policy & responsible disclosure
├── CHANGELOG.md              # Version history
├── .gitignore                 # Ignored files
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── bug_report.md
│   │   └── feature_request.md
│   ├── PULL_REQUEST_TEMPLATE.md
│   └── workflows/
│       └── deploy.yml         # GitHub Pages auto-deploy CI/CD
└── assets/
├── favicon.ico
└── og-image.png           # Social preview image

````

---

## 🚀 Getting Started

### Prerequisites
No build tools required — this is a pure static site. You only need:
- A modern web browser
- (Optional) [VS Code](https://code.visualstudio.com/) + [Live Server extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) for local development

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/Dev-moe-kyawaung/Moe-Kyaw-Aung-Portfolio-1.1.git

# 2. Navigate into the project directory
cd Moe-Kyaw-Aung-Portfolio-1.1

# 3. Open directly in your browser
open index.html        # macOS
start index.html        # Windows
xdg-open index.html     # Linux
````

Or simply launch with **Live Server** in VS Code for hot-reload during editing.

### Deploying to GitHub Pages

1. Go to your repository **Settings → Pages**
2. Under **Source**, select the `main` branch and `/ (root)` folder
3. Save — your site will be live at:
   `https://dev-moe-kyawaung.github.io/Moe-Kyaw-Aung-Portfolio-1.1/`

---

## 🎯 Customization Guide

| What to change | Where to look |
|---|---|
| Profile photo / media | Cloudinary `<img>` / `<video>` `src` attributes near the top of `index.html` |
| Color theme | `tailwind.config` script block + `:root` CSS variables |
| Certificates | `#certificates` section — duplicate `.cert-card` blocks |
| Projects | `#projects` section — duplicate `.app-card` blocks |
| GitHub / Lovable links | `#github` and `#lovable` sections |
| Contact info | `#contact` section + footer |
| Resume PDF link | `#resumeDownload` button — replace alert handler with real file link |

---

## 🗺️ Roadmap

- [ ] Wire contact form to a real backend (EmailJS / Formspree)
- [ ] Add MDX-powered blog section
- [ ] PDF resume auto-generation
- [ ] Multi-language expansion beyond Burmese/English
- [ ] Lighthouse performance pass (target 95+ across all metrics)

See [CHANGELOG.md](CHANGELOG.md) for full version history.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting a pull request, and check our [Code of Conduct](CODE_OF_CONDUCT.md).

---

## 🔐 Security

Found a vulnerability? Please **do not open a public issue** — instead, follow the responsible disclosure process outlined in [SECURITY.md](SECURITY.md).

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Moe Kyaw Aung** — Senior Android Developer
📍 Tachileik, Myanmar 🇲🇲 ↔ Bangkok, Thailand 🇹🇭

- GitHub: [@Dev-moe-kyawaung](https://github.com/Dev-moe-kyawaung)
- Gravatar: [moekyawaung13721](https://gravatar.com/moekyawaung13721)
- LinkedIn: [Moe Kyaw Aung](https://www.linkedin.com/in/moe-kyaw-aung-2653093a1)
- Email: moekyawaung@programmer.net
- Phone: +95 9 889 000 889

<div align="center">

### ⭐ If this project inspired you, consider giving it a star!

*"Code with culture. Build with purpose."*

</div>
