# Namaste Food Delivery

A food-ordering app I'm rebuilding while working back through Akshay Saini's
**[Namaste React](https://namastedev.com/learn/namaste-react)** course — mostly to
knock the rust off the fundamentals and see what's changed in the ecosystem since
I last set a project up from scratch.

Tracking the course chapter by chapter: JSX and rendering, component composition,
hooks, config-driven data, routing, class components, context, and the
performance/optimization passes toward the end.

## Stack

- React 19
- Vite (+ HMR)
- React Compiler via `babel-plugin-react-compiler`
- ESLint (flat config) + Prettier

## Running it

```bash
npm install
npm run dev
```

## Scripts

| Command                | Does                        |
| ---------------------- | --------------------------- |
| `npm run dev`          | Dev server with HMR         |
| `npm run build`        | Production build to `dist/` |
| `npm run preview`      | Serve the production build  |
| `npm run lint`         | ESLint                      |
| `npm run format`       | Prettier write              |
| `npm run format:check` | Prettier check (CI)         |

## Notes to self

- Prettier owns formatting; `eslint-config-prettier` is last in the flat config so
  ESLint stays out of its way. Run `npm run format` before committing.
- Config lives in `.prettierrc.json` — defaults plus single quotes.

---

Course by [Akshay Saini](https://namastedev.com/).
