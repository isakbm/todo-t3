# Todo

A tiny todo app (Next.js, tRPC, Prisma, Mantine).

## Requirements

- Node 24 (`nvm use` picks it up from `.nvmrc`)
- Docker

## Start

1. `docker compose up -d` (Postgres on port 5434)
2. `npm i` (audit / install-script warnings are expected, ignore them)
3. `npx prisma migrate dev`
4. `npm run dev` and open http://localhost:3000
