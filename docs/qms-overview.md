# Quality management system – overview

```mermaid
flowchart TD
    event["Event: excursion, damage,<br/>wrong delivery, audit finding"] --> dev["Deviation opened<br/>(SOP-QA-02)"]
    dev --> assess{"Impact on<br/>product quality?"}
    assess -- "no" --> close["Close with rationale"]
    assess -- "yes / unknown" --> rca["Root cause analysis"]
    rca --> capa["CAPA plan"]
    capa --> eff["Effectiveness check<br/>after 90 days"]
    eff --> close
    capa -. "may change" .-> sop["SOP revision<br/>(SOP-QA-01)"]
    sop --> train["Re-training<br/>(training matrix)"]
```

## Document hierarchy

1. Quality manual (not in this repository)
2. SOPs – `sops/`
3. Templates and forms – `templates/`
4. Records – `registers/`, `validation/`, `audits/`
