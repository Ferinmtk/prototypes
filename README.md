# Tester LLC — Landing Page

A single-page marketing site for Tester LLC, a custom home builder (Utah · Colorado · Illinois).
Prototype for direction review — built as one self-contained `index.html` (no build step, no dependencies).

## Run it

Open `index.html` in any modern browser, or serve it locally:

```bash
python3 -m http.server 5500
# then visit http://localhost:5500
```

## Features

- Animated intro preloader
- Scroll-driven hero (exterior → interior reveal)
- "Homes by style" gallery — pinned horizontal scrub on desktop, swipe rail with arrows on mobile
- Count-up stats, scroll reveals, card hover lift/shadow
- Frosted nav with a full-screen overlay menu on mobile
- Respects `prefers-reduced-motion`

## Before launch

- Replace the Unsplash placeholder photography with real project photos.
- Update contact details (email, phone, address) in the footer.
- Wire the "Start your build" / contact links to a real form.

## Deploy (GitHub Pages)

Push to GitHub, then: **Settings → Pages → Build and deployment → Deploy from a branch → `main` / `root`.**
The site will be live at `https://<user>.github.io/<repo>/`.
