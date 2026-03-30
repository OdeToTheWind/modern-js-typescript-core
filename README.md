# modern-js-typescript-core

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?logo=zod&logoColor=white)
![tRPC](https://img.shields.io/badge/tRPC-2596BE?logo=trpc&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?logo=vitest&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
![Progress](https://img.shields.io/badge/Progress-0%2F100-blue)

**A complete 100-demo roadmap to master modern JavaScript + TypeScript from beginner to production-grade applications.**

Live Repository: https://github.com/OdeToTheWind/modern-js-typescript-core.git

---

## Overview

`modern-js-typescript-core` is a structured, hands-on learning repository designed to take you from TypeScript fundamentals to advanced type-level programming and real-world full-stack applications.

It follows a **progressive learning path** with 100 carefully crafted demos, proper monorepo structure using Yarn/PNPM workspaces, shared utilities, automated CI/CD, and detailed daily progress documentation.

Whether you're a beginner aiming to build strong foundations or an experienced developer looking to outperform in modern frontend/backend TypeScript ecosystems, this repo provides everything you need.

---

## Why This Repository?

- **Systematic Progression**: 25 demos each at Beginner, Intermediate, Advanced, and Real-World levels.
- **Production-Ready Practices**: Strict TypeScript, modern tooling (Vite, Turborepo, Biome/SWC, tRPC, TanStack, etc.), testing, linting, and CI/CD.
- **Type Safety First**: Deep focus on generics, conditional types, branded types, and end-to-end type safety.
- **Documented Journey**: Every demo includes `docs/progress/demo_XX.md` with learnings, challenges, and reflections.
- **Outperform Ready**: By completing all 100 demos, you'll gain skills that set you apart in interviews and real projects.
- **Reusable Architecture**: Shared types, utils, and styles across all demos.

---

## Repository Structure

```bash
modern-js-typescript-core/
├── .github/
│   └── workflows/
│       └── ci-cd.yml           # Automated testing, linting & building
├── docs/
│   ├── progress/
│   │   └── demo_01.md → demo_100.md   # Daily learning logs
│   └── architecture/
│       └── system-design.md    # High-level architecture & tool decisions
├── demos/
│   ├── beginner/               # Demo 01–25
│   ├── intermediate/           # Demo 26–50
│   ├── advanced/               # Demo 51–75
│   └── real-world/             # Demo 76–100
├── shared/
│   ├── types/                  # Global TypeScript interfaces & utilities
│   ├── utils/                  # Common helper functions
│   └── styles/                 # Shared Tailwind/CSS design tokens
├── .gitignore
├── LICENSE
├── package.json                # Root config with Yarn/PNPM workspaces
├── README.md
└── tsconfig.json               # Base TypeScript configuration
```
## Daily Progress

Track your 100-day learning journey. Update the **Status** column as you complete each demo. Every completed demo should also have its own detailed log at `docs/progress/demo_XX.md`.

| Day | Project / Topic                                              | Level          | Status      | Key Learnings / Deliverables |
|-----|--------------------------------------------------------------|----------------|-------------|---------------------------------------------------------------------------------------------|
| 01  | Hello World with Strict TS                                   | Beginner       | ⏳ Planned  | `tsconfig.json` strict mode, ESM setup, `tsc` vs `ts-node`, basic project scaffolding |
| 02  | Variables, Types & Type Inference                            | Beginner       | ⏳ Planned  | Primitives, `unknown`, `never`, type narrowing, type inference rules |
| 03  | Functions & Overloads                                        | Beginner       | ⏳ Planned  | Function signatures, overloads, rest/spread parameters, basic generics |
| 04  | Interfaces vs Types                                          | Beginner       | ⏳ Planned  | Declaration merging, extending interfaces, index signatures, type vs interface differences |
| 05  | Arrays, Tuples & Enums                                       | Beginner       | ⏳ Planned  | Readonly arrays, tuple types, const assertions, string/number enums |
| 06  | Objects & Mapped Types Basics                                | Beginner       | ⏳ Planned  | `keyof`, `typeof`, basic mapped types, optional properties |
| 07  | Union & Intersection Types                                   | Beginner       | ⏳ Planned  | Discriminated unions, type narrowing with `in` and `typeof` |
| 08  | Type Guards & Type Predicates                                | Beginner       | ⏳ Planned  | Custom type guards, `is` keyword, user-defined guards |
| 09  | Classes & Access Modifiers                                   | Beginner       | ⏳ Planned  | `public`/`private`/`protected`, getters/setters, abstract classes |
| 10  | Modules & Namespaces                                         | Beginner       | ⏳ Planned  | `import/export`, barrel files, ambient declarations |
| 11  | Async/Await & Promises                                       | Beginner       | ⏳ Planned  | Proper error handling, `Promise.all`, `Promise.race`, async iterators |
| 12  | Error Handling with Custom Errors                            | Beginner       | ⏳ Planned  | Extending `Error` class, typed custom errors |
| 13  | DOM Manipulation with TS                                     | Beginner       | ⏳ Planned  | Typed DOM APIs, event listeners, type assertions |
| 14  | Fetch API with Typed Responses                               | Beginner       | ⏳ Planned  | Generic fetch wrapper, response typing |
| 15  | LocalStorage with Type Safety                                | Beginner       | ⏳ Planned  | Generic storage utility with JSON serialization |
| 16  | Basic Form Validation                                        | Beginner       | ⏳ Planned  | Native form handling + Zod schema validation |
| 17  | Event Emitter from Scratch                                   | Beginner       | ⏳ Planned  | Typed custom event system |
| 18  | Simple Counter (Vanilla + TS)                                | Beginner       | ⏳ Planned  | State management patterns in vanilla TS |
| 19  | Todo List (CRUD)                                             | Beginner       | ⏳ Planned  | Array immutability, CRUD operations with types |
| 20  | Timer & Debounce Utility                                     | Beginner       | ⏳ Planned  | `setTimeout`, debounce/throttle implementation |
| 21  | ESLint + Prettier Setup                                      | Beginner       | ⏳ Planned  | Linting & formatting configuration |
| 22  | Vitest Basics                                                | Beginner       | ⏳ Planned  | Unit testing setup, `describe`/`it`/`expect` |
| 23  | Vite + TS Template                                           | Beginner       | ⏳ Planned  | Modern bundler setup, HMR, dev server |
| 24  | GitHub Workflow (CI)                                         | Beginner       | ⏳ Planned  | Basic CI pipeline with GitHub Actions |
| 25  | Project Setup Script                                         | Beginner       | ⏳ Planned  | Automating new demo creation |
| 26  | Advanced Generics & Constraints                              | Intermediate   | ⏳ Planned  | `extends`, generic constraints, utility types (`Partial`, `Pick`, `Omit`) |
| 27  | Utility Types Deep Dive                                      | Intermediate   | ⏳ Planned  | `Exclude`, `Extract`, `NonNullable`, `ReturnType`, `Parameters` |
| 28  | Template Literal Types                                       | Intermediate   | ⏳ Planned  | String manipulation at type level |
| 29  | Conditional Types & Infer                                    | Intermediate   | ⏳ Planned  | Type-level if-else, `infer` keyword |
| 30  | Decorators (Stage 3)                                         | Intermediate   | ⏳ Planned  | Class/method/property decorators + `reflect-metadata` |
| 31  | Singleton & Factory Patterns                                 | Intermediate   | ⏳ Planned  | GoF design patterns in TypeScript |
| 32  | Observer Pattern with Types                                  | Intermediate   | ⏳ Planned  | Typed pub-sub system |
| 33  | Dependency Injection Container                               | Intermediate   | ⏳ Planned  | Simple IoC container |
| 34  | Zustand Store with TS                                        | Intermediate   | ⏳ Planned  | Zustand + middleware + persistence |
| 35  | TanStack Query Basics                                        | Intermediate   | ⏳ Planned  | Data fetching, caching, invalidation |
| 36  | React Hook Form + Zod                                        | Intermediate   | ⏳ Planned  | Schema-based form validation |
| 37  | Tailwind + shadcn/ui Setup                                   | Intermediate   | ⏳ Planned  | Component library creation |
| 38  | Axios Interceptors with TS                                   | Intermediate   | ⏳ Planned  | Auth token handling, request/response interceptors |
| 39  | JWT Authentication Flow                                      | Intermediate   | ⏳ Planned  | Login, refresh token, protected routes |
| 40  | Infinite Scroll with TanStack Query                          | Intermediate   | ⏳ Planned  | `useInfiniteQuery` implementation |
| 41  | Dark Mode with Tailwind + Zustand                            | Intermediate   | ⏳ Planned  | Theme persistence and switching |
| 42  | Drag & Drop with `dnd-kit`                                   | Intermediate   | ⏳ Planned  | Accessible drag-and-drop |
| 43  | File Upload with Progress                                    | Intermediate   | ⏳ Planned  | Progress tracking with Fetch/XMLHttpRequest |
| 44  | WebSocket Chat (Basic)                                       | Intermediate   | ⏳ Planned  | Typed WebSocket communication |
| 45  | i18n with next-intl / i18next                                | Intermediate   | ⏳ Planned  | Type-safe internationalization |
| 46  | Date Handling with date-fns + TZ                             | Intermediate   | ⏳ Planned  | Timezone-safe date operations |
| 47  | Form Wizard (Multi-step)                                     | Intermediate   | ⏳ Planned  | Multi-step form state management |
| 48  | Debounce + Throttle + RequestAnimationFrame                  | Intermediate   | ⏳ Planned  | Performance optimization utilities |
| 49  | Vitest + React Testing Library                               | Intermediate   | ⏳ Planned  | Component testing with MSW mocking |
| 50  | Husky + lint-staged + Commitlint                             | Intermediate   | ⏳ Planned  | Git hooks and commit standards |
| 51  | Type-Level Programming (FizzBuzz)                            | Advanced       | ⏳ Planned  | Fully type-level logic implementation |
| 52  | Advanced Conditional Types & Recursion                       | Advanced       | ⏳ Planned  | Deep recursive types |
| 53  | Branded Types & Nominal Typing                               | Advanced       | ⏳ Planned  | Preventing invalid type assignments |
| 54  | Parser Combinators with TS                                   | Advanced       | ⏳ Planned  | Building a small typed parser |
| 55  | Zod + Type Inference Pipeline                                | Advanced       | ⏳ Planned  | Advanced schema composition |
| 56  | tRPC Backend + Frontend                                      | Advanced       | ⏳ Planned  | End-to-end type safety |
| 57  | Effect-TS Basics                                             | Advanced       | ⏳ Planned  | Functional effect system |
| 58  | RxJS with TS (Marble Testing)                                | Advanced       | ⏳ Planned  | Observables, operators, testing |
| 59  | Advanced Zustand (Slices + Middleware)                       | Advanced       | ⏳ Planned  | Immer, devtools, persist middleware |
| 60  | TanStack Router                                              | Advanced       | ⏳ Planned  | Type-safe file-based routing |
| 61  | Next.js 15 App Router + Server Actions                       | Advanced       | ⏳ Planned  | Server Components, streaming |
| 62  | Turborepo + Monorepo Setup                                   | Advanced       | ⏳ Planned  | Workspace caching and sharing |
| 63  | Biome + Oxc Tooling                                          | Advanced       | ⏳ Planned  | Next-gen linting & formatting |
| 64  | SWC + Custom Plugins                                         | Advanced       | ⏳ Planned  | Rust-based compilation |
| 65  | Web Workers + Comlink                                        | Advanced       | ⏳ Planned  | Off-main-thread computation |
| 66  | IndexedDB with Dexie.js                                      | Advanced       | ⏳ Planned  | Offline-first data layer |
| 67  | Service Worker + PWA                                         | Advanced       | ⏳ Planned  | Progressive Web App features |
| 68  | Advanced Animation (Framer Motion)                           | Advanced       | ⏳ Planned  | Gesture and layout animations |
| 69  | Canvas + WebGL Basics                                        | Advanced       | ⏳ Planned  | Typed 2D/3D rendering |
| 70  | Three.js + React Three Fiber                                 | Advanced       | ⏳ Planned  | Declarative 3D scenes |
| 71  | Custom ESLint + TS Rules                                     | Advanced       | ⏳ Planned  | Writing custom lint rules |
| 72  | AST Manipulation                                             | Advanced       | ⏳ Planned  | Code transformation with SWC/Babel |
| 73  | TypeScript Compiler API Basics                               | Advanced       | ⏳ Planned  | Programmatic TS analysis |
| 74  | Performance Profiling                                        | Advanced       | ⏳ Planned  | Lighthouse & Web Vitals optimization |
| 75  | End-to-End Testing with Playwright                           | Advanced       | ⏳ Planned  | Visual regression & E2E testing |
| 76  | Fullstack SaaS Boilerplate (Next.js + tRPC + Prisma)         | Real-World     | ⏳ Planned  | Authentication, Stripe billing, database |
| 77  | Real-time Collaborative Todo                                 | Real-World     | ⏳ Planned  | Multi-user editing with Liveblocks |
| 78  | AI Chat App with Streaming                                   | Real-World     | ⏳ Planned  | Vercel AI SDK, streaming responses |
| 79  | E-commerce Platform                                          | Real-World     | ⏳ Planned  | Cart, wishlist, checkout flow |
| 80  | Dashboard with TanStack Table v8                             | Real-World     | ⏳ Planned  | Sorting, filtering, virtualization |
| 81  | Social Media Feed (Infinite + Virtualized)                   | Real-World     | ⏳ Planned  | High-performance feed |
| 82  | Video Streaming Platform UI                                  | Real-World     | ⏳ Planned  | Custom video player controls |
| 83  | Design System with Storybook + Chromatic                     | Real-World     | ⏳ Planned  | Component library publishing |
| 84  | Micro-Frontend Architecture                                  | Real-World     | ⏳ Planned  | Module Federation |
| 85  | Offline-First Notes App                                      | Real-World     | ⏳ Planned  | Conflict resolution with IndexedDB |
| 86  | Analytics Dashboard                                          | Real-World     | ⏳ Planned  | Data visualization |
| 87  | Multi-tenant Admin Panel                                     | Real-World     | ⏳ Planned  | Role-based access control |
| 88  | Real-time Multiplayer Game Lobby                             | Real-World     | ⏳ Planned  | WebSocket matchmaking |
| 89  | Content Management System                                    | Real-World     | ⏳ Planned  | Markdown editor with live preview |
| 90  | Job Board with Advanced Filters                              | Real-World     | ⏳ Planned  | URL state sync |
| 91  | Finance Tracker with Charts & Export                         | Real-World     | ⏳ Planned  | CSV/PDF export |
| 92  | Booking System (Calendar + Availability)                     | Real-World     | ⏳ Planned  | Complex date logic |
| 93  | Learning Management System UI                                | Real-World     | ⏳ Planned  | Progress tracking |
| 94  | GitHub-like Repo Explorer                                    | Real-World     | ⏳ Planned  | GraphQL + REST hybrid |
| 95  | Accessibility-First Component Library                        | Real-World     | ⏳ Planned  | ARIA compliance & audits |
| 96  | Internationalized E-commerce Store                           | Real-World     | ⏳ Planned  | Currency, locale, RTL support |
| 97  | Low-Code Form Builder                                        | Real-World     | ⏳ Planned  | Drag-and-drop form creation |
| 98  | CI/CD Dashboard for Monorepo                                 | Real-World     | ⏳ Planned  | Workflow visualization |
| 99  | Full Performance Audit Tool                                  | Real-World     | ⏳ Planned  | Custom metrics & reporting |
| 100 | Portfolio + Demo Showcase Site                               | Real-World     | ⏳ Planned  | Final masterpiece combining everything |


## Table of Progress

| Level          | Demos   | Focus                                              | Status         |
|----------------|---------|----------------------------------------------------|----------------|
| **Beginner**   | 1–25    | TypeScript fundamentals, modern JS syntax, basic tooling | ⏳ Planned     |
| **Intermediate**| 26–50   | Design patterns, state management, advanced tooling     | ⏳ Planned     |
| **Advanced**   | 51–75   | Type-level programming, performance, complex architecture | ⏳ Planned     |
| **Real-World** | 76–100  | Production-grade fullstack apps, scalability, end-to-end type safety | ⏳ Planned     |

## Key Features

- **Structured 100-Demo Roadmap** — Progressive learning from basics to production mastery
- **Monorepo Architecture** — Powered by workspaces for clean separation and reusability
- **Shared Layer** — Common types, utilities, and design tokens across all demos
- **Strict TypeScript** — Full strict mode + advanced type-level techniques
- **Modern Tooling** — Vite, Turborepo, Biome, SWC, tRPC, TanStack ecosystem, Zod
- **Testing & Quality** — Vitest, React Testing Library, Playwright, CI/CD pipeline
- **Detailed Documentation** — Daily progress logs + architecture docs
- **Production Practices** — Git hooks, linting, formatting, automated workflows
- **Outperform Focus** — Skills that help you stand out in interviews and real projects

## Getting Started

```bash
# 1. Clone the repository
git clone https://github.com/OdeToTheWind/modern-js-typescript-core.git
cd modern-js-typescript-core

# 2. Install dependencies
pnpm install
# or
yarn install

# 3. Navigate to any demo and run it
cd demos/beginner/demo_01_hello_world
pnpm dev

# 4. Run tests across all demos
pnpm test

# 5. Build everything
pnpm build
```
**Tip**: Start with `demo_01` and follow the daily progress table. Document your learnings in `docs/progress/demo_01.md` after completion.

## Backend Tech Stack & Deployment Strategy

### Tech Stack (Real-World Demos)
- **Framework**: Next.js 15 App Router (Server Components + Server Actions)
- **Type Safety**: tRPC (end-to-end types) + Zod schemas
- **Database**: Prisma ORM + PostgreSQL (or SQLite for local)
- **Authentication**: NextAuth.js / Clerk / JWT
- **Payments**: Stripe (for SaaS demos)
- **Real-time**: Liveblocks / Pusher / Socket.io
- **State Management**: Zustand + TanStack Query
- **Styling**: Tailwind CSS + shadcn/ui

### Deployment Strategy
- **Frontend & Fullstack**: Vercel (recommended) or Netlify
- **Database**: Supabase / Neon / Railway
- **CI/CD**: GitHub Actions (lint → test → build → deploy)
- **Preview Deployments**: Automatic on every PR
- **Production**: Vercel Edge Functions + Serverless
- **Monitoring**: Vercel Analytics + Sentry (error tracking)

## Contributing

Contributions are highly welcome! Whether it's:

- Adding a new demo
- Improving existing code or documentation
- Fixing bugs
- Suggesting better patterns or tools

Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-demo`)
3. Commit your changes (`git commit -m 'Add amazing demo'`)
4. Push to the branch (`git push origin feature/amazing-demo`)
5. Open a Pull Request

<!-- Read the full guidelines in [CONTRIBUTING.md](CONTRIBUTING.md). -->

## License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

Feel free to use, modify, and distribute the code as you learn and build.