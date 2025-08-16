# Faith & Fitness — Coming Soon

## Run locally
- Serve statics with any server (example):
  - `npx http-server -p 4173`
  - Open http://localhost:4173

## Validate
- HTML: `npx html-validate index.html`
- Links: `npx linkinator . -r`

## Deploy (GitHub Pages)
- In GitHub: Settings → Pages → Source: `main` / `/root`
- Wait for the Pages URL to appear.

## AI Assistant (Cline)
- Workflows live in `.clinerules/workflows/`
- Run with `/project-init.md` or `/homepage-coming-soon.md` in Cline chat.
- MCP servers enabled for Git and filesystem (verify in Cline → MCP Servers).

## Conventions
- One task per change.
- Keep files < 500 lines.
- Update this README and TASK.md after changes.

## Lighthouse CI
- Local (mobile): start server `npx http-server -p 4173`, then `npm run lh:mobile`
- Desktop (local): `npm run lh:desktop`
- After deploy: set the Pages URL in `lighthouserc.json`, then `npm run lh:autorun`
- Reports: see `lhci-reports/`
- Example (live):
  npm run lh:autorun -- --collect.url=https://draft-domain.github.io/fit-faith/


## Design reference
- Visual inspiration: https://codepen.io/itismowgli/pen/gjLJeE
- We reimplemented the look to keep licensing clean. If we reuse code, we will add license/attribution here.

## Known Issues
- The Facebook group link (`https://www.facebook.com/groups/fitandfocusedinfaith2`) returns a `400 Bad Request` error when checked with `linkinator`. This may be because the group is private and requires a login to view. The link has been kept as is for now.
