# SlateSMS — Colleges, Universities & Post-Secondary

**Presentation deck (Markdown)** · The product is a **multi-tenant school institution** model (same `school_code` tenant). Post-secondary fit comes from **role dashboards and modules** implemented for higher-ed-style jobs (dean, registrar, program coordinator, etc.), not a separate “university product SKU” in code. **Updated:** April 2026 — **Photographer** and **event gallery** workflows included where institutions use official portraits and event photography.

---

## Slide 1 — Title

**SlateSMS for colleges and universities**

Deliver student services, academics, exams, placements, and leadership oversight **inside one institution tenant** — with dashboards aligned to faculty and administrative roles.

---

## Slide 2 — How post-secondary maps technically

- **No separate “university tenant type”** in the codebase: your institution uses a **school** tenant (`…/[school_code]/…`).  
- **Governance** (state/district/zone) applies if your system links the institution into public hierarchy — optional for private HE.  
- Value is in **roles and modules**: registrar workflows, dean scope, examinations, research, placements, student affairs.

---

## Slide 3 — Leadership & academic oversight

| Role (examples in app) | Typical use |
|------------------------|-------------|
| **Dean** | Scoped KPIs (grades/departments/programs), academic performance views, approvals, compliance-oriented pages — see `docs/DEAN_DASHBOARD_IMPLEMENTATION_SUMMARY.md` |
| **HOD** | Department-level academic leadership |
| **Principal / Vice-principal** | Institution-wide leadership (also common in senior secondary) |

---

## Slide 4 — Registrar & records

- **Registrar**: enrollments, course registrations, transcripts, certificates, student verification, transfers, academic calendars, bulk communications  
- **Controller of examinations**: exam-centric operations (role dashboard present)  
- Supports transcripts and formal academic records workflows documented in product features  

---

## Slide 5 — Programs, research, careers

| Role | Direction |
|------|-----------|
| **Program coordinator** | Program-level coordination dashboard |
| **Research coordinator** | Research administration views |
| **Placement officer** | Placements |
| **Internship coordinator** | Internships |
| **Career counselor** | Career assessments, sessions, applications pipeline (school-level CRM overlaps admissions) |
| **Academic advisor** | Advising workflows |

*Routes referenced from `lib/routeHelpers.ts` role mappings.*

---

## Slide 6 — Student & campus life

- **Student affairs officer** — student-life oriented dashboard  
- **Hostel attendant**, **cafeteria supervisor**, **sports** — auxiliary operations often relevant on residential campuses  
- **Medical officer / nurse** — health workflows  
- **Library**, **IT support**, **security admin** — shared services  
- **Photographer / media** — same **school tenant** module as K–12: **staff** and **student** (and **parent/guardian** where used) portraits; **event galleries** for convocation, sports, alumni, and campus events; **library** uploads with **approval** by leadership (**principal**, **school admin**, etc.) before publication; **events coordinator** gallery management where that role is used  

---

## Slide 7 — Shared platform strengths

- **Fees and finance**: payment gateways, refunds, reporting — relevant for tuition-driven institutions  
- **HRMS & payroll**: staff lifecycle and payroll runs  
- **Communication**: messaging, templates, broadcasts  
- **Integrations**: configurable integration settings per product docs  
- **Official imagery**: governed **media** pipeline (optional **photographer** role + reviewer workflow) reduces ad-hoc file sharing for ID photos and public-facing event assets  

---

## Slide 8 — Honest positioning

- **Strengths**: breadth of roles, registrar/exam/dean-style depth where implemented, single stack for ops + academics + HR.  
- **Caveat**: evaluate against your **SIS/LMS/regulatory** needs; the repo describes capabilities **as built**, not every regional compliance niche.  
- **Governance**: public systems of HE may still use **state/district** decks if policy requires oversight tenants.  

---

## Slide 9 — Suggested next steps

1. Map your org chart to SlateSMS **roles** (dean, registrar, program lead, etc.).  
2. Pilot registrar + examinations + dean scope for one faculty or school-within-university.  
3. Layer placements, internships, and research coordination.  
4. Connect payment and HR/payroll when finance is ready.  
5. If you contract **campus photography** or run a **communications studio**: assign **photographer** users, configure storage, and set **who approves** published media (`docs/USER_MANUAL_PHOTOGRAPHER_DASHBOARD.md`).  

---

*Cross-check role list with `lib/routeHelpers.ts` and dashboard folders under `app/[school_code]/dashboard/`. Product catalog: `docs/SLATESMS_PRODUCT_FEATURES_AND_FUNCTIONALITY.md` §3.13.*
