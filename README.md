# Portfolio — Dmytro Dumka

All 15 builds, with architecture, decisions and results. Three origins, labelled honestly:

- **Client** — paid work (Upwork or direct), running in production
- **Own product** — built, piloted, kept as an asset
- **Training build** — full working implementations from the AI-automation program I completed (Nov 2025 – Apr 2026). Not client orders — but not toy demos either; each one runs end to end

| # | Build | Origin | Stack | Detail |
|---|---|---|---|---|
| 1 | AI Omnichannel Content Factory | Training build | Make · n8n · OpenAI · Replicate · Airtable | [01-omnichannel-content-factory.md](./01-omnichannel-content-factory.md) · → [content-repurposing-pipeline](https://github.com/TrueSkillMaster/content-repurposing-pipeline) |
| 2 | AI EdTech Ecosystem | Training build | ManyChat · Airtable · OpenAI · Telegram · Make | [02-edtech-ecosystem.md](./02-edtech-ecosystem.md) |
| 3 | Real Estate AI Lead Nurturing | Training build | Airtable · OpenAI · Make · Gmail | [03-real-estate-lead-nurturing.md](./03-real-estate-lead-nurturing.md) · → [ai-lead-intake](https://github.com/TrueSkillMaster/ai-lead-intake) |
| 4 | Multi-modal AI Finance Manager | Training build | Make/n8n · OpenAI Vision + Whisper · Google Sheets | [04-multimodal-finance-manager.md](./04-multimodal-finance-manager.md) |
| 5 | Form → Make → AI → Email/PDF | **Client** (UK) | Make · Jotform · OpenAI · CloudConvert · Gmail · GHL | [05-form-ai-email-pdf.md](./05-form-ai-email-pdf.md) · → [ai-lead-intake](https://github.com/TrueSkillMaster/ai-lead-intake) |
| 6 | Self-hosted n8n Production Hub | Own infrastructure | Oracle Cloud · Docker · Nginx · Let's Encrypt | → [n8n-selfhosted-setup](https://github.com/TrueSkillMaster/n8n-selfhosted-setup) |
| 7 | GHL Email Auth & Calendar Sync Fix | **Client** (UK) | GoHighLevel · DNS · iCloud/Google · Mailgun | → [ghl-architecture-patterns](https://github.com/TrueSkillMaster/ghl-architecture-patterns) |
| 8 | AI Carousel Factory | Own product | n8n · Apify · Claude · OpenAI · Creatomate · R2 · Telegram | → [ai-carousel-factory](https://github.com/TrueSkillMaster/ai-carousel-factory) |
| 9 | Tender Monitor — Hybrid AI Filtering | **Client** (DE) | n8n · Prozorro API · gpt-4o-mini · Sheets · Telegram | → [n8n-tender-monitor](https://github.com/TrueSkillMaster/n8n-tender-monitor) |
| 10 | GHL Two-Pipeline Collision Fix | **Client** (UK) | GoHighLevel · tag-proxy · helper workflows · dedup | → [ghl-architecture-patterns](https://github.com/TrueSkillMaster/ghl-architecture-patterns) |
| 11 | Make Job Classifier | **Client** (US) | Make · GoHighLevel | [11-make-job-classifier.md](./11-make-job-classifier.md) |
| 12 | Multi-Tenant Booking & Direct-Debit Payments | **Client** (UK) | WordPress · custom JS journey · GoHighLevel · GoCardless · Make | → [multi-tenant-booking](https://github.com/TrueSkillMaster/multi-tenant-booking) |
| 13 | Tender Market Analysis — 5,535 tenders | **Client** (DE) | Python · pandas · Chart.js · pptxgenjs | → [tender-market-analysis](https://github.com/TrueSkillMaster/tender-market-analysis) |
| 14 | Coach Website — Game-Menu UI, 3 languages | **Client** (direct) | HTML/CSS/JS · Python build · Cloudflare · n8n | → [coach-website-game-ui](https://github.com/TrueSkillMaster/coach-website-game-ui) |
| 15 | Animated Multi-Step Application Form | **Client** (direct) | HTML/CSS/JS · n8n webhook · messaging bot | → [animated-multistep-form](https://github.com/TrueSkillMaster/animated-multistep-form) |

Reusable patterns extracted from these: [automation-patterns](https://github.com/TrueSkillMaster/automation-patterns).

## Client work in numbers (as of June 2026 — builds 12–15 came after)

- 3 paying clients, 8 closed engagements, all on Upwork
- UK fractional marketing director: 5 milestones, every one a repeat order; retainer under discussion
- German B2B equipment supplier: 2 milestones closed, third delivered
- US client: one-off Make ↔ GHL classifier, closed without issues
