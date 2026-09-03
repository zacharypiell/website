# Zachary Piell — Personal Website

A single-page personal website built with HTML, Tailwind CSS (via CDN), and vanilla JavaScript.

## Features

- Single-page layout with smooth scrolling anchor navigation
- Responsive design using Tailwind CSS utility classes
- Sections: About, Experience, Skills, Music, Visuals (Photos/Designs/Videos), Contact
- Lazy-loaded images for performance
- Scroll-triggered fade-in animations
- Mobile hamburger menu

## Project Structure

```
├── index.html          # Single-page site
├── assets/
│   └── images/         # All image assets
├── favicon.ico
├── CNAME               # Custom domain config
└── README.md
```

## Running Locally

Any static file server will work. For example:

```bash
npx serve .
# or
python3 -m http.server 8080
```

## Deployment

This site is configured for GitHub Pages via the `CNAME` file pointing to `www.zacharypiell.com`.
