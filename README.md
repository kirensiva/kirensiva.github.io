# Kiren S — Personal Portfolio

> Professional portfolio website of Kiren S, Technical Lead with 14+ years of experience in PHP, Laravel, Symfony, System Design, and enterprise web development.

---

## Screenshot

> _Add a screenshot here after deployment: `assets/screenshot.png`_

---

## Features

- **Sticky navigation** with smooth scroll and active link highlighting
- **Dark / light mode** toggle with system preference detection and localStorage persistence
- **Responsive design** — fully optimised from mobile to desktop
- **Professional timeline** for work experience and education
- **Skills grid** with colour-coded technology badges
- **Project cards** with role, achievements, and tech stack
- **Career highlights** section
- **Contact section** with all relevant links
- **Scroll animations** using pure CSS
- **SEO-ready** — meta tags, Open Graph, Twitter Card, JSON-LD structured data
- **Print stylesheet** included
- **Accessible** — semantic HTML, ARIA labels, keyboard navigation, visible focus styles
- **Zero dependencies** — pure HTML5, CSS3, and vanilla JavaScript

---

## Technologies Used

| Layer      | Technology       |
|------------|-----------------|
| Markup     | HTML5            |
| Styling    | CSS3 (Variables, Grid, Flexbox) |
| Scripting  | Vanilla JavaScript (ES6+) |
| Typography | Google Fonts (Playfair Display + Inter) |
| Hosting    | GitHub Pages     |

---

## Folder Structure

```
/
├── index.html          # Main HTML file
├── style.css           # All styles (variables, responsive, dark mode)
├── script.js           # Interactivity (dark toggle, scroll spy, nav)
├── assets/
│   ├── profile.jpg     # Profile photo (add your own)
│   ├── resume.pdf      # Downloadable resume (add your own)
│   └── icons/          # Optional icons
└── README.md
```

---

## Local Setup

No build tools required. Just open the file directly:

```bash
# Clone the repository
git clone https://github.com/kirensiva/kirensiva.github.io.git
cd kirensiva.github.io

# Open in browser
open index.html
# or on Linux:
xdg-open index.html
```

---

## GitHub Pages Deployment

This repository is automatically deployed via GitHub Pages.

1. Push your changes to the `main` branch
2. Go to **Settings → Pages**
3. Set source to **Deploy from a branch → main**
4. Your site will be live at `https://kirensiva.github.io/` within a minute

---

## Customisation

### Add your profile photo
Replace `assets/profile.jpg` with your own photo. Then update `index.html`:
```html
<!-- Replace the photo-placeholder div with: -->
<img src="assets/profile.jpg" alt="Kiren S" class="profile-photo" loading="lazy" />
```

### Add your LinkedIn URL
Search for `Add your profile →` in `index.html` and replace the `href="#"` with your LinkedIn URL.

### Update the resume PDF
Add your resume as `assets/resume.pdf` — the Download Resume button will automatically link to it.

---

## License

© Kiren S. All rights reserved.
