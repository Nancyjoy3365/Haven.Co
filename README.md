# Haven & Co. — Real Estate Website

A fully responsive real estate company landing page built as a front-end portfolio piece. No frameworks, no build tools — just hand-written HTML, CSS, and vanilla JavaScript.

**[Live Demo](#)** · **[View Code](#)**

![Haven & Co. preview](#)

---

## Overview

Haven & Co. is a concept real estate brand created to demonstrate front-end design and development skills: layout architecture, typography pairing, interactive UI, and clean component structure — all without relying on a framework or external libraries.

## Features

- **Responsive design** — fluid layouts from mobile through desktop using CSS Grid and Flexbox
- **Sticky navigation** — transitions from transparent to solid on scroll
- **Asymmetric property grid** — featured listing card + supporting grid, built with CSS Grid
- **Functional search & filtering** — filters property cards live by location, type, and price range (no backend, pure client-side JS)
- **Favorites system** — toggle properties as saved, with a live counter badge in the nav
- **Contact modal** — accessible modal (closes on outside click, Escape key, or close button) with a working form flow
- **Scroll-reveal animations** — sections fade in on scroll using the native `IntersectionObserver` API
- **Smooth-scroll navigation** — all nav links and CTAs route to real, working page sections

## Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (Custom Properties, Grid, Flexbox, transitions/animations) |
| Interactivity | Vanilla JavaScript (ES6) |
| Fonts | Google Fonts — Playfair Display, DM Sans |
| Images | Unsplash |

No npm, no bundler, no frameworks. The entire site is a single `index.html` file with embedded CSS and JS — by design, to keep the project lightweight and easy to read end-to-end.

## Project Structure

```
Haven.Co/
└── index.html   # all markup, styles, and scripts
```

## Running Locally

No build step required.

```bash
git clone https://github.com/Nancyjoy3365/Haven.Co.git
cd Haven.Co
open index.html
```

Or just double-click `index.html` in a file explorer.

## What I'd Improve With More Time

- Move CSS and JS into separate files for better maintainability at scale
- Connect the contact form and "List Property" flow to a real backend (e.g. Supabase, similar to other projects in my portfolio)
- Add a property detail page with an image gallery
- Componentize the markup (likely a Next.js or Vite + React rebuild) to support dynamic listing data from an API
- Add unit/E2E tests for the search filtering logic

## About This Project

This is a static front-end demo built to showcase UI/UX and vanilla JavaScript skills. Buttons, forms, and the contact flow are functional in terms of client-side behavior (filtering, modals, validation) but are not connected to a live backend or database — submitting the contact form will not send a real message.

## Author

**Joy** — Developer based in Kenya, building a web development portfolio alongside [ElimuCards](#), a school report card management system for Kenyan schools.

GitHub: [@Nancyjoy3365](https://github.com/Nancyjoy3365)

## License

This project is open for viewing as a portfolio reference. Feel free to use it as inspiration, but please don't republish it as your own.