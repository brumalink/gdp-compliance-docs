# SOP-QA-01 Document control

| Document ID | Version | Effective date | Owner | Approved by |
|---|---|---|---|---|
| SOP-QA-01 | 1.0 | 2025-03-05 | Piotr Kaczmarek | Joanna Kowalczyk |

## 1. Purpose

Define how controlled quality documents are created, reviewed, approved, distributed and retired.

## 2. Scope

All SOPs, templates and registers in the `gdp-compliance-docs` repository.

## 3. Procedure

1. A change is proposed on a branch and submitted as a **pull request** using the document change template.
2. The pull request must be approved by QA & Compliance. Transport and warehouse SOPs also need operations approval.
3. On merge to `main`, the new version becomes **effective** on the date in its header.
4. Approved baselines are tagged `qms-YYYY.N`.
5. Superseded versions remain available in the repository history and must **never be deleted**.

## 4. Records

- Pull request with approvals = change record
- Repository history = document history (retention: at least 5 years, see ADR 0004 in `shipment-platform`)

## 5. Revision history

| Version | Date | Change |
|---|---|---|
| 1.0 | 2025-03-05 | First issue |
