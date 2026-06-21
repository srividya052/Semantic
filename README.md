# semantic

A multi-page personal portfolio website built with pure HTML5 and CSS3 — no frameworks, no JavaScript dependencies. Built with a strong focus on **semantic markup**, **WCAG accessibility**, and **SEO best practices**.

## Features

- **Fully semantic HTML5** — `header`, `nav`, `main`, `section`, `article`, `aside`, `footer` used purposefully, not just for styling hooks
- **Accessible by design** — proper heading hierarchy, labeled form fields, ARIA attributes, visible focus states, skip-to-content link, keyboard-navigable throughout
- **Responsive layout** — mobile-first CSS that scales cleanly from small phones to large desktops, no media query hacks
- **SEO-ready** — unique titles, meta descriptions, canonical links, and robots meta on every page
- **Zero dependencies** — just HTML and CSS, runs anywhere, no build step required

## Pages

| Page | Description |
|---|---|
| `index.html` | Home — intro, hero section, quick overview of skills |
| `about.html` | About — background, approach, skills list, quick facts sidebar |
| `projects.html` | Projects — showcase grid of featured work |
| `contact.html` | Contact — accessible form with labeled fields, fieldset/legend grouping, and a contact info sidebar |

## Project Structure

```
semantic/
├── index.html
├── about.html
├── projects.html
├── contact.html
└── style.css
```

## Getting Started

No build tools, no installs. Just clone and open.

## ♿ Accessibility

This project follows WCAG 2.1 AA guidelines:

- Single `<h1>` per page with a logical, unbroken heading hierarchy
- All images include descriptive `alt` text
- Form inputs are paired with `<label for>`, required fields use `aria-required`, and hints are linked via `aria-describedby`
- Landmarks (`nav`, `main`, `aside`, `footer`) are uniquely labeled where more than one exists on a page
- Visible focus outlines on all interactive elements (`:focus-visible`)
- A skip link lets keyboard users jump straight to main content
- Color combinations meet 4.5:1 minimum contrast for body text

## SEO

Every page includes:

- A unique, descriptive `<title>`
- A unique `meta description` under 160 characters
- `meta name="robots" content="index, follow"`
- A `rel="canonical"` link
- Properly nested headings for crawlability

## Tech

- HTML5
- CSS3 (custom properties, Flexbox, Grid)
- No JavaScript, no frameworks, no build pipeline

## License

MIT 

---

Built by srividya.mallavarapu
