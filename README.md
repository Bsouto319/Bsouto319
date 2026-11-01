### Hi, I'm Bruno 👋

**AI Automation Engineer** in Brasília, Brazil. Fluent in English, working on US hours.

I build AI automations that run unattended for small businesses in the US and Brazil, and I keep them running in production: discovery with the owner, build, deploy, support. Claude Code (with MCP tools) is my daily development environment.

🎥 **2-minute portfolio video:** [watch on YouTube](https://youtu.be/bme30SUeiic)

---

#### What I've shipped

| System | What it does | Stack |
|---|---|---|
| **LeadPilot** | Answers every new lead for US home-service contractors within minutes: texts and calls, detects voicemail, qualifies the job, books the visit, alerts the owner only when needed. Live in FL, SC, NJ, MD. | Node.js, Docker, Twilio, ElevenLabs, OpenAI, Postgres |
| **ServiceFlow** · [live demo](https://serviceflow-pi-three.vercel.app/demo.html) | A contractor talks through a job site visit; it becomes an itemized estimate in the client's language. Per-customer AI cost metering, HMAC-signed webhooks to Zapier/QuickBooks. | React, Supabase (Postgres, Edge Functions), Whisper, GPT-4o with strict JSON schemas |
| **BoxCerto** | Voice-to-work-order for auto repair shops, sold and onboarded through a self-serve funnel (video → checkout → automatic provisioning). | React, Supabase, PWA, QR |
| **ClinicaFlow** | CRM + WhatsApp AI assistant for clinics, with automatic patient dose reminders. | React, Supabase, WhatsApp API, OpenAI |
| [**service-desk-rag**](https://github.com/Bsouto319/service-desk-rag) | Grounded Q&A over a business handbook: hybrid retrieval (pgvector + BM25), cited answers, refusal on unknowns, and an eval harness (hit@k, MRR, LLM judge, cost, latency). | Python, FastAPI, OpenAI, pgvector |

Most client systems are private; happy to walk through any of them on a call.

#### How I work

- **Production first**: logging, alerts and safe defaults before features. Every incident becomes a checklist so it doesn't repeat.
- **Cost-aware AI**: tokens and dollars tracked per call and per customer; models chosen by measured accuracy and price.
- **Agentic development**: I lead AI coding agents and review their work hard, especially around auth, data and payments.

📫 [linkedin.com/in/brunosouto007](https://www.linkedin.com/in/brunosouto007)
