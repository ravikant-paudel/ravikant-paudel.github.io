# Portfolio Plan — ravikant-paudel.github.io

## Overview

A single-page resume/portfolio built on the Start Bootstrap Resume template, hosted via GitHub Pages.

**Live site:** https://ravikant-paudel.github.io

## Current State

- `index.html` is the only page actively used for the portfolio
- Content in index.html still has placeholder/template text (fake experience, education, lorem ipsum descriptions)
- Social media links (`Facebook`, `Twitter`, `LinkedIn`, `GitHub`) all point to `#`
- Profile section has a generic bio paragraph

## What Needs to Be Done

### 1. Update index.html Content

- [ ] Replace placeholder bio with a real personal summary
- [ ] Update Experience section with actual work history
- [ ] Update Education section with real education details
- [ ] Update Skills section with actual tech stack
- [ ] Update Interests section with real interests
- [ ] Update Awards section (or remove if not applicable)
- [ ] Fix social links — point Facebook, Twitter, LinkedIn, GitHub to real profiles
- [ ] Update page `<title>` from "Resume - Start Bootstrap Theme" to actual name

### 2. About Section

- [ ] Update address/phone/email in the subheading (currently shows Chandragiri, Kathmandu address and phone number publicly)
- [ ] Consider removing phone number from public HTML for privacy

### 3. SCSS / Styling

- [ ] Customize colors in `scss/_variables.scss` if needed
- [ ] Run `gulp` to recompile `css/resume.min.css` after any SCSS changes

### 4. Other Pages

- `rv-haker-news/privacy-policy.html` — Privacy policy for the RV Hacker News iOS app (already exists, linked from App Store)

## Tech Stack

- HTML5, Bootstrap 4
- Font Awesome icons
- SCSS → compiled via Gulp to `css/resume.min.css`
- jQuery + jQuery Easing (smooth scroll)

## Project Structure

```
├── index.html                      # Main portfolio page
├── css/resume.min.css              # Compiled styles (do not edit directly)
├── scss/                           # Edit styles here, then run gulp
├── js/resume.min.js                # Scroll behavior
├── img/ravikant.jpg                # Profile photo
├── vendor/                         # Bootstrap, Font Awesome, devicons, jQuery
├── rv-haker-news/privacy-policy.html
├── gulpfile.js                     # Build: sass compile + browser-sync
└── package.json
```

## Local Development

```bash
npm install
gulp
```
