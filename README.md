# Muiz Oyebowale
 
Backend engineer. I build systems that hold up when things get real.
 
[muizzyranking.me](https://muizzyranking.me)
 
Most of what I've shipped is backend systems that can't afford to be wrong —
payments, auth, job scheduling, reconciliation. I've also led full-stack
teams when the job called for it. Backend is home base, not a boundary.
 
---
 
## What I work with

**Languages:** Python, JavaScript, TypeScript, Bash, SQL  
**Core:** Django, FastAPI, Django Ninja, Django REST Framework, Next Js, React
**Data:** PostgreSQL, MongoDB, Redis, MySQL
**Infrastructure:** Docker, Celery, Nginx, Gunicorn, Uvicorn
**Auth:** JWT, OAuth, API Keys, Webhooks, RBAC
**Tools:** Neovim, Git, Postman, Linux
 
---

## Things I have built

**[Settle](https://github.com/Muizzyranking/settle-be)** · [frontend](https://github.com/Muizzyranking/settle-fe)
Payment collection infrastructure for Nigerian SMEs, built on Nomba's virtual
account APIs. Every customer gets a dedicated account number so incoming
transfers auto-reconcile — no more manually matching who paid what across
a shared account. Idempotent webhook processing, an append-only ledger, and
two separate SSE channels for real-time payment status. Built solo in under
a week.

**[Flint](https://github.com/Muizzyranking/flint)** · [frontend](https://github.com/Muizzyranking/flint-web)
A background job scheduler built from scratch — no Celery, no Redis queue.
An in-memory heap handles priority dispatch with aging, so low-priority jobs
are mathematically guaranteed to eventually run instead of starving forever.
A DAG engine handles job dependencies with cascade retry and cascade failure.
Dead-letter queue with threshold alerting for jobs that fail for good.

**[Galleria](https://github.com/Muizzyranking/gallerai)** · [frontend](https://github.com/Muizzyranking/gallerai-ui)
Event photo platform using face recognition. Attendees scan their face once
and get every photo they appear in, instead of scrolling through hundreds of
images. RetinaFace + ArcFace running through Celery workers, embeddings
stored in MongoDB, cosine similarity search across thousands of faces in
under 100ms.

**[Insighta Labs](https://github.com/Muizzyranking/insighta-backend)** · [web](https://github.com/Muizzyranking/insighta-web) · [CLI](https://github.com/Muizzyranking/insighta-cli)
Demographic-intelligence API with a dual OAuth flow — standard cookie-based
auth for the browser, and a full PKCE flow with a local callback server for
the CLI. Short-lived JWTs paired with single-use hashed refresh tokens, and
a rule-based natural-language query parser for filtering people by age,
gender, and country from plain text.

---

## Where I have worked

**HNG Internship** — Finalist in a highly competitive, global backend
internship. Tech lead over an 11-engineer team building an AI-agent tooling
product, and built Insighta Labs solo. Before that, built the admin system
and notification system for Sitelytics, a website analysis platform.

**Taskingdom** — Backend developer on a task-based gaming platform with
real-money rewards. Built fraud prevention logic, a hybrid Redis/PostgreSQL
state tracking system, and webhook integration for third-party game outcomes.

**Meerge Africa** — Owned the Supplier service from scratch. 500+ suppliers,
a four-state approval workflow, JWT service-to-service auth, and 8 weeks as
acting backend lead when the engineering lead left mid-project.

---

## What I am exploring

Systems that make hard problems boring — priority queues, reconciliation
engines, real-time infra. Lately I'm curious about where AI-assisted tooling
actually earns its place in a backend engineer's workflow, beyond
autocomplete.

---

# Blog posts
<!-- BLOG-POST-LIST:START -->
- [The Art of Git Is Dying](https://muizzyranking.me/blog/the-art-of-git-is-dying)
- [Why I Built My Own Rate Limiting Library for FastAPI](https://muizzyranking.me/blog/why-i-built-fastlimit)
- [My Experience With HNG: Two Tasks That Stuck With Me](https://muizzyranking.me/blog/my-experience-with-hng)
- [Understanding the Linux Shell: Aliases, Special Parameters, and Security](https://muizzyranking.me/blog/understanding-the-linux-shell-aliases-special-parameters-and-security)
- [Understanding the Linux Shell: Variables, Expansions, and Shell Scripts](https://muizzyranking.me/blog/understanding-the-linux-shell-variables-expansions-and-shell-scripts)
<!-- BLOG-POST-LIST:END -->

---

<oyebowaleabdulmuiz@gmail.com> · [muizzyranking.me](https://muizzyranking.me) · [Twitter](https://twitter.com/muizzyranking)
> :wq
