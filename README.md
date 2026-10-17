# Nexus

Nexus is a polished landing page for an AI agent infrastructure platform. It presents a unified platform for building, deploying, and operating production-ready AI agents.

## Value proposition

Build and ship reliable AI agents without stitching together infrastructure, integrations, security, and observability yourself.

## Key capabilities

- Agent development workflows for engineering teams
- Production infrastructure, deployment, and observability
- Integrations for connecting agents to existing tools and services
- Security-focused controls for dependable enterprise adoption
- Clear pricing and conversion paths for teams evaluating the platform

## Tech stack

- Next.js 16 with the App Router
- React 19 and TypeScript
- Tailwind CSS 4
- shadcn/ui and Radix UI primitives
- Lucide icons
- React Three Fiber and Three.js for interactive visuals

## Getting started

Install dependencies using the project package manager, then start the development server:

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Available scripts

- `npm run dev` — start the development server
- `npm run build` — create a production build
- `npm run start` — start the production server
- `npm run lint` — run ESLint

## Project structure

```text
app/                    Next.js routes, layout, and global styles
components/landing/     Landing page sections
components/ui/           Reusable shadcn/ui components
hooks/                  Shared React hooks
lib/                    Shared utilities
public/                 Static assets
```

## Deployment

The project is ready to deploy on Vercel. Connect the repository to Vercel, select the Next.js framework preset, and deploy. Vercel will automatically build the app using the project scripts.
