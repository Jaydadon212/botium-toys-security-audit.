This project is a mock internal security audit for **Botium Toys**, a fictional e‑commerce and retail toy company.  
It was completed as part of the **Google Cybersecurity Professional Certificate**.

The goal of this audit is to:
- Review the current security posture of Botium Toys
- Identify which security controls are in place and which are missing
- Evaluate compliance with key regulations (PCI DSS, GDPR, SOC)
- Provide recommendations to reduce risk and improve security maturity

## Repository structure

- `README.md` – Project overview (this file)
- `controls-checklist.md` – Assessment of technical, administrative, and physical controls
- `compliance-checklist.md` – PCI DSS, GDPR, and SOC best‑practice review
- `recommendations.md` – Prioritized remediation plan and summary for stakeholders

## Scenario summary

Botium Toys is a small U.S.‑based toy company with:
- One physical office / storefront / warehouse
- A growing online presence with U.S. and international customers
- An internal IT department that manages on‑prem equipment, internal network, databases,
  e‑commerce platform, and legacy systems

The IT manager is concerned about:
- Asset management and visibility
- Compliance with **PCI DSS** (cardholder data) and **GDPR** (E.U. customers)
- Business continuity and disaster recovery
- Overall risk to customer data, operations, and reputation

The audit is scoped to **the entire security program**, including assets, controls, and
compliance practices managed by the IT department.

## High‑level findings

- Asset management and data classification are incomplete.
- Technical baseline is mixed: firewalls and antivirus are present, but there is **no IDS**,
  **no backups**, and **no encryption** for stored card data.
- Access control is weak: **no least‑privilege**, **no separation of duties**, and
  **no centralized password management system**.
- Disaster recovery planning is missing (no DR plan, no regular backups).
- Physical security is relatively strong (locks, CCTV, fire detection/prevention).

Detailed control and compliance results are documented in the checklist files.
