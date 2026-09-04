---
name: production-qa
description: Review a finished web page like a senior product designer and frontend engineer. Use for visual QA, responsive checks, accessibility, broken states, console errors, performance, and release readiness.
---
# Production QA

Review the site in this order:

1. Visual hierarchy: first 5 seconds, typography, spacing, composition, imagery, CTA clarity.
2. Responsive behavior: mobile, tablet, desktop, overflow, awkward wrapping, touch targets.
3. Interaction: navigation, menus, galleries, forms, hover/focus/active states, transitions.
4. Content: spelling, consistency, factual claims, empty states, captions, labels, links.
5. Accessibility: keyboard flow, focus, headings, alt text, contrast, reduced motion.
6. Performance: image weight, layout shift, unnecessary client JavaScript, loading behavior.
7. Engineering: console errors, broken routes, missing assets, invalid HTML, type/lint/build failures.

Do not declare the site finished because it looks good in one viewport. Fix the highest-impact issues first and re-test after changes.
