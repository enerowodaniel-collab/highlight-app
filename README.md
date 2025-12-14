# Highlight — Study Smarter

Simple single-page React app (Vite + Tailwind) for taking notes, highlighting, generating flashcards, and a Pomodoro timer.

Quick start:

1. Install dependencies:

```bash
npm install
```

2. Run dev server:

```bash
npm run dev
```

App features:
- Notes editor (contentEditable) with color highlights. Saved to `localStorage`.
- Flashcards generated from highlighted spans (question = highlighted text, answer = surrounding paragraph or full note text).
- Pomodoro timer (25/5) with progress bar and optional sound.

Deploy: build with `npm run build` and deploy `dist` to Vercel or GitHub Pages.
