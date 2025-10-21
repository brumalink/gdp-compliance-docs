# SOP-TR-07 Handling of temperature excursions

| Document ID | Version | Effective date | Owner | Approved by |
|---|---|---|---|---|
| SOP-TR-07 | 3.0 | 2025-10-21 | Piotr Kaczmarek | Joanna Kowalczyk |

## 1. Purpose

Define what happens when a shipment leaves its allowed temperature range during transport or storage.

## 2. Definition

An **excursion** is any period in which the measured temperature is outside the shipment's **product profile**:

| Profile | Range |
|---|---|
| `2-8C` | 2 to 8 °C |
| `15-25C` | 15 to 25 °C |
| `frozen` | -25 to -15 °C |

### 2.1 Tolerated short spikes (new in 3.0)

Opening the doors during loading causes short spikes that do not affect product quality. A period outside
the range is **not an excursion** if it lasts **less than 10 minutes** and deviates from the range by
**less than 5 °C**. Justification: stability data review SR-2025-09 (18 products, worst case).

## 3. Procedure

1. The shipment platform detects the excursion, sets the shipment to **quarantined** and alerts the QA duty officer.
2. The driver or hub operator keeps the product in the correct conditions and **does not deliver** it.
3. QA assesses the excursion within **4 hours** using the product's stability data.
4. QA decides: **release** (product may be delivered) or **reject** (return / destruction).
5. A deviation is opened for every rejection (SOP-QA-02).

## 4. Revision history

| Version | Date | Change |
|---|---|---|
| 1.0 | 2025-04-09 | First issue |
| 2.0 | 2025-05-21 | Product profiles 15-25C and frozen added |
| 3.0 | 2025-10-21 | Tolerated short door-open spikes (section 2.1); reduces false quarantines by ~40 % |
