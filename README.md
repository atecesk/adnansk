# Adnan SK — Executive Advisory Website Package (`adnansk.ca`)

Production-ready static web package structured for deployment on any static host (Cloudflare Pages, Vercel, Netlify, GitHub Pages, or cPanel/Apache/Nginx).

## Directory Structure

```text
adnansk-website/
├── index.html             # Primary semantic HTML5 document
├── css/
│   └── styles.css         # Custom luxury obsidian/champagne styles & animations
├── js/
│   ├── tailwind.config.js # Tailwind theme tokens (fonts, colors, letter spacing)
│   ├── data.js            # Structured data for Advisory Pillars, Engagements & Briefs
│   └── app.js             # UI interactivity, modals, drawers & dossier state
├── robots.txt             # Search engine crawler directives
├── sitemap.xml            # XML sitemap for canonical domain (https://adnansk.ca/)
├── site.webmanifest       # Progressive web app metadata
└── README.md              # Deployment and customization guide
```

## Quick Local Preview

1. Extract the ZIP archive.
2. Open `index.html` directly in any modern browser, or run a lightweight local HTTP server:
   ```bash
   npx serve .
   # or
   python3 -m http.server 8080
   ```
3. Navigate to `http://localhost:8080`.
