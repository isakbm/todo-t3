# Todo

A tiny todo app (Next.js, tRPC, Prisma, Mantine).

## Requirements

- Node 24 (`nvm use` picks it up from `.nvmrc`)
- Docker

## Start

1. `cp .env.example .env`
2. `docker compose up -d` (Postgres on port 5434)
3. `npm i` (audit / install-script warnings are expected, ignore them)
4. `npx prisma migrate dev`
5. `npm run dev` and open http://localhost:3000
