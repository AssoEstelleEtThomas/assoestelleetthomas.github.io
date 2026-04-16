# estelle-thomas.fr

Official website for **Association Estelle & Thomas**, a French nonprofit organization dedicated to fighting school bullying (*harcèlement scolaire*). The association provides listening, support, and kindness to students and their families.

**Live site:** [www.estelle-thomas.fr](https://www.estelle-thomas.fr)

## About the Association

Founded by Estelle Masson, the association promotes positive and reassuring communication to support students affected by school bullying. Its core values are:

- **Partage** (Sharing) — Creating connections and mutual understanding
- **Écoute** (Listening) — A welcoming space for free expression
- **Soutien** (Support) — Accompanying with empathy and solidarity

RNA registration: W141005251

## Tech Stack

| Tool | Purpose |
|------|---------|
| [Astro](https://astro.build) v5 | Static site generator |
| [Tailwind CSS](https://tailwindcss.com) v4 | Utility-first CSS |
| TypeScript | Type safety |
| GitHub Pages | Hosting & deployment |

## Getting Started

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Project Structure

```
src/
├── assets/images/     # Logo and illustrations
├── components/        # Reusable Astro components (Navigation, Footer)
├── layouts/           # Base page layout with SEO meta tags
├── pages/             # index.astro — single-page website
└── styles/            # Global CSS with theme variables and animations
public/                # Static assets (CNAME, robots.txt)
.github/workflows/     # CI/CD — auto-deploys to GitHub Pages on push to main
```

## Deployment

The site automatically deploys to GitHub Pages when changes are pushed to the `main` branch. The workflow is defined in `.github/workflows/deploy.yml`.

## Contact

- **Email:** contact.assoestelleetthomas@gmail.com
- **Website:** [www.estelle-thomas.fr](https://www.estelle-thomas.fr)
