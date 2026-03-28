# hello-vue

This repository contains a minimal Vite + Vue 3 + TypeScript project.

- Source: vue-helloworld/
- GitHub Pages site served from: `main` branch -> `/docs` folder

This project was created by OpenClaw.

Development:

1. Install dependencies

```bash
cd vue-helloworld
pnpm install
```

2. Run dev server

```bash
pnpm dev
```

3. Build

```bash
pnpm run build
```

Deployment (manual):

After build, copy the `dist/` output into the repository `docs/` folder and push to main. GitHub Pages should be set to serve from `main` / `/docs`.
