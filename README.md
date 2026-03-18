# pmo-raid-log-template

Professional PMO RAID Log template built for government ICT project delivery in Malaysia. Covers all four RAID categories across four dedicated sheets with KPI summary cards, realistic sample data, and a full instructions sheet.

All sample data is fictional and constructed for portfolio purposes.

---

## Overview

| Field | Details |
|-------|---------|
| Template Type | RAID Log — Risks, Assumptions, Issues, Dependencies |
| Format | Microsoft Excel (.xlsx) |
| Sheets | 5 (Risks, Assumptions, Issues, Dependencies, Instructions) |
| Sample Entries | 6 Risks, 6 Assumptions, 5 Issues, 6 Dependencies |
| Target Roles | Project Coordinator, PMO Analyst, Project Executive |
| Context | Government ICT project delivery, Malaysia |

---

## What Is Included

### Sheet 1 — Risks

Tracks potential events that have not yet occurred but could negatively impact the project.

| Column | Field |
|--------|-------|
| B | Risk ID (R-001 format) |
| C | Category |
| D | Risk Description |
| E | Trigger / Cause |
| F | Probability (HIGH / MEDIUM / LOW) |
| G | Impact (HIGH / MEDIUM / LOW) |
| H | Risk Rating (HIGH / MEDIUM / LOW) |
| I | Mitigation Plan |
| J | Contingency Plan |
| K | Owner |
| L | Date Raised |
| M | Review Date |
| N | Status |
| O | Remarks |

KPI Cards: Total Risks, Open, Closed, Escalated, High Rated, Medium Rated, Low Rated.

---

### Sheet 2 — Assumptions

Tracks statements accepted as true for planning purposes but not yet confirmed.

| Column | Field |
|--------|-------|
| B | Assumption ID (A-001 format) |
| C | Category |
| D | Assumption Description |
| E | Basis / Rationale |
| F | Owner |
| G | Date Raised |
| H | Validated By |
| I | Validation Date |
| J | Status |
| K | Impact if Wrong |
| L | Remarks |

KPI Cards: Total, Validated, Pending, Invalidated, Closed.

---

### Sheet 3 — Issues

Tracks problems that have already occurred and require active resolution.

| Column | Field |
|--------|-------|
| B | Issue ID (I-001 format) |
| C | Category |
| D | Issue Description |
| E | Impact |
| F | Priority (HIGH / MEDIUM / LOW) |
| G | Raised By |
| H | Owner |
| I | Date Raised |
| J | Target Resolution Date |
| K | Actual Resolution Date |
| L | Status |
| M | Resolution Action |
| N | Remarks |

KPI Cards: Total, Open, Resolved, Escalated, Closed, High Priority count.

---

### Sheet 4 — Dependencies

Tracks external and internal items the project depends on to proceed.

| Column | Field |
|--------|-------|
| B | Dependency ID (D-001 format) |
| C | Type (Internal / External) |
| D | Dependency Description |
| E | Dependent On |
| F | Owner |
| G | External Party |
| H | Required By Date |
| I | Status |
| J | Impact if Late |
| K | Mitigation Action |
| L | Remarks |

KPI Cards: Total, Open, Met, At Risk, Blocked.

---

### Sheet 5 — Instructions

Step-by-step guidance on all four RAID categories, risk rating matrix, and review cadence.

---

## Risk Rating Matrix

| Probability | Impact | Rating |
|-------------|--------|--------|
| HIGH | HIGH | HIGH |
| HIGH | MEDIUM | HIGH |
| MEDIUM | HIGH | HIGH |
| MEDIUM | MEDIUM | MEDIUM |
| LOW | HIGH | MEDIUM |
| LOW | MEDIUM | LOW |
| LOW | LOW | LOW |

---

## Status Reference

### Risks
| Status | Meaning |
|--------|---------|
| OPEN | Active and being monitored |
| CLOSED | Mitigated or no longer applicable |
| ESCALATED | Requires immediate attention from PM or Steering Committee |

### Assumptions
| Status | Meaning |
|--------|---------|
| PENDING | Not yet validated |
| VALIDATED | Confirmed as true |
| INVALID | Proven wrong — reassess impact immediately |
| CLOSED | No longer relevant to the project |

### Issues
| Status | Meaning |
|--------|---------|
| OPEN | Raised and being worked on |
| RESOLVED | Resolved — awaiting formal close-out confirmation |
| ESCALATED | Requires decision from PM or Steering Committee |
| CLOSED | Formally closed — retained for audit trail |

### Dependencies
| Status | Meaning |
|--------|---------|
| OPEN | Not yet fulfilled |
| MET | Fulfilled on time |
| AT RISK | May not be met by required date — monitor closely |
| BLOCKED | Actively blocking project progress — escalate immediately |

---

## Sample Data

All sample data reflects realistic Malaysian government ICT project scenarios across a Waterfall SDLC delivery lifecycle.

**Risks** — Schedule, Technical, Scope, Resource, and Compliance categories. Covers UAT resource availability, data migration complexity, integration failure risk, scope creep, PM availability, and government security approval delays.

**Assumptions** — Resource, Technical, Client, Environment, Scope, and Compliance categories. Covers team availability, API documentation, UAT participant confirmation, test environment stability, scope freeze, and security approval timelines.

**Issues** — Technical, Data, Client, Process, and Resource categories. Covers integration environment delays, legacy data quality problems, UAT participant confirmation failures, client change requests, and QA resource gaps.

**Dependencies** — Internal and External types. Covers legacy system API documentation, government security approval, BRS sign-off, schedule baseline, client UAT participants, and hardware delivery.

---

## How This Reflects Real PMO Practice

- Four-sheet structure separates RAID categories cleanly, matching how professional PMO teams maintain the log on formal government contracts in Malaysia
- Separate mitigation plan and contingency plan columns on the Risks sheet reflects the distinction between prevention and response, a standard requirement in risk management frameworks including ISO 31000
- Assumption validation tracking with PENDING and VALIDATED statuses reflects formal phase gate requirements on government ICT contracts where unvalidated assumptions must be resolved before subsequent phases proceed
- Issue escalation status reflects the real escalation chain from Project Coordinator to PM to Steering Committee used on Malaysian government ICT deliveries
- Dependency tracking with external party and required-by date mirrors how government ICT projects manage third-party obligations under LOA-based contracts
- Closed and resolved items are retained in the log — this is deliberate audit trail design, not a cleanup exercise. Government auditors will ask to see full resolution history
- KPI summary cards on all four sheets provide instant visibility on log health without scrolling through all entries, reflecting how PMO teams present RAID status in steering committee meetings

---

## Files Included

| File | Description |
|------|-------------|
| `PMO_RAID_Log.xlsx` | Full Excel RAID log with all four sheets and instructions |
| `README.md` | Repository documentation |

---

## Skills Demonstrated

`Risk Management` `Assumption Tracking` `Issue Management` `Dependency Tracking` `PMO Governance` `RAID Log` `Escalation Management` `Document Control` `Government ICT Delivery` `Microsoft Excel` `RAG Status Reporting`

---

*Built by Muhammad Muqris bin Shazly — Project Coordinator and PMO Support*
*[github.com/muhammadmuqris14](https://github.com/muhammadmuqris14)*
