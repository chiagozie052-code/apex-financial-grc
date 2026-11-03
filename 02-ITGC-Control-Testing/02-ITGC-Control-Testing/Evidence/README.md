# Evidence

> **Simulated evidence.** Every record in this folder is fictional and was generated for portfolio purposes. No real employer, customer or employee data is used.

Source reports for the ITGC tests at **Apex Financial Services**. Each workbook has a **Report Info** sheet (source system, period, population, control tested) and one or more data sheets. Each file is a **full population**; samples are selected in the testing step.

| File | Source system | Population | Control |
|---|---|---|---|
| Access-NewUser-Evidence.xlsx | ServiceNow, Entra ID | 45 new accounts | AM-01 |
| Access-Termination-Evidence.xlsx | Workday, Entra ID | 38 terminations | AM-02 |
| EntraID-MFA-Report.xlsx | Entra ID | 500 enabled accounts | AM-04 |
| ServiceNow-Change-Report.xlsx | ServiceNow | 64 production changes | CM-01 |
| Intune-Patch-Compliance-Report.xlsx | Intune / Defender | 150 endpoint-patch pairs | OP-01 |
| Backup-Job-Report.xlsx | Backup platform | 552 system-days | BK-01 |

**Audit period:** July 1 – September 30, 2026 (simulated). Reports generated October 5, 2026.

Results are recorded in `ITGC-Test-Results.xlsx` (planned).
