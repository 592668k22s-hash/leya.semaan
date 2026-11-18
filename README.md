# Lea's engineering portfolio: Blueprint Blush

A single-page, static portfolio site. No build step: open `index.html` in a browser.

## Look and feel
Feminine yet serious, modern, classy. Soft blush pink with black, bold grotesque type. Engineering details: a faint drafting grid behind the hero, a dimension line around the portrait, mono-spaced labels, line-art drawings for the projects.

- **Fonts (Google Fonts):** Bricolage Grotesque (headings and body, weights 400/600/800) and DM Mono (labels, buttons).
- **Colours (CSS variables at the top of `index.html`):** `--blush #F6DADF`, `--accent #F0A9BC`, `--ink #17121A`, `--paper #FBF7F5`, `--muted #5C4F57`.
- **Layout:** fluid, max width 1240px, cards use auto-fit grids and stack to one column on phones.

## Sections
Hero, one-line intro, The Work (3 project cards), The Method (dark section), Formula Student, Contact.

## Placeholders still to fill in (search for `[` and `TODO` in index.html)
- Surname, university, major (not shown yet), CAD software (not shown yet)
- Formula Student subteam and what was worked on
- Email, LinkedIn and GitHub (the contact pills are plain text, make them links)
- Portrait photo (see TODO in the hero)
- Project thumbnails: replace the line drawings with CAD renders or screenshots
- "case study" and "view the code" links point to `#`
- "download cv" button should link to a CV file

## Project facts used (from Lea's coursework)
- Scissor lift table: power screw buckling (Tetmajer and Euler), welds to Eurocode 3, chain drive, DIN 6885 keyways, cam follower bearings
- Gearbox predimensioning: 37 kW, 1000 rpm, i = 37, K_A = 1.75, 5000 h, C45E rotary-hardened
- Robot cell simulation in Python: Cylinder, PickList, RobotPLC classes, CSV data, matplotlib

## Ideas for next steps
- A dedicated case-study page per project
- A short About section with the portrait
- Light animation on scroll, and a favicon
- Deploy on GitHub Pages or Netlify
