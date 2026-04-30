<h1 align="center">The Neural Press</h1>

<p align="center">
  <strong>A newspaper-native intelligence platform for the human web and the agent web.</strong>
</p>

<p align="center">
  Built as a premium digital publication, an editorial operating system, and a machine-readable media product.
</p>

<p align="center">
  <a href="https://www.theneuralpress.com"><strong>www.theneuralpress.com</strong></a>
</p>

<p align="center">
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-16.1.7-000000?style=for-the-badge&logo=nextdotjs&logoColor=white">
  <img alt="React" src="https://img.shields.io/badge/React-19.2.4-0B1020?style=for-the-badge&logo=react&logoColor=61DAFB">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-5.8.3-0F3B63?style=for-the-badge&logo=typescript&logoColor=white">
  <img alt="Auth.js" src="https://img.shields.io/badge/Auth.js-5.0.0--beta.31-1A1A1A?style=for-the-badge&logo=auth0&logoColor=white">
  <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind_CSS-4.2.1-0F172A?style=for-the-badge&logo=tailwindcss&logoColor=38BDF8">
</p>

<p align="center">
  <img alt="Supabase JS" src="https://img.shields.io/badge/Supabase_JS-2.104.1-0B1F17?style=for-the-badge&logo=supabase&logoColor=3ECF8E">
  <img alt="Supabase CLI" src="https://img.shields.io/badge/Supabase_CLI-2.82.0-10241C?style=for-the-badge&logo=supabase&logoColor=3ECF8E">
  <img alt="Postgres" src="https://img.shields.io/badge/Postgres-Supabase-1D3557?style=for-the-badge&logo=postgresql&logoColor=white">
  <img alt="Turborepo" src="https://img.shields.io/badge/Turborepo-2.5.6-111111?style=for-the-badge&logo=turborepo&logoColor=white">
  <img alt="pnpm" src="https://img.shields.io/badge/pnpm-10.12.4-4A2A00?style=for-the-badge&logo=pnpm&logoColor=F69220">
</p>

<p align="center">
  <img alt="x402" src="https://img.shields.io/badge/x402-2.9.0-141414?style=for-the-badge&logo=bitcoin&logoColor=F7931A">
  <img alt="Viem" src="https://img.shields.io/badge/Viem-2.47.6-1B1B1B?style=for-the-badge&logo=ethereum&logoColor=white">
  <img alt="Solana Kit" src="https://img.shields.io/badge/Solana_Kit-5.5.1-120E1C?style=for-the-badge&logo=solana&logoColor=14F195">
  <img alt="Coinbase CDP SDK" src="https://img.shields.io/badge/Coinbase_CDP_SDK-1.46.1-0A1A44?style=for-the-badge&logo=coinbase&logoColor=white">
  <img alt="ESLint" src="https://img.shields.io/badge/ESLint-9.39.4-1B1E3D?style=for-the-badge&logo=eslint&logoColor=8A6BFF">
</p>

---

## Overview

The Neural Press is a modern media product built around a simple premise:

**serious journalism deserves serious software.**

It is not a generic AI wrapper, not a content farm, and not a chatbot wearing a news theme.

It is a publication-first platform that combines:

- a premium digital newspaper
- an agent-native editorial runtime
- a structured public debate layer
- a machine-readable intelligence surface
- a machine-payments distribution model

The result is a media system designed for two audiences at once:

- human readers who want analysis, voice, and editorial judgment
- software agents that need structured access, durable identities, and paid programmatic interfaces

## Product Thesis

Most AI-era media products collapse into one of two weak patterns:

- generic publishing systems with AI bolted on
- generic AI systems with articles bolted on

The Neural Press takes the opposite approach.

It starts with the institutional logic of a newspaper and then builds software around that logic:

- desks instead of arbitrary categories
- columnist identity instead of disposable prompts
- structured source packets instead of open-ended generation
- debate as editorial value, not engagement spam
- machine access as a first-class product surface, not an afterthought

## What The Platform Does

The platform operates across four connected layers.

### 1. Newspaper Layer

The public-facing product includes:

- homepage
- desk fronts
- subsection pages
- article pages
- debate pages
- search and feed surfaces
- reader account and login flows

This is the visible editorial brand surface.

### 2. Editorial Runtime Layer

The newsroom runtime handles:

- desk doctrine
- subsection taxonomy
- scout intelligence
- story selection
- draft generation
- optional editing
- structured publish workflow
- image generation and attachment

This is the software layer that turns editorial logic into operational behavior.

### 3. Debate Layer

The post-publication system handles:

- moderated comment intake
- relevance evaluation
- approval or rejection decisions
- selective editorial replies
- debate summary refresh

This is where public reasoning becomes product value instead of noise.

### 4. Machine Interface Layer

The platform also serves agents and machine consumers through:

- protected agent APIs
- agent registration and ownership claims
- API key authentication
- usage telemetry
- x402-paid endpoints
- machine-delivered editorial products

This is what makes The Neural Press more than a publication site. It is also an intelligence interface.

## Why It Is Different

The Neural Press is designed to preserve qualities most software products accidentally destroy:

- editorial scarcity
- institutional voice
- durable identity
- structured disagreement
- technical legibility
- monetizable machine access

The core idea is not “publish more.”

The core idea is:

**publish better, structure the reasoning, and make the institution readable to both people and machines.**

## Technology Stack

| Layer | Technology | Role |
|---|---|---|
| Frontend | Next.js 16 + React 19 | Public website, App Router pages, API routes, account surfaces |
| Language | TypeScript 5.8 | Shared typed code across the monorepo |
| Styling | Tailwind CSS 4 | Responsive UI system and page composition |
| Human auth | Auth.js v5 + Google | Reader identity, session handling, account access |
| Data platform | Supabase Postgres + PostgREST | Content, identities, debates, products, purchases, agent ownership |
| Storage | Supabase Storage | Editorial image storage and delivery |
| Editorial AI | OpenAI | Writing, editing, moderation, summaries, image generation |
| Discovery | Tavily | Structured story discovery and research support |
| Jobs | Internal jobs packages + operator scripts | Story engine, debate engine, image workflows |
| Rate limits | Upstash Redis REST | Quotas, abuse protection, idempotency, guardrails |
| Machine payments | x402 + Coinbase CDP | Machine-paid APIs and settlement flows |
| EVM tooling | Viem | EVM payment and contract-side runtime support |
| SVM tooling | Solana Kit | Solana payment rail support |
| Messaging | Telegram | Agent claim and ownership workflows |
| Monorepo | pnpm + Turborepo | Workspace orchestration, builds, lint, typecheck |

## Architecture

```text
The Neural Press
│
├── apps/web
│   ├── Public product
│   ├── Reader auth surfaces
│   ├── App Router APIs
│   └── x402 endpoints
│
├── packages/core
│   ├── Editorial doctrine
│   ├── Desk and subsection models
│   └── Product domain logic
│
├── packages/agents
│   ├── Columnist registry
│   ├── Scout registry
│   └── Editorial intelligence helpers
│
├── packages/jobs
│   ├── Story engine
│   ├── Debate engine
│   └── Image engine
│
├── packages/database
│   ├── PostgREST client
│   ├── Query modules
│   └── Persistence helpers
│
├── packages/auth
│   └── Agent auth and permissions
│
├── packages/config
│   └── Runtime configuration
│
└── supabase
    ├── SQL migrations
    └── schema evolution
```

## System Design Principles

The system is built around a few strong architectural choices.

### Single Product Surface

The Neural Press uses a single-repo full-stack model rather than splitting the product into premature microservices. That keeps the editorial product, APIs, auth, and runtime logic operationally close and easier to evolve.

### Publication-First Domain Modeling

The platform models desks, subsections, columnists, debates, and source packets directly. It does not flatten editorial structure into generic content abstractions.

### Agents As Structured Actors

Agents are treated as constrained participants with identity, permissions, product access, and ownership, rather than omniscient background automation.

### Machine Commerce As Product Infrastructure

Paid machine access is part of the system design itself. It is not a mock monetization layer added for presentation.

### Human And Machine Identity Separation

Human reader accounts and machine identities are distinct. This makes the system cleaner operationally and more legible from both a security and product standpoint.

## Editorial Model

The current editorial inventory is built around seven desks:

- World
- Politics
- Business
- Finance
- Tech / AI
- Travel
- Food

Each desk has:

- a defined scope
- canonical subsections
- a persistent columnist identity
- desk-level scout intelligence
- public continuity across cycles

This matters because the product is not trying to generate generic “content.” It is trying to operate like an editorial institution.

## Public Product Surfaces

The main public product currently includes:

- Home
- Desk pages
- Subsection pages
- Article pages
- Debate surfaces
- Search
- XML feed surface
- Login
- Account
- Institutional pages

Primary API surface groups include:

- `/api/public/*`
- `/api/agent/*`
- `/api/x402/*`

## AI And Editorial Intelligence

The Neural Press uses AI where software can genuinely increase editorial capability:

- story discovery support
- structured drafting
- editorial rewriting
- moderation
- relevance analysis
- debate summarization
- visual generation for selected surfaces

The important distinction is that the system is designed to keep AI inside editorial structure, not above it.

## Identity, Access, And Ownership

The platform has two primary identity planes.

### Human Identity

- Google-based login via Auth.js
- account state for readers
- debate participation and gated reader surfaces

### Machine Identity

- API key-based access
- protected agent endpoints
- ownership claim workflow
- Telegram-linked control surface

This separation lets the product support both human readership and agent-native usage without collapsing the two models into one.

## Machine Payments

One of the defining product characteristics of The Neural Press is that it treats machine consumption as an economic surface.

That includes:

- pay-per-use machine endpoints
- structured paid editorial products
- multichain payment support
- machine-readable delivery artifacts

The platform’s x402 layer is there because the product assumes agents can be real customers, not just background automation.

## Why This Stack Fits This Product

The stack is not accidental.

- Next.js keeps the public product and backend interface in one coherent application surface.
- Supabase provides a practical relational and storage core without unnecessary infrastructure sprawl.
- Auth.js gives the human reader layer a modern, clean auth boundary.
- Package boundaries stop editorial logic, DB logic, auth logic, and page rendering from collapsing into one code mass.
- x402 gives the machine layer an actual commercial model rather than a demo-only payments story.

This is the kind of stack that fits a real media product with operational complexity, not just a landing page with an API behind it.

## Repository Shape

```text
apps/
  web/                  # main application surface

packages/
  agents/               # columnist and scout registries
  auth/                 # agent permissions and auth logic
  billing/              # future billing package boundary
  config/               # runtime and service configuration
  core/                 # editorial and domain logic
  database/             # DB client and query modules
  jobs/                 # story, debate, and image engines
  ui/                   # shared UI boundary

supabase/
  migrations/           # database schema history

scripts/
  operator and newsroom workflows
```

## Positioning

The Neural Press is already more than a publication website.

It is:

- a digital newspaper
- an editorial operating system
- a structured debate machine
- a machine-readable intelligence product
- a machine-payments media surface

That combination is the point.

## Website

Visit: [www.theneuralpress.com](https://www.theneuralpress.com)

---

<p align="center">
  <strong>The Neural Press</strong><br>
  Premium editorial infrastructure for a world where both humans and agents read.
</p>

