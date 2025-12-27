# Nuxt 3 UI Starter

This project is a minimal starter template for building applications with [Nuxt 3](https://nuxt.com/) and styling them using [`@nuxt/ui`](https://ui.nuxt.com/), which is built on top of [Tailwind CSS](https://tailwindcss.com/).

The setup includes:

- Nuxt 3
- [`@nuxt/ui`](https://ui.nuxt.com/) (using Tailwind CSS utility classes)
- Custom CSS support via `~/assets/css/main.css` configured in [`nuxt.config.ts`](nuxt.config.ts)

## Setup

Make sure to install dependencies:

```bash
# npm
npm install

# pnpm
pnpm install

# yarn
yarn install

# bun
bun install
```

## Custom Styling

While `@nuxt/ui` uses Tailwind CSS internally, you can define your own base styles, utility classes, or global imports in `assets/css/main.css`. This file is explicitly included in the project configuration:

See [`nuxt.config.ts`](nuxt.config.ts:6):

```typescript
css: ['~/assets/css/main.css'],
```

To use custom styles, ensure the `assets/css/main.css` file contains your desired CSS.

## Development Server

Start the development server on `http://localhost:3000`:

```bash
# npm
npm run dev

# pnpm
pnpm dev

# yarn
yarn dev

# bun
bun run dev
```

## Production

Build the application for production:

```bash
# npm
npm run build

# pnpm
pnpm build

# yarn
yarn build

# bun
bun run build
```

Locally preview production build:

```bash
# npm
npm run preview

# pnpm
pnpm preview

# yarn
yarn preview

# bun
bun run preview
```

Check out the [Nuxt 3 deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.
