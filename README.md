# Goa Frame Generator

A small React application for creating shareable Goa Frame Generator cards from a photo, name, and technology stack.

## Stack

- React + TypeScript
- Vite
- React Router
- Tailwind CSS
- Convex + Convex Auth
- Framer Motion
- Lucide Icons

## Run locally

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Create a production build:

```bash
npm run build
```

## Environment

The app expects the Convex client configuration used by the existing project, including `VITE_CONVEX_URL`. Keep your real environment values in `.env` and do not commit secrets.

## Main areas

- `src/pages/Landing.tsx` — card creation experience
- `src/lib/card-renderer.ts` — canvas rendering
- `src/lib/image-utils.ts` — photo validation and decoding
- `src/lib/titles.ts` — badge title generation
- `src/convex/` — persistence and authentication
- `src/components/` — reusable interface pieces

The visual design and card-generation behavior are intentionally kept intact while the project structure and documentation remain focused on the actual application.

WESIT LINK 
https://g-cranberry.github.io/ggh2026/
