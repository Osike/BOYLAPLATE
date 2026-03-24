# boyla

This project was created with [Better Fullstack](https://github.com/Marve10s/Better-Fullstack), a modern TypeScript stack that combines Next.js, Self, and more.

## Features

- **TypeScript** - For type safety and improved developer experience
- **Next.js** - Full-stack React framework
- **TailwindCSS** - CSS framework
- **shadcn/ui** - UI components
- **Mongoose** - TypeScript-first ORM
- **MongoDB** - Database engine
- **Authentication** - Supabase Auth
- **Turborepo** - Optimized monorepo build system
- **Oxlint** - Oxlint + Oxfmt (linting & formatting)
- **PWA** - Progressive Web App support
- **Starlight** - Documentation site with Astro
- **TanStack Virtual** - Virtualized lists & grids for 60fps performance
- **TanStack DB** - Reactive client-first data store
- **TanStack Pacer** - Debounce, throttle & rate-limit utilities

## Getting Started

First, install the dependencies:

```bash
pnpm install
```

## Database Setup

This project uses MongoDB with mongoose.

1. Make sure you have MongoDB set up.
2. Update your `apps/web/.env` file with your MongoDB connection URI.

3. Apply the schema to your database:

```bash
pnpm run db:push
```

Then, run the development server:

```bash
pnpm run dev
```

Open [http://localhost:3001](http://localhost:3001) in your browser to see the fullstack application.

## Git Hooks and Formatting

- Format and lint fix: `pnpm run check`

## Project Structure

```
boyla/
├── apps/
│   └── web/         # Fullstack application (Next.js)
│   ├── docs/        # Documentation site (Astro Starlight)
├── packages/
│   ├── api/         # API layer / business logic
│   ├── auth/        # Authentication configuration & logic
│   └── db/          # Database schema & queries
```

## Available Scripts

- `pnpm run dev`: Start all applications in development mode
- `pnpm run build`: Build all applications
- `pnpm run check-types`: Check TypeScript types across all apps
- `pnpm run db:push`: Push schema changes to database
- `pnpm run db:studio`: Open database studio UI
- `pnpm run check`: Run Oxlint and Oxfmt
- `cd apps/web && pnpm run generate-pwa-assets`: Generate PWA assets
- `cd apps/docs && pnpm run dev`: Start documentation site
- `cd apps/docs && pnpm run build`: Build documentation site


## ADITIONS MYSELF 
- 
◇  Dependencies installed successfully

 ╭───────────────────────────────────────────────────────────╮
 │                                                           │
 │  Next steps                                               │
 │  1. cd boyla                                              │
 │  2. pnpm run dev                                          │
 │  Your project will be available at:                       │
 │  • Frontend: http://localhost:3001                        │
 │  • Docs: http://localhost:4321                            │
 │  • Fumadocs: http://localhost:4000                        │
 │                                                           │
 │  Git hooks with Lefthook:                                 │
 │  • Install hooks: pnpm lefthook install                   │
 │                                                           │
 │  Linting and formatting:                                  │
 │  • Format and lint fix: pnpm run check                    │
 │                                                           │
 │  Documentation with Starlight:                            │
 │  • Start docs site: cd apps/docs && pnpm run dev          │
 │  • Build docs site: cd apps/docs && pnpm run build        │
 │                                                           │
 │  Like Better Fullstack? Please consider giving us a star  │
 │     on GitHub:                                            │
 │  https://github.com/Marve10s/Better-Fullstack             │
 │                                                           │
 ╰───────────────────────────────────────────────────────────╯

│
◆  You can reproduce this setup with the following command:
│  pnpm create better-fullstack@latest boyla --frontend next --backend self --runtime none --database mongodb --orm mongoose --api none --auth supabase-auth --payments dodo --email nodemailer --file-upload filepond --effect effect-full --css-framework tailwind --ui-library shadcn-ui --shadcn-base radix --shadcn-style maia --shadcn-icon-library hugeicons --shadcn-color-theme yellow --shadcn-base-color zinc --shadcn-font roboto --shadcn-radius default --ai none --state-management zustand --forms conform --validation typebox --testing jest --animation framer-motion --realtime socket-io --job-queue inngest --logging pino --observability grafana --caching upstash-redis --cms payload --search meilisearch --file-storage r2 --addons turborepo oxlint lefthook mcp skills ruler wxt opentui pwa fumadocs starlight tanstack-virtual tanstack-db tanstack-pacer --examples none --db-setup mongodb-atlas --web-deploy none --server-deploy none --ai-docs claude-md agents-md --no-git --package-manager pnpm --install
│
└  Project created successfully in 2545.23 seconds!