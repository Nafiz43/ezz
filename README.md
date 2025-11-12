# Ezana Huda Portfolio

This repository contains the static portfolio website for architectural designer Ezana Huda. The landing page (`index.html`) features:

- A hero section that highlights Ezana's focus on sustainable design, adaptive reuse, façade systems, BIM, and urban planning.
- Project spotlights with imagery, descriptions, and key project metadata.
- Skills, certifications, software proficiencies, and education history laid out in responsive grids.
- A contact form scaffold and footer with social links.

All styling and interactivity live directly in `index.html` through embedded CSS and a lightweight intersection observer script for scroll-based reveal animations. The `img/` directory holds supporting imagery and logos referenced throughout the page.

## Local preview

You can preview the site locally by serving the repository root with any static file server. For example, using Python:

```bash
python -m http.server 8000
```

Then open <http://localhost:8000> in your browser to browse the portfolio.
