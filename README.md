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