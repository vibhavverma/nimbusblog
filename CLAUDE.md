# Nimbus Blog

## Structure
- `App.tsx` — Main app component with mode toggle
- `components/` — React components (editor, preview, article cards)
- `data/` — Article data and content
- `hooks/` — Custom React hooks
- `types.ts` — TypeScript type definitions
- `metadata.json` — Site metadata config

## Build & Dev
- Dev: `pnpm dev`
- Build: `pnpm run build`
- Deploy: Push to main (auto-deploys via GitHub Pages)

## Tech
- React 19 + TypeScript + Vite
- Marked for markdown rendering
- GitHub Pages hosting

## Key Patterns
- Preview/Edit mode toggle (bottom-right corner)
- Notion content paste auto-converts to markdown
- Scheduled articles visible in edit mode only until publish date
