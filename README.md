# Hi, I'm Navin

Backend engineer focused on Ruby on Rails — API design, background job
processing, third-party/webhook integrations, and multi-tenant SaaS
architecture. I build on PostgreSQL, Redis, Docker, and AWS, and have
recently been adding LLM/RAG features (Groq, Ollama, pgvector) directly
into Rails apps.

## Featured Projects

**[Curovia](https://github.com/Navin-Baliyase/care-hub) — multi-tenant clinic management SaaS**
Rails 8.1 · PostgreSQL/pgvector · Hotwire · WhatsApp (Meta Cloud API) · Kamal
Branded per-organisation portals, role-based staff access, billing, an
MCP/REST API for AI-agent integrations, and a two-language WhatsApp
booking flow.
🚀 Live: [curovia.life](https://curovia.life)

**[DB Chat](https://github.com/Navin-Baliyase/db-chat) — talk to any PostgreSQL database in plain English**
Rails 8.1 · pgvector · Groq · Ollama (RAG)
Retrieves the relevant tables via vector search, generates a read-only
SQL query from a natural-language question, runs it, and explains the
result.
📖 Technical case study

**[RailShunt](https://github.com/Navin-Baliyase/railshunt) — embeddings-based job-matching platform**
Rails 7.2 · pgvector · OpenAI · Sidekiq-Cron · ActionCable
Scores scraped job postings against a resume across five weighted
dimensions and tracks applications through a state machine.
📖 Technical case study

**[Creator Hub](https://github.com/Navin-Baliyase/creator-hub) — social-media management API**
Rails 7.1 · PostgreSQL · Redis · Sidekiq · Devise+JWT
Adapter-pattern API for connecting and publishing to multiple social
platforms from one unified feed.
📖 Technical case study

**[Interactive Virtual Background](https://github.com/Navin-Baliyase/interactive-virtual-background) — cross-platform virtual camera**
TypeScript · Electron · Three.js · MediaPipe
Full system-design writeup (process topology, frame budgets, per-OS
virtual-camera tradeoffs, security review) plus an in-progress capture/
segmentation/compositing implementation.
📖 Early-stage POC + design doc

**[FII Accumulation Tracker](https://github.com/Navin-Baliyase/fii-tracker) — scored investment-signal pipeline**
Rails 7.2 · Sidekiq · Redis · Pundit
Scheduled pipeline scrapes shareholding and financial data for Indian
equities and computes a composite accumulation score per stock.
📖 Technical case study

## Technical Skills

**Backend** Ruby · Ruby on Rails · Python
**Databases** PostgreSQL · pgvector · Redis
**Background processing** Sidekiq · Solid Queue · Sidekiq-Cron
**Frontend** Hotwire (Turbo + Stimulus) · Tailwind CSS
**Cloud / infra** AWS · Docker · Kamal · Cloudflare
**Integrations** REST APIs · webhooks · WhatsApp Cloud API · OAuth
**AI / LLM** Groq · Ollama · OpenAI embeddings · RAG (pgvector)

## Engineering Areas

- Multi-tenant SaaS architecture — org/branch scoping, plan gating, RBAC
- API design — JSON-RPC + REST/OpenAPI, adapter patterns
- Background job design — scheduled pipelines, per-item failure isolation
- Query performance — N+1 elimination, HTTP caching, targeted indexing
- Third-party integrations — WhatsApp, payments, LLM providers
- RAG / vector search — pgvector, embedding pipelines

## Contact

- Email — navinkumar2508@gmail.com
- LinkedIn — [linkedin.com/in/dynamicnavin](https://linkedin.com/in/dynamicnavin)
- Site — [rubyonrails.tech](https://rubyonrails.tech)
- Case studies — [actnavin.github.io](https://actnavin.github.io)
