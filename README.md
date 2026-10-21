# ISO/IEC 27001:2022 Compliance Gap Assessment

A simulated Governance, Risk, and Compliance (GRC) portfolio project assessing 30 selected ISO/IEC 27001:2022 Annex A controls for a fictional organization.

## Project Overview

**Organization:** Meridian Digital Services  
**Industry:** Software and IT Services  
**Primary Framework:** ISO/IEC 27001:2022  
**Cross-Framework Mapping:** NIST Cybersecurity Framework (CSF) 2.0  
**Project Type:** Simulated compliance gap assessment

This project demonstrates a structured approach to assessing information security controls, documenting potential gaps, tracking evidence requests, evaluating control applicability, and recommending remediation activities.

All findings and evidence descriptions are simulated for educational and portfolio purposes. No real organization's controls were audited.

## Project Objectives

- Assess 30 selected Annex A controls across organizational, people, physical, and technological categories.
- Document implementation statuses, identified gaps, and proposed risk ratings.
- Develop a Statement of Applicability (SoA) excerpt for the selected controls.
- Track evidence requests and outstanding validation activities.
- Map selected ISO/IEC 27001 controls to relevant NIST CSF 2.0 outcomes.
- Recommend corrective actions with suggested owners and target timelines.
- Present findings in a report structured for management review.

## Tools and Frameworks

- **ISO/IEC 27001:2022:** Information security management system standard.
- **NIST CSF 2.0:** Framework used for preliminary cross-framework mapping.
- **CSV:** Structured assessment, SoA, evidence tracking, and mapping records.
- **Markdown:** Project documentation, methodology, and reporting.
- **GitHub:** Version control and portfolio presentation.

## Repository Structure

| File | Purpose |
|---|---|
| [`assessment/iso27001_gap_assessment.csv`](assessment/iso27001_gap_assessment.csv) | Detailed assessment of 30 selected controls |
| [`assessment/statement_of_applicability.csv`](assessment/statement_of_applicability.csv) | Applicability decisions, justifications, and preliminary treatment decisions |
| [`assessment/evidence_tracking_matrix.csv`](assessment/evidence_tracking_matrix.csv) | Proposed evidence requests and follow-up tracking |
| [`assessment/nist_csf_mapping.csv`](assessment/nist_csf_mapping.csv) | Preliminary ISO 27001 to NIST CSF 2.0 mapping |
| [`docs/assessment-scope.md`](docs/assessment-scope.md) | Assessment boundaries and objectives |
| [`docs/assessment-methodology.md`](docs/assessment-methodology.md) | Assessment approach, evidence criteria, and status definitions |
| [`docs/selected-controls.md`](docs/selected-controls.md) | List of selected Annex A controls |
| [`docs/remediation-plan.md`](docs/remediation-plan.md) | Proposed corrective actions, priorities, and validation |
| [`docs/executive-summary.md`](docs/executive-summary.md) | Executive-level project summary |
| [`reports/assessment-findings.md`](reports/assessment-findings.md) | Detailed findings and recommendations |
| [`evidence/evidence-register-guide.md`](evidence/evidence-register-guide.md) | Guidance for tracking assessment evidence |

## Assessment Statuses

| Status | Meaning |
|---|---|
| Implemented | Available and sufficient evidence supports implementation. |
| Partially Implemented | Some control activities exist, but deficiencies remain. |
| Not Implemented | The assessment scenario indicates that the control has not been implemented. |
| Not Verified | Available information is insufficient to determine implementation status. |

A Not Verified status does not automatically mean a control is absent or ineffective. Further evidence or testing may be required.

## Key Findings

The simulated assessment identified improvement opportunities involving:

- Asset inventory and ownership.
- Access control, access reviews, privileged access, and authentication.
- Supplier security and cloud service responsibilities.
- Incident response preparation and business continuity.
- Vulnerability management, configuration management, logging, monitoring, and secure development.

Three controls are currently marked **Not Verified**:

| Control | Area |
|---|---|
| A.7.4 | Physical security monitoring |
| A.8.13 | Information backup |
| A.8.24 | Use of cryptography |

Additional evidence is needed before implementation can be confirmed for these controls. Evidence requests have been documented, but the requested evidence has not yet been received and validated.

## Key Deliverables

1. A structured assessment of 30 selected ISO/IEC 27001:2022 Annex A controls.
2. A selected-control SoA excerpt with applicability justifications and preliminary treatment decisions.
3. An evidence tracking matrix for proposed evidence requests and follow-up.
4. A preliminary NIST CSF 2.0 cross-framework mapping.
5. A remediation plan with proposed actions, owners, and target timelines.
6. An assessment findings report and executive summary.

## Important Limitations

This is a simulated portfolio exercise based on a fictional organization. It is not a real audit, a verified assessment of an operating company, or evidence of ISO/IEC 27001 certification.

The project covers 30 selected Annex A controls, not the full set of 93 Annex A controls. Applicability decisions, implementation statuses, risk ratings, and remediation recommendations are illustrative. The NIST CSF mappings are preliminary relationships, not proof of equivalent requirements or compliance.

Evidence validation, management review, confirmation of provisional risk references, and final quality assurance remain outstanding.

## Project Status

**Status:** Core assessment deliverables drafted; evidence validation and final quality review remain outstanding.



