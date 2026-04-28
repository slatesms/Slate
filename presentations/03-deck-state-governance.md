# SlateSMS — State / Province Governance

**Presentation deck (Markdown)** · Grounded in `docs/GOVERNANCE_MODULE.md`, `docs/SLATESMS_PRODUCT_FEATURES_AND_FUNCTIONALITY.md` §4, and `docs/ARCHITECTURE_GOVERNANCE_AND_SCHOOL_MODULES.md`. **Updated:** April 2026 (cross-reference to school-tenant photographer module — §3.13).

---

## Slide 1 — Title

**SlateSMS for state or provincial education authorities**

A **state-level tenant** uses the same URL pattern as schools: `…/[state_code]/…` — e.g. state dashboard at `/[state_code]/dashboard/state-admin/`.

---

## Slide 2 — Problem this solves

- **Fragmented visibility**: spreadsheets and ad hoc reports across districts  
- **Weak master data**: inconsistent school lists and user access  
- **Policy distribution**: hard to publish once and notify downstream  

SlateSMS adds a **governance layer** with APIs scoped to **state_id** — no cross-state data leakage.

---

## Slide 3 — Hierarchy position

```
Country → State (state_code) → Districts → Subdistricts / Zones → Schools (school_code)
```

Schools remain unchanged as tenants; optional columns link a school to state/district/zone for rollup.

**School tenant reminder:** Day-to-day modules (academics, fees, HR, **optional photography / event media** for portraits and galleries) run inside each **`school_code`** tenant — not on the state dashboard. State users see **registry and rollups**, not individual school portrait workflows.

---

## Slide 4 — State dashboard — overview & master data

| Area | Capability (product) |
|------|----------------------|
| **Overview** | Totals: districts, subdistricts, schools, students, teachers, staff, attendance rate, exam pass rate; quick links |
| **Districts / Subdistricts** | Create, read, update, activate/deactivate |
| **Schools** | Registry, edit, activate/deactivate, logo; **bulk import** |
| **Users** | Governance users: list, add, edit, remove scope; onboarding; **import** |

---

## Slide 5 — State dashboard — insight & policy

| Area | Capability (product) |
|------|----------------------|
| **Analytics & reports** | Statewide analytics; reports and export |
| **Policies** | Create, publish, delete; **notify districts** |
| **Infrastructure** | School-level infrastructure view and edit |
| **Finance** | Summary and allocations |
| **Teachers** | Workforce summary and vacancies |
| **Payroll** | Summary (e.g. payslip counts, schools with payroll) |
| **Trainings** | Programs, enrollments, school counts |
| **Communication** | Templates, sent mail, messaging |

---

## Slide 6 — State roles (examples)

Role-based navigation limits menus (not everyone sees finance vs IT):

- State admin, education commissioner, academic director  
- Data analytics officer, finance controller, infrastructure officer  
- Teacher development officer, IT admin, policy officer, accreditation officer  

*See governance role seeds in `db/scripts/governance_roles_seed.sql` and docs.*

---

## Slide 7 — Security & isolation

- APIs enforce **state scope**; data does not cross state boundaries  
- Governance users live in `governance_user_scope` with **state_id** (and optional district/zone for hybrid roles where configured)  
- **Platform tools**: hierarchy management and data auditor routes exist for operators (`docs/SLATESMS_PRODUCT_FEATURES_AND_FUNCTIONALITY.md` §7)  

---

## Slide 8 — Suggested next steps

1. Apply governance SQL scripts in documented order (`docs/GOVERNANCE_MODULE.md`).  
2. Load state code, districts, zones, and school registry.  
3. Onboard governance users and map titles to governance roles.  
4. Pilot analytics and policy notifications with one region.  

---

*Inspection workflows at district/zone are noted as extensible placeholders in product docs. For **photographer / school media** capabilities, see private or public K–12 school decks and `docs/SLATESMS_PRODUCT_FEATURES_AND_FUNCTIONALITY.md` §3.13.*
