# Student Certificate Generator

A lightweight web app that lets students:
- Upload a CSV of records **or** manually enter data via a form
- See a live preview of a certificate template
- Download the result as a PNG

## Features
- White‑theme + premium dark theme (toggle button)
- Responsive design with glass‑morphism in dark mode
- Smooth hover animations and micro‑interactions
- Built with Vite + plain JavaScript (no heavy frameworks)

## Project Structure
```
cert-generator/
├─ public/
│   └─ template.png   # certificate mock‑up (generated image)
├─ src/
│   ├─ index.html
│   ├─ styles.css
│   └─ app.js
├─ sample.csv          # example CSV file
├─ package.json
└─ vite.config.js
```

## Setup
```bash
npm install
npm run dev   # start dev server at http://localhost:5173
npm run build # production bundle in /dist
```

## Usage
1. Choose a theme (white or dark).
2. Upload a CSV **or** fill the form on the right.
3. Preview updates instantly.
4. Click **Download PNG** to save the certificate.

---
*All UI follows premium design guidelines with dark teal background, gold accents, and a clean white variant for beginners.*
