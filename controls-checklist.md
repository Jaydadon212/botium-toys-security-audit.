For each control, the question is: **“Does Botium Toys currently have this control in place?”**  
Answers are based on the *Scope, goals, and risk assessment report* from the scenario.

## Administrative / Managerial Controls

| Control                          | In Place? | Notes |
|----------------------------------|----------:|-------|
| Least privilege                  | **No**    | Access controls for least privilege have **not** been implemented; all employees can access internally stored data and potentially cardholder data and PII/SPII. |
| Disaster recovery plans          | **No**    | There are currently **no disaster recovery plans** in place and no backups of critical data. |
| Password policies                | **Yes***  | A password policy exists but is **weak and not aligned** with current minimum complexity requirements. |
| Separation of duties             | **No**    | Separation of duties has **not** been implemented. |

\* _Yes, but needs improvement._

## Technical Controls

| Control                                              | In Place? | Notes |
|------------------------------------------------------|----------:|-------|
| Firewall                                             | **Yes**   | Firewall is configured to block traffic based on an appropriately defined set of security rules. |
| Intrusion detection system (IDS)                     | **No**    | The IT department has **not** installed an IDS. |
| Backups                                              | **No**    | Company does **not** have backups of critical data. |
| Antivirus software                                   | **Yes**   | Antivirus software is installed and monitored regularly. |
| Manual monitoring / maintenance for legacy systems   | **Yes***  | Legacy systems are monitored and maintained, but there is **no regular schedule** and intervention methods are unclear. |
| Encryption                                           | **No**    | Encryption is **not** used to protect customers’ credit card information stored in the internal database. |
| Password management system                           | **No**    | There is **no centralized password management system** enforcing the password policy. |

\* _Exists but should be formalized and scheduled._

## Physical / Operational Controls

| Control                                   | In Place? | Notes |
|-------------------------------------------|----------:|-------|
| Locks (offices, storefront, warehouse)    | **Yes**   | Physical location has sufficient locks. |
| Closed‑circuit television (CCTV)          | **Yes**   | CCTV surveillance is up‑to‑date and functioning. |
| Fire detection / prevention               | **Yes**   | Fire alarms and sprinkler systems are present and functioning. |

---

## Overall control posture

- **Strengths:** Basic perimeter and endpoint defenses (firewall, AV), and strong physical security.
- **Weaknesses:** Access control, encryption, detection capabilities, and resilience (backups/DR) are all lacking.
- **Risk impact:** Missing preventative and corrective controls significantly increase the likelihood of data loss, regulatory fines, and long recovery times after an incident.
