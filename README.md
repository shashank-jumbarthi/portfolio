# Shashank Jumbarthi — Cloud & DevOps Portfolio

> IT and Cloud Engineer with 7+ years of experience across AWS, Azure, Kubernetes, Terraform, CI/CD, automation, DevSecOps, observability, and secure infrastructure.

[**View the live portfolio**](https://shashank-jumbarthi.github.io/portfolio/) · [LinkedIn](https://www.linkedin.com/in/shashankjumbarthi/) · [GitHub](https://github.com/shashank-jumbarthi) · [Email](mailto:shashankjumbarthi7@gmail.com)

## About

This repository contains the source for Shashank Jumbarthi's personal portfolio website. The site uses a developerFolio-inspired layout while staying as a lightweight static GitHub Pages site.

The portfolio is aligned with the updated resume and a DevOps/cloud career direction, highlighting AWS, Azure, Kubernetes, Terraform, CI/CD, scripting, monitoring, DevSecOps, infrastructure reliability, and production troubleshooting. A downloadable resume PDF is included in the site assets.

## Portfolio Highlights

- **developerFolio-style introduction** — Greeting, social links, resume button, project link, and a large hero visual.
- **Career proof points** — 7+ years of IT/cloud experience, graduate cybersecurity education, CEH, cloud/CI/CD experience, and infrastructure troubleshooting background.
- **What I do section** — Cloud infrastructure, DevOps automation, DevSecOps, and observability.
- **Proficiency bars** — Practical strengths across cloud infrastructure, CI/CD, containers, scripting, security, and monitoring.
- **Featured projects** — KubeForge and AegisForge.
- **Technical expertise** — Skills grouped around cloud platforms, infrastructure as code, DevOps, automation, security, and monitoring.
- **Experience timeline** — Datara Inc, Smart & Creative Solutions Group, and EditPoint roles.
- **Education and certifications** — Cybersecurity master's degrees, B.S. Computer Science, and CEH.
- **Template inspiration** — Adapted from the structure and feel of [developerFolio](https://github.com/saadpasta/developerFolio), implemented without requiring a React build pipeline.

## Featured Projects

- **KubeForge** — Kubernetes cluster qualification and reliability framework using Kubernetes, AWS EKS, Terraform, Python, GitHub Actions, Docker, Helm, Prometheus, Grafana, and OpenTelemetry.
- **AegisForge** — DevSecOps and SOC automation platform using Python, FastAPI, React, PostgreSQL, Docker, Kubernetes, Terraform, AWS, GitHub Actions, Nmap, SIEM concepts, and MITRE ATT&CK mapping.

## Built With

- Semantic HTML5
- Modern CSS3
- Vanilla JavaScript
- GitHub Pages

The portfolio intentionally remains framework-free for lightweight performance, simple deployment, and full customization control.

## Template Note

The requested reference template, [saadpasta/developerFolio](https://github.com/saadpasta/developerFolio), is a React/Create React App project. This repo keeps the same GitHub Pages root deployment flow, so the template was adapted into static HTML/CSS instead of replacing the project with a build-based React app.

## Run Locally

```bash
git clone https://github.com/shashank-jumbarthi/portfolio.git
cd portfolio
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Repository Structure

```text
portfolio/
├── assets/
│   └── programmer.svg          # developerFolio hero illustration
│   └── shashank-jumbarthi-resume.pdf
├── index.html                  # Portfolio content and structure
├── styles.css                  # Responsive styling and theme
└── README.md                   # Project overview and setup
```

## Updating The Portfolio

- Edit page content in `index.html`.
- Edit layout, colors, and responsive styling in `styles.css`.
- Replace the hero illustration at `assets/programmer.svg`.
- Replace the resume at `assets/shashank-jumbarthi-resume.pdf`.
- Commit changes and push to `main`.

## GitHub Pages Deployment

This repository is configured to deploy from the `main` branch using GitHub Pages:

```text
Settings -> Pages -> Source: Deploy from branch -> Branch: main -> Folder: /root
```

After each push to `main`, GitHub Pages rebuilds the site and publishes it at:

```text
https://shashank-jumbarthi.github.io/portfolio/
```

## Connect

- [Portfolio](https://shashank-jumbarthi.github.io/portfolio/)
- [LinkedIn](https://www.linkedin.com/in/shashankjumbarthi/)
- [GitHub](https://github.com/shashank-jumbarthi)
- [Email](mailto:shashankjumbarthi7@gmail.com)

© 2026 Shashank Jumbarthi. All rights reserved.
