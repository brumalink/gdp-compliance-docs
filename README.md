# Brumalink GDP compliance documents

> **Fictional company.** Brumalink is a fictional company used for demonstration purposes. All company names, people, customers and data in this repository are invented. Any resemblance to real entities is coincidental.
>
> **AI-generated content.** This repository was created with the help of AI and contains documentation only.

Quality management documents for Good Distribution Practice (GDP) at Brumalink.
This repository **is the controlled document system**: the version of a document in force on any date is the
version on `main` at that date, and every change is approved through a reviewed pull request (SOP-QA-01).

> ⚠️ Audit-relevant. Never rewrite history or delete branches in this repository.

## Contents

| Folder | What | Examples |
|---|---|---|
| [`sops/`](sops/) | Standard operating procedures | SOP-TR-07 temperature excursions, SOP-QA-02 deviations |
| [`registers/`](registers/) | Registers kept as CSV | deviation register, training matrix |
| [`validation/`](validation/) | Computerised system validation records, restore tests | VAL-001, VAL-002 |
| [`audits/`](audits/) | Audit reports and plans | 2025 customer audit |
| [`templates/`](templates/) | Blank forms | deviation report, CAPA plan |
| [`docs/`](docs/) | Overview of the quality system | [QMS overview](docs/qms-overview.md) |

## Document baselines

Approved sets of documents are tagged `qms-YYYY.N` (see [CHANGELOG](CHANGELOG.md)).

## Roles

- **Responsible Person (GDP):** Joanna Kowalczyk, Head of Quality
- **QA & Compliance:** Piotr Kaczmarek
- Approvals: `@brumalink/qa-compliance` (see [CODEOWNERS](.github/CODEOWNERS))
