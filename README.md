<h1 align="center">Hi, I'm Uzair Javaid</h1>

<p align="center">
  <b>Full-stack & AI engineer.</b> I ship LLM features the way production teams run them: evals that block bad changes, gateways that survive a dead provider, SLOs, traces and rollbacks.<br/>
  CS @ COMSATS '27 · Pakistan · <b>Open to remote roles</b>
</p>

<p align="center">
  <a href="https://uzairjiqbal.github.io"><img src="https://img.shields.io/badge/Portfolio-uzairjiqbal.github.io-0A0A0A?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio: uzairjiqbal.github.io"/></a>
  <a href="mailto:uzair.j1089@gmail.com"><img src="https://img.shields.io/badge/Email-uzair.j1089%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email: uzair.j1089@gmail.com"/></a>
</p>

### Start here

[**Dispatch**](https://github.com/UzairJIqbal/dispatch) · [live](https://dispatch-prod.ashybay-480692f5.malaysiawest.azurecontainerapps.io/readyz): an LLM ticket-triage service where the model call is one line and everything around it is the project.

- An eval gate in CI blocked a deliberately worse prompt (52.7% vs 70.3%, n=74).
- My own gateway handles retries, provider fallback and a circuit breaker.
- SLOs with burn-rate alerts, OpenTelemetry traces, canary releases with auto-rollback, k6 load tests, a runbook and a postmortem.
- 99.99% availability over 7 days (13,310 of 13,311 checks). The traffic is synthetic; the bill is $0 on free tiers.

| Project | What it is | Stack |
|---|---|---|
| [**VerifAI**](https://github.com/UzairJIqbal/verifai) | Evaluation system for a tool-using customer-support agent: runs it on fixed tasks, records every step, grades with code and counts hallucinations. | Next.js, Vercel AI SDK, Gemini, Groq, Langfuse, Vitest |
| [**FlowLens**](https://github.com/UzairJIqbal/flowlens) · [demo, no sign-in](https://flowlens-rouge.vercel.app/demo) | Dependency map of any public TypeScript/JavaScript repo, built by the TypeScript compiler. AI explanations use only what the parser found, plus a chat agent and an MCP server for coding agents. | Next.js, ts-morph, Supabase RLS, LangSmith |
| [**NeuraMeet**](https://github.com/UzairJIqbal/Neurameet) · [live](https://neurameet.vercel.app) | AI meeting platform: video calls with guest access, transcripts, summaries, action items and a chat grounded in each meeting's transcript. | Next.js, Stream, Supabase pgvector, Gemini, Groq |
| [**Kunji**](https://github.com/UzairJIqbal/kunji) · [live](https://kunji-two.vercel.app) | Digital subscription store in PKR: mobile-wallet checkout, seller-approved payments and an AES-256-GCM encrypted credential vault. | Next.js, Clerk, Supabase, Postgres RLS |
| [**JobPilot**](https://github.com/UzairJIqbal/Job_Pilot) · [live](https://jobpilot-psi-nine.vercel.app) | AI job-hunting assistant: finds roles, scores matches against your profile, researches companies with a headless browser and prepares interview material. | Next.js, Gemini, Stagehand, InsForge |
| [**YouTube Study Bookmarks**](https://github.com/UzairJIqbal/youtube_bm) · [Edge Add-ons](https://microsoftedge.microsoft.com/addons/detail/youtube-study-bookmarks/ciobpmgaabihaoabjjiifhigfbnggmob) | Browser extension, live on Microsoft Edge Add-ons, to bookmark lectures at exact timestamps, with notes, tags, clip loops and Markdown/Obsidian export. | React 19, TypeScript, Vite, MV3, Playwright |

More: [StoreIt](https://github.com/UzairJIqbal/Store_It_Solution) (cloud drive) · [SoonerSlot](https://github.com/UzairJIqbal/soonerslot) (Edge extension for earlier interview slots).

### What I work on

- **Running LLM features in production:** eval gates in CI, provider gateways, SLOs and burn-rate alerts, tracing, canary releases, postmortems
- **AI features with receipts:** tool-calling agents, RAG over pgvector, MCP servers, and checks that catch answers the data doesn't support
- **Full-stack products:** Next.js, TypeScript, Supabase/Postgres, auth, payments and row-level security

### Tech stack

**Web:** TypeScript · JavaScript · React · Next.js · Node.js · Express · Tailwind CSS<br/>
**Data:** Postgres · Supabase · Redis (Upstash) · SQLite<br/>
**AI:** Gemini · Cohere · Groq · OpenAI SDK · Vercel AI SDK · Langfuse · LangSmith · MCP · pgvector<br/>
**Operations:** OpenTelemetry · Prometheus · Grafana · k6 · Docker · Azure Container Apps · GitHub Actions · Vercel<br/>
**Testing:** Vitest · Playwright · Zod

<!-- Last reviewed 2026-11-20. Review again when: a new flagship ships, Dispatch's README numbers change, or a job search starts. -->
