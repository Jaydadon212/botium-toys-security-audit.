For each best practice, the question is: **“Does Botium Toys currently adhere to this best practice?”**

## Payment Card Industry Data Security Standard (PCI DSS)

| Best Practice                                                                 | In Place? | Notes |
|-------------------------------------------------------------------------------|----------:|-------|
| Only authorized users have access to customers’ credit card information.     | **No**    | All employees currently have access to internally stored data and may be able to access cardholder data. |
| Credit card information is stored/processed/transmitted in a secure environment. | **No** | Card data is stored in an internal database without encryption or strong access control. |
| Data encryption is used to secure card transaction touchpoints and data.     | **No**    | Encryption is not currently used for customers’ credit card information. |
| Secure password management policies are adopted and enforced.                | **No***   | A nominal password policy exists but is weak; there is no centralized password management system. |

\* _Policy exists but is not strong or consistently enforced._

## General Data Protection Regulation (GDPR)

| Best Practice                                                                                          | In Place? | Notes |
|--------------------------------------------------------------------------------------------------------|----------:|-------|
| E.U. customers’ data is kept private and secure.                                                       | **Partially** | Privacy policies and processes are documented, but weak access control, lack of encryption, and lack of backups introduce significant risk. |
| There is a plan to notify E.U. customers within 72 hours of a breach.                                  | **Yes**   | IT department has established a 72‑hour notification plan. |
| Data is properly classified and inventoried.                                                           | **No**    | Assets and data are not fully identified or classified; asset management is described as inadequate. |
| Privacy policies, procedures, and processes are enforced to properly document and maintain data.       | **Yes***  | Policies and procedures exist and are enforced, but underlying technical controls need improvement. |

## System and Organization Controls (SOC 1 / SOC 2 – conceptual)

| Best Practice                                                            | In Place? | Notes |
|--------------------------------------------------------------------------|----------:|-------|
| User access policies are established.                                   | **Partially** | Basic password policy exists, but no least‑privilege model or separation of duties. |
| Sensitive data (PII/SPII) is confidential and private.                  | **No**    | All employees may be able to access PII/SPII; no least‑privilege or encryption. |
| Data integrity is ensured (consistent, complete, accurate, validated).  | **Yes**   | IT department has controls in place to ensure data integrity. |
| Data is available to authorized users when needed.                      | **Yes***  | Availability is ensured, but lack of backups and DR plan places availability at risk during major incidents. |

## Compliance summary

- **PCI DSS:** High risk of non‑compliance (access control, encryption, and secure storage are missing).
- **GDPR:** Partially compliant on process/notification, but technical gaps around access control, classification, and encryption expose customer data.
- **SOC:** Some integrity and availability practices exist, but confidentiality and access governance are weak.
