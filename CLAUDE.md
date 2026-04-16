# CLAUDE.md - estelle-thomas.fr

## Project Overview

Website for **Association Estelle & Thomas**, a French nonprofit fighting school bullying (harcèlement scolaire). Single-page site with hero, about, values, and contact sections.

Live at: https://www.estelle-thomas.fr

## Tech Stack

- **Astro** v5.2 — static site generator
- **Tailwind CSS** v4 — utility-first styling via `@tailwindcss/vite`
- **TypeScript** — strict mode
- **@lucide/astro** — icons
- **@astrojs/sitemap** — SEO sitemap generation

## Commands

```bash
npm run dev      # Start dev server
npm run build    # Production build → dist/
npm run preview  # Preview production build
```

## Project Structure

```
src/
├── assets/images/     # Logo, illustrations
├── components/        # Navigation.astro, Footer.astro
├── layouts/           # BaseLayout.astro (master template)
├── pages/             # index.astro (single-page site)
└── styles/            # global.css (theme variables, animations)
public/
├── CNAME              # Custom domain config
└── robots.txt         # SEO robots config
.github/workflows/     # GitHub Pages deployment
```

## Styling Conventions

- Color palette defined as CSS custom properties in `src/styles/global.css`
- Primary: `#3D7579` (teal), Accent: `#EB8F5F` (coral), Background: `#F2ECDF` (cream)
- Fonts: **Montserrat** (headings), **Poppins** (body) — loaded from Google Fonts
- Custom animation classes: `.hero-animate-*`, `.reveal`, `.card-hover`, `.stagger-children`
- Mobile-first responsive design

## Deployment

- Auto-deploys to **GitHub Pages** on push to `main` via `.github/workflows/deploy.yml`
- Custom domain: `www.estelle-thomas.fr`

## Language

All user-facing content is in **French**. Code and comments are in English.
