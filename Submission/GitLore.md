# Open Source Hackathon 2026 Project Submission

## Team Details

**Team Name:** Ablazers

**College/University:** Sir M. Visvesvaraya Institute Of Technology, Yelahanka, Bengaluru

---

### Participant 1

**Full Name:** Deekshith J Gowda

**GitHub Username:** dee-hacks

**Role:** Team Member

---

### Participant 2

**Full Name:** Santhosh

**GitHub Username:** santhosh

**Role:** Team Member

---

### Participant 3

**Full Name:** Sairaj M Nadaf

**GitHub Username:** SairajMN

**Role:** Team Member

---

## Project Details

**Project Title:** GitLore — The Lore Behind Your Codebase

**Project Description:**
GitLore is an AI-powered **codebase archaeology system** that explains *why* code exists, how it evolved, and what historical decisions, incidents, PR discussions, issues, and ADRs shaped its current form.

This is **not** a chatbot, **not** a code completion tool, and **not** an IDE assistant. GitLore is a *historical reasoning system* for repositories. It indexes a GitHub repository's commits, pull requests, issues, documentation, and architectural decision records, then answers intent-classified queries (`why`, `when`, `what_changed`, `dependency`, `edge_case`, `rationale`, `historical_trace`, `unknown`) with grounded, evidence-cited answers.

**The problem it solves:** engineering decisions are scattered across years of git history — buried in commit messages, lost in closed PRs, or implied by code that "just works." New contributors (and often the original authors) lose the *why* behind a piece of code. GitLore unifies that context and surfaces it on demand, with explicit confidence scores and a transparent evidence trail (commits, PRs, issues, ADRs) so reviewers can verify every claim.

**Key capabilities:**
- Connect any public GitHub repository and index its full history (commits, PRs, issues, docs)
- 8-way query intent classification routed to the cheapest/fastest LLM that is good enough for the task, with automatic fallback across providers
- Hybrid retrieval: lexical + semantic + 1–2 hop graph expansion over a 12-table relational model
- Evidence-cited answers with confidence badges, timeline visualization, and Mermaid diagrams
- Investigation and watchlist modules to save and monitor queries
- LLM provider abstraction supporting Groq, OpenRouter, and Inception Labs

A full evaluation framework with 8 base traces and 5 custom multi-hop traces across well-known repositories (React, CPython, Next.js, curl, Postgres, Redis, Godot, SQLite) is included in the README.

**Tech Stack Used:**
- **Frontend:** Next.js 15, React 19, TypeScript, Tailwind CSS 4, Mermaid, Zod
- **Backend:** Python 3.12, FastAPI, SQLAlchemy 2 (async), Pydantic v2, Alembic, pgvector, Redis, structlog
- **Datastores:** PostgreSQL 16 with pgvector extension, Redis
- **LLM Providers:** Groq, OpenRouter, Inception Labs (with router + automatic fallback)
- **Integrations:** GitHub Octokit, AI SDK, Cheerio
- **Tooling / Infra:** Docker, docker-compose, uv (Python package manager), Vitest, Pytest
- **Testing:** Vitest (frontend), Pytest (backend, async mode)

**GitHub Repository Link:** https://github.com/SairajMN/GitLore

**Live Demo Link:**
*(No live deployment — see demo video below.)*

**Presentation / Demo Video Link:** https://youtu.be/PTGIIfTrbgU

---

## Open Source Readiness

- [x] My project is public on GitHub
- [x] My repository has a proper README.md
- [x] I have added setup/installation instructions (docker-compose quick start in README)
- [x] I have added screenshots/demo where possible (SCREENSHOTS.md + demo video at https://youtu.be/PTGIIfTrbgU)
- [x] I have added a license file 
- [x] My project is original and built/updated during the hackathon period

---

## Memori Labs Sponsor Task

Please complete these before submitting:

- [x] I have starred the Memori Labs GitHub repository  
  https://github.com/MemoriLabs/Memori

- [x] I have followed Memori Labs on LinkedIn  
  https://www.linkedin.com/company/memorilabs/

- [x] I have followed Memori Labs on X  
  https://x.com/memorilab

- [x] I have checked Memori Labs social links  
  https://linktr.ee/memorilabs

---

## ID Card Verification

- [x] I have generated my ID card from https://oshack.xyz
- [x] If my ID was not verified, I completed the mandatory verification/giveaway form and tried again

---
