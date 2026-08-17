# Hi, I'm Navin

Backend engineer focused on Ruby on Rails — API design, background job processing, third-party/webhook integrations, and multi-tenant SaaS architecture. I build on PostgreSQL, Redis, Docker, and AWS, and have recently been adding LLM/RAG features (Groq, Ollama, pgvector) directly into Rails apps.

Below are six of my side projects — real screenshots and a real recorded conversation, not mockups.

---

### 🏥 [Curovia](https://curovia.life) — multi-tenant clinic management SaaS
<img src="https://raw.githubusercontent.com/Navin-Baliyase/Navin-Baliyase/main/assets/curovia/dashboard.png" width="800" alt="Curovia org admin dashboard">

Branded per-organisation portals, role-based staff access, billing, an MCP/REST API for AI-agent integrations, and a WhatsApp booking flow in English and Hindi.

`Rails 8.1` `PostgreSQL` `pgvector` `Hotwire` `WhatsApp Cloud API` `Kamal`

🚀 **Live at [curovia.life](https://curovia.life)**

---

### 💬 DB Chat — talk to any PostgreSQL database in plain English
<img src="https://raw.githubusercontent.com/Navin-Baliyase/Navin-Baliyase/main/assets/db-chat/demo.gif" width="800" alt="DB Chat conversation demo">

Retrieves the relevant tables via vector search (RAG), generates a read-only SQL query from a natural-language question, runs it, and explains the result. The GIF above is a real recorded conversation — note the read-only safety layer correctly deflecting a "delete posts table" request.

`Rails 8.1` `pgvector` `Groq` `Ollama`

📖 Technical case study — not deployed (no reason to run this publicly, but nothing stops it either)

---

### 🎯 RailShunt — embeddings-based job-matching platform
<img src="https://raw.githubusercontent.com/Navin-Baliyase/Navin-Baliyase/main/assets/railshunt/dashboard.png" width="800" alt="RailShunt dashboard with real scraped job matches">

Scores real scraped job postings against a resume across five weighted dimensions (semantic similarity, skills, experience, salary, location) and tracks applications through a full pipeline.

<img src="https://raw.githubusercontent.com/Navin-Baliyase/Navin-Baliyase/main/assets/railshunt/applications.png" width="800" alt="RailShunt applications Kanban pipeline">

`Rails 7.2` `pgvector` `OpenAI` `Sidekiq-Cron` `ActionCable`

📖 Technical case study — the scraper runs against real job boards on a schedule, not something to leave running on a public demo

---

### 📈 FII Accumulation Tracker — scored investment-signal pipeline
<img src="https://raw.githubusercontent.com/Navin-Baliyase/Navin-Baliyase/main/assets/fii-tracker/dashboard.png" width="800" alt="FII Accumulation Tracker dashboard">

A scheduled scrape → score → rank pipeline tracking institutional-investor accumulation in Indian equities, with a composite scoring algorithm over shareholding trends and fundamentals.

`Rails 7.2` `Sidekiq` `Redis` `Pundit`

📖 Technical case study

---

### 🔌 Creator Hub — adapter-pattern social media API
Real response from the running app — one interface hiding four different platform APIs:

```json
{
  "platforms": [
    { "name": "youtube",   "connected": true, "profile": { "followers": 1204 } },
    { "name": "instagram", "connected": true },
    { "name": "twitter",   "connected": true },
    { "name": "linkedin",  "connected": false }
  ]
}
```

An API-only Rails service for connecting and publishing to multiple social platforms from one unified feed — no UI, so no screenshot, just the real API doing its job.

`Rails 7.1` `PostgreSQL` `Redis` `Sidekiq` `Devise+JWT`

📖 Technical case study

---

### 🎥 Interactive Virtual Background — cross-platform virtual camera
<img src="https://raw.githubusercontent.com/Navin-Baliyase/Navin-Baliyase/main/assets/background/architecture.png" width="800" alt="Frame pipeline architecture">

A from-scratch system design and early POC for a desktop app that segments and composites a webcam feed in real time, then exposes it to Meet/Zoom/Teams as a virtual camera. Capture, MediaPipe segmentation, and a Linux virtual-camera bridge are working; Windows/macOS bridges are their own native workstreams, not yet built.

`Electron` `TypeScript` `Three.js` `MediaPipe`

📖 Early-stage POC + design doc

---

## 🛠️ Technical Skills

**Backend** Ruby · Ruby on Rails · Python
**Databases** PostgreSQL · pgvector · Redis
**Background processing** Sidekiq · Solid Queue · Sidekiq-Cron
**Frontend** Hotwire (Turbo + Stimulus) · Tailwind CSS
**Cloud / infra** AWS · Docker · Kamal · Cloudflare
**Integrations** REST APIs · webhooks · WhatsApp Cloud API · OAuth
**AI / LLM** Groq · Ollama · OpenAI embeddings · RAG (pgvector)

## 🏗️ Engineering Areas

- Multi-tenant SaaS architecture — org/branch scoping, plan gating, RBAC
- API design — JSON-RPC + REST/OpenAPI, adapter patterns
- Background job design — scheduled pipelines, per-item failure isolation
- Query performance — N+1 elimination, HTTP caching, targeted indexing
- Third-party integrations — WhatsApp, payments, LLM providers
- RAG / vector search — pgvector, embedding pipelines

## 📫 Contact

- Email — navinkumar2508@gmail.com
- LinkedIn — [linkedin.com/in/dynamicnavin](https://linkedin.com/in/dynamicnavin)
- Site — [rubyonrails.tech](https://rubyonrails.tech)
- Case studies — [actnavin.github.io](https://actnavin.github.io)
