# Portfolio Plan — ravikant-paudel.github.io

## Overview

Modern single-page portfolio built with vanilla HTML/CSS/JS. Dark navy theme with teal accent (`#64ffda`), light/dark mode toggle, scroll animations, and scroll progress bar. No build tools or frameworks — fully self-contained in `index.html`.

**Live site:** https://ravikant-paudel.github.io

## Current State

The new design is live with:
- Hero section with profile card, social links, and CTA buttons
- Stats bar (9+ years, 50+ projects, 500K+ downloads, 4.8/5 rating)
- Work Experience (YCO Solutions, Khalti, Ekbana, Uber Opus)
- Featured Projects (NEPSE Uncle, Khalti, Hours and Pay, AlmostMe, Bigmart)
- Technical Skills (Languages, Frameworks, Tools, Methodologies)
- Education section
- Contact section

## What Needs to Be Done

### 1. Assets
- [x] Favicon added at root (`favicon.ico`) and link updated in index.html
- [ ] Add CV PDF — `/ravikant_paudel_mobile_cv.pdf` linked from "Download CV" button but missing

### 2. Content Updates
- [ ] LinkedIn URL in profile card social link points to `https://linkedin.com/in/ravikant` — update to correct full URL `https://www.linkedin.com/in/ravikant-paudel-5b688b8b/`
- [ ] Verify Play Store / App Store links are live and correct for all projects
- [ ] Add Stack Overflow profile link to social links (currently only Email, GitHub, LinkedIn)

### 3. Mobile Navigation
- [ ] Nav links on small screens overflow/wrap — consider a hamburger menu for mobile

### 4. Other Pages
- `rv-haker-news/privacy-policy.html` — Privacy policy for the RV Hacker News iOS app (live, email updated)

## Tech Stack

- Vanilla HTML5, CSS3 (CSS variables, Grid, Flexbox)
- Font Awesome 6.4.0 (CDN)
- Google Fonts: Manrope + JetBrains Mono
- Vanilla JS (theme toggle, scroll progress, IntersectionObserver animations)
- No build tools required

## File Structure

```
├── index.html                          # Entire portfolio (self-contained)
├── img/ravikant.jpg                    # Profile photo
├── favicon.ico                         # Browser tab icon
├── ravikant_paudel_mobile_cv.pdf       # MISSING — needs to be added
├── rv-haker-news/privacy-policy.html   # RV HackerNews app privacy policy
└── plan.md                             # This file
```
