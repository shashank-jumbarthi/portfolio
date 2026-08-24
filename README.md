# Shashank Jumbarthi — DeveloperFolio-Style Portfolio

> Desktop Support Technician and cloud engineer focused on Tier 1/2 support, Microsoft 365, Active Directory, endpoint support, cloud operations, automation, DevOps, and cybersecurity.

[**View the live portfolio**](https://shashank-jumbarthi.github.io/portfolio/) · [LinkedIn](https://www.linkedin.com/in/shashankjumbarthi/) · [GitHub](https://github.com/shashank-jumbarthi) · [Email](mailto:shashankjumbarthi7@gmail.com)

## About

This repository contains the source for Shashank Jumbarthi's personal portfolio website. The site now uses a developerFolio-inspired layout while staying as a lightweight static GitHub Pages site.

The portfolio is aligned with the latest resume and highlights hands-on enterprise support across Windows, macOS, Linux, Microsoft 365, Active Directory, Microsoft Entra ID, endpoint management, networking, AWS, Azure, CI/CD, scripting, monitoring, and documentation.

## Portfolio Highlights

- **developerFolio-style introduction** — Greeting, social links, call-to-action buttons, and a large hero visual.
- **Career proof points** — Enterprise user support, M.S. Cybersecurity, CEH, and cloud/CI/CD experience.
- **What I do section** — Desktop support, identity/endpoint operations, and cloud automation.
- **Proficiency bars** — Practical strengths across support, Microsoft platforms, cloud, monitoring, and troubleshooting.
- **Featured projects** — KubeForge, AegisForge, TitanFabric, enterprise networking, and containerized Python work.
- **Technical expertise** — Skills grouped by IT support, systems/Microsoft, networking/endpoint, and cloud/automation/monitoring.
- **Experience timeline** — Datara Inc, Smart & Creative Solutions Group, and EditPoint roles.
- **Education and certifications** — M.S. Cybersecurity, B.S. Computer Science, CEH, and CCNA in progress.
- **LinkedIn support file** — Ready-to-paste profile copy in `linkedin-profile-update.md`.
- **Template inspiration** — Adapted from the structure and feel of [developerFolio](https://github.com/saadpasta/developerFolio), implemented without requiring a React build pipeline.

## Featured Projects

- **KubeForge** — Kubernetes cluster qualification and reliability framework using Kubernetes, AWS EKS, Terraform, Python, GitHub Actions, Docker, Helm, Prometheus, Grafana, and OpenTelemetry.
- **AegisForge** — DevSecOps and SOC automation platform using Python, FastAPI, React, PostgreSQL, Docker, Kubernetes, Terraform, AWS, GitHub Actions, Nmap, SIEM concepts, and MITRE ATT&CK mapping.
- **TitanFabric** — Infrastructure discovery and network intelligence platform for asset discovery, topology mapping, and infrastructure visibility.
- **Enterprise Network Infrastructure Solution** — Campus network design using Cisco switching concepts, VLANs, IP addressing, security practices, BOMs, and proposal documentation.
- **Sample Python Project** — Containerized Python application with Docker and AWS CodeBuild-ready configuration.

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
│   └── portfolio-hero.png      # Hero section image
├── index.html                  # Portfolio content and structure
├── styles.css                  # Responsive styling and theme
├── linkedin-profile-update.md  # LinkedIn profile copy based on the latest resume
└── README.md                   # Project overview and setup
```

## Updating The Portfolio

- Edit page content in `index.html`.
- Edit layout, colors, and responsive styling in `styles.css`.
- Replace the hero image at `assets/portfolio-hero.png`.
- Use `linkedin-profile-update.md` when updating the LinkedIn profile.
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
