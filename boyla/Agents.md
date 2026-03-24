# boyla

This file provides context about the project for AI assistants.

## Project Overview

- **Ecosystem**: Typescript

## Tech Stack

- **Runtime**: none
- **Package Manager**: pnpm

### Frontend

- Framework: next
- CSS: tailwind
- UI Library: shadcn-ui
- State: zustand

### Backend

- Framework: self
- Validation: typebox

### Database

- Database: mongodb
- ORM: mongoose

### Authentication

- Provider: supabase-auth

### Additional Features

- Testing: jest
- Email: nodemailer
- Payments: dodo
- Realtime: socket-io
- Job Queue: inngest
- Caching: upstash-redis
- CMS: payload
- Logging: pino
- Observability: grafana

## Project Structure

```
boyla/
├── apps/
│   ├── web/         # Frontend application
├── packages/
│   ├── auth/        # Authentication
│   └── db/          # Database schema
```

## Common Commands

- `pnpm install` - Install dependencies
- `pnpm dev` - Start development server
- `pnpm build` - Build for production
- `pnpm test` - Run tests
- `pnpm db:push` - Push database schema
- `pnpm db:studio` - Open database UI

## Maintenance

Keep Agents.md updated when:

- Adding/removing dependencies
- Changing project structure
- Adding new features or services
- Modifying build/dev workflows

AI assistants should suggest updates to this file when they notice relevant changes.
