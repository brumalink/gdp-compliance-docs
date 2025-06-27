# VAL-001 Validation record – Shipment Platform v1.0

| Field | Value |
|---|---|
| System | Brumalink Shipment Platform |
| Version | 1.0 (go-live 2025-07-01) |
| GxP relevance | Direct – excursion detection, custody chain |
| Validation approach | Risk-based, GAMP 5 category 5 (custom) |
| Result | **Released for production use** |
| Approved | Joanna Kowalczyk, 2025-06-27 |

## Scope

| Function | Risk | Tests | Result |
|---|---|---|---|
| Excursion detection per product profile | High | 24 | Pass |
| Quarantine on excursion | High | 6 | Pass |
| Custody chain integrity detection | High | 9 | Pass |
| Reading ingestion, duplicates | Medium | 11 | Pass (1 deviation, see below) |
| Route planning | Low | 5 | Pass |

## Deviations during validation

- VD-01: duplicate readings stored after tracker reconnect. Accepted for go-live with procedural control;
  fixed in v1.0.1 (platform change 2025-07-15).

## Traceability

Design documents: `shipment-platform` repository, tag `v1.0.0`.
