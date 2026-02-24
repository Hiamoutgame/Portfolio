## Portfolio Website

A modern, responsive personal portfolio website built with **HTML**, **CSS**, and **vanilla JavaScript**. It features smooth in-page navigation, scroll animations (AOS), and dedicated sections for **About**, **Skills**, **Projects**, and **Contact**.

## Features

- **Responsive layout**: Works well on desktop, tablet, and mobile
- **Smooth scrolling navigation**: Click navbar links to jump to sections
- **Scroll animations**: Powered by AOS (Animate On Scroll) via CDN
- **Projects showcase**: Card-based grid with roles, tech stack, and links
- **Contact & social links**: Email/phone and social profiles in the footer

## Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **Animations**: [AOS](https://michalsnik.github.io/aos/)
- **Icons**: Boxicons, Devicon, Font Awesome (via CDN)

## Project Structure

- `index.html` — Page structure and content (sections + project cards)
- `style.css` — Styling, layout, and responsive rules
- `script.js` — AOS init + smooth scrolling behavior
- `me.jpg`, `aboutme.png`, `logo.png` — Images used on the page

## Getting Started (Local)

Because this is a static site, you can run it in the simplest way:

- **Option A**: Open `index.html` directly in your browser
- **Option B (recommended)**: Use a local server (e.g. VS Code “Live Server”, or any static server)

Example using Python:

```bash
python -m http.server 5500
```

Then open `http://localhost:5500` in your browser.

## Customization

- **Content**: Edit text, links, and project entries in `index.html`
- **Styling**: Adjust colors, spacing, and layout in `style.css`
- **Animations**: Change AOS effects by editing `data-aos` attributes in `index.html`
- **Images**: Replace `me.jpg` / `aboutme.png` / `logo.png` with your own assets (keep filenames or update the `<img>` paths)

## Deployment

You can deploy this site as static hosting on:

- GitHub Pages
- Netlify
- Vercel
- Any static hosting provider

## License

This project is for personal portfolio use. If you plan to reuse it, please keep attribution or adapt it to your own design and content.
