# Namaste Food Delivery

A food‑ordering web app built while following the **[Namaste React](https://namastedev.com/learn/namaste-react)** course by Akshay Saini ([NamasteDev](https://namastedev.com/)).

This repository is coursework — the code is written step by step alongside the lessons to learn React from the ground up: components, JSX, hooks, state management, routing, class components, custom hooks, performance optimization, and building a scalable frontend architecture.

## Tech stack

- **React 19**
- **Vite** — dev server and build tooling, with HMR
- **React Compiler** — enabled via `babel-plugin-react-compiler`
- **ESLint** — linting (flat config)
- **Prettier** — code formatting

## Getting started

```bash
npm install
npm run dev
```

The app runs at the URL Vite prints (default `http://localhost:5173`).

## Scripts

| Command                | Description                              |
| ---------------------- | ---------------------------------------- |
| `npm run dev`          | Start the Vite dev server with HMR       |
| `npm run build`        | Build for production into `dist/`        |
| `npm run preview`      | Preview the production build locally     |
| `npm run lint`         | Run ESLint over the project              |
| `npm run format`       | Format all files with Prettier           |
| `npm run format:check` | Check formatting without writing changes |

## Code style

Formatting is handled by Prettier (config in `.prettierrc.json`); ESLint defers all
formatting concerns to it via `eslint-config-prettier`. Run `npm run format` before
committing.

## Acknowledgements

Course and curriculum by [Akshay Saini](https://namastedev.com/) — Namaste React.
