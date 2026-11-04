<div align="center">

# Srivathsa Sherla · Agentic AI Engineer Portfolio

A fast, accessible, framework-free portfolio built with plain HTML, CSS and a little vanilla JavaScript.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/docs/Web/JavaScript)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![AI](https://img.shields.io/badge/Agentic_AI-ff7a3d?style=for-the-badge&logo=openai&logoColor=white)](https://github.com/srivathsa12)
[![Lighthouse](https://img.shields.io/badge/a11y-semantic_%26_keyboard_friendly-0b0a09?style=for-the-badge)](#accessibility)

![GitHub repo size](https://img.shields.io/github/repo-size/srivathsa12/my-portfolio?style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/srivathsa12/my-portfolio?style=flat-square)
![GitHub stars](https://img.shields.io/github/stars/srivathsa12/my-portfolio?style=flat-square)

</div>

---

## Overview

This repository contains the personal portfolio of **Srivathsa Sherla**, a B.Tech Computer Science and Engineering (AI & ML) student at Newton School of Technology, S-VYASA University, focused on **agentic AI, LLM workflows and automation**.

The entire site is **one `index.html` file**: no build step, no dependencies, no frameworks. It presents the About, Skills, Projects, Impact, Learning and Contact sections with a dark, modern design.

**Highlights**

- Semantic landmarks, skip link, visible focus states and `aria-current` navigation
- Responsive from 320px phones to wide desktops, with an accessible mobile menu
- Respects `prefers-reduced-motion` and works with JavaScript disabled
- Structured data (JSON-LD) and Open Graph metadata for sharing
- Honest status labels on every project (Built, Repository, Concept design)

## Live Demo

> **Live site:** https://srivathsa12.github.io/my-portfolio/ *(placeholder: enable GitHub Pages to activate it, see [Deployment](#deployment))*

## Tech Stack

| Layer | Choice |
| --- | --- |
| Markup | HTML5 (semantic elements, ARIA only where needed) |
| Styling | CSS3 (custom properties, grid, flexbox, `clamp()`, media queries) |
| Behaviour | Minimal vanilla JavaScript (menu toggle, scroll reveal, active link, card spotlight) |
| Hosting | GitHub Pages (static) |
| Frameworks | None |

## Project Structure

```text
my-portfolio/
├── index.html   # markup, styles and scripts in one file
└── README.md
```

## Local Setup

No installation is required.

**Option 1: open the file**

```bash
git clone https://github.com/srivathsa12/my-portfolio.git
cd my-portfolio
open index.html        # macOS
# xdg-open index.html  # Linux
# start index.html     # Windows
```

**Option 2: serve it locally (recommended)**

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

1. Push the repository to GitHub.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Your site will be live at `https://<username>.github.io/my-portfolio/` within a minute or two.

## Customising

- Replace the text, links and project cards directly in `index.html`.
- Change the accent colour by editing `--accent` and `--accent-2` in the `:root` block.
- The portrait loads from the GitHub avatar URL. Swap the `src` for a local image (for example `assets/profile.jpg`) if you prefer. An initials fallback appears if the image fails to load.

## Accessibility

- Skip-to-content link and logical heading order
- Keyboard-operable navigation, including `Escape` to close the mobile menu
- Colour contrast tuned for dark mode, visible `:focus-visible` outlines
- Motion is disabled when the user prefers reduced motion
- Decorative elements are hidden from assistive technology with `aria-hidden`

## Contact

- **Email:** [sherlasrivathsa12@gmail.com](mailto:sherlasrivathsa12@gmail.com)
- **GitHub:** [@srivathsa12](https://github.com/srivathsa12)
- **LinkedIn:** [srivathsa-sherla](https://www.linkedin.com/in/srivathsa-sherla)

## License

Released under the [MIT License](https://opensource.org/licenses/MIT). Feel free to fork the structure; please replace the personal content with your own.