# Sviatoslav Oleksiv

**Lead AI product engineer.** Production AI SaaS, agents and media pipelines. React, Node, AWS. Krakow, Poland.

Three years as lead engineer of a live AI SaaS, one profitable product of my own, thirteen years in production software. I own the whole product: architecture, AI pipelines, billing, infrastructure and the consequences in production.

Most of my code lives in client and product repositories, so this profile is quiet. The work is described below and in more detail at [oleksiv.com](https://oleksiv.com).

## Work

**[LIVEDAB](https://app.livedab.com)**, lead engineer, December 2023 to present. Multi-tenant SaaS that turns event photos into branded AI images and videos, with a CRM underneath. Used by event organizers and brands in Germany. 5,300 commits on the main repo, about seven times the next contributor. Per-layer AI chains over Replicate, Gemini and OpenAI, server-side video rendering with Remotion on AWS Lambda, durable reload-safe workflows, six-level permissions, a Playwright end-to-end suite.

**[mosfoto.com](https://mosfoto.com)**, founder, solo, May 2026 to present. Paid tool that turns any photo into the exact residence-card photo Poland's MOS portal accepts. 211 paying customers in October 2026. Next.js, Stripe, Replicate (BiRefNet, BiSeNet), Vercel Blob, PostgreSQL.

**Personalized sales videos**, own tooling, 2026. One command renders a demo video for a single prospect: Playwright records their website, Claude writes a call script constrained by the production voice agent's own system prompt, ElevenLabs voices both sides, Remotion renders the MP4.

## Numbers

| | |
|---|---|
| Job success on Upwork | 100% across 18 contracts, Top Rated Plus |
| Hours billed on Upwork | 3,658. Average engagement 180 hours, longest 1,300 and still running |
| Years in production software | 13, since 2013 |
| Stack Overflow | Answers reached 856,000 people |
| The Pets and Love | A blog I built and run, 100,000 monthly visitors |

## How I work with AI coding agents

Test-first, with a closed loop. Business requirements become tests, the agent writes code against the tests, the tests run, and the loop repeats until green. The tests define correctness, not the agent. The agent gets rules and structure in the codebase before it writes a line, and the rules that matter are the ones that fail the build rather than wait for a reviewer.

Three notes on the method: [a durable workflow for a multi-step AI chain](https://oleksiv.com/notes/durable-ai-workflows), [every AI step falls back to its input](https://oleksiv.com/notes/fallback-to-input), [rules for coding agents in a production codebase](https://oleksiv.com/notes/rules-for-coding-agents).

## Stack

TypeScript, React, Next.js, Node.js, NestJS, PostgreSQL, MongoDB, Supabase, AWS (Lambda, S3, SQS), Vercel, Azure, Stripe, Auth0, PostHog, Playwright, Remotion, Replicate, OpenAI, Anthropic, Gemini, ElevenLabs.

## Contact

sviatoslav.oleksiv@gmail.com · [Book a 30-minute call](https://calendar.app.google/t2THq2pPfe2txZds8) · [LinkedIn](https://www.linkedin.com/in/oleksiv) · [Upwork](https://www.upwork.com/freelancers/oleksiv) · [Stack Overflow](https://stackoverflow.com/users/4360292/sviatoslav-oleksiv) · [CV](https://oleksiv.com/cv.pdf)
