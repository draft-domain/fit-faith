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

## Design reference
- Base layout inspired by: https://codepen.io/itismowgli/pen/gjLJeE
- Goal: full-viewport hero with centered “Coming Soon” text and social links.
- We will **reimplement** the look. Prefer our own CSS.

## Brand copy (source: community about text)
Short tagline and values drawn from the Facebook group text:
- Tagline: “Where your wellness walk begins with the Word.”
- Verse reference (1 Thessalonians 5:23) — include as a short line, not a long block.
- Pillars: Faith • Food • Fitness.
- Tone: Christ-centered, warm, encouraging, no diet-culture hype.

## Content constraints
- Keep the “About” copy **very short** on the coming-soon page (one–two lines max), link to socials for more.
- Show social links:
  - Facebook group
  - Instagram
  - Threads
  - TikTok
- Add an accessible image alt for the banner (e.g., “Faith & Fitness banner”).

## Visual rules
- Single hero image (1920×1080) as full-bleed background for now (cover + center).
- Ask designer for 3 sizes: 1920×1080 (desktop), ~1280×720 (tablet), ~720×1280 (mobile).
- High contrast for overlaid text (AA at minimum).

## Lighthouse targets (coming-soon)
- Perf ≥ 90 (mobile), A11y ≥ 95, SEO ≥ 90.
