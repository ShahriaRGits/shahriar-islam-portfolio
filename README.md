# Shahriar Islam — Portfolio

A static portfolio of Shahriar Islam, positioned across **data and business analytics, MIS and business systems, automation, and project/product management**.

## Purpose

The site turns a CV and selected public GitHub evidence into a concise professional narrative. It is intentionally designed for recruiters, hiring managers, and business leaders who need to understand the candidate’s role, business context, technical approach, and verified outcomes quickly.

The content follows a strict source hierarchy: the CV is the primary professional record, GitHub is used for technical and project evidence, and LinkedIn is linked as a professional destination. No metrics, employers, dates, responsibilities, technologies, or outcomes are added unless supported by the available sources.

## Technology

The website uses semantic HTML5, CSS3, and vanilla JavaScript. It has no build step or runtime dependency and is suitable for GitHub Pages. Google Fonts are loaded from the web for Manrope and DM Mono; the layout remains readable with system fallbacks if the font request is unavailable.

## Features

The single-page experience includes a positioning-led hero section, capabilities, four selected project case studies, professional experience, education, leadership and achievements, contact CTAs, a downloadable resume, responsive navigation, scroll reveals, reduced-motion support, semantic headings, accessible focus states, Open Graph metadata, JSON-LD structured data, `robots.txt`, and `sitemap.xml`.

The selected case studies are MIS Copilot, AI Student Support Assistant, MFS Adoption ML Evaluation, and Starbucks Customer Loyalty. Prototype and academic boundaries are stated explicitly where applicable.

## Project structure

```text
.
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── main.js
├── assets/
│   └── documents/
│       └── Shahriar-Islam-Resume.pdf
├── .github/workflows/
│   └── pages.yml
├── robots.txt
├── sitemap.xml
└── README.md
```

## Local development

Because this is a static site, it can be opened directly in a browser or served with any static server. For a local server with Python:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## GitHub Pages deployment

The included workflow publishes the repository through GitHub Pages whenever changes reach the default branch. In the repository settings, set **Pages → Source** to **GitHub Actions**. The expected project-site URL is:

```text
https://shahriargits.github.io/shahriar-islam-portfolio/
```

If the repository is instead renamed to `ShahriaRGits.github.io`, update the canonical URL, Open Graph URL, sitemap URL, and workflow assumptions accordingly.

## Customization

Update the verified content in `index.html`, replace the resume under `assets/documents/`, and adjust the design tokens at the top of `css/styles.css`. Keep the public contact channels limited to the approved email, LinkedIn, and GitHub links. Any new project claim should be supported by a source before it is added to the site.

## Credits

The site uses Google Fonts: Manrope and DM Mono. The favicon is an inline SVG mark created for this portfolio. No external images or third-party JavaScript libraries are used.
