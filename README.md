# Nimbus Blog

A blog CMS and publishing tool built with React and TypeScript. Designed as a Notion-to-website pipeline — write content in Notion, publish through the editor, preview on a staging site.

**Live:** [vibhavverma.github.io/nimbusblog](https://vibhavverma.github.io/nimbusblog/)

## Features

- **Preview + Edit modes** — Toggle between staging preview and content editing
- **Notion integration** — Paste content from Notion, auto-converts to markdown
- **Scheduled publishing** — Set future publication dates for articles
- **Featured content** — Cycle featured articles on the main page
- **Category management** — Organize articles by topic
- **Article management** — Create, edit, archive, and reorder articles

## Tech Stack

- **React 19** + **TypeScript**
- **Vite** — Build tooling
- **Marked** — Markdown rendering
- **GitHub Pages** — Hosting via automated deploy

## Development

```bash
pnpm install
pnpm dev
```

## Deploy

Pushes to `main` auto-deploy to GitHub Pages via the included workflow.

```bash
pnpm run build
# Or manually: npm run deploy
```

## License

MIT — see [LICENSE](LICENSE) for details.
