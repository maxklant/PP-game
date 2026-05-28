# PP-Game — Privacy Quest

> *Edim en Max epic voor privacy quest.*

A small browser game built as a collaboration between **Edim** and **Max**, themed around privacy and the choices we make with our data.

## Status

Early scaffold — the project skeleton is in `pp-game/`, built on Vite + React + TypeScript. Gameplay is still being designed; expect rapid changes.

## Tech stack

- **Vite** — dev server and bundler
- **React 19** + **TypeScript**
- **ESLint** — code quality
- **PostCSS** + **Autoprefixer**

## Quick start

```bash
git clone https://github.com/maxklant/PP-game.git
cd PP-game/pp-game
npm install
npm run dev
```

Open the printed URL (usually http://localhost:5173).

### Other scripts

```bash
npm run build        # type-check + production bundle
npm run preview      # preview the production build
npm run lint         # run ESLint
```

## Project structure

```
PP-game/
└── pp-game/
    ├── src/         # game code
    ├── public/      # static assets
    ├── index.html
    └── vite.config.ts
```

## Concept

A short, narrative-driven quest where the player makes choices about how their data is collected, shared, and used — and lives with the consequences. Inspired by real-world privacy patterns (cookies, consent banners, dark patterns) and reframed as a game.

More to come.

## License

MIT — see `LICENSE` once added.
