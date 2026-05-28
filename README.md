### Hi, I'm Gauthier.

I'm building **Shot** (codename: Horscope) — real-time AI coaching for B2B sales teams. Solo eng end-to-end. My co-founder Clément runs sales.

**What I work on right now**

- A desktop overlay invisible to screen share — Electron `BrowserWindow.setContentProtection(true)` wrapping macOS `NSWindowSharingNone` + Windows `WDA_EXCLUDEFROMCAPTURE`. Coaching surfaces on the rep's screen; the prospect never sees it.
- A real-time audio pipeline (Recall.ai → Gladia ASR → Anthropic Haiku 4.5 streaming) targeting sub-2s p95 from word spoken to coaching shown.
- Multi-source memory ingesting CRM, Gmail, Slack, Notion, calendar, and call transcripts into a unified semantic layer with identity resolution.
- Closed-loop coaching adapted from [Karpathy's `autoresearch`](https://github.com/karpathy/autoresearch): every Monday the VP Sales corrects 3–5 key call moments, corrections become structured rules with a strict lifecycle, rules auto-apply to every rep's next call.

**Previously shipped**

I've deliberately shipped fast across adjacent problems (sales infra, enrichment, video, IC) to converge on the one I want to live in for 5+ years. Shot is it. Everything else is archived or maintenance.

- [**Shot**](https://github.com/zoxeavv/shot) — current focus. Source private.
- [**Closer Claw**](https://github.com/zoxeavv/Closer-Claw) — competitive-intelligence SaaS, 83 K LOC. Adaptive selectors that survive DOM changes (Scrapling + 11 BullMQ workers + Claude). Archived after pivoting to Shot.
- [**email-pipeline**](https://github.com/zoxeavv/email-pipeline) — autonomous 24/7 B2B email enrichment, 150 K–190 K verified emails/month on ~€48/mo infra.
- [**Scalezia**](https://github.com/zoxeavv/scalezia-app) — Slack-native bot template that unifies a company's tools into one queryable memory.
- [**Kiwi**](https://github.com/zoxeavv/kiwi) — video-prospecting SaaS prototype, paused.

**Stack I live in**

Next.js · TypeScript · Postgres + pgvector · Vercel AI SDK · Anthropic · Composio · Supabase · Electron (desktop overlays) · Recall.ai · Gladia

**Where I am**

Paris, relocating to San Francisco mid-2026.

**Reach me**

[Twitter / X](https://x.com/gauthiergirlt) · [Email](mailto:thier0811@gmail.com)
