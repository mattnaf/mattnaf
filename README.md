# Matt Nafarrete

**AI / Full-Stack Engineer** · San Diego, CA · AWS Certified Cloud Practitioner

AI/full-stack engineer who ships multi-tenant SaaS solo and orchestrates agent systems that run themselves. I deliver applied AI for clients — API layers between LLMs and apps, agentic RAG, OAuth platform integrations — and build production SaaS end to end on AWS and Firebase/GCP, with Postgres RLS, Stripe Connect, and CI/CD. When I'm not on client work, I'm running autonomous multi-agent pipelines on a private fleet.

## What I'm building

**A multi-agent "AI household."** Role-decoupled Claude Code agents — an executer, an overwatch, an accountability keeper — coordinate over a task-MCP job queue, backed by a private hybrid-search RAG (Qdrant) on a self-hosted Mac/GPU fleet. Config lives in a git-synced hub with session hooks; headless `claude -p` jobs run on cron. It plans, executes, and verifies its own work with me in the loop only where it counts.

**Production multi-tenant SaaS, solo.** [OnCadenceOS](#) is a boutique-gym management platform — a Turborepo monorepo of six independently-deployed Next.js surfaces, multi-tenancy on Drizzle + Supabase Postgres with RLS (subdomain → middleware → JWT-claim isolation), Stripe Connect behind a payment-provider abstraction, Inngest background jobs, and GitHub Actions + Vercel CI/CD. [Ohh-Snaps](#) is a 10-repo modular event-engagement platform (7 Next.js + Firebase apps + native iOS) with Stripe slot-metered billing, no-install guest modules, and nightly Playwright E2E across every surface — plus an autonomous lead pipeline of 5 Claude Code agents on cron across a 3-machine fleet that scored 2,398 leads in 34 minutes at zero marginal API cost.

## Selected work

- **Multi-Agent Assistant Household** — agentic orchestration over MCP + private RAG on a self-hosted fleet. *(writeup coming)*
- **OnCadenceOS** — solo-built multi-tenant boutique-gym SaaS; live demo tenant on prod.
- **Ohh-Snaps / Lasana Creative** — modular event-engagement SaaS that has run real customer events.
- **Parsley360** — .NET/C# API layer between an AI engine and client apps, agentic RAG, AWS infra (contract).
- **Fanded** — AI business assistant with OAuth into artists' platforms (Spotify, YouTube) (contract).

## Tech

**AI / Agentic:** LLM orchestration · Claude Code (headless `-p`) · multi-agent systems · MCP · RAG / Qdrant hybrid · agentic RAG · Python / FastAPI
**Web:** React · Next.js · TypeScript · Tailwind · Node.js · .NET / C#
**Data:** Postgres / Supabase · RLS · Drizzle · Firestore · SQLite · Qdrant
**Payments & Multi-tenancy:** Stripe Connect · Stripe Billing · subdomain isolation · white-label
**Cloud & DevOps:** AWS · Firebase / GCP · Vercel · GitHub Actions · Turborepo · Playwright
**Mobile:** Flutter · Swift · iOS

## Links

[LinkedIn](https://www.linkedin.com/in/mattnafarrete/) · mattnaf@gmail.com
