# SlateSMS — District Governance

**Presentation deck (Markdown)** · District tenants resolve via **district `code`** in the URL; dashboard base: `/[district_code]/dashboard/district-admin/`. **Updated:** April 2026.

---

## Slide 1 — Title

**SlateSMS for district education offices**

Regional oversight: schools and zones in your district, analytics, finance summary, teachers, users — **scoped to district_id**.

---

## Slide 2 — Who this is for

- District superintendents and academic officers  
- Operations, student welfare, teacher coordination  
- District finance and IT administration  
- Inspection coordinators  

Role-based navigation shows the right sections per governance role.

---

## Slide 3 — District dashboard — core sections

| Section | Path pattern | What it does |
|---------|----------------|---------------|
| **Overview** | `/district-admin` | Entry point; links to schools, subdistricts, analytics, teachers, finance, inspections, users |
| **Schools** | `/district-admin/schools` | Schools **in this district** |
| **Subdistricts** | `/district-admin/subdistricts` | Zones/blocks under the district |
| **Users** | `/district-admin/users` | Governance users for the district (and zone roles within district) |
| **Analytics** | `/district-admin/analytics` | District analytics |
| **Teachers** | `/district-admin/teachers` | Teacher workforce summary |
| **Finance** | `/district-admin/finance` | District finance summary |
| **Inspections** | `/district-admin/inspections` | Placeholder / extensible for inspection workflow |

---

## Slide 4 — Relationship to state and schools

- **Below state**: districts belong to a state; district users do not see other districts’ data  
- **Above schools**: each **school** remains its own tenant for daily operations  
- **Linkage**: schools carry optional `district_id` (and state/subdistrict) for rollup  
- **School-only modules**: features such as the **Photographer** dashboard (portraits, event galleries, library media, approvals) are **per-school** APIs — the district dashboard does not replace or centralize those workflows  

---

## Slide 5 — Isolation

- All district APIs enforce **district scope**  
- No cross-district data return  
- Same user table as schools (`edumate_users`); governance assignments use `governance_user_scope` with **district_id**  

---

## Slide 6 — Compared to state

| State | District |
|-------|----------|
| Creates districts, statewide policies, full finance/teacher/trainings picture | Focuses on **local** schools, subdistricts, district analytics and finance summary |
| Broader user onboarding | Users scoped to district (and child zones) |

---

## Slide 7 — Suggested next steps

1. Ensure district codes are unique for tenant resolution (`docs/GOVERNANCE_SCHEMA_ANALYSIS.md`).  
2. Link schools to `district_id` for accurate lists and metrics.  
3. Assign district governance roles and verify nav per role.  
4. Plan inspection process if you extend beyond the placeholder.  

---

*Feature list from `docs/SLATESMS_PRODUCT_FEATURES_AND_FUNCTIONALITY.md` §5. School-level media: §3.13.*
