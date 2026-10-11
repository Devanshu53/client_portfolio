# Client Portfolio

A production-grade portfolio website built for a client, featuring server-side rendering, smooth animations, and a mobile-first responsive design.

**Live:** https://anjali-portfolio-xf65.vercel.app

## Features
- Server-Side Rendering (SSR) for fast initial loads and SEO
- Dynamic page transitions and scroll-based animations via Framer Motion
- Mobile-first responsive layout (Tailwind CSS)
- Optimized asset loading using `next/image` and `next/font`
- Project showcase section with case studies
- Contact section with validated form inputs
- Lighthouse-optimized (performance, accessibility, SEO)

## Tech Stack
- **Framework:** Next.js (App Router)
- **Language:** JavaScript
- **Styling:** Tailwind CSS, PostCSS
- **Animations:** Framer Motion
- **Fonts:** Inter via `next/font`
- **Linting:** ESLint
- **Deployment:** Vercel

## Project Structure
client_portfolio/
├── public/            # Static assets (images, icons)
├── src/
│   ├── app/           # Pages & layouts (App Router)
│   └── components/    # Reusable UI components
├── tailwind.config.js
├── next.config.mjs
└── package.json

## Getting Started

### Prerequisites
- Node.js >= 18

### Setup
```bash
git clone https://github.com/Devanshu53/client_portfolio.git
cd client_portfolio
npm install

Run

npm run dev          # http://localhost:3000
npm run build        # Production build
npm run start        # Serve production build
npm run lint         # ESLint check

Deployment

Deployed on Vercel with automatic previews on every push. To deploy your own fork:
1. Push the repo to GitHub.
2. Import it in Vercel (https://vercel.com/new).
3. Framework is auto-detected as Next.js — no extra config needed.
