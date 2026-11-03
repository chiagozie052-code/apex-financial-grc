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
4. Test samples of 25 per control for operating effectiveness, using formulas that compare evidence timestamps and attributes
5. Document exceptions and reconcile them to the test results
6. Issue an audit finding with root cause, risk, recommendation and management response

Traceability chain: **Risk → Control → Evidence → Test → Finding → Remediation → Reporting**

## Deliverables

| File | Description | Status |
|---|---|---|
| ITGC-Control-Matrix.xlsx | 26 controls mapped to risks, assets, NIST CSF 2.0 and SOC 2 | Complete |
| Evidence/ | Fictional access, HR, change, MFA, patch and backup reports (full populations) | Complete |
| ITGC-Test-Results.xlsx | Sample-level test results, exception log and summary | Complete |
| Audit-Finding-001.pdf | Formal finding on delayed removal of terminated user access | Complete |

## Test Results

| Control | Description | Sample | Exceptions |
|---|---|---|---|
| AM-01 | New user access approved before account creation | 25 | 2 |
| AM-02 | Terminated users disabled within 24 hours | 25 | 3 |
| AM-04 | MFA registered and enforced | 25 | 1 |
| CM-01 | Production changes approved before implementation | 25 | 1 |
| OP-01 | Critical/high patches applied within 30 days | 25 | 2 |
| BK-01 | Daily backups successful or re-run within 24 hours | 25 | 1 |

**Total:** 150 items tested, 10 exceptions (6.7%). Tolerable deviations: 0.

## Key Finding
**AF-001 (High):** 3 of 25 sampled terminated users (12%) were disabled 3 to 15 days late, and one account recorded a successful sign-in after termination. Extended testing found 5 of 38 late in the full population, all handled manually. Related risk: R-010 from the NIST risk register. See Audit-Finding-001.pdf for the condition, criteria, cause, risk, recommendation, management response and remediation dates.

## Framework References
- NIST CSF 2.0 (PR.AA, PR.PS, PR.DS, DE.CM, RS.MA)
- SOC 2 Trust Services Criteria (CC6, CC7, CC8, A1)
- Links to Risk IDs in `01-NIST-Risk-Assessment/Risk-Register.xlsx`

## Disclaimer
This is a simulated educational portfolio project. It does not reflect any real organization's controls or results. Sample seeds were chosen so each sample contains at least one exception, to demonstrate exception handling (see the Methodology sheet).
