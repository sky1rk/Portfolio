# Portfolio Website

Personal portfolio for Wilfame Esponilla, showcasing background, skills, selected projects, achievements, and contact details.

The current design is a single-page, responsive "Ghibli Reverie" portfolio with a persistent light/dark theme toggle. The theme uses Tailwind CSS utility classes backed by CSS variables, so both palettes share the same markup and stay in sync.

## Features

- Plain section navigation vertically centered on the right side at every screen size, with responsive spacing and text sizing
- Downloadable CV (`resume.pdf`) linked from the hero button
- About section with technical skills and competencies
- Featured creations/project showcase
- Education, academic honors, and key achievements
- Contact section with direct links and an interactive message form
- Light/dark theme toggle with preference saved in `localStorage`
- Responsive layouts for desktop, tablet, and mobile
- Scroll-reveal animations with reduced-motion support

## Technologies Used

- HTML5
- Tailwind CSS (Play CDN)
- CSS custom properties for theming
- JavaScript for theme switching, form feedback, and scroll reveals

## Deployment

The site is deployed to Vercel from the `main` branch of this repository:
https://esponillaportfolio.vercel.app

Pushing to `main` triggers a new Vercel deployment automatically.
