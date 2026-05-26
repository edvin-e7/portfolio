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

### 📄 CV-Tailor — job-ad ranker + tailored application generator
Ranks live job ads against a candidate profile and generates a tailored CV + cover letter
per role, for the Swedish job market.

- **Multi-tier scoring** — keyword overlap + semantic embeddings (EmbeddingGemma, 768-dim)
  against the candidate profile, with geo bonus and hard exclusion rules
- **Multi-LLM backend** — Anthropic / Ollama / Gemini, each opt-in, local-first by default
- **Outcome tracking** — every application's result feeds back as empirical data for future
  ranking weights (no fine-tuning required)
- **Stack:** TypeScript · Express · React/Vite · Anthropic SDK · Ollama

> Both codebases are private (they contain client/personal data), but I'm happy to walk
> through either live on a call and show how the architecture actually works.

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
- **Reddit:** _<!-- fyll i ditt handle, t.ex. /u/vibecoder_se -->_
- **Discord:** _<!-- fyll i ditt handle -->_

DM with the problem and I'll get back to you fast.
