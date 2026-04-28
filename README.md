# Yuvraj Devesh Srivastava - Developer Portfolio

Open: https://yuvrajdsrivastava-dev.netlify.app/

A modern, responsive personal portfolio built with React.

[![React](https://img.shields.io/badge/React-17.0.2-61DAFB?logo=react&logoColor=white)](https://react.dev/)
[![Node](https://img.shields.io/badge/Node-Compatible-339933?logo=node.js&logoColor=white)](https://nodejs.org/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## Quick Links

- [Overview](#overview)
- [Live Local Preview](#live-local-preview)
- [Tech Stack](#tech-stack)
- [Current Portfolio Content](#current-portfolio-content)
- [Project Structure](#project-structure)
- [Interactive Setup Guide](#interactive-setup-guide)
- [Customization Map](#customization-map)
- [Deployment](#deployment)
- [Troubleshooting](#troubleshooting)
- [Contact](#contact)

## Overview

This portfolio presents:

- Name and profile: Yuvraj Devesh Srivastava
- Role: Full-Stack Developer
- Resume integration (download button)
- Education, experience, projects, skills, and certifications
- Social links (GitHub and LinkedIn)

## Live Local Preview

### 1. Install dependencies

```bash
npm install --legacy-peer-deps
```

### 2. Start the dev server

Windows PowerShell:

```powershell
$env:NODE_OPTIONS="--openssl-legacy-provider"
npm start
```

macOS/Linux:

```bash
export NODE_OPTIONS=--openssl-legacy-provider
npm start
```

### 3. Build production bundle

Windows PowerShell:

```powershell
$env:NODE_OPTIONS="--openssl-legacy-provider"
npm run build
```

macOS/Linux:

```bash
export NODE_OPTIONS=--openssl-legacy-provider
npm run build
```

## Tech Stack

- Frontend: React 17, React Router, Material UI
- Styling/UI: CSS, React Icons, React Reveal, Slick Carousel
- Utilities: Axios, Validator
- Tooling: Create React App (react-scripts)

## Current Portfolio Content

- Summary: B.Tech Computer Science student and Full-Stack Developer focused on Java (Spring Boot), Django, REST APIs, and responsive web applications.
- Experience: Full Stack Developer Intern at Sanchvi Studio (Jul 2024 - Sep 2024)
- Education: B.Tech in Computer Science, J.S. Institute of Education (Expected Aug 2026)
- Highlight Projects:
  - School Management System
  - Sanchvi Studio Client Platform
  - Starbucks Clone Website
- Certifications:
  - OCI 2025 Certified AI Foundations Associate
  - Programming Foundation and SQL
  - Programming Using C++
  - Java for Beginners
  - Programming in Python

## Project Structure

```text
src/
  assets/
    pdf/
    png/
    svg/
  components/
  contexts/
  data/
  pages/
  theme/
  utils/
```

## Interactive Setup Guide

<details>
  <summary><strong>Step 1 - Update personal header details</strong></summary>

Edit: `src/data/headerData.js`

- `name`
- `title`
- `desciption`
- `image`
- `resumePdf`

</details>

<details>
  <summary><strong>Step 2 - Update About and Contact</strong></summary>

Edit:

- `src/data/aboutData.js`
- `src/data/contactsData.js`
- `src/data/socialsData.js`

Tip: Keep only links you actively use. Empty strings are automatically hidden in UI.

</details>

<details>
  <summary><strong>Step 3 - Update Resume Sections</strong></summary>

Edit:

- `src/data/educationData.js`
- `src/data/experienceData.js`
- `src/data/skillsData.js`
- `src/data/projectsData.js`
- `src/data/achievementData.js`

</details>

<details>
  <summary><strong>Step 4 - Optional sections</strong></summary>

- Blog: `src/data/blogData.js`
- Testimonials: `src/data/testimonialsData.js`
- Services: `src/data/servicesData.js`

If arrays are empty, those sections can stay hidden.

</details>

## Customization Map

- Theme selection: `src/data/themeData.js`
- Theme colors: `src/theme/theme.js`
- Landing section: `src/components/Landing/`
- Navigation: `src/components/Navbar/Navbar.js`
- Contact form behavior: `src/components/Contacts/Contacts.js`

## Deployment

Any static host works after `npm run build`, including:

- Netlify
- Vercel
- GitHub Pages
- Azure Static Web Apps

Publish the `build/` folder.

## Troubleshooting

<details>
  <summary><strong>Issue: react-scripts build fails with OpenSSL error</strong></summary>

Use:

- Windows: `$env:NODE_OPTIONS="--openssl-legacy-provider"`
- macOS/Linux: `export NODE_OPTIONS=--openssl-legacy-provider`

Then rerun `npm start` or `npm run build`.

</details>

<details>
  <summary><strong>Issue: npm install peer dependency conflicts</strong></summary>

Run:

```bash
npm install --legacy-peer-deps
```

</details>

## Contact

- GitHub: [YUVRAJDEVESHSRIVASTAVA](https://github.com/YUVRAJDEVESHSRIVASTAVA)
- LinkedIn: [yuvrajdsrivastava](https://www.linkedin.com/in/-yuvrajdsrivastava/)
- Email: yuvrajsrivastava02@gmail.com

---

If you want, I can also add a project banner image and section screenshots to make this README even more visual.
