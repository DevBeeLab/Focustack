# Focustack — AI-Generated Landing Page

A responsive, one-page marketing website for **Focustack**, a fictional productivity app that helps remote teams batch their work into focused sprints.

Built with semantic HTML5 and modern CSS (Flexbox + Grid) as part of the IDA/3MTT Software Development capstone project.

---

## Live Demo

> _Add your deployed link here (e.g. GitHub Pages URL)_

---

## Project Structure

```
ai-generated-landing-page/
├── index.html   # Page structure and content
├── style.css    # Styles, layout, and responsive rules
└── README.md    # This file
```

---

## Sections

| Section | Description |
|---|---|
| **Header** | Sticky navigation bar with logo and CTA link |
| **Hero** | Full-viewport headline, subtext, and primary button |
| **Features** | Three feature cards in a responsive CSS Grid layout |
| **CTA** | Call-to-action with persuasive copy and sign-up button |
| **Footer** | Logo, links, and copyright |

---

## Tech Used

- **HTML5** — semantic tags: `<header>`, `<section>`, `<footer>`, `<nav>`
- **CSS3** — custom properties, Flexbox, CSS Grid, media queries
- **Google Fonts** — Syne (headings) + DM Sans (body)
- No frameworks, no build tools — plain files opened in a browser

---

## Responsive Design

The layout adapts at `max-width: 700px`:

- The three-column features grid collapses to a single column
- Header padding and section padding tighten for narrow screens
- All text uses `clamp()` for fluid font sizing across screen widths

---

## AI Assistance

AI was used **only for planning and copy** — not for writing the final code.

Specifically, AI helped with:
- Inventing the app name (**Focustack**) and value proposition
- Drafting the hero headline, subtext, and feature card copy
- Suggesting the color palette (dark navy/green/cyan) and font pairing (Syne + DM Sans)
- Recommending the layout structure (sticky header, full-vh hero, 3-column grid, centered CTA)

All HTML and CSS was written by hand based on that plan.

---

## Commit History

Commits were made incrementally as each section was completed:

1. `init: create project folder and empty files`
2. `feat: add hero section structure and base styles`
3. `feat: add features section with CSS Grid layout`
4. `feat: add CTA section`
5. `feat: add header nav and footer`
6. `style: add responsive media query for mobile`
7. `docs: add README`

---

## Stretch Goals Attempted

- [x] Sticky navigation bar (`position: sticky`)
- [x] Hover animations on cards and buttons (`transition`, `:hover`)
- [ ] ARIA labels and accessibility audit

---

## Repository

[github.com/DevBeeLab/Focustack](https://github.com/DevBeeLab/Focustack)

---

## Author

**DevBee** · [dev-bee.vercel.app](https://dev-bee.vercel.app) · [github.com/DevBeeLab](https://github.com/DevBeeLab)