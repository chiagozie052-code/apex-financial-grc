# Project 2 — ITGC Control Testing

> **Simulated project.** All data, evidence and findings are fictional and created for portfolio purposes. No real employer, customer or employee information is used.

## Overview
This project demonstrates how a GRC analyst or IT auditor evaluates whether IT general controls (ITGCs) are designed and operating effectively at **Apex Financial Services**, a fictional 500-employee financial services company.

## Objective
Build a control inventory, test a selected set of key controls against sampled evidence, identify exceptions, and report a formal audit finding with remediation.

## Scope and Audit Period
- **Audit period:** July 1 – September 30, 2026 (simulated)
- **Domains covered:** Access Management, Change Management, IT Operations, Backup & Recovery, Incident Management, Security Operations
- **Controls inventoried:** 26
- **Controls tested:** 6 (AM-01, AM-02, AM-04, CM-01, OP-01, BK-01)

## Methodology
1. Build a control matrix linked to risks (Project 1), assets, NIST CSF 2.0 and SOC 2 criteria
2. Select key controls for testing
3. Generate fictional evidence (reports, tickets, change records)
4. Test samples of 25 per control for operating effectiveness
5. Document exceptions
6. Issue an audit finding with root cause, risk, recommendation and management response

Traceability chain: **Risk → Control → Evidence → Test → Finding → Remediation → Reporting**

## Deliverables

| File | Description | Status |
|---|---|---|
| ITGC-Control-Matrix.xlsx | 26 controls mapped to risks, assets, NIST CSF 2.0 and SOC 2 | Complete |
| Evidence/ | Fictional access, HR, change, MFA, patch and backup reports | Planned |
| ITGC-Test-Results.xlsx | Sample-level test results and exception log | Planned |
| Audit-Finding-001.pdf | Formal finding: Condition, Criteria, Cause, Risk, Recommendation, Management Response, Remediation Date | Planned |

## Controls Tested

| ID | Control | Sample |
|---|---|---|
| AM-01 | New user access approved before account creation | 25 |
| AM-02 | Terminated users disabled within 24 hours | 25 |
| AM-04 | MFA enforced for user accounts | 25 |
| CM-01 | Production changes approved before implementation | 25 |
| OP-01 | Critical/high patches applied within 30 days | 25 |
| BK-01 | Daily backups successful or re-run | 25 |

## Framework References
- NIST CSF 2.0 (PR.AA, PR.PS, PR.DS, DE.CM, RS.MA)
- SOC 2 Trust Services Criteria (CC6, CC7, CC8, A1)
- Links to Risk IDs in `01-NIST-Risk-Assessment/Risk-Register.xlsx`

## Disclaimer
This is a simulated educational portfolio project. It does not reflect any real organization's controls or results.
