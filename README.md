# ISO/IEC 27001:2022 Compliance Gap Assessment

A simulated Governance, Risk, and Compliance (GRC) portfolio project assessing 30 selected ISO/IEC 27001:2022 Annex A controls for a fictional software and IT services organization.

## Project Overview

- **Organization:** Meridian Digital Services
- **Industry:** Software and IT Services
- **Primary Framework:** ISO/IEC 27001:2022
- **Cross-Framework Mapping:** NIST Cybersecurity Framework (CSF) 2.0
- **Project Type:** Simulated compliance gap assessment
- **Assessment Scope:** 30 selected Annex A controls

This project demonstrates a structured approach to information security control assessment, risk identification, applicability decisions, evidence tracking, and remediation planning.

The assessment uses simulated organizational information to document potential control gaps, assign illustrative risk ratings, identify evidence requirements, and recommend corrective actions. It is designed to demonstrate practical GRC documentation and analysis skills.

All findings and evidence descriptions are simulated. No real organization's controls were audited, and this project does not establish ISO/IEC 27001 compliance or certification.

## Project Objectives

- Assess 30 selected Annex A controls across organizational, people, physical, and technological categories.
- Document control implementation statuses, potential gaps, and supporting evidence requirements.
- Develop a Statement of Applicability (SoA) excerpt with applicability justifications and preliminary treatment decisions.
- Identify and document 20 cybersecurity risks in a structured risk register.
- Calculate illustrative inherent and residual risk scores using a defined scoring methodology.
- Track proposed evidence requests, receipt status, and follow-up activities.
- Map selected ISO/IEC 27001 controls to relevant NIST CSF 2.0 outcomes.
- Develop a remediation plan with proposed actions, responsible roles, priorities, and target timelines.
- Present assessment results and recommendations in reports intended for management review.

## Tools and Frameworks

- **ISO/IEC 27001:2022:** Primary information security management standard used to organize the control assessment.
- **NIST CSF 2.0:** Used for preliminary cross-framework mapping.
- **CSV:** Used for structured assessment records, the risk register, the SoA, evidence tracking, and control mappings.
- **Markdown:** Used for project documentation, methodology, findings, and reporting.
- **GitHub:** Used for version control, documentation management, and portfolio presentation.

## Repository Structure

| File | Purpose |
|---|---|
| [`assessment/iso27001_gap_assessment.csv`](assessment/iso27001_gap_assessment.csv) | Assessment records for 30 selected Annex A controls |
| [`assessment/risk_register.csv`](assessment/risk_register.csv) | Register of 20 cybersecurity risks, including inherent and residual scores, risk owners, and treatment decisions |
| [`assessment/statement_of_applicability.csv`](assessment/statement_of_applicability.csv) | Selected-control applicability decisions, justifications, implementation statuses, and risk references |
| [`assessment/evidence_tracking_matrix.csv`](assessment/evidence_tracking_matrix.csv) | Proposed evidence requests, receipt status, and follow-up tracking |
| [`assessment/nist_csf_mapping.csv`](assessment/nist_csf_mapping.csv) | Preliminary mapping between selected ISO controls and NIST CSF 2.0 outcomes |
| [`docs/assessment-scope.md`](docs/assessment-scope.md) | Assessment boundaries, objectives, and scope limitations |
| [`docs/assessment-methodology.md`](docs/assessment-methodology.md) | Assessment approach, evidence criteria, and implementation-status definitions |
| [`docs/risk-scoring-methodology.md`](docs/risk-scoring-methodology.md) | Likelihood and impact scales, scoring formula, risk levels, and scoring limitations |
| [`docs/selected-controls.md`](docs/selected-controls.md) | List and description of the selected Annex A controls |
| [`docs/remediation-plan.md`](docs/remediation-plan.md) | Proposed corrective actions, priorities, owners, and target timelines |
| [`docs/executive-summary.md`](docs/executive-summary.md) | Executive-level summary of the simulated assessment |
| [`reports/assessment-findings.md`](reports/assessment-findings.md) | Detailed assessment findings and recommendations |
| [`evidence/evidence-register-guide.md`](evidence/evidence-register-guide.md) | Guidance for organizing and tracking assessment evidence |

## Assessment Status Definitions

| Status | Meaning |
|---|---|
| Implemented | Available and sufficient evidence supports implementation. |
| Partially Implemented | Some control activities exist, but deficiencies remain. |
| Not Implemented | The assessment scenario indicates that the control has not been implemented. |
| Not Verified | Available information is insufficient to determine implementation status. |

A **Not Verified** status does not automatically mean a control is absent or ineffective. Additional documentation, evidence review, or testing may be needed before a conclusion can be reached.

## Risk Assessment Approach

The risk register documents 20 simulated cybersecurity risks affecting business systems, information assets, users, suppliers, and technology processes.

Each risk record includes:

- Risk ID and title
- Affected asset or process
- Risk description, threat, and vulnerability
- Likelihood and impact ratings
- Inherent risk score and level
- Existing controls considered in the assessment
- Illustrative residual likelihood, impact, score, and level
- Risk owner and treatment decision
- Related ISO/IEC 27001 Annex A control references
- Risk status

Risk scores are calculated by multiplying likelihood by impact. The scoring methodology defines the rating scales and the thresholds used to classify risks.

Inherent risk represents risk before considering controls. Residual risk represents the estimated risk remaining after considering existing controls. Because this is a simulated assessment and control effectiveness has not been independently validated, residual scores are illustrative rather than verified measurements.

Planned remediation activities should not be treated as implemented controls until implementation and effectiveness have been supported by appropriate evidence.

## Key Assessment Findings

The simulated assessment identifies improvement opportunities in several information security areas:

- **Asset management:** Completing the inventory of information assets and associated cloud resources.
- **Access management:** Improving access restrictions, periodic access reviews, privileged access oversight, and secure authentication.
- **Supplier security:** Documenting supplier security assessments and reviewing security requirements in supplier agreements.
- **Cloud security:** Clarifying cloud security responsibilities and improving configuration management.
- **Incident response and continuity:** Strengthening incident response preparation and obtaining evidence of backup and restoration testing.
- **Vulnerability management:** Defining vulnerability remediation expectations and improving tracking.
- **Logging and monitoring:** Improving logging requirements, monitoring coverage, and review of security alerts.
- **Data protection:** Validating encryption and cryptographic key management practices.
- **Change management and secure development:** Improving change approval, testing, and integration of security activities into development.

Three selected controls are currently marked **Not Verified**:

| Control | Control Area | Evidence Needed |
|---|---|---|
| A.7.4 | Physical security monitoring | Evidence of monitoring coverage and relevant review activities |
| A.8.13 | Information backup | Backup records and evidence of restoration testing |
| A.8.24 | Use of cryptography | Evidence supporting encryption and cryptographic key management practices |

Evidence requests have been documented, but the requested evidence has not yet been received and validated. These statuses should remain provisional until sufficient evidence is available.

## Statement of Applicability

The project includes an SoA excerpt for the 30 selected controls. It records whether each control is applicable, the reason for its applicability, its current simulated implementation status, evidence references, related risk IDs, and whether treatment is required.

The SoA is a portfolio-level excerpt rather than a complete organizational SoA. Its applicability decisions and risk relationships are proposed for this simulated scenario and would require appropriate organizational review in a real assessment.

## NIST CSF 2.0 Mapping

The project includes a preliminary mapping between selected ISO/IEC 27001:2022 Annex A controls and relevant NIST CSF 2.0 outcomes.

The mapping is intended to demonstrate cross-framework analysis and help organize security activities. It is an informative relationship between selected controls and outcomes, not proof that the frameworks are equivalent or that the organization satisfies either framework.

## Key Deliverables

1. A structured gap assessment of 30 selected ISO/IEC 27001:2022 Annex A controls.
2. A risk register documenting 20 simulated cybersecurity risks.
3. A selected-control Statement of Applicability excerpt.
4. An evidence tracking matrix for proposed evidence requests and follow-up.
5. A preliminary ISO/IEC 27001 to NIST CSF 2.0 mapping.
6. A documented risk-scoring methodology.
7. A remediation plan with proposed actions, priorities, owners, and timelines.
8. An assessment findings report and executive summary.
9. Supporting scope, methodology, and evidence-register documentation.

## Important Limitations

This project is a simulated portfolio exercise based on a fictional organization. It is not a real audit, a verified assessment of an operating company, or evidence of ISO/IEC 27001 certification.

The assessment covers 30 selected Annex A controls rather than the complete set of 93 Annex A controls in ISO/IEC 27001:2022. It does not constitute a complete assessment of all requirements for an information security management system.

Implementation statuses, risk ratings, applicability decisions, control relationships, and remediation recommendations are illustrative. Risk scores and residual-risk estimates have not been validated against real organizational evidence. The NIST CSF 2.0 mappings are preliminary and do not demonstrate equivalent compliance.

Evidence validation, review of the proposed control-to-risk relationships, management review, and final quality assurance remain outstanding.

## Project Status

**Status:** Core assessment deliverables drafted. Evidence validation and final quality review remain outstanding.

This repository demonstrates a structured GRC assessment workflow, from control review and risk documentation through evidence tracking, cross-framework mapping, and remediation planning.



