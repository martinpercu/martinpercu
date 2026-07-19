# Hey, I'm Martin 👋

**AI Solution Architect & Full-Stack Engineer** based in **NYC**.  
I specialize in building autonomous AI agents and scalable web architectures. With a background as a **2x Founder**, I bridge the gap between complex engineering and business impact.

---

### 🚀 Featured Projects

🎙️ **[ARS — Adaptive Restaurant Speech](https://github.com/martinpercu/adaptive-restaurant-asr)** **An ASR engineering deep-dive** *(exploration, not a product)*
* A hands-on study of a problem I find fascinating: **bilingual (es + en) speech recognition in drive-thru noise** — built as a small self-improving pipeline (noise lab → **LoRA fine-tuning** → rule-based correction) to *measure* what actually helps, not assume it.
* Everything is gated and numbered: a **Noise Damage Index** ranks noise types by measured WER/KER damage, denoisers that sound cleaner but transcribe worse get auto-rejected, and every shortcut is documented in an [honest build report](https://github.com/martinpercu/adaptive-restaurant-asr/blob/main/BUILD-REPORT.md) — bugs included.
* Comes with [design reflections](https://github.com/martinpercu/adaptive-restaurant-asr/blob/main/docs/BEYOND-THE-BUILD.md) on where systems like this should go: the acoustic front-end, the ASR→NLU handoff, and measuring user friction beyond WER.

🤖 **[Odoo AI Agent](https://github.com/martinpercu/odoo-agent-front)** **Production-Grade Voice-Enabled ERP Assistant** [→ live demo](https://theodooagent.com)
* Developed a **21-node LangGraph pipeline** enabling complex natural language interaction with Odoo ERP modules (Sales, Inventory, Finance, CRM).
* **Voice interface**: **Speech-to-Text (Groq Whisper)** + **Text-to-Speech (Kokoro ONNX)** with synchronized streaming — talk to your ERP.
* **Safe CRUD Operations**: strict confirmation gates and interactive ambiguity resolution cards to ensure zero accidental data modifications.
* **Data-Driven UX**: **SSE streaming** for real-time responses, integrated live analytics, and automated Excel/PDF reporting engine.
* **Architecture**: Next.js 16 (React 19) + FastAPI + LangGraph + Odoo XML-RPC.

🎯 **[TalentGraph](https://github.com/martinpercu/Talent-Graph)** **AI-Powered Voice Recruitment Platform** [→ live demo](https://talent-graph.web.app)
* Developed a **34-node LangGraph agent** with a multi-level detection system for ultra-low latency (<10ms for Fast Paths).
* **Multi-modal I/O**: Integrated **Speech-to-Text (Groq Whisper)** and **Text-to-Speech (Kokoro ONNX)** with synchronized streaming.
* **Autonomous Workflows**: Implemented **MCP integration** for automated Google Calendar scheduling and Gmail management.
* **Performance**: Features **Silent Loading** and heuristic routing, achieving a 70% reduction in context-related latency.
* **Architecture:** Angular 19 (Signals) + FastAPI + LangGraph + PostgreSQL (Checkpoints).

📚 **[AI-Trainer-Teacher](https://github.com/martinpercu/AI-Trainer-Teacher)** **Intelligent RAG-powered Educational Platform** [→ live demo](https://trainer-teacher.web.app)
* Engineered a **hierarchical RAG pipeline** with dynamic page filtering, reducing irrelevant context by **70%**.
* Implemented **history-aware question reformulation** and Redis-backed session persistence for multi-turn learning.
* **Impact:** Faster retrieval and higher precision by narrowing vector search scope to specific document sections.

*Also on the shelf:* [LangGraph agent templates](https://github.com/martinpercu/Langchain-Langgraph_Agents-Structure) (6 production-ready agentic patterns) · [OAuth 2.0 & JWT deep-dives](https://github.com/martinpercu/JWT-OAuth-flows) (PKCE, Auth Code, real-world API integrations).

---

### 🛠 Tech Stack

**Speech & ML:** faster-whisper (CTranslate2) • PEFT/LoRA fine-tuning • Silero VAD • STT/TTS streaming (Groq Whisper, Kokoro) • WER/KER evaluation pipelines  
**AI Engineering:** LangGraph • LangChain • RAG Orchestration • Model Routing • Vector DBs (Pinecone/Chroma)  
**Frontend:** Angular 19 (Signals/Standalone) • React (Vite/Context) • Vue.js • Tailwind CSS  
**Backend:** Node.js • TypeScript • Python (FastAPI/Flask) • RESTful APIs  
**Data & Cloud:** PostgreSQL • Redis • MongoDB • Firebase • Docker • CI/CD (GitHub Actions)  
**Business Tech:** Stripe API (Complex Subscriptions) • OAuth 2.0 • Product Analytics

---

### ⚡ Quick Facts

- 📍 **Based in NYC** (Green Card holder, no sponsorship required).
- 🏢 **Former CEO & Founder:** Ex-Drinkko & 4TIMP. I build with "Product Ownership" in mind.
- 🎓 **Continuous Learner:** Music conservatory background 🎸 → 40+ Technical Certifications.
- 🌍 **Trilingual:** English, French, Spanish (Fluent) — and I ship bilingual speech systems.
- 🛠 **Workflow:** Cursor & Claude Code power user (Agentic Dev workflow).

---

### 🤝 Let's Connect

📧 [info@mart-in.us](mailto:info@mart-in.us)  
🔗 [LinkedIn](https://www.linkedin.com/in/martin-e-mendez-3a43b564) • [Portfolio](https://mart-in.us) • [Certifications](https://mart-in.us/cert/ai)

---
*"The quick shall inherit the earth. I ship clean, performant code every week — measured, not assumed."*
