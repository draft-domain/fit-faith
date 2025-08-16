# Planning

## Purpose
A simple “Coming soon” site for Faith & Fitness. One banner, “Coming soon” text, and social links.

## Scope (Phase 1)
- Static index.html only.
- Full-viewport banner.
- Responsive layout (desktop, tablet, mobile).
- Basic accessibility (alt text, contrast, keyboard focus).
- No tracking, no forms, no backend.

## Tech
- Plain HTML and CSS. No build step.
- Image assets from designer.

## Assets
- Current: 1920×1080 banner.
- Request from designer: 1920×1080 (desktop), ~1280×720 (tablet), ~720×1280 (mobile).
- Use `<picture>` later when we have all sizes. For now, cover-fit the 1920×1080.

## Performance targets
- Mobile LCP target < 2.5s on fast 4G.
- Keep image under 250–400 KB per variant if possible.
- Avoid layout shift.

## Hosting
- Stage on GitHub Pages from `main` branch root.
- Move to custom domain later.

## Rules
- One task at a time.
- Keep files < 500 lines; split if needed.
- Update README.md and TASK.md after each change.

## Accessibility
- Provide alt text for the banner.
- Check color contrast for text over image.