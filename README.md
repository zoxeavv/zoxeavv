<div align="center">

# Gauthier Girault

### Real-time AI that coaches sales reps mid-call — live on their screen, invisible to the prospect.

Solo engineer, end-to-end. Building **[Shot](https://github.com/zoxeavv/shot)** with my co-founder Clément (sales).
Paris, relocating to San Francisco.

<br/>

![Founder](https://img.shields.io/badge/Founder-Solo_Engineer-111111?style=for-the-badge)
![Focus](https://img.shields.io/badge/Currently-Shot-6E56CF?style=for-the-badge)
![Location](https://img.shields.io/badge/Paris-San_Francisco-111111?style=for-the-badge)

[![X](https://img.shields.io/badge/@gauthiergirlt-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/gauthiergirlt)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:thier0811@gmail.com)

</div>

---

### 🎯 What I'm building — Shot

A coaching layer that lives on top of every B2B sales call. The rep sees the next best move in real time; the prospect never knows it's there.

- **Invisible overlay** — Electron `BrowserWindow.setContentProtection(true)` over macOS `NSWindowSharingNone` + Windows `WDA_EXCLUDEFROMCAPTURE`. Coaching shows on the rep's screen and is stripped from screen share.
- **Real-time audio pipeline** — Recall.ai → Gladia ASR → Anthropic Haiku 4.5 streaming, targeting **sub-2s p95** from word spoken to coaching shown.
- **Unified memory** — CRM, Gmail, Slack, Notion, calendar and call transcripts ingested into one semantic layer with identity resolution.
- **Closed feedback loop** — every Monday the VP Sales corrects 3–5 key call moments; corrections become structured rules with a strict lifecycle and auto-apply to every rep's next call. Adapted from [Karpathy's `autoresearch`](https://github.com/karpathy/autoresearch).

### 📈 Proof of execution

| | |
|---|---|
| **< 2s p95** | latency from word spoken to coaching surfaced, on live calls |
| **150K–190K** | verified B2B emails per month, running on **~€48/mo** of infra |
| **83K LOC** | shipped solo on a full competitive-intelligence SaaS before the pivot |

I ship fast across adjacent problems — sales infra, enrichment, video, internal tooling — to converge on the one I want to live in for the next 10 years. **Shot is it.** Everything else is archived or on maintenance.

### 🚀 Shipped

| Project | What it is | Status |
|---|---|---|
| **[Shot](https://github.com/zoxeavv/shot)** | Real-time AI coaching for B2B sales teams | 🟣 Current focus · source private |
| **[Closer Claw](https://github.com/zoxeavv/Closer-Claw)** | Competitive-intelligence SaaS — adaptive selectors that survive DOM changes (Scrapling + 11 BullMQ workers + Claude), 83K LOC | Archived after pivoting to Shot |
| **[email-pipeline](https://github.com/zoxeavv/email-pipeline)** | Autonomous 24/7 B2B email enrichment engine at scale | 🟢 Live |
| **[Scalezia](https://github.com/zoxeavv/scalezia-app)** | Slack-native bot unifying a company's tools into one queryable memory | Template |
| **[Kiwi](https://github.com/zoxeavv/kiwi)** | Video-prospecting SaaS prototype | Paused |

### 🛠 Stack I live in

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Postgres](https://img.shields.io/badge/Postgres_+_pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Vercel AI SDK](https://img.shields.io/badge/Vercel_AI_SDK-000000?style=flat-square&logo=vercel&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![Composio](https://img.shields.io/badge/Composio-6366F1?style=flat-square)
![Recall.ai](https://img.shields.io/badge/Recall.ai-111111?style=flat-square)
![Gladia](https://img.shields.io/badge/Gladia-111111?style=flat-square)

<div align="center">
<br/>

**Building in public-ish.** Reach out if you're working on real-time AI, sales tooling, or you run an incubator — I'm relocating to SF and always up for a conversation.

</div>
