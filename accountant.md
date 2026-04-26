# Accountant — your SlateSMS dashboard (easy guide)

This page is the **end-user** version. A more technical list of screens and permissions is in [`accountant.md`](../accountant.md).

---

## At a glance

The Accountant manages all financial and accounting operations within an educational institution, including accounting & bookkeeping, payroll management, expense & reimbursement processing, vendor finance, and financial reporting & compliance. Academic advisor uses role_id 39 in this codebase (see lib/permissions/roles/academic-advisor.ts). Description: "Handles accounting, expenses, payroll, reimbursements, and financial reporting for the institution"

---

## Sign in and open the right place

- Open your **school** login page (your school shares the address). Sign in with **your** username and password—do not share logins.
- After you sign in, go to your **Accountant** area. The address will include your **school code** and look like: `https://<your-domain>/{school_code}/dashboard/accountant`.
- If you have more than one school in your list, **pick the right school** before you work, so you do not change data in the wrong place.

- If you see **Unauthorized**, your user’s role in the database or session may not match this route (ask **system admin** or **school admin** to verify the account).


---

## What you can do (menu at a glance)

The names below are what the product’s menu is built around. Your school can turn modules on or off.

Use the menu in the order that matches *your* school’s process (your admin may give you a checklist).

### Main
- **Dashboard**
- **Fees & collections**
- **Fee issues**
- **Ledgers**
- **Vouchers**
- **Chart of Accounts**
- **Financial Years**
- **Expenses & Reimbursements**
- **Expense Categories**
- **Vendors**
- **Vendor Payments**
- **Payroll**
- **Reports & Analytics**
- **Communications**
- **Notifications**
- **Settings**

---

## A simple day-to-day routine

- Open **Dashboard** to see your home view; confirm the correct **school** (or governance tenant) is selected.
- Use the permissioned **approve/verify** actions in forms and lists; add a short note when you reject or send back.
- Use the left navigation in order for routine work: Fees & collections, then Fee issues, then Ledgers, then Vouchers. Finish one record (save, then confirm) before switching screens.
- At end of day: run any **reports or exports** your role owns, log outstanding items, and hand off to **school admin / registrar / IT** as your school defines.

---

## Common questions

- **I see "Unauthorized."** Your account may not be assigned to this **role** or the correct **school or tenant**, or you used a bookmark from another person. Sign out, sign in again, and if it still fails ask **school admin** or **IT / system admin**.
- **A menu item is missing.** Some modules are optional. Your **permissions** may also hide an item. Ask an administrator before assuming it is a bug.
- **Numbers or names look wrong.** Check **date**, **academic year**, and **class or section** filters, then check with the team that creates the data (for example, registrar, fee office, or school admin).

## Need more detail?

- **Your area in general** (policies, big picture): [`04-Finance-HR-and-Operations.md`](../../04-Finance-HR-and-Operations.md)
- **All screens, routes, and permissions (reference):** [`accountant.md`](../accountant.md)
- **Getting started (login, basics):** [`00-Login-and-Getting-Started.md`](../../00-Login-and-Getting-Started.md)
- **Role list (which guide is mine?):** [`09-Role-to-Manual-Mapping.md`](../../09-Role-to-Manual-Mapping.md)
