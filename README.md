## Abdul Wasay

Backend-focused full-stack engineer in Lahore. I build CRM and SaaS platforms end to end and
connect them to the systems clients already run.

Three years at [Hatzs Dimensions](https://www.linkedin.com/in/abdul-wasay01), where I've shipped
four CRM products across four industries. Two of them, Befer and DealerIQ, were later registered
as their own companies.

Most of my work sits at the boundary between systems: REST APIs, event-driven jobs, third-party
integrations, and the logging and alerting that tells you when one of them quietly stopped
working.

---

### Open source

**[TanStack Query #11188](https://github.com/TanStack/query/pull/11188)** — merged

Root-caused false-positive warnings in the `no-unstable-deps` rule of
`@tanstack/eslint-plugin-query`. Lookup tables were inheriting from `Object.prototype`, so
built-in method names were being flagged as unstable dependencies. Fixed with prototype-free
dictionaries (`Object.create(null)`) plus regression tests across all three affected code paths.
Merged by a maintainer on first push.

---

### What I've built

**Befer** — AI CRM for field service businesses (HVAC, plumbing, electrical, cleaning). Built end
to end: scheduling, dispatch, quoting, Stripe invoicing. An OpenAI-backed intake service turns a
technician's voice note into a validated job record, pulling out parts, labour hours and customer
details. Onboarded the first 9 businesses myself. 4,000+ jobs processed in production.

**Voice and chat agents** — Twilio and ElevenLabs, with conversation state shared across channels
so a call continues from wherever the previous chat left off. Built to a hard latency budget.

**Social Hub** — restaurant CRM covering the full order and customer lifecycle.

**Integrations** — lender APIs, service scheduling, inventory platforms, Stripe, Square, and a
Bank of America payment gateway. Authentication, webhook delivery, retries, reconciliation of
failed transactions.

**[intent-engine](https://github.com/wasaybuilds/intent-engine)** — B2B lead pipeline in Python.
Scraping with Playwright, LLM enrichment, Celery for the job queue.

**[horology-api](https://github.com/wasaybuilds/horology-api)** — renders your GitHub history as a
3D mechanical watch. Winding physics, custom shaders. Nobody asked for it.

---

### Stack

**Languages** TypeScript · JavaScript · Python · SQL

**Backend** Node.js · Express · REST API design · event-driven architecture · OAuth 2.0 / SSO ·
webhooks · ETL pipelines

**Frontend** React · Next.js · Redux · Tailwind

**Data** PostgreSQL · MySQL · MongoDB · Redis

**Infra** AWS (Lambda, Step Functions, S3) · Docker · CI/CD · Vercel · structured logging,
monitoring and alerting

**AI** OpenAI API · prompt design · structured output and validation · ElevenLabs · Twilio

**Testing** Jest · Playwright · regression suites

---

### Reach me

[LinkedIn](https://www.linkedin.com/in/abdul-wasay01) · [wasaya670@gmail.com](mailto:wasaya670@gmail.com) · [Portfolio](https://wasay-one.vercel.app)

Open to remote work.
