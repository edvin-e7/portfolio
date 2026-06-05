# Edvin Pierre — AI agent builder & vibecoder

I ship AI-first software end to end. Heavy [Claude Code](https://claude.com/claude-code)
user, comfortable across the LLM stack — Anthropic, OpenAI, Gemini, and local Ollama —
and across the full app: Python/FastAPI backends, TypeScript/React frontends, ML
detection pipelines, and the prompt/agent layer that ties them together.

Self-taught, output-first. The proof is two production systems I built solo this year.

---

## Production work (2026)

### ☀️ Solar Unified — multi-agent prospecting platform
An end-to-end prospecting tool for the Swedish solar industry: find rooftops with solar
potential, qualify them, score them, and hand a sales team a ranked lead list.

- **Multi-agent coordinator** — search → qualify → score → journal, each a distinct agent
- **Custom ML detection** for roof and panel imagery (ONNX runtime, local inference)
- **CoVe-style verification**, prompt versioning, and structured journaling for reliability
- **Cost-safe by design** — every paid API (satellite, external LLM) is triple-gated behind
  explicit env flags so a run can never silently bill
- **Stack:** Python · FastAPI · React/Electron · Gemini · ONNX · SQLite

### 🛍️ e7-stylez — fashion aggregator (Next.js 16)
A shopping aggregator that pulls real product feeds from 60+ stores into one searchable
catalogue, with brand pages and cross-store price comparison.

- **Live feed ingestion** — 60+ sources, real Shopify product feeds (live prices, images,
  stock), validated + cached so a drifted feed degrades gracefully instead of crashing
- **Brand aggregation** — one brand across every store, cheapest first; canonicalises messy
  feed data (Nike/NIKE/"NIKE Retail B.V." → one brand) with ground-truth tests
- **Product-grade UX** — ⌘K command palette, personalised "For You" rerank, cross-store
  price compare, mobile-first, SSG + JSON-LD for SEO
- **Stack:** Next.js 16 · TypeScript · React · Vercel (serverless) · Vitest

> Codebases are private, but I'm happy to walk through either live on a call and show how
> the architecture actually works.

---

## Open for hire

I take on focused, fast-turnaround AI work — fixed-price so you know the cost up front:

| Service | Price | Turnaround |
|---|---|---|
| Custom Claude/GPT chatbot | $150 | 24h |
| Prompt audit + optimization | $80 | 12h |
| Fix a broken AI script (Python/JS/TS) | $60 | same-day |
| Build a Claude Code workflow for a repetitive task | $200 | 48h |

Hourly available too: **$40/h** prompt-only work · **$80/h** build work.

- **Stack:** Claude (heavy), GPT-4/5, Ollama (local), Python, TypeScript, React, FastAPI, Express
- **Languages:** English + Swedish (native)
- **Payment:** Wise · PayPal · crypto
- **Timezone:** CET, flexible

I quote within 2 hours of getting the problem, and I refund if you're not satisfied.

---

## Contact

- **GitHub:** [github.com/edvin-e7](https://github.com/edvin-e7)
- **Email:** edvin.pierre03@gmail.com

DM with the problem and I'll get back to you fast.
