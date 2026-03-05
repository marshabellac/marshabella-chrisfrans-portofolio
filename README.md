# Marshabella Chrisfrans — Portfolio Website

[![Deploy static content to Pages](https://github.com/marshabellac/marshabella-chrisfrans-portofolio/actions/workflows/static.yml/badge.svg)](https://github.com/marshabellac/marshabella-chrisfrans-portofolio/actions/workflows/static.yml)

Personal portfolio website of **Marshabella Chrisfrans** — an Information Systems student at **Universitas Pelita Harapan (UPH)** — showcasing works in **UI/UX design, web design, graphic design, and video editing**.

## Live Website

- GitHub Pages: https://marshabellac.github.io/marshabella-chrisfrans-portofolio/

---

## Sections

This is a single-page portfolio with these main sections:

- **Home** (hero video background + typing animation)
- **About Me** (tools and software + languages)
- **My Works** (images, videos, carousel, and embedded reels)
- **Contact**

---

## Built With

- **HTML5**
- **CSS3**
- **JavaScript**
- **Bootstrap 5** (CDN)
- **AOS (Animate On Scroll)** for scroll animations
- **Typed.js** for the typing effect in the hero section
- **Remix Icon** for social icons
- **Google Fonts** (Caveat, DM Sans, Roboto Mono)

---

## Project Structure

```text
.
├── index.html
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── main.js
│   └── images/
│       ├── hero-video.mp4
│       ├── my-works/
│       ├── tools-software_logos/
│       ├── languages/
│       └── favicon_io/
└── docs/
    └── portfolio-mockup.pdf
```

---

## Run Locally

Because this is a static website, there’s no build step.

### Option A — Open directly
You can open `index.html` directly in your browser.

### Option B — Run a local server (recommended)
Some browsers behave better with a local server.

**Python**
```bash
python -m http.server 8000
```
Then open:
- http://localhost:8000

**VS Code**
- Install the **Live Server** extension
- Right click `index.html` → **Open with Live Server**

---

## Customize Content

### 1) Update text/content
Edit content directly inside:
- `index.html`

### 2) Replace the hero video
Replace this file (keep the same filename for easiest update):
- `assets/images/hero-video.mp4`

### 3) Change the typing text (hero animation)
In `index.html`, find the Typed.js script and update the `strings` value.

Example:
```js
new Typed('#typing', {
  strings: ["Your Text Here"],
  typeSpeed: 60,
  backSpeed: 40,
  loop: true,
  cursorChar: '',
});
```

### 4) Update “My Works”
- Add/replace media inside: `assets/images/my-works/`
- Update the related `<img>`, `<video>`, carousel items, or embeds in `index.html`

### 5) Update contact + socials
- Footer email uses `mailto:` (edit in `index.html`)
- Social links are in the footer section of `index.html`

---

## Deployment

This repo is deployed to **GitHub Pages** via **GitHub Actions**.

- Push to the `main` branch → GitHub Actions deploys the site automatically.
- If you fork this repo, make sure GitHub Pages is enabled:
  - **Settings → Pages → Source: GitHub Actions**

---

## Design / Mockup

A PDF mockup is included here:
- `docs/portfolio-mockup.pdf`

---

## Contact

- Email: marshabellachrisfrans@gmail.com  
- LinkedIn: https://www.linkedin.com/in/marshabella-chrisfrans  
- Instagram: https://www.instagram.com/marshabellac/  
- YouTube: https://www.youtube.com/@marshabellac  
- TikTok: https://www.tiktok.com/@marshabellac  

---

## License

© Marshabella Chrisfrans. All rights reserved.
