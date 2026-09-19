### Hi, I'm Aryan Madaan 👋

**AI-native full-stack developer.** I build software end to end, from domain
model and database to integrations, interface, tests, and deployment. I use AI
coding tools as a force multiplier and keep correctness, security, and
auditability in my own hands.

My focus is **fintech and accounting automation**: systems where a wrong number
is worse than no number, so every figure must be traceable and every automated
action reviewable.

Case studies with the story behind each project: **[aryanmadaan.myportfolio.com](https://aryanmadaan.myportfolio.com)**

#### Featured projects

**[Shimline: bookkeeping automation engine for QuickBooks Online](https://github.com/wig1-max/shimline-bookkeeping-engine)**

An evidence-native engine that pulls QuickBooks Online data over OAuth 2.0,
rebuilds the ledger in double entry, and runs 16 deterministic accounting
checks. Each defect becomes a correction proposal that a human approves; the
engine then writes it back idempotently, verifies it by read-back, and
reconciles.

- 848 tests: property-based tests, a grammar fuzzer, and a Beancount differential oracle
- Canadian GST/HST return preparation, bank statement matching, and job costing
- Multi-tenant firm workspace with TOTP MFA, separation of duties, and an append-only audit log
- Python · FastAPI · SQLite · HTMX · WeasyPrint

[![Shimline cleanup review screen](https://raw.githubusercontent.com/wig1-max/shimline-bookkeeping-engine/main/docs/images/bookkeeping-review.png)](https://github.com/wig1-max/shimline-bookkeeping-engine)

**[OweAhead: Making Tax Digital software for UK sole traders](https://github.com/wig1-max/oweahead)**

Tax planning and digital recordkeeping for HMRC Making Tax Digital. A pure,
deterministic, versioned tax engine (integer pennies, GOV.UK-sourced rates)
estimates Income Tax and Class 4 NIC, with CSV bank import, user-authored
bookkeeping rules, private receipts, quarterly reconciliation and close, and a
simulated HMRC provider.

- 965 tests plus Playwright end-to-end journeys with accessibility checks
- PostgreSQL row-level security, fail-closed production configuration, and malware-scanned uploads
- Next.js 16 · React 19 · TypeScript · PostgreSQL · Drizzle · Tailwind

[![OweAhead home screen](https://raw.githubusercontent.com/wig1-max/oweahead/main/docs/images/dashboard.png)](https://github.com/wig1-max/oweahead)

**[TaxDesk OS: practice management and ITR preparation for Indian CA offices](https://github.com/wig1-max/taxdesk-os)**

An operations command center for Indian tax practices (clients, cases, expiring
client upload links, document custody, fees and PDFs) with a Tax Desk built on a
deterministic, versioned AY 2026-27 income tax engine. Every rule cites committed
statutory text, every figure traces back to a ledger row, and filing readiness is
gated by validation, client approval and qualified-reviewer sign-off.

- 2,400+ automated checks: 1,861 unit tests, 312 hostile-client security checks, Playwright end-to-end suites
- Supabase row-level security with guarded `SECURITY DEFINER` RPCs, AES-256-GCM encrypted PAN, audited reveals
- Next.js 15 · React 19 · TypeScript · Supabase / PostgreSQL · Tailwind

[![TaxDesk OS computation screen](https://raw.githubusercontent.com/wig1-max/taxdesk-os/main/docs/images/tax-case-computation.png)](https://github.com/wig1-max/taxdesk-os)

#### What I work with

`Python` `FastAPI` `TypeScript` `Next.js` `React` `PostgreSQL` `Supabase` `SQL / SQLite` `OAuth 2.0` `REST API integrations`
`QuickBooks Online API` `HTMX` `HTML/CSS` `pytest` `property-based testing`
`Linux / Nginx / systemd` `security hardening` `AI-assisted development`

#### Reach me

🌐 Portfolio: [aryanmadaan.myportfolio.com](https://aryanmadaan.myportfolio.com)  
💼 LinkedIn: [linkedin.com/in/aryanmadaan](https://www.linkedin.com/in/aryanmadaan)  
📫 aryanmadaan@gmail.com
