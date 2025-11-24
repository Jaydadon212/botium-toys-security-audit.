This document summarizes recommended actions to improve Botium Toys’ security posture
and reduce risk related to PCI DSS, GDPR, and SOC expectations.

## 1. Strengthen access control and identity management (HIGH PRIORITY)

- Implement **least‑privilege access** so only employees who need cardholder data or PII/SPII can access it.
- Introduce **role‑based access control (RBAC)** tied to job functions (e.g., finance, customer support, IT).
- Enforce **separation of duties** for sensitive operations such as payment processing, refunds, and system administration.
- Deploy a **centralized password management system** that:
  - Enforces strong password complexity and rotation
  - Supports secure self‑service resets to reduce IT tickets
  - Integrates with SSO or directory services where possible

## 2. Introduce encryption and secure handling of payment data (HIGH PRIORITY)

- Encrypt credit card data **at rest** in the internal database.
- Ensure transport‑level encryption (**TLS**) for all payment processing traffic.
- Limit direct storage of card data whenever possible—use tokenization or a trusted payment processor.

## 3. Implement backups and a formal disaster recovery (DR) plan (HIGH PRIORITY)

- Design and implement **regular, automated backups** of critical systems and databases.
- Store backups securely (ideally off‑site or in the cloud) and encrypt backup data.
- Define **RTO** and **RPO** for key systems and test restoration procedures.

## 4. Improve detection and monitoring capabilities (MEDIUM–HIGH PRIORITY)

- Deploy an **IDS/IPS** to monitor network traffic for anomalies.
- Centralize logs in a **SIEM** or log management platform for correlation and alerting.
- Define alert thresholds and escalation procedures for suspicious activity.

## 5. Mature legacy system management (MEDIUM PRIORITY)

- Create a **formal schedule** for monitoring, patching, and maintaining legacy systems.
- Document **intervention procedures** when vulnerabilities or failures are detected.
- Plan to **retire or replace** high‑risk legacy systems over time.

## 6. Continue strengthening physical and operational security (LOW–MEDIUM PRIORITY)

- Maintain existing **locks, CCTV, and fire detection/prevention** systems.
- Periodically review camera coverage and retention settings.
- Conduct physical security walkthroughs to verify adherence to procedures.

## Executive summary

Botium Toys has a solid foundation in physical security and basic technical controls,
but critical gaps around access control, encryption, backups/DR, and monitoring
create significant risk. Addressing these recommendations will move the organization
toward stronger PCI DSS, GDPR, and SOC alignment while better protecting customers
and business operations.
