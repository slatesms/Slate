# SlateSMS — Private & Independent Schools

**Presentation deck (Markdown)** · Source: `docs/SLATESMS_PRODUCT_FEATURES_AND_FUNCTIONALITY.md` (§3.13 photographer / school media), `docs/SLATESMS_MARKETING_OVERVIEW.md`, `docs/USER_MANUAL_PHOTOGRAPHER_DASHBOARD.md`, application routes under `app/[school_code]/dashboard/`. **Updated:** April 2026.

---

## Slide 1 — Title

**SlateSMS for private and independent schools**

One platform for academics, people, revenue, and engagement — multi-tenant, role-based, and built for day-to-day operations.

---

## Slide 2 — What you get

- **Single system of record** per institution: your school uses a dedicated tenant URL pattern `…/[school_code]/…`.
- **Strict isolation**: data is scoped by school; staff and families see only what their roles allow.
- **Depth without fragmentation**: replace separate tools for SIS, fees, HR, messaging, and reporting where the product supports your process.

---

## Slide 3 — Student & academic lifecycle

- Enrollment, profiles, promotion, verification, and transfers  
- Grade levels, subjects, courses, classes, schedules (including AI-assisted scheduling where configured)  
- Attendance (including optional **biometric** and **badge** flows)  
- Assessments, grades, transcripts, certificates, academic documents and calendars  
- **Registrar**-oriented workflows: documents, bulk communications, transcript requests  

---

## Slide 4 — Revenue & growth

- **Fees**: structures, student fees, payments, refunds, waivers, bank accounts, gateways (e.g. Stripe, Razorpay), reports and exports  
- **Admissions & CRM**: applications, interviews, documents, leads, pipeline, appointments, reminders, templates  

---

## Slide 5 — People & payroll

- Staff directory, onboarding, documents, leave, training, HRMS (including performance where configured)  
- **Payroll**: structures, runs, payslips, deductions, reporting  

---

## Slide 6 — Engagement & operations

- Messaging, templates, broadcasts, notifications, announcements  
- **Role-specific dashboards** so teams work in tailored workspaces: principal, vice-principal, teachers, fee-admin, counselors, transport, hostel, cafeteria, security, library, sports, discipline, events, QA, MIS, PTA, nurse/medical, and more — as implemented in the product  

---

## Slide 6b — Photography & school media (optional module)

- **Photographer dashboard** (`/dashboard/photographer`) for vendors or in-house staff: roster-scoped **student**, **staff**, and **parent/guardian** portrait uploads; **event galleries** tied to school events; **library** uploads for general school media  
- **Delivery options:** file upload plus **live camera / device capture** where browsers allow  
- **Governance of publication:** uploads can enter a **review queue**; **principals**, **school admins**, and designated roles (e.g. **events coordinator**, **vice-principal**) **publish or reject** — photographers typically **upload only**  
- **Principal “Media approval”** and **events-coordinator gallery** pages complement the same school-scoped media model  
- **Tenant isolation:** all assets stay under the school’s `school_code` / `school_id` APIs  

---

## Slide 7 — Why private schools care

- **Commercial clarity**: fees, gateways, and admissions/CRM in one stack  
- **Parent and staff experience**: consistent portals without exposing internal roles  
- **Operational maturity**: HRMS and payroll alongside academics reduces duplicate entry  

---

## Slide 8 — Technical confidence (short)

- Next.js / PostgreSQL stack; school-scoped APIs  
- Authentication, session handling, tenant login patterns  
- Schema evolution via reviewed SQL scripts (operator-controlled rollouts)  

---

## Slide 9 — Suggested next steps

1. Map your roles to SlateSMS dashboards (school-admin, principal, registrar, fee-admin, etc.).  
2. Pilot one academic term on students, attendance, and fees.  
3. Layer admissions/CRM and payroll when ready.  
4. If you use external or in-house photographers: enable the **photographer** role, confirm S3/storage, and align **who approves** published media (principal / school admin workflow).  

---

*Aligned to repository documentation; update slides when routes or modules change.*
