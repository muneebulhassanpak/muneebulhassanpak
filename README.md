# Muhammad Muneeb-Ul-Hassan

Full-stack Next.js + Supabase/Postgres developer. I build SaaS products and add AI features that ship.

## Featured work

| Project | What it is | Stack | Links |
| --- | --- | --- | --- |
| **LLM Lead Qualifier** | An API that scores incoming sales enquiries with Claude, sends uncertain ones to a person for review, and syncs approved leads to a CRM with retries and no duplicates. 360 tests, 98% coverage. | FastAPI, Python, Postgres, Claude API, Docker, Render | [Live API docs](https://lead-qualification-api-h4sy.onrender.com/docs) · [Code](https://github.com/muneebulhassanpak/fastapi-llm-lead-qualifier) |
| **Proposly** | An internal quoting tool for agencies: reps build quotes, managers approve discounts, clients accept branded proposals from a link. Data isolation checked with 71 row-level security tests. | Next.js, TypeScript, Supabase, Resend, Vercel | [Live demo](https://proposly-three.vercel.app) · [Code](https://github.com/muneebulhassanpak/Proposly) |
| **Stackboard** *(in development)* | Multi-tenant project management for agencies: Kanban boards, sprints, time tracking, invoices and a client portal. | Next.js, TypeScript, Neon Postgres, Drizzle, Better Auth, Cloudflare Workers | [Live preview](https://nextjs-neon-project-management-saas.vercel.app) · [Code](https://github.com/muneebulhassanpak/nextjs-neon-project-management-saas) |
| **TrendScope** | A market intelligence dashboard for sneakers, bags and watches, with rankings, comparisons and an admin area for research articles. | Next.js, TypeScript, Supabase, Recharts, GitHub Actions | [Live demo](https://trendscope-ruddy-kappa.vercel.app) · [Code](https://github.com/muneebulhassanpak/trendscope) |
| **RentDesk** | Property management for landlords, managers, tenants and vendors: properties, units, tenants and the full lease lifecycle, with a role-based dashboard for each. | Next.js, TypeScript, FastAPI, Neon Postgres | [Live demo](https://rentdesk-web.vercel.app) · [Frontend](https://github.com/muneebulhassanpak/rentdesk-web) · [API](https://github.com/muneebulhassanpak/rent-desk-api) |
| **Lockerly** *(in development)* | Drive-style cloud file storage: upload, organise, preview, share and search files. | Next.js, Supabase, Cloudflare R2 | [Code](https://github.com/muneebulhassanpak/nextjs-supabase-r2-cloud-drive) |

## How I build

- **Tested and checked before merge.** On my main projects, CI runs lint, type checks, unit, integration and end-to-end tests, and replays database migrations before anything merges.
- **Data isolation in the database.** Multi-tenant apps use Postgres row-level security, so one customer can never read another's data, even if app code has a bug.
- **Typed end to end.** TypeScript in strict mode on the frontend, Pydantic and strict mypy on Python services.
- **Small, reviewable pull requests** with Conventional Commits, so history is easy to follow and every change can be traced.
- **Database changes only through migrations**, never by hand, and deploys run from `main` after CI passes.

## Stack

Next.js, React, TypeScript, Tailwind CSS, shadcn/ui · Supabase, Neon, Postgres, Drizzle · FastAPI, Python · Claude and OpenAI APIs, RAG · Stripe · Vercel, Cloudflare (Workers, R2), Render, Docker · GitHub Actions, Vitest, Playwright, pytest
