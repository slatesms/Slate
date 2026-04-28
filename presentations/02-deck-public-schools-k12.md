# SlateSMS — Public K–12 (School Site Level)

**Presentation deck (Markdown)** · Same **school tenant** and modules as private institutions; public buyers emphasize policy fit, scale, and oversight. **Updated:** April 2026 (photographer / school media — see product doc §3.13).

---

## Slide 1 — Title

**SlateSMS for public K–12 schools (site level)**

Full operational capability for each school, designed to sit under state, district, or zone governance when your deployment links schools into the hierarchy.

---

## Slide 2 — Same core as any school tenant

Each public school signs in under its **school code** (`…/[school_code]/…`) with **school-scoped** data:

- Students, staff, academics, attendance, assessments, grades  
- Fees and payments **where your jurisdiction uses them**  
- Admissions, HRMS, payroll, transport, messaging, reports  
- Optional biometric / badge attendance  
- Optional **Photographer** workspace: portraits (students, staff, parents/guardians), **event-linked galleries**, **library** media with **approval** before publication — school-scoped only  

---

## Slide 3 — Role-based delivery

Dashboards and APIs follow **RBAC** at the school: principals, teachers, registrars, fee-admin, counselors, transport, security, medical/nurse, discipline, cafeteria, PTA, MIS, events, quality assurance, **photographer** (media vendor or staff), and others — matching how public sites divide responsibility.

---

## Slide 4 — Fit for public-sector priorities

- **Audit-friendly reporting** and exports where roles permit  
- **Consistent processes** across sites without merging tenant data  
- **Path to oversight**: schools can be linked to governance hierarchy (`state_id`, `district_id`, `subdistrict_id` on schools — see `docs/GOVERNANCE_MODULE.md`) so authorities get registry and analytics in separate governance tenants  

---

## Slide 5 — What “public” does not change

- **Isolation**: one school never sees another school’s data through school APIs  
- **Governance is optional**: a school tenant works even if hierarchy is not fully deployed  
- **Procurement**: modern web UX, documented deployment patterns (e.g. Docker, CI/CD in repo docs)  

---

## Slide 6 — When to add governance tenants

If your state, district, or zone needs **central registry, analytics, policies, and users** above the school, use the governance decks:

- State → `03-deck-state-governance.md`  
- District → `04-deck-district-governance.md`  
- Subdistrict / zone → `05-deck-subdistrict-zone-governance.md`  

---

## Slide 7 — Suggested next steps

1. Confirm which modules you will enable first (e.g. attendance, grades, HR).  
2. Align roles to local job titles and SlateSMS dashboards.  
3. Plan governance rollout if ministry or regional office requires oversight.  
4. For **district media programs** (yearbook vendors, official portraits): define **photographer** users, **reviewers** (principal / school admin), and storage policy per school tenant.  

---

*School capabilities from `docs/SLATESMS_PRODUCT_FEATURES_AND_FUNCTIONALITY.md` §3 and §3.13.*
