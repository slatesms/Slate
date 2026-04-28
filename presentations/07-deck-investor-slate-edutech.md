# SLATE EDUTECH (SlateSMS) — Investor Deck

**Presentation deck (Markdown)** · **Product / engineering sources:** `docs/SLATESMS_PRODUCT_FEATURES_AND_FUNCTIONALITY.md`, `docs/SLATESMS_MARKETING_OVERVIEW.md`, `docs/SLATESMS_MARKETING_HANDBOOK.md`, `enterprise/README.md`, `package.json`, `lib/routeHelpers.ts`, `lib/permissions/`, `app/[school_code]/dashboard/`, `app/api/[school_code]/`, governance routes and seeds (`db/scripts/governance_roles_seed.sql`). **Updated:** April 2026.

**Disclaimer:** Financial metrics, revenue, headcount, and funding terms in brackets are **placeholders** for the leadership team to complete. This deck reflects **documented product and repository capabilities**, not forward-looking guarantees.

---

## Slide 1 — Title

**SLATE EDUTECH — SlateSMS**

The operating system for **schools** and the **education authorities** that govern them — one multi-tenant platform, strict data isolation, role-based experiences from classroom to payroll to policy.

*Confidential — for qualified investors and strategic partners*

---

## Slide 2 — Executive summary (the investment story)

- **Category:** Multi-tenant **education management SaaS** spanning K–12, multi-level institutions, and post-secondary-style roles within the same product surface (no separate “university SKU” in-repo; dean/registrar/controller-of-examinations and related dashboards).
- **Core thesis:** Institutions and governments fail when **data, authority, and daily work are fragmented**. SlateSMS unifies **deep school operations** with a **full governance layer** (state → district → zone → school) in a **single URL and security model**.
- **Differentiation:** Breadth (students through payroll through admissions CRM through communications) **plus** hierarchical tenants **plus** modular RBAC (`lib/permissions/`) enforced on APIs — not “reports bolted onto an SIS.”
- **Technical readiness:** Modern **Next.js 14** application, **PostgreSQL** + **Drizzle ORM**, **AWS-aligned** delivery (S3, SES, SSM, ECS/Fargate patterns documented in `enterprise/`), payments (e.g. **Stripe**, **Razorpay**), optional **PWA**, **Redis** / caching patterns in stack.
- **Traction & ask:** *[Team: insert ARR, logos, pilots, pipeline, round size, use of funds.]*

---

## Slide 3 — Problem

| Stakeholder | Pain |
|-------------|------|
| **Schools** | Spreadsheets, paper, and point tools for SIS, fees, HR, messaging — duplicate entry, weak audit trails, poor parent experience. |
| **District / state** | Need **registry, policy distribution, workforce and finance visibility** — school systems rarely align with oversight without risky ad-hoc exports. |
| **IT & compliance** | **Who may see what** across boundaries is often “trust-based”; breaches and disputes follow. |

**Insight (from product strategy docs):** Failure mode is **fragmentation of data and authority**, not lack of individual apps.

---

## Slide 4 — Solution

**One platform, four conceptual planes**

1. **School tenant** — Day-to-day: students, staff, academics, attendance, assessments, grades, transcripts, certificates, fees, gateways, payroll, admissions, CRM, messaging, transport, hostel, cafeteria, health, library, sports, security, events, QA, MIS, media/photographer workflows, and **60+ modular school-role permission surfaces** (`lib/permissions/roles/*.ts`) feeding role-specific dashboards under `/[school_code]/dashboard/…`.
2. **State / province tenant** — Registry, districts/zones, users, analytics, reports, policies (incl. district notification), infrastructure, finance summaries, teachers, trainings, communication.
3. **District & zone tenants** — Scoped schools, users, analytics, teachers, finance (district), inspections (extensible placeholders where noted in product doc).
4. **Platform governance** — Hierarchy management (`/governance/platform-admin`), data integrity views (`/governance/data-auditor`), support engineer role patterns for enterprise operations.

**URL consistency:** `https://<domain>/[tenant_code]/…` where `tenant_code` is school, state, district, or zone code — **same product patterns**, **scoped data**.

---

## Slide 5 — Product depth (school layer) — evidence from codebase

- **Student lifecycle:** Enrollment, profiles, promotion, verification, transfers.
- **Academics:** Grade levels, subjects, courses, classes, schedules (incl. AI-assisted scheduling where configured), assessments, grades, attendance (incl. optional **biometric** and **badge** paths), transcripts, academic documents, calendars, certificates.
- **Revenue:** Fee structures, payments, refunds, waivers, bank accounts, gateway configuration, reports/exports.
- **Growth:** Admissions lifecycle, interviews, documents, leads; **CRM** (pipeline, appointments, reminders, templates).
- **People:** Staff directory, onboarding, leave, training, performance (where configured), **payroll** runs and payslips.
- **Engagement:** Messaging, templates, broadcasts, notifications, announcements; parent/student portals.
- **Differentiated module example:** **Photographer / school media** — roster-scoped uploads, event galleries, library queue, **principal (and designated roles) media approval**, S3-backed tenant paths, CSV reporting — shows attention to **governed operational detail**, not only core SIS.

---

## Slide 6 — Product depth (governance layer)

- **State dashboard:** Overview KPIs, districts, subdistricts, school registry (incl. bulk import), governance users (incl. onboarding and bulk import), analytics, reports, policies, infrastructure, finance, teachers (e.g. vacancies), payroll summary, trainings, communication.
- **Seeded governance roles (example scale):** Product documentation references **28 governance roles** (e.g. state finance controller, policy officer, accreditation officer, district roles, zone roles, plus technical **platform-admin**, **data-auditor**, **support-engineer** patterns).
- **Enforcement:** APIs scoped by `state_id`, `district_id`, `subdistrict_id`, `school_id` / codes — **no cross-boundary reads** by design.

---

## Slide 7 — Why now / market angle (qualitative)

- **Digital mandate** for education systems (public and private) accelerated expectations for **portals, payments, and visibility**.
- **Consolidation** favors platforms that reduce integration tax — especially where **government and schools** must share **truth** without sharing **inappropriate access**.
- *[Optional: Team to add TAM/SAM/SOM, geography focus, regulatory tailwinds.]*

---

## Slide 8 — Competitive positioning (narrative, not a named matrix)

| Dimension | SlateSMS stance |
|-----------|------------------|
| **Depth vs. governance** | Many products are strong at **either** school ops **or** reporting; SlateSMS implements **both** as first-class tenants and navigation. |
| **Isolation vs. integration** | Multi-tenancy is not cosmetic — routing, repositories, and API layout reflect **tenant + role** enforcement. |
| **Breadth** | Wide role surface (instruction, finance, HR, health, network ops, procurement schema, events, media) supports **land-and-expand** within one contract. |

---

## Slide 9 — Technology & moat (investor-relevant)

- **Application:** Next.js (App Router), React, TypeScript, Tailwind/Radix-style UI stack; extensive **`app/api/`** surface (product doc: **thousands** of route handlers; school-scoped `app/api/[school_code]/…`).
- **Data:** PostgreSQL, Drizzle ORM; schema spans core school domains, governance, procurement, and operational modules.
- **Auth / identity:** Next-Auth, Kinde integration present in dependencies; session and tenant login patterns implemented in-app.
- **Infrastructure:** Documented **ECS/Fargate**, ECR, GitHub Actions deploy pipeline; enterprise docs for **custom client domains**, DR/scaling themes in `enterprise/DEPLOYMENT_MODEL_END_TO_END.md`.
- **Moat sources (defensible over time):** (1) **RBAC + route** complexity accumulated per role, (2) **governance + school** unified data model, (3) **deployment and data-integrity** operational maturity, (4) vertical feature completeness reducing switching once live.

---

## Slide 10 — Business model (outline for team to finalize)

- **Primary:** *[Per-seat / per-student / per-school / hybrid SaaS — specify.]*
- **Expansion:** Additional modules (e.g. media, advanced analytics), governance-tier pricing, professional services for migration and training.
- **Payments revenue share:** Gateway-attached flows (Stripe/Razorpay) — *[state economics if any.]*

---

## Slide 11 — Go-to-market (segments already articulated in-repo)

| Segment | Deck / narrative asset |
|---------|-------------------------|
| Private & independent schools | `01-deck-private-schools.md` |
| Public K–12 (school tenant) | `02-deck-public-schools-k12.md` |
| State / province | `03-deck-state-governance.md` |
| District | `04-deck-district-governance.md` |
| Zone / subdistrict | `05-deck-subdistrict-zone-governance.md` |
| Colleges & universities (HE-style roles) | `06-deck-colleges-universities-postsecondary.md` |

**Sales motion:** *[Team: single-school land vs. authority-led rollout; partner/channel strategy.]*

---

## Slide 12 — Traction & milestones

*[Insert: logos, institutions, students on platform, governance pilots, NPS, retention, YoY growth, key partnerships.]*

**Product milestones (repository-informed, illustrative):** Multi-tenant governance GA patterns; photographer/media governance; extensive role permission modules; enterprise deployment documentation — treat as **engineering maturity signals**, not customer traction.

---

## Slide 13 — Roadmap themes (non-binding)

- Deeper **inspections** and authority workflows where placeholders exist.
- Continued **analytics and export** parity for governance buyers.
- **AI** where already present (scheduling, assessments) — expand responsibly with measurable ROI.
- Internationalization, mobile experience, and integration marketplace — *[prioritize per company strategy.]*

---

## Slide 14 — Team

*[Founders, key executives, advisors, relevant domain experience (education + enterprise SaaS + govtech).]*

---

## Slide 15 — Financial snapshot

*[Historical and projected revenue, burn, runway, unit economics — finance-owned slides.]*

---

## Slide 16 — The ask

**Raising:** *[e.g. $X M Series A]*  
**Use of funds:** *[Product & engineering, sales & marketing, customer success, geographic expansion, security/compliance certifications.]*  
**Contact:** *[email / calendar link]*

---

## Appendix A — Role surface (sampling)

School and authority experiences are decomposed into **many** role dashboards (principal, registrar, fee-admin, nurse, network admin, events coordinator, photographer, district superintendent, zone education officer, etc.) with permissions centralized in `lib/permissions/` — supporting the **“operating system”** positioning with **workflow depth**, not a single monolithic admin UI.

---

## Appendix B — Key file map (for technical diligence)

| Area | Location |
|------|----------|
| Role → routes | `lib/routeHelpers.ts` |
| Permissions | `lib/permissions/` |
| School UI | `app/[school_code]/dashboard/` |
| School APIs | `app/api/[school_code]/` |
| Governance seeds | `db/scripts/governance_roles_seed.sql` |
| Enterprise ops | `enterprise/` |
| Canonical features | `docs/SLATESMS_PRODUCT_FEATURES_AND_FUNCTIONALITY.md` |

---

*This deck is generated from the SlateSMS / Slate Edutech repository and documentation. Maintain parity with `docs/SLATESMS_PRODUCT_FEATURES_AND_FUNCTIONALITY.md` when claiming specific capabilities in external materials.*
