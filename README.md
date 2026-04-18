<p align="center">
  <img src="./assets/front.png" alt="holbertonschool-web-front-end image" width="200">
</p>

# holbertonschool-web_front_end

> Structure it, then style it — from semantic bones to polished pixels. 🎨

---

## 📄 Description

This repository contains my front-end development projects completed as part of the Holberton School curriculum. It covers the two foundational layers of every website: HTML structure and CSS styling. Starting from a blank file, I build the complete Techium website — a fictional digital agency — first by writing clean, semantic HTML5 markup, then by progressively styling it with advanced CSS techniques. The two projects are intentionally sequential: no styling happens until the structure is solid, which is exactly the right order to learn front-end development.

---

## 🎯 Learning Objectives

Across these projects, I learn how to create a valid, well-structured HTML5 document from scratch — including the correct use of semantic tags like `header`, `main`, `footer`, `section`, `article`, `nav`, and `aside` — and why choosing the right element matters for both accessibility and SEO. I understand the difference between `div` and `span` as non-semantic containers, and how to structure headings in a meaningful hierarchy. I know how to embed images, audio, video, tables, and iframes, and how to validate my markup with the W3C Validator. On the CSS side, I learn how to use custom properties (CSS variables) to build a consistent and maintainable design system, implement a float-based grid layout, use pseudo-classes and pseudo-elements for interactive and decorative effects, integrate Google Fonts, apply CSS animations and `@keyframes`, create background gradients, build smooth transitions with cubic-bezier timing functions, and use 2D transforms on hover. I also understand the importance of CSS resets for cross-browser consistency, and I know how to apply a dark theme using data attributes. By the end of this repository, I am able to take a design from zero to a fully styled, interactive, and browser-consistent webpage using nothing but HTML and CSS.

---

## 📁 Repository Structure

```bash
holbertonschool-web_front_end/
├── html_advanced/
├── CSS_advanced/
└── README.md
```

---

## ✨ Projects / Contents

### html_advanced
- Complete semantic HTML5 structure for the Techium website: navigation, sections, articles, media, tables, lists, and a full styleguide page — no CSS involved
- HTML5, W3C Validator, Chrome 78.x

### CSS_advanced
- Full CSS styling of the Techium website built in `html_advanced`: custom properties, float grid, pseudo-elements, Google Fonts, transitions, transforms, animations, and a dark theme
- CSS3, Normalize.css, Google Fonts (Open Sans, Raleway), Chrome 78.x

---

## 🛠️ Technologies Used

Both projects in this repository use only **HTML5** and **CSS3** — no JavaScript, no frameworks, no preprocessors. The HTML is validated with the **W3C Validator**. The CSS uses **Normalize.css** (necolas version) as a browser reset baseline and integrates **Google Fonts** (Open Sans and Raleway) via font-family variables. All styling is tested in **Chrome version 78.x**. No external dependencies or package managers are required.

---

## ⚙️ Prerequisites

- Browser: Chrome (version 78.x) for CSS rendering
- Editors: `vi`, `vim`, `emacs`, `VSCode`, `Atom`, or any editor of your choice
- W3C Validator access (online at validator.w3.org) for HTML validation
- No package manager or build tool required — everything runs directly in the browser

---

## ▶️ Usage

```bash
git clone https://github.com/GwenP88/holbertonschool-web_front_end.git
cd holbertonschool-web_front_end
```

Navigate into any project directory and open the relevant HTML file in Chrome:

```bash
cd CSS_advanced
xdg-open index.html
# or simply double-click the file in your file manager
```

For the CSS project, make sure the correct stylesheet is linked in `index.html` before opening it. Each task produces its own numbered CSS file (e.g., `styles/32-style.css` for the final version). Each project directory contains its own `README.md` with detailed task-by-task instructions.

---

## 🤝 Contributions & Acknowledgements

A sincere thank you to the Holberton School team for designing a front-end curriculum that teaches the right habits from the start: structure before style, semantics before aesthetics, and understanding before decoration. Special thanks to the W3C for the validator, to necolas for Normalize.css, and to the CSS specification authors for giving us custom properties, pseudo-elements, and cubic-bezier transitions — three features that make writing CSS feel genuinely creative.

---

## 👤 Author

**Gwenaelle PICHOT**
- Student at Holberton School
- Repository: `holbertonschool-web_front_end`