# ShopApp Angular Frontend

Frontend e-commerce application built with Angular 19 and SSR support.

## Tech Stack

- Angular 19
- TypeScript
- SCSS
- Bootstrap 5 + Font Awesome
- PNPM (recommended package manager)

## Prerequisites

- Node.js 20+
- Corepack enabled (`corepack enable`)

## Getting Started

```bash
corepack pnpm install
corepack pnpm start
```

The app starts on `http://localhost:4200`.

## Hướng Dẫn Chạy Dự Án

1. Cài dependencies:

```bash
corepack pnpm install
```

2. Chạy môi trường development:

```bash
corepack pnpm start
```

3. Build production:

```bash
corepack pnpm run build
```

4. Chạy test một lần (CI/headless):

```bash
corepack pnpm run test:ci
```

## Available Scripts

- `corepack pnpm start`: Run development server.
- `corepack pnpm run start:dev`: Run development server on port `4300`.
- `corepack pnpm run build`: Build production bundles.
- `corepack pnpm run build:production`: Explicit production build.
- `corepack pnpm run watch`: Build in watch mode.
- `corepack pnpm run test`: Run Karma test watcher.
- `corepack pnpm run test:ci`: Run tests once in Chrome Headless mode.

## Production Notes

- SSR build output is generated in `dist/shopapp-angular`.
- Prerender is currently disabled for build stability.

## Project Structure

- `src/app/components`: Feature and layout components.
- `src/app/services`: API and state services.
- `src/app/guards`: Route guards.
- `src/app/interceptors`: HTTP interceptors.
- `src/environments`: Environment configurations.

## UI Attribution

Footer attribution in the app is set to: `Làm bởi Nguyễn Sơn 2026`.

## Chủ Dự Án

Dự án này được thực hiện bởi **Nguyễn Sơn**.
