# OET Learning Platform

![Live App](https://img.shields.io/badge/Live%20App-oet--learn.netlify.app-2563eb?style=for-the-badge&labelColor=e0e7ff)
![License](https://img.shields.io/badge/License-MIT-10b981?style=for-the-badge&labelColor=dcfce7)
![Platform](https://img.shields.io/badge/Platform-Astro-ff5d01?style=for-the-badge&logo=astro&logoColor=white&labelColor=fff7ed)

A free, structured learning platform for healthcare professionals preparing for the **Occupational English Test (OET)**. Master medical vocabulary, clinical grammar, and speaking skills through AI-assisted practice.

## Tech Stack

![Astro](https://img.shields.io/badge/Astro-6.2.1-ff5d01?style=for-the-badge&logo=astro&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)

## Features

- **5 Structured Modules** — From introduction to mastery, sequential learning path
- **35+ Lessons** — Comprehensive coverage of OET sub-tests
- **AI-Assisted Practice** — Chatbot-powered speaking practice with role-plays
- **Medical Context** — Real healthcare scenarios for authentic learning
- **Instant Feedback** — Track your progress and performance
- **100% Free** — No paywalls, no subscriptions

## Learning Modules

| Module | Title | Description |
|--------|-------|-------------|
| 1 | Introduction to OET | Foundational concepts, core vocabulary, essential grammar |
| 2 | Speaking 1 | Foundational speaking skills, AI chatbot practice, patient communication |
| 3 | Speaking 2 | Advanced scenarios, specialized healthcare communication |
| 4 | Speaking 3 | Professional fluency in complex clinical dialogues |
| 5 | Speaking 4 | Mastery with integrated practice and exam-ready performance |

## Getting Started

### Prerequisites

- Node.js >= 22.12.0
- npm or pnpm

### Installation

```bash
# Clone the repository
git clone https://github.com/username/astro-oet-med.git
cd astro-oet-med

# Install dependencies
npm install

# Start development server
npm run dev
```

The app will be available at `http://localhost:4321`

### Build for Production

```bash
npm run build
npm run preview
```

## Project Structure

```
/
├── public/
│   └── images/          # Static images
├── src/
│   ├── components/       # Astro components
│   │   ├── sections/    # Page section components
│   │   ├── Navbar.astro
│   │   ├── Sidebar.astro
│   │   └── ...
│   ├── layouts/         # Page layouts
│   │   ├── BaseLayout.astro
│   │   └── ModuleLayout.astro
│   ├── pages/           # Routes
│   │   ├── index.astro
│   │   ├── about.astro
│   │   └── modules/
│   │       ├── module-1.astro
│   │       ├── module-2.astro
│   │       └── ...
│   └── styles/
│       └── global.css   # Global styles
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

## Target Audience

Healthcare professionals including:

- Doctors & Physicians
- Nurses
- Pharmacists
- Dentists
- Allied Health Workers

## About the Lecturer

**Emilius German** — Academic & Lecturer at President University

Specializes in English Language Education with a focus on Educational Technology (EdTech). Currently pursuing a Doctoral (Ph.D.) degree in Educational Technology.

## Development

Built with [Astro](https://astro.build) — the all-in-one web framework designed for speed.

Deployed on [Netlify](https://netlify.com) with automatic deployments from the main branch.

---

<p align="center">
  Developed with care by <a href="https://hijrahassalam.com" target="_blank" rel="noopener">hijrahassalam.com</a>
</p>
