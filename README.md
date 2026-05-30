# Makeover Lounge by GRACE

Ludhiana's premier destination for luxury hair, skin, nails & bridal artistry.

> Rani Jhansi Rd, Civil Lines, Ludhiana, Punjab 141001 | Call: 08288800139 | Instagram: @gracesalons

## Getting Started

### Prerequisites
- Node.js 18+ and npm

### Install & Run Locally

```bash
npm install
npm run dev
```

Visit `http://localhost:5173` in your browser.

### Build for Production

```bash
npm run build
```

The production-ready files are output to `dist/`.

## Deploy to GitHub Pages

This repo includes an automated GitHub Actions workflow.

1. Push this code to a GitHub repository
2. Go to **Settings → Pages** → set Source to **GitHub Actions**
3. Push to `main` — the site deploys automatically

### Deploy Anywhere Else

The `dist/` folder after `npm run build` is a static site and can be hosted on:
- **Netlify** — drag & drop the `dist/` folder at app.netlify.com
- **Vercel** — import the repo, set framework to Vite
- **Firebase Hosting**, **Cloudflare Pages**, etc.

## Project Structure

```
src/
├── components/         # Page sections
│   ├── Navbar.tsx
│   ├── Hero.tsx
│   ├── TrustBanner.tsx
│   ├── Services.tsx
│   ├── InstagramFeed.tsx
│   ├── Contact.tsx
│   ├── Footer.tsx
│   └── MobileCTA.tsx   # Sticky booking bar on mobile
├── App.tsx
├── main.tsx
└── index.css           # Global styles & Tailwind theme
public/                 # Static images (hero, services, Instagram tiles)
```

## Tech Stack

- React 19 + TypeScript
- Vite 7
- Tailwind CSS 4
- Framer Motion (animations)
- Lucide React (icons)
