# Repository restore test – Q2 2026

| Field | Value |
|---|---|
| Date | 2026-06-29 |
| Performed by | Aleksandra Nowak (DevOps) |
| Witnessed by | Piotr Kaczmarek (QA) |
| Requirement | ADR 0004 (`shipment-platform`): quarterly restore test of GDP-relevant repositories |
| Result | **Pass** |

## Scenario

Restore of `gdp-compliance-docs` and `shipment-platform` from the independent backup to a **new, empty
organization**, as of point in time **2026-03-01 00:00 UTC**.

## Checks

| # | Check | Result |
|---|---|---|
| 1 | All branches and tags present | Pass |
| 2 | Commit history identical up to 2026-03-01 (hash comparison of `main`) | Pass |
| 3 | SOP-TR-07 in the restored copy is version 3.0 (effective 2025-10-21) | Pass |
| 4 | Pull requests restored with review comments and approvals | Pass |
| 5 | Issues (deviation discussions) restored with comments and labels | Pass |
| 6 | Wiki restored | Pass |
| 7 | Time to restore both repositories | 11 min (target: < 4 h) |

## Observations

- O-01: Restored repositories must be made read-only immediately to avoid confusion with the originals.
  Added to the restore runbook in `infra-docs`.
