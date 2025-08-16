# Homepage — Coming Soon (no code)

## 1) Plan
- Read `PLANNING.md` and `TASK.md`.
- Confirm banner strategy:
  - For now: use 1920×1080 with cover-fit.
  - Ask designer for 3 sizes (desktop, tablet, mobile) for later `<picture>`.

## 2) Create files
- Ensure `index.html` exists at repo root.
- If missing, create minimal structure only (no CSS framework).
- Add placeholders for:
  - Banner area
  - "Coming soon"
  - Social links section

## 3) Accessibility
- Add alt text plan for the banner.
- Ensure readable text over image (contrast checks in later step).

## 4) Verification (local)
- Run `npx html-validate index.html`
- Run `npx linkinator . -r`
- Serve locally (e.g., `npx http-server -p 4173`) and:
  - Check desktop (≥1280px), tablet (~768px), and mobile (~375–430px) viewports.
  - Confirm banner fills viewport, text is readable, and links are clickable.

## 5) Commit
- Use Git MCP or git CLI to:
  - `git add .`
  - `git commit -m "feat: scaffold coming soon page structure (no styles yet)"`

## 6) Documentation update
- Update `README.md`:
  - Note how to run and validate
  - Add any known issues
- Update `TASK.md`:
  - Move “Build responsive Coming Soon page” to **Done** when verified
  - Add new items to **Backlog** or **Discovered During Work**
