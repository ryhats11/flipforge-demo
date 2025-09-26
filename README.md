# FlipForge Lite

Minimal, fast, single-page app to plan website turnarounds with drag-and-drop blocks. Pure frontend.  
**Tech:** React + Zustand + @dnd-kit + Tailwind + Zod + shadcn/ui + Lucide icons.

## Getting Started

```sh
pnpm install
pnpm dev
```

Then open [http://localhost:5173/](http://localhost:5173/) in your browser.

## Keyboard Shortcuts

- Move: ↑ / ↓
- Indent/Outdent: Cmd/Ctrl + [ / ]
- Edit: Enter
- Quick Add: Cmd/Ctrl + K
- Multi-select: Shift / Cmd + click
- Undo/Redo: Cmd/Ctrl + Z / Y

## Import/Export

Toolbar → Import/Export. JSON is validated.

## JSON Schema

See `src/lib/schema.ts`.

## Accessibility

- Full keyboard drag, focus rings, ARIA live
- High-contrast, aria-labels on icons

## Test

```sh
pnpm test
```