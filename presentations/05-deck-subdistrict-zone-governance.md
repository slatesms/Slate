# SlateSMS — Subdistrict / Zone Governance

**Presentation deck (Markdown)** · Zone (subdistrict) tenants use **subdistrict `code`** in the URL; dashboard: `/[zone_code]/dashboard/zone-admin/`. **Updated:** April 2026.

---

## Slide 1 — Title

**SlateSMS for block, cluster, and zone officers**

Closest governance layer to schools: monitor compliance, schools, and workforce in a **narrow geographic scope** — **subdistrict_id** APIs.

---

## Slide 2 — Role in the hierarchy

```
State → District → Subdistrict (Zone) → Schools
```

- Zone officers see **only** schools and metrics tied to their **subdistrict**  
- District and state retain broader rollups  
- **School operations** (including optional **photography / event media** under each `school_code`) remain inside the **school tenant** — zone dashboards do not host portrait or gallery uploads  

---

## Slide 3 — Zone dashboard — sections

| Section | Path pattern | What it does |
|---------|----------------|---------------|
| **Overview** | `/zone-admin` | Zone dashboard; schools, analytics, teachers, inspections, users |
| **Schools** | `/zone-admin/schools` | Schools in the zone |
| **Users** | `/zone-admin/users` | Governance users scoped to the zone |
| **Analytics** | `/zone-admin/analytics` | Zone-level analytics |
| **Teachers** | `/zone-admin/teachers` | Teacher workforce summary for the zone |
| **Inspections** | `/zone-admin/inspections` | Placeholder / extensible |

---

## Slide 4 — Typical zone roles (examples)

- Zone education officer  
- Inspection officer, academic coordinator  
- Attendance officer, training coordinator  
- Infrastructure inspector, reporting officer  

Menus are **role-filtered** so each role sees relevant items.

---

## Slide 5 — Why zones matter

- **Local accountability**: same platform as state/district but scoped data  
- **Field alignment**: officers work against the same school registry as upper tiers  
- **Compliance narratives**: attendance and inspection storylines (as you extend workflows) without schools losing autonomy inside their tenant  

---

## Slide 6 — Isolation

- Zone APIs enforce **subdistrict (zone) scope**  
- No cross-zone leakage  
- `governance_user_scope` uses **subdistrict_id** for zone-only users  

---

## Slide 7 — Suggested next steps

1. Define zone codes uniquely (globally unique index on `subdistricts.code` per schema docs).  
2. Attach schools to `subdistrict_id`.  
3. Onboard zone staff and validate analytics against a known school sample.  
4. Co-design inspection workflows if moving beyond placeholder.  

---

*Feature list from `docs/SLATESMS_PRODUCT_FEATURES_AND_FUNCTIONALITY.md` §6. School-level media: §3.13.*
