# Denis Fejza

Backend engineer in Belgrade. Node.js, TypeScript, Rust, Python, PostgreSQL.

3+ years of production work for EU and US clients: APIs and services, PostgreSQL data models, authentication and access control, Stripe billing, real-time data pipelines.

- **Now:** Open to full-time backend and full-stack roles, remote or Belgrade
- **Before:** Full-Stack Engineer at Macks Studios (took a paid membership platform to production, billing, Meta Ads and GA4 tracking); Full-Stack Engineer on [gradi.rs](https://gradi.rs), a Serbian construction marketplace; Rust backend engineer at FUKU AI, an AI trading platform where an LLM agent executes DeFi trades; Upwork freelancer with Top Rated Plus and 100% Job Success
- **Education:** M.Sc. in Software Engineering (in progress) and B.Sc. in Electrical Engineering and Computing (2026), University of Belgrade, School of Electrical Engineering

**[fejzadenis.github.io](https://fejzadenis.github.io)** · [LinkedIn](https://www.linkedin.com/in/denis-fejza/) · fejza.denis@gmail.com · looking for a full-time backend or full-stack role, remote or Belgrade

## Production work (private code)

| Project | What I built | Stack |
| --- | --- | --- |
| **FUKU** | Rust monorepo with about 22 services in production. Sole author of the real-time signal service (Redis stream of Hyperliquid perps activity, risk classification, Telegram fan-out, indicator packs) and of the Agent Commerce Protocol adapter that lets other AI agents buy trade execution. Worked on the agent tool layer exposing 113 trading functions to the LLM. | Rust, PostgreSQL, Redis, Solana, Hyperliquid |
| **[DoorCall AI](https://doorcall-ai.vercel.app)** | Multi-tenant voice-AI receptionist SaaS for US garage-door companies, built solo. Tenant isolation with PostgreSQL row level security, calendar booking, idempotent Stripe webhooks. Live demo, no accounts needed. | Next.js, TypeScript, PostgreSQL, Supabase, Stripe |
| **Client platforms** | Took a SvelteKit membership platform on Cloudflare to production for about 640 paying members: durable WooCommerce webhooks, access control, tracking with GTM, Meta Pixel and Ads, GA4 and HYROS, and an analytics dashboard. Query and caching work that cut page loads by about 40% on gradi.rs. | SvelteKit, Cloudflare Workers, D1, WooCommerce, Meta Ads, GA4, PHP |

## Public code

| Project | What it is | Stack |
| --- | --- | --- |
| **[Text-to-SQL thesis](https://github.com/fejzadenis/natural-language-to-sql-query-generation-using-large-language-models)** | Natural language to SQL with LLMs, with result explanation and confidence-based abstention: the system declines instead of returning a wrong query. | Python, LLMs, SQL |
| **[riscv-bare-metal-kernel](https://github.com/fejzadenis/riscv-bare-metal-kernel)** | Multithreaded OS kernel from scratch for RISC-V: threads, semaphores, a memory allocator and the user/supervisor boundary. No standard library. | C++, RISC-V assembly |
| **[mikrojava-compiler](https://github.com/fejzadenis/mikrojava-compiler)** | Full compiler for a Java-like language: lexer, LALR(1) parser, semantic analysis and bytecode generation. | Java, JFlex, CUP |
| **[inrooms](https://github.com/fejzadenis/inrooms)** | Networking platform for tech sales professionals: events, messaging, Stripe subscriptions, LinkedIn OAuth. | React, TypeScript, Supabase, Stripe |
| **[vlsi](https://github.com/fejzadenis/vlsi)** | PicoComputer CPU in SystemVerilog: RTL design, UVM verification, FPGA-ready synthesis. | SystemVerilog, UVM |

## Tech

**Backend:** Node.js, TypeScript, Rust, Python, PostgreSQL, Redis, REST APIs

**AI:** LLM agents and tool calling, voice AI, Text-to-SQL

**Web3:** Solana, Jupiter, Raydium, Meteora, Hyperliquid

**Frontend:** Next.js, React, SvelteKit, Tailwind

**Infra and tools:** Docker, Linux, Git, CI/CD, Cloudflare Workers, Vercel, HashiCorp Vault

**Analytics and marketing:** Meta Pixel and Ads API, GA4, Google Tag Manager, HYROS, ActiveCampaign

**Systems:** C, C++, RISC-V, compilers, SystemVerilog
