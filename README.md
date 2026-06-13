# Amakio — Marketing Site

[![Astro](https://img.shields.io/badge/Astro-FF5D01?logo=astro&logoColor=white)](https://astro.build)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)](https://tailwindcss.com)
[![Vercel](https://img.shields.io/badge/Deployed_on-Vercel-000000?logo=vercel&logoColor=white)](https://amakio-landing.vercel.app)

Marketing website for **Amakio** — a school operating system that digitises every aspect of school administration. Built with Astro and Tailwind CSS, featuring a dark/light theme system, analytics dashboard gallery, and full brand identity.

## Live Site

[https://amakio-landing.vercel.app](https://amakio-landing.vercel.app)  
[https://amakio-landing.vercel.app/about](https://amakio-landing.vercel.app/about) — Founder portfolio

## Features

- **Dark/Light Theme** — Persisted via localStorage with flash-free initialisation
- **Dashboard Gallery** — Live SVG dashboards for Attendance, Finance, and CBT Results
- **Brand System** — Navy (#0B1F4D) + Gold (#D4A017), Montserrat + Inter fonts
- **Responsive Design** — Mobile-first, full-width layouts across all breakpoints
- **Analytics Showcase** — Realistic product screenshots demonstrating key modules
- **Founder Portfolio** — Full CV, expertise domains, experience timeline, education

## Tech Stack

| Technology | Purpose |
|------------|---------|
| Astro | Static site generation |
| Tailwind CSS | Utility-first styling |
| Vercel | Hosting & deployment |
| SVG | Inline dashboard graphics |

## Getting Started

`ash
npm install
npm run dev
`

Build for production:

`ash
npm run build
`

## Project Structure

`
public/
  dashboards/       # SVG dashboard screenshots
  Aquilo-Dominic.png # Founder photo
src/
  layouts/
    Layout.astro    # Base layout with theme system
  pages/
    index.astro     # Landing page
    about.astro     # Founder portfolio
`

## Deployment

Deployed via Vercel. Each push to main triggers an automatic production deploy:

`ash
vercel deploy --prod
`

## License

Private — Aquilo-Dominic Godwin Udo