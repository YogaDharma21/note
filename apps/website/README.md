# AI Notetaking

A React and TypeScript notebook workspace built with Vite and Tailwind CSS.

## Prerequisites

- Node.js 20.19 or newer
- pnpm 10

## Setup

```bash
corepack enable
pnpm install
```

## Commands

```bash
pnpm dev      # Start the development server
pnpm lint     # Run ESLint
pnpm build    # Type-check and create a production build
pnpm preview  # Preview the production build
```

The frontend calls the Go API through `VITE_API_BASE_URL`, which defaults to `http://127.0.0.1:3000`.
