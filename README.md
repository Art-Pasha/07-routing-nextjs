# NoteHub (Next.js)

Продовження домашнього завдання 05-notehub: перенесено на Next.js (App Router)
з підтримкою SSR/CSR, багатосторінковою структурою та гідратацією TanStack Query.

## Маршрути

- `/` — головна сторінка
- `/notes` — список нотаток (SSR + CSR, пошук, пагінація, створення нотатки)
- `/notes/[id]` — деталі однієї нотатки (SSR + CSR)

## Запуск

```bash
npm install
cp .env.example .env.local   # і впиши свій NEXT_PUBLIC_NOTEHUB_TOKEN
npm run dev
```

Документація бекенда: https://notehub-public.goit.study/api/docs
