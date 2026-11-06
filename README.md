# HealthTrail Hospital | PCI DSS Security & Compliance Assessment

**IT Audit | Governance, Risk & Compliance (GRC) | PCI DSS v4.0.1 | Network Security | Risk & Control Assessment**

## 1. Project Overview

This project presents a structured PCI DSS security and compliance assessment of HealthTrail Hospital's payment infrastructure, with particular emphasis on network segmentation, firewall configurations and Cardholder Data Environment (CDE) protection.

The assessment focused on identifying security control weaknesses, evaluating potential exposure pathways, assessing PCI DSS requirements and developing risk-based remediation recommendations to strengthen the protection of payment card information.

## 2. Organisation & Assessment Context

HealthTrail Hospital processes patient payments through reception-based payment terminals and an online patient portal.

The hospital's payment infrastructure requires appropriate network security controls to restrict unauthorised connectivity, protect cardholder data and maintain effective separation between payment processing systems and other operational networks.

The assessment considered how network connectivity, firewall configurations and insufficiently defined CDE boundaries could affect the security of payment processing operations.

## 3. Assessment Scope & PCI DSS Framework

The assessment focused on relevant requirements of **PCI DSS v4.0.1**, particularly:

- **Requirement 1:** Install and maintain network security controls.
- **Requirement 2:** Apply secure configurations to system components.
- **Requirement 11:** Test the security of systems and networks regularly.
- **Requirement 12:** Support information security through policies, governance and risk management.

Key assessment areas included:

- Identification and scoping of the Cardholder Data Environment.
- Network segmentation between payment systems and other hospital networks.
- Firewall-rule restrictions and network traffic permissions.
- Security risks arising from unnecessary connectivity.
- Supporting evidence required to evaluate control effectiveness.

## 4. Audit Methodology

### Scope Definition & Risk Identification

- Assessed the payment environment and relevant network connectivity.
- Identified potential exposure pathways between payment systems and other network segments.
- Considered the implications of unclear CDE boundaries for PCI DSS scope and security.

### Control Assessment

- Evaluated firewall-rule configurations against network access restriction principles.
- Considered whether connectivity was limited to necessary and authorised traffic.
- Identified areas requiring stronger network segmentation and firewall governance.
- Mapped relevant findings to PCI DSS requirements.

### Audit Evidence Evaluation

- Reviewed available network and firewall information.
- Identified documentation required to substantiate network security controls.
- Developed proposed audit procedures to evaluate segmentation and firewall restrictions.
- Distinguished identified control concerns from areas requiring further verification.

### Risk Assessment & Reporting

- Developed a Risk and Control Matrix (RCM).
- Documented three principal risk findings.
- Considered potential impacts on cardholder data security, PCI DSS compliance and hospital operations.
- Developed remediation recommendations and supporting evidence requirements.

## 5. Key Assessment Findings

| Assessment Area | Risk Identified | Recommended Action |
|---|---|---|
| CDE Scoping | Unclear payment environment boundaries may lead to incomplete identification of in-scope systems | Establish and maintain an accurate CDE inventory and network/data flow diagrams |
| Network Segmentation | Unnecessary connectivity may increase the exposure of payment processing systems | Implement and validate appropriate segmentation between payment and non-payment networks |
| Firewall Governance | Overly permissive or insufficiently justified firewall rules may permit unauthorised network communication | Review and restrict firewall rules, document business justification and periodically validate configurations |

## 6. Key Audit Insights

### PCI DSS Scope Must Be Clearly Defined

An accurate understanding of where cardholder data is stored, processed and transmitted is essential for determining which systems and controls fall within PCI DSS scope.

### Network Segmentation Requires Verification

Network segmentation cannot be considered effective solely because firewall rules or VLANs exist. The assessment must consider whether unnecessary communication paths are restricted and whether segmentation controls have been appropriately validated.

### Firewall Rules Require Business Justification

Firewall permissions should be assessed against legitimate operational requirements, approved source and destination relationships, and the principle of least privilege.

### Audit Conclusions Must Be Evidence-Based

Control effectiveness should be supported by appropriate documentation, configuration records and testing results. Where evidence is insufficient, additional verification is required before reaching a definitive conclusion.

## 7. Skills Demonstrated

- PCI DSS v4.0.1 framework interpretation
- IT Audit planning and scoping
- Cardholder Data Environment assessment
- Network segmentation and firewall control analysis
- Risk identification and control evaluation
- Risk and Control Matrix development
- Audit evidence requirements and testing procedures
- Security findings and remediation reporting
- Governance, Risk & Compliance analysis

## 8. Project Deliverable

**HealthTrail Hospital — PCI DSS Security & Compliance Assessment Report**

The accompanying report includes the assessment scope, PCI DSS control mapping, risk findings, Risk and Control Matrix, firewall-rule analysis, proposed audit procedures and remediation recommendations.

## 9. Assessment Basis

The assessment was developed using documented payment infrastructure information and representative firewall configurations. Conclusions and recommendations reflect the information available for evaluation, with further validation requirements identified where appropriate.
