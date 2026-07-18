# Nonconformity Log

**Reference:** ISO/IEC 27001:2022 Clause 10.1 (Nonconformity and Corrective Action)
**Prepared by:** TrustGrid Technology

---

## Purpose

Every nonconformity identified during the audit must be logged, tracked through root cause analysis, and followed to closure. Certification bodies expect to see this log as evidence that findings are managed systematically, not just noted and forgotten.

---

## Severity Classification

| Severity | Definition |
|---|---|
| Major Nonconformity | Absence or complete breakdown of a required control, or a systemic issue affecting the ISMS's ability to achieve its intended outcomes |
| Minor Nonconformity | A single lapse or isolated instance that does not indicate a systemic breakdown |
| Observation | Not a nonconformity, but a potential future risk or improvement opportunity worth noting |

---

## Nonconformity Log Template

### Nonconformity 1

| Field | Details |
|---|---|
| NC ID | NC-001 |
| Date Identified | |
| Severity | Major / Minor / Observation |
| Clause or Control Reference | |
| Description of Nonconformity | |
| Evidence | |
| Root Cause | |
| Corrective Action Proposed | |
| Action Owner | |
| Target Closure Date | |
| Status | Open / In Progress / Closed |
| Verification of Closure | |
| Closed By | |
| Date Closed | |

### Nonconformity 2

| Field | Details |
|---|---|
| NC ID | NC-002 |
| Date Identified | |
| Severity | |
| Clause or Control Reference | |
| Description of Nonconformity | |
| Evidence | |
| Root Cause | |
| Corrective Action Proposed | |
| Action Owner | |
| Target Closure Date | |
| Status | |
| Verification of Closure | |
| Closed By | |
| Date Closed | |

*Duplicate this block for each additional nonconformity identified.*

---

## Root Cause Analysis Guidance

A corrective action that only addresses the symptom, not the root cause, will likely recur. Use a simple "5 Whys" approach:

**Example:**
- Nonconformity: MFA was not enabled on three privileged accounts
- Why? The accounts were created during a system migration
- Why? The migration checklist did not include an MFA verification step
- Why? The checklist was written before MFA became a mandatory control
- Why? There is no process to review and update checklists when policies change
- Root cause: No process exists to keep operational checklists aligned with current security policy

The corrective action here should address the missing review process, not just enable MFA on the three accounts found.

---

## Tracking Summary

| NC ID | Clause/Control | Severity | Status | Target Date | Actual Closure Date |
|---|---|---|---|---|---|
| NC-001 | | | | | |
| NC-002 | | | | | |
| NC-003 | | | | | |

---

## Escalation

Major nonconformities typically require closure verification before certification can proceed or be maintained. Minor nonconformities usually allow certification to proceed with a corrective action plan and follow-up verification at the next surveillance audit.

---

*Built by TrustGrid Technology. Reference log only. Not certification advice. Verify current requirements with your certification body, as closure timelines and escalation rules can vary.*
