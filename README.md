# Bicol Region Travel Website

A 5-page static tourism website promoting the **Bicol Region (Region V)** of the
Philippines — built with **HTML5 and CSS3 only**, no JavaScript, no frameworks.

Final project for **IntroComp · Introduction to Computing**.

---

## Live Preview

Open `index.html` in any modern browser — no build step, no server, no
dependencies. (Just keep the folder structure intact so the relative paths
resolve.)

---

## Project Structure

```
Student_Bicol_Website/                ← rename to <YourLastName>_Bicol_Website
├── index.html                        # Homepage — hero, intro, featured, gallery
├── destinations.html                 # Popular Destinations — 6 spots
├── activities.html                   # Activities & Experiences — 4 categories
├── history.html                      # Our History & Culture
├── plan-trip.html                    # Plan Your Trip — itinerary, form, etc.
├── css/
│   └── style.css                     # All styling — organised in 22 sections
└── assets/
    ├── images/                       # 17 real, freely-licensed Bicol photos
    ├── videos/                       # Reserved for future video clips
    └── icons/                        # Reserved (icons are inline SVG in HTML)
```

> **Rename the folder** to `<YourLastName>_Bicol_Website` before submission.
> Example: `Santos_Bicol_Website`. The GitHub repository name must match.

---

## Pages

| Page             | Purpose                                                          |
|------------------|------------------------------------------------------------------|
| `index.html`     | Hero, intro paragraph, featured destination, gallery, culture   |
| `destinations.html` | 6 destination sections (Mayon, Cagsawa, Caramoan, Donsol, CWC, Misibis) |
| `activities.html`   | 4 categories: Adventure · Culture · Food · Nature                |
| `history.html`      | 3-paragraph history + timeline + festivals + crafts/foods        |
| `plan-trip.html`    | 3-day itinerary table, travel tips, packing checklist, contact form |

---

## Tech Stack

- **HTML5** — semantic elements throughout (`header`, `nav`, `main`, `section`,
  `article`, `figure`, `aside`, `footer`)
- **CSS3** — custom properties, Grid, Flexbox, transitions, keyframe
  animations, media queries, `prefers-reduced-motion`
- **Google Fonts** — Playfair Display (display) + Inter (body)
- **No JavaScript**, no React/Vue/jQuery/Bootstrap/Tailwind

The mobile navigation menu uses the CSS-only **checkbox hack** — no scripting.

---

## Design System

| Token              | Value      | Use                              |
|--------------------|------------|----------------------------------|
| `--sand-cream`     | `#F6F0E5`  | Page background                  |
| `--ink`            | `#1F1B16`  | Primary text                     |
| `--ocean`          | `#0E3A4A`  | Primary accent (deep teal)       |
| `--terracotta`     | `#C85A3C`  | Warm accent (Mayon glow)         |
| `--gold`           | `#B5832A`  | Subtle accent (pili)             |
| `--font-display`   | Playfair Display | Headlines                  |
| `--font-body`      | Inter      | Body, UI                         |

All design tokens live in `:root` at the top of `css/style.css`.

---

## Image Credits

All photographs are from **Wikimedia Commons** and are freely licensed for
educational use. Each file is named descriptively (e.g. `mayon-volcano.jpg`,
`caramoan-island.jpg`) per the rubric's naming-convention requirement.

If you replace them with your own photos later, keep the same file names so
the HTML references continue to resolve.

---

## Rubric Self-Check

### HTML Standards (40 pts)
- [x] Proper structure — DOCTYPE + semantic tags on all 5 pages
- [x] Clean formatting — consistent 2-space indentation
- [x] Logical organization — HTML comments mark every major section
- [x] File management — `css/`, `assets/images/`, `assets/videos/`, `assets/icons/`
- [x] Naming conventions — descriptive class names throughout

### CSS Standards (15 pts)
- [x] Organization — 22 numbered sections with comment headers
- [x] Consistency — uniform naming and formatting

### Functionality & Design (20 pts)
- [x] Navigation — all links work; nav consistent on every page; active page highlighted
- [x] Images — proper sizing via `object-fit` + `aspect-ratio`
- [x] Forms — contact form properly structured and styled (5 fields + Send)

### Content & Presentation (25 pts)
- [x] Visual design — consistent colour scheme and typography
- [x] Layout — asymmetric grids, generous whitespace, magazine-style numbering
- [x] Content — complete, well-written information on every page
- [x] Creativity — editorial travel-magazine aesthetic with drop caps, italic emphasis, alternating layouts

---

## GitHub Upload

1. Sign in to [github.com](https://github.com).
2. Click **+ → New repository**.
3. Set the **Repository name** to exactly your folder name:
   `<YourLastName>_Bicol_Website` (e.g. `Santos_Bicol_Website`).
4. Set visibility to **Public** (so your instructor can view it).
5. Do **not** initialise with README/license/gitignore (we already have files).
6. Click **Create repository**.
7. In your terminal, from inside the project folder:

   ```bash
   cd Student_Bicol_Website       # or your renamed folder
   git init
   git add .
   git commit -m "Initial commit: Bicol tourism website"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<YourLastName>_Bicol_Website.git
   git push -u origin main
   ```

8. Copy the repository URL and paste it into the Canvas submission text field.

---

## Accessibility

- Semantic HTML throughout (`header`, `nav`, `main`, `article`, `figure`, `aside`)
- Skip-to-content link on every page
- Visible keyboard focus outlines
- `alt` text on every meaningful image
- `aria-label` and `aria-hidden` on interactive controls
- `prefers-reduced-motion` honoured (animations disabled)
- Sufficient colour contrast (WCAG AA on all body text)

---

## Responsive Behavior

| Breakpoint   | Width        | Behaviour                                              |
|--------------|--------------|--------------------------------------------------------|
| Desktop      | ≥ 1025px     | Full multi-column layouts, large hero, sticky nav      |
| Tablet       | 769 – 1024px | Two-column layouts collapse to single column           |
| Mobile       | ≤ 768px      | Hamburger menu, single column, gallery 2-up            |
| Small mobile | ≤ 480px      | Buttons full-width, stacked actions                    |

---

## Student

**Name:** _(fill in your full name before submission)_
**Course:** IntroComp — Introduction to Computing
**Region Assigned:** Bicol (Region V)
**Date:** 2025
