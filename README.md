# Internal Security Audit - Botium Toys

## Overview
This repository contains documentation and findings from an internal security audit conducted for Botium Toys. The audit follows the **National Institute of Standards and Technology Cybersecurity Framework (NIST CSF)** to evaluate security controls, compliance, and risk management.

## Objectives
The primary objectives of this audit are:
- To assess the current security posture of Botium Toys.
- To identify and mitigate potential risks, threats, and vulnerabilities.
- To ensure compliance with regulations for online payments and business operations in the EU.
- To provide recommendations for improving security controls.

## Scope
The audit covers:
1. **IT Assets Management** – Identifying and securing critical IT resources.
2. **Compliance with Standards** – Ensuring adherence to industry regulations.
3. **Risk Assessment** – Evaluating potential cybersecurity threats.
4. **Security Controls** – Verifying implementation of security measures.
5. **Incident Response** – Reviewing the effectiveness of response plans.

## Supporting Materials
This repository includes the following documents:
- **Scope, Goals, and Risk Assessment Report** – A detailed analysis of security risks.
- **Controls and Compliance Checklist** – A structured assessment based on security best practices.


## Methodology
The audit was conducted using the **NIST CSF** framework, focusing on the following control categories:
1. **Identify** – Asset management, risk assessment, and governance.
2. **Protect** – Access control, data security, and maintenance.
3. **Detect** – Continuous monitoring and threat detection.
4. **Respond** – Incident response planning and execution.
5. **Recover** – Business continuity and disaster recovery.

## Findings and Recommendations
### Key Findings:
- **Lack of Least Privilege Controls** – All employees currently have access to customer data, increasing the risk of a breach.
- **No Disaster Recovery Plan** – A structured disaster recovery plan is missing, posing a risk to business continuity.
- **Weak Password Policies** – Minimal password requirements increase the risk of unauthorized access.
- **No Intrusion Detection System (IDS)** – Without an IDS, the company lacks proactive threat monitoring.
- **No Encryption** – Customer financial and personal data are not encrypted, reducing confidentiality.
- **Lack of Access Controls** – No password management system or separation of duties in place.
- **Use of Legacy Systems** – Legacy systems are in use but lack scheduled maintenance and clear intervention policies.

### Recommendations:
- Implement **Least Privilege** by restricting employee access to customer data.
- Develop and enforce a **Disaster Recovery Plan** to ensure business continuity.
- Strengthen **Password Policies** and introduce a **Password Management System**.
- Deploy an **Intrusion Detection System (IDS)** for proactive security monitoring.
- Apply **Data Encryption Standards** to protect customer financial and personal information.
- Enforce **Separation of Duties** to prevent unauthorized data access.
- Establish a **Regular Maintenance Schedule for Legacy Systems** with clear intervention procedures.

## Controls and Compliance Checklist
A detailed **Controls and Compliance Checklist** was completed as part of this audit. The checklist evaluates security measures across multiple domains, ensuring compliance with industry standards and best practices.

### Compliance Findings:
- **PCI DSS Non-Compliance**: All employees currently have access to customer credit card data, and encryption is not in place.
- **GDPR Gaps**: Customer data is not encrypted, and assets are not classified properly.
- **SOC Type 1 & 2 Deficiencies**: No access control policies, lack of encryption for sensitive data, and unrestricted data availability.

## How to Use This Repository
1. Review the **Scope, Goals, and Risk Assessment Report** and **Control Categories** for an overview.
2. Check the **Controls and Compliance Checklist** to understand security gaps.
3. Refer to **Findings and Recommendations** to apply security improvements.



