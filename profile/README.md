# ChatCue AI

> Turning chaotic conversations into clear, actionable work.

Welcome to **ChatCue AI** — an experiment in building **AI‑powered tools** that
help developers and teams turn unstructured communication (WhatsApp, chat,
notifications) into structured, actionable tasks.

This organization currently hosts **personal and open‑source projects** by
[YungBenn](https://github.com/YungBenn) focused on:

- Backend & cloud engineering (Go, TypeScript, AWS/VPS, Docker)
- Practical AI/LLM integration using **OpenRouter**
- Developer productivity & workflow automation

---

## 🧠 Flagship Project

### ChatCue AI – WhatsApp‑to‑Tasks Copilot

**ChatCue AI** is a personal productivity tool that helps engineers stop losing
work inside WhatsApp chats.

**What it does:**

- Ingests WhatsApp messages via a gateway (personal or business number)
- Uses **LLMs via OpenRouter** to:
  - Detect **work‑related** vs personal messages
  - Decide if a message is **actionable** (should become a task)
  - Classify intent (bug, feature, question, info)
  - Guess the right **project** using names + keywords
  - Generate a clean **task title & description**
- Automatically creates structured tasks in a **Go + PostgreSQL** backend
- Provides a simple **web dashboard** to:
  - Review and triage new tasks (Inbox)
  - Assign tasks to projects
  - Track status (Inbox → Todo → Doing → Done)

**Tech highlights:**

- **Backend:** Go (monolith, clean modular structure)
- **Database:** PostgreSQL
- **AI/LLM:** OpenRouter (chat completions, JSON‑structured prompts)
- **Infra:** Docker, Docker Compose, VPS/Dokploy deployment
- **UI:** Minimal web dashboard for weekly task review

> Core idea: *“Don’t make me scroll WhatsApp to remember my work.
> Just give me a task list.”*

---

## 🔧 Focus Areas

Across all projects in this organization, the recurring themes are:

- **AI + Backend Integration**
  - LLM‑driven classification, extraction, and summarization
  - Task and workflow automation built on top of OpenRouter

- **Cloud & DevOps Practices**
  - Containerized services (Docker)
  - Simple, reliable deployments (VPS, Dokploy, CI/CD)

- **Developer Productivity**
  - Tools that reduce repetitive work (docs, triage, task creation)
  - Opinionated workflows that fit real engineers’ lives

---

## 🧩 Tech Stack

Typical stacks used in ChatCue AI projects:

- **Languages:** Go, TypeScript
- **Backend:** HTTP APIs, clean architecture, background workers
- **DB & Storage:** PostgreSQL, Redis (where relevant)
- **AI / LLM:** OpenRouter (multi‑model, JSON‑structured prompts)
- **Infra:** Docker, Docker Compose, VPS/Dokploy, GitHub Actions
- **Frontend:** Minimal HTML/Go templates or small React/Next.js frontends

---

## 📌 Roadmap (High‑Level)

Planned directions for ChatCue AI:

- Solid MVP of **WhatsApp‑to‑tasks** for personal use
- Safer / clearer integration patterns for:
  - WhatsApp Web gateway (personal usage)
  - WhatsApp Cloud API (business usage)
- Optional integrations:
  - GitHub / GitLab context for “how to start” suggestions
  - Issue creation from tasks
- More “conversation → action” tools (email, Slack, etc.)

---

## 🤝 About the Author

**Ruben Adisuryo (YungBenn)**  
Backend Engineer • Cloud/DevOps • Co‑Founder of SportGather  
Focused on Go, AWS/GCP, Kubernetes, CI/CD, and now **AI‑augmented workflows**
for developers.

- GitHub: [@YungBenn](https://github.com/YungBenn)
- LinkedIn: [Ruben Adisuryo Nugroho](https://www.linkedin.com/in/ruben-adisuryo-nugroho/)

If you’re interested in AI‑powered developer tools, backend/cloud systems, or
want to discuss ChatCue AI, feel free to reach out or open an issue in one of
the repos.
