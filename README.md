# Adovate Agreement Hub (prototype)

A clickable prototype of a central platform for tracking Adovate's third-party agreements: CDAs, MTAs, consulting, vendor, investor and grant agreements.

**All data in this repository is made up.** No real agreements, counterparties or investor information are included.

## What's here

| Path | What it is |
| --- | --- |
| `index.html` | The prototype website. Open it in any browser; no install needed. |
| `Adovate_Agreement_Tracker.xlsx` | Starter Excel tracker with dropdowns and automatic expiration alerts (one example row). |

## Prototype screens

- **Overview** – active agreements, what needs attention, obligations due soon, agreements in progress
- **Agreements** – searchable, filterable list; click a row for the agreement's details, obligations and history
- **Obligations** – things Adovate or a partner must do under signed agreements
- **Expiration alerts** – weekly summary email to the CEO and CFO, plus urgent alerts 14 days before expiration and a past-due alert
- **Add agreement** – intake form (the "fill with sample values" button shows how signed PDFs could be read automatically)

## Status

Prototype only. Changes made in the page reset on reload, and no emails are sent. Hosting, storage and access controls for real agreement data still need IT review.

## Planned data model

Each record = a **relationship** (type and internal owner) + one or more **agreement components** (confidentiality, material transfer, research, services, consulting, advisory, grant, investment) + **actions** (re-sign, extend, return materials, reports, milestones).
