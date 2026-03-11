# Open Business Protocol

**A shared vocabulary for goal-directed autonomous business operations.**

OBP defines what business concepts mean — universally, portably, and without vendor lock-in. When an agent writes an `_v.invoice`, any OBP-compatible system knows exactly what that record contains and how to work with it.

---

## What OBP Defines

- **`_v.*` Namespace Registry** — 58 ratified business concept definitions across Finance, CRM, HR, Operations, Marketing, Customer Success, Product, and Analytics
- **Goal System** — `_v.goal` as the highest-order protocol primitive; agents resolve goals from nearest context outward
- **Agent Behavior Spec** — what OBP-compliant agents MUST, SHOULD, and MUST NOT do
- **Data Sovereignty Model** — your data stays yours; full portability via NDJSON export/import

---

## Status

> **v0.9** — All 58 v1.0 target namespaces ratified. Publication coming soon.

| Domain | Types |
|--------|-------|
| Universal | goal, contact, metric, task, schedule, knowledge, note, document, event, feedback |
| Finance | invoice, payment, expense, contract, budget, estimate, receipt, subscription, payroll, tax_record |
| CRM | deal, lead, activity, campaign, pipeline, quote |
| HR | employee, job_posting, applicant, performance_review, leave_request, attendance, onboarding |
| Operations | reservation, inventory, order, shipment, supplier, asset, location, purchase_order |
| Marketing | content, audience, ab_test, landing_page |
| Customer Success | ticket, sla, health_score, escalation |
| Product | issue, milestone, sprint, roadmap, release |
| Analytics | report, dashboard, funnel, cohort |

---

## Governed by merit. Owned by no one.

Namespace ratification is based on universality, stability, and non-redundancy — not payment or membership. Any party can propose a namespace via pull request.

**Founding maintainer**: [Spluc, LLC](https://spluc.jp)
**Contact**: contact@openbusinessprotocol.org

→ [openbusinessprotocol.org](https://openbusinessprotocol.org)
