# Shashank Jumbarthi Portfolio

A responsive personal portfolio website for Shashank Jumbarthi, highlighting work across cloud engineering, DevOps, DevSecOps, cybersecurity, automation, and IT infrastructure support.

## Live Portfolio

https://shashank-jumbarthi.github.io/portfolio/

## Overview

This portfolio is built as a lightweight static website and hosted with GitHub Pages. It presents Shashank's professional summary, featured technical projects, core skills, work experience, education, certifications, and contact links in a clean single-page layout.

## Featured Content

- Cloud, DevOps, and DevSecOps hero section
- Career highlights and education proof points
- Featured project cards with GitHub links
- Technical skills grouped by discipline
- Professional experience timeline
- Education and CEH certification
- Email, LinkedIn, and GitHub contact links

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- GitHub Pages

## Project Structure

```text
portfolio/
├── assets/
│   └── portfolio-hero.png
├── index.html
├── styles.css
└── README.md
```

## Local Preview

Open `index.html` directly in a browser, or serve the folder locally:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Updating the Portfolio

- Edit page content in `index.html`
- Edit layout, colors, and responsive styling in `styles.css`
- Replace the hero image at `assets/portfolio-hero.png`
- Commit changes and push to `main`

## GitHub Pages Deployment

This repository is configured to deploy from the `main` branch using GitHub Pages:

```text
Settings -> Pages -> Source: Deploy from branch -> Branch: main -> Folder: /root
```

After each push to `main`, GitHub Pages rebuilds the site and publishes it at:

```text
https://shashank-jumbarthi.github.io/portfolio/
```
