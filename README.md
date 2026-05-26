# architecture-planner

## Stack

- [Next.js](https://nextjs.org/) (App Router)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [shadcn/ui](https://ui.shadcn.com/)
- [ESLint](https://eslint.org/) + [Prettier](https://prettier.io/)

## Getting Started

```bash
npm run dev       # start dev server → http://localhost:3000
npm run build     # production build
npm run lint      # lint
```

## Structure

```
src/
├── app/
│   ├── layout.tsx
│   ├── page.tsx
│   └── globals.css
├── components/
│   ├── Dashboard.tsx
│   ├── EmptyState.tsx
│   ├── LoadingSpinner.tsx
│   └── PageHeader.tsx
├── features/
├── hooks/
├── types/
├── services/
└── lib/
    ├── api/
    └── utils.ts
```

## Conventions

- Components in `src/components/` are shared across the app
- Use `cn()` from `@/lib/utils` for conditional Tailwind classes
- shadcn/ui components live in `src/components/ui/`
