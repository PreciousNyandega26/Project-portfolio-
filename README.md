# Policap Portfolio

A simple, responsive personal portfolio website for Policap Onchiri showcasing services, work samples and contact details.

## Features

- Hero header with background image
- About section with tabbed skills/experience/education
- Services grid
- Portfolio gallery (images from `images/`)
- Contact form
- Responsive layout and hover effects

## Project structure

- `index.html` — main page markup
- `style.css` — site styles
- `images/` — project and portfolio images

## How to view locally

1. Open `index.html` in your browser (double-click) OR
2. Serve the folder with a simple static server for correct relative routing and better dev UX:

   - With Python 3 (PowerShell):
     ```powershell
     python -m http.server 8000
     ```
     Then open http://localhost:8000

   - Or use the VS Code Live Server extension and open the workspace, then "Open with Live Server".

## Customization

- Change the hero/background image: edit `background-image` in `style.css` (look for `.hero` or the header styles).
- Replace portfolio images in the `images/` folder and update `index.html` `<img>` sources.
- Edit text content directly in `index.html`.

## Performance & accessibility tips

- Resize and compress images before publishing (WebP or optimized JPG at appropriate resolutions).
- Add meaningful `alt` attributes to `<img>` elements for accessibility.
- Ensure keyboard access to interactive elements (use `tabindex` where needed) and test with a screen reader.

## Deployment

You can deploy the site to GitHub Pages by pushing this repository to GitHub and enabling Pages in the repository settings (use the `main` branch root).

## Notes

- If you want the submit button, form behavior, or image overlays adjusted I can apply changes to `style.css` or `index.html` for you.

## License

This repository is provided as-is. Add a license file if you plan to publish publicly.

---

Generated for the Policap Portfolio project.
