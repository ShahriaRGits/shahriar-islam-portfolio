# QA Report

## Static checks
The repository contains the expected static-site files: `index.html`, `css/styles.css`, `js/main.js`, the resume PDF, `robots.txt`, `sitemap.xml`, README, `.gitignore`, and a GitHub Pages workflow. The title, meta description, reduced-motion media query, resume link, and resume file were verified. No API keys or credentials were found; the only grep matches were the expected GitHub Actions `id-token` permission and ordinary documentation words.

## Browser verification
The homepage rendered successfully at `http://127.0.0.1:4173/` with the intended editorial layout, large positioning-led hero, analytical signal map, clear project hierarchy, experience timeline, contact section, and footer. All major navigation and CTA elements were present, including three resume links, email, LinkedIn, GitHub, and four repository links.

An in-page check at a 1280px viewport reported `scrollWidth: 1265` versus `innerWidth: 1280`, so there was no horizontal overflow. The page contains no raster images, meaning there are no missing image alt attributes to audit. The mobile navigation toggle exists and uses an `aria-expanded` state. Reduced-motion handling is implemented in CSS and the reveal script has a non-IntersectionObserver fallback.

## Known deployment item
The live URL, GitHub repository creation, and Pages deployment remain dependent on GitHub authentication and repository permissions. The repository is prepared for a project site named `shahriar-islam-portfolio`; no deployment is claimed until GitHub confirms it.
