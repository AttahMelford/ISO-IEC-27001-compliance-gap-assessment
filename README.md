# ISO/IEC 27001:2022 Compliance Gap Assessment

A completed simulated Governance, Risk, and Compliance (GRC) portfolio project assessing 30 selected ISO/IEC 27001:2022 Annex A controls for a fictional software and IT services organization.

## Project Overview

- **Organization:** Meridian Digital Services
- **Industry:** Software and IT Services
- **Primary Framework:** ISO/IEC 27001:2022
- **Cross-Framework Mapping:** NIST Cybersecurity Framework (CSF) 2.0
- **Project Type:** Simulated compliance gap assessment
- **Assessment Scope:** 30 selected Annex A controls

This project involved conducting a structured information security control assessment, identifying potential risks and control gaps, documenting applicability decisions, tracking evidence requirements, and developing remediation recommendations.

Using simulated organizational information, I documented control implementation statuses, assigned illustrative risk ratings, identified evidence requirements, and developed supporting GRC documentation.

All findings and evidence descriptions are simulated. No real organization's controls were audited, and this project does not establish ISO/IEC 27001 compliance or certification.

## Project Objectives

The project addressed the following objectives:

- Assessed 30 selected Annex A controls across organizational, people, physical, and technological categories.
- Documented control implementation statuses, potential gaps, and supporting evidence requirements.
- Developed a Statement of Applicability (SoA) excerpt with applicability justifications and preliminary treatment decisions.
- Identified and documented 20 cybersecurity risks in a structured risk register.
- Calculated illustrative inherent and residual risk scores using a defined scoring methodology.
- Documented proposed evidence requests, receipt status, and follow-up activities.
- Mapped selected ISO/IEC 27001 controls to relevant NIST CSF 2.0 outcomes.
- Developed a remediation plan with proposed actions, responsible roles, priorities, and target timelines.
- Prepared assessment findings and management-level recommendations.

## Tools and Frameworks

- **ISO/IEC 27001:2022:** Primary information security management standard used to organize the control assessment.
- **NIST CSF 2.0:** Used for preliminary cross-framework mapping.
- **CSV:** Used to maintain structured assessment records, the risk register, the SoA, evidence tracking, and control mappings.
- **Markdown:** Used to document the project methodology, findings, and reports.
- **GitHub:** Used for version control, documentation management, and portfolio presentation.

## Repository Structure

| File | Purpose |
|---|---|
| [`assessment/iso27001_gap_assessment.csv`](assessment/iso27001_gap_assessment.csv) | Assessment records for 30 selected Annex A controls |
| [`assessment/risk_register.csv`](assessment/risk_register.csv) | Register of 20 cybersecurity risks, including inherent and residual scores, risk owners, and treatment decisions |
| [`assessment/statement_of_applicability.csv`](assessment/statement_of_applicability.csv) | Selected-control applicability decisions, justifications, implementation statuses, and risk references |
| [`assessment/evidence_tracking_matrix.csv`](assessment/evidence_tracking_matrix.csv) | Evidence requests, receipt status, and follow-up tracking |
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

A **Not Verified** status does not automatically mean a control is absent or ineffective. Additional documentation, evidence review, or testing may be required before a conclusion can be reached.

## Risk Assessment Approach

The project included a risk register documenting 20 simulated cybersecurity risks affecting business systems, information assets, users, suppliers, and technology processes.

Each risk record included:

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

Risk scores were calculated by multiplying likelihood by impact. The scoring methodology defined the rating scales and thresholds used to classify risks.

Inherent risk represented risk before considering controls. Residual risk represented the estimated risk remaining after considering existing controls.

Because this was a simulated assessment and control effectiveness was not independently validated, residual scores were treated as illustrative rather than verified measurements.

The remediation plan documented proposed corrective actions. These recommendations were not treated as implemented controls without supporting evidence.

## Key Assessment Findings

The simulated assessment identified improvement opportunities in several information security areas:

- **Asset management:** Completing the inventory of information assets and associated cloud resources.
- **Access management:** Improving access restrictions, periodic access reviews, privileged access oversight, and secure authentication.
- **Supplier security:** Documenting supplier security assessments and reviewing security requirements in supplier agreements.
- **Cloud security:** Clarifying cloud security responsibilities and improving configuration management.
- **Incident response and continuity:** Strengthening incident response preparation and obtaining evidence of backup and restoration testing.
- **Vulnerability management:** Defining vulnerability remediation expectations and improving tracking.
- **Logging and monitoring:** Improving logging requirements, monitoring coverage, and review of security alerts.
- **Data protection:** Validating encryption and cryptographic key management practices.
- **Change management and secure development:** Improving change approval, testing, and integration of security activities into development.

Three selected controls were classified as **Not Verified**:

| Control | Control Area | Evidence Needed |
|---|---|---|
| A.7.4 | Physical security monitoring | Evidence of monitoring coverage and relevant review activities |
| A.8.13 | Information backup | Backup records and evidence of restoration testing |
| A.8.24 | Use of cryptography | Evidence supporting encryption and cryptographic key management practices |

The evidence tracking matrix documented the related evidence requests and their receipt status. These control statuses remained provisional because the requested evidence had not been received and validated within the simulated assessment.

## Statement of Applicability

The project included a Statement of Applicability (SoA) excerpt covering the 30 selected controls.

The SoA documented:

- Whether each control was applicable.
- The justification for its applicability.
- Its simulated implementation status.
- Supporting evidence references.
- Related risk IDs.
- Whether treatment was required.

The completed SoA is a portfolio-level excerpt rather than a complete organizational SoA. Its applicability decisions and risk relationships were developed for the fictional scenario and would require organizational review in a real assessment.

## NIST CSF 2.0 Mapping

A preliminary mapping was completed between selected ISO/IEC 27001:2022 Annex A controls and relevant NIST CSF 2.0 outcomes.

This mapping demonstrated cross-framework analysis and provided a structured way to relate information security controls to cybersecurity outcomes.

The mapping represents informative relationships between selected controls and outcomes. It does not establish that the frameworks are equivalent or that the organization satisfies either framework.

## Key Deliverables

The project produced the following deliverables:

1. A structured gap assessment of 30 selected ISO/IEC 27001:2022 Annex A controls.
2. A risk register documenting 20 simulated cybersecurity risks.
3. A selected-control Statement of Applicability excerpt.
4. An evidence tracking matrix documenting evidence requests and follow-up.
5. A preliminary ISO/IEC 27001 to NIST CSF 2.0 mapping.
6. A documented risk-scoring methodology.
7. A remediation plan with proposed actions, priorities, owners, and timelines.
8. An assessment findings report and executive summary.
9. Supporting scope, methodology, and evidence-register documentation.

## Important Limitations

This project was completed as a simulated portfolio exercise based on a fictional organization. It was not a real audit, a verified assessment of an operating company, or evidence of ISO/IEC 27001 certification.

The assessment covered 30 selected Annex A controls rather than the complete set of 93 Annex A controls in ISO/IEC 27001:2022. It did not constitute a complete assessment of all requirements for an information security management system.

Implementation statuses, risk ratings, applicability decisions, control relationships, and remediation recommendations were illustrative. Risk scores and residual-risk estimates were not validated against real organizational evidence. The NIST CSF 2.0 mappings were preliminary and did not demonstrate equivalent compliance.

Evidence validation and management review would be necessary before applying these assessment conclusions to a real organization.

## Project Status

**Status: Completed — Portfolio Project**

The project deliverables and supporting documentation were prepared and organized in GitHub. The completed work demonstrates a structured GRC assessment workflow covering control assessment, risk identification, Statement of Applicability development, evidence tracking, cross-framework mapping, and remediation planning.

