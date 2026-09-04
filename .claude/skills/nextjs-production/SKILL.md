---
name: nextjs-production
description: Build production-quality Next.js App Router sites with correct Server/Client boundaries, routing, metadata, image handling, loading states, caching, and deployment-ready structure.
---
# Next.js Production

- Prefer Server Components. Keep Client Components at the smallest interactive leaf.
- Use semantic route structure and reusable components.
- Make caching decisions explicit for data fetching.
- Use `next/image` for content photography and responsive image sizes.
- Use `next/font` for controlled typography and avoid layout shift.
- Provide loading, error, and not-found states where relevant.
- Keep secrets and server-only logic out of client bundles.
- Use route metadata, sitemap, robots, Open Graph, and structured data where appropriate.
- Avoid unnecessary JavaScript and dependencies.
