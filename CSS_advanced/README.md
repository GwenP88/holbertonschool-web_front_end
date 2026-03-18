![Advanced CSSL Banner](/home/gpichot/holbertonschool-web_front_end/assets/banner.png) 
# Project - Advanced CSS — Techium Project

## Description

This project builds upon the Advanced HTML Techium project by introducing CSS styling. The goal is to style the Techium agency webpage using advanced CSS techniques, including custom properties (variables), transitions, transforms, animations, and a float-based grid system — all targeting Chrome 78.x compliance.

## Learning Objectives

By the end of this project, you should be able to explain:

- Selectors, properties, and values
- The difference between block and inline styling
- How to ensure consistency across all browsers (CSS reset)
- How to set up and use CSS variables (custom properties)
- The differences between inline, embedded, and external CSS
- How grid systems work (with floats)
- The difference between icon webfonts and SVG icons
- The difference between pseudo-classes and pseudo-elements
- How to make background gradients
- How to animate elements in CSS
- How to transform elements in 2D and 3D
- What vendor prefixes are and when to use them

## CSS Architecture

### CSS Variables (Custom Properties)

All design tokens are defined as CSS variables in `:root`:

| Variable | Purpose |
|---|---|
| `--color-primary` | Brand red `#d73953` |
| `--color-black` / `--color-white` | Base colors |
| `--font-family-base` | Body font — Open Sans |
| `--font-family-title` | Heading font — Raleway |
| `--transition-duration` | Global transition timing `.3s` |
| `--transition-cubic-bezier` | Custom easing curve |

### Dark Theme

Sections with `data-section-theme="dark"` automatically override text and background colors via CSS variable re-declaration — no extra class needed.

### Grid System

A simple float-based two-column layout:

- `.row` — clearfix container
- `.col-1-3` — one-third width (33.33%)
- `.col-1-2` — one-half width (50%)

### Key Components

| Component | Description |
|---|---|
| `.card-services` | Service cards with hover color change |
| `.card-work` | Portfolio cards with image zoom and overlay on hover |
| `.card-testimonial` | Testimonial cards with decorative quote mark |
| `.card-blog` | Blog/news article cards |
| `.button` | CTA button with border and hover background fill |
| `.nav` | Float-based navigation with animated underline on hover |

### Transitions & Transforms (Task 32)

- **Navigation links** — animated underline slides in on hover using `::before` pseudo-element
- **Buttons** — smooth background and color fill on hover via `transition-property`
- **Work cards** — image scales up (`scale(1.2)`) and card container scales down (`scale(0.95)`) on hover, with a dark overlay revealing the title

## Requirements

- Allowed editors: `vi`, `vim`, `emacs`, `VSCode`, `Atom`
- All files interpreted on **Chrome 78.x**
- All files must end with a new line
- Every file must start with a comment describing the task
- A `README.md` file at the root of the project folder is mandatory
- Code must be **W3C compliant** and validate with [W3C Validator](https://validator.w3.org/)

## Resources

- [CSS Reference — A free visual guide to CSS](https://cssreference.io/)
- [Can I use… — HTML5/CSS3 support tables](https://caniuse.com/)
- [CSS Properties | HTML Dog](https://htmldog.com/references/css/properties/)
- [Box Sizing](https://css-tricks.com/box-sizing/)
- [CSS Specificity](https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity)
- [CSS Specificity Calculator](https://specificity.keegan.st/)
- [Play with CSS Selectors](https://css4-selectors.com/browser-selector-test/)

## Author

## Authors
**Gwenaelle PICHOT**
- Student at Holberton School
- Track: holbertonschool-web_front_end
- Project: Advanced CSS