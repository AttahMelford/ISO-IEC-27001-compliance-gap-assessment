# ISO/IEC 27001:2022 Assessment Findings Report

## 1. Report Overview

**Organization:** Meridian Digital Services (fictional)  
**Assessment Type:** Simulated Annex A control gap assessment  
**Framework:** ISO/IEC 27001:2022  
**Controls Assessed:** 30 selected Annex A controls  
**Assessment Status:** Portfolio exercise — simulated findings

## 2. Assessment Objective

The objective was to assess the simulated implementation status of selected information security controls, document potential control gaps, identify evidence requirements, assign preliminary risk ratings, and recommend corrective actions.

This assessment is a learning and portfolio exercise. It is not an independent audit, a complete ISO/IEC 27001 conformity assessment, or a certification decision.

## 3. Assessment Approach

The assessment reviewed 30 selected controls across the organizational, people, physical, and technological control categories.

For each selected control, the assessment records its objective, implementation status, evidence description, identified gap, proposed risk rating, recommendation, suggested control owner, target timeline, and preliminary NIST CSF 2.0 mapping.

The detailed results are maintained in `assessment/iso27001_gap_assessment.csv`. The assessment methodology and status definitions are documented in `docs/assessment-methodology.md`.

## 4. Key Findings

### 4.1 Asset Management

**Related control:** A.5.9 — Inventory of information and other associated assets

The simulated assessment identified a need to establish more complete and consistently maintained records of information assets and cloud services.

**Recommended action:** Maintain an inventory with assigned owners and a defined review process.

### 4.2 Identity and Access Management

**Related controls:** A.5.15 — Access control; A.5.18 — Access rights; A.8.2 — Privileged access rights; A.8.5 — Secure authentication

The assessment identified gaps in access-control documentation, access review evidence, privileged access management, and authentication practices.

**Recommended action:** Standardize access-control requirements, periodically review access rights, restrict privileged access, and validate authentication safeguards.

### 4.3 Supplier and Cloud Security

**Related controls:** A.5.19 — Information security in supplier relationships; A.5.20 — Addressing information security within supplier agreements; A.5.23 — Information security for use of cloud services

Supplier security assessments, contractual security requirements, and documentation of cloud security responsibilities require more consistent management.

**Recommended action:** Establish a repeatable supplier security review process, document relevant contractual requirements, and clarify cloud security responsibilities.

### 4.4 Incident Response and Business Continuity

**Related controls:** A.5.24 — Information security incident management planning and preparation; A.5.30 — ICT readiness for business continuity

The simulated assessment identified a need for stronger evidence of incident response preparation and ICT recovery readiness.

**Recommended action:** Maintain incident response procedures, document exercises, and test relevant recovery arrangements.

### 4.5 Vulnerability Management and Technical Security

**Related controls:** A.8.8 — Management of technical vulnerabilities; A.8.9 — Configuration management; A.8.15 — Logging; A.8.16 — Monitoring activities; A.8.25 — Secure development life cycle; A.8.32 — Change management

The assessment identified improvement opportunities involving vulnerability remediation records, configuration baselines, logging, monitoring, secure development practices, and change approval and testing.

**Recommended action:** Define repeatable technical security procedures and retain records demonstrating that required activities have been performed and reviewed.

### 4.6 Controls Requiring Further Evidence

Three selected controls are marked **Not Verified** in the gap assessment:

| Control ID | Control | Evidence Need |
|---|---|---|
| A.7.4 | Physical security monitoring | Obtain and review relevant monitoring records and supporting procedures. |
| A.8.13 | Information backup | Obtain backup records and evidence of restoration testing. |
| A.8.24 | Use of cryptography | Obtain documentation showing relevant cryptographic requirements and implementation. |

These statuses indicate that the available simulated information is insufficient to confirm implementation. They do not establish that the controls are absent or ineffective.

The evidence tracking matrix identifies proposed evidence requests and follow-up requirements. The requests have not yet been received or validated.

## 5. Implementation Status Interpretation

The assessment uses four implementation statuses:

- **Implemented:** Available and sufficient evidence supports that the control is implemented.
- **Partially Implemented:** Available information indicates that some control activities exist, but deficiencies remain.
- **Not Implemented:** The assessment scenario indicates that the control has not been implemented.
- **Not Verified:** Available information is insufficient to determine implementation status.

Most selected controls are recorded as Partially Implemented. This reflects the simulated assessment results and should not be interpreted as a conclusion about a real organization.

## 6. Risk Ratings and Remediation Priorities

The gap assessment assigns proposed High, Medium, or Low risk ratings. These ratings are preliminary qualitative judgments based on the simulated scenario, potential impact, likelihood, existing safeguards, and urgency.

The remediation plan proposes actions, suggested owners, and target timelines. These are recommendations, not approved management commitments.

Recommended management actions are:

1. Review the findings with relevant control owners and validate the proposed risk ratings.
2. Prioritize high-risk gaps and determine appropriate treatment actions.
3. Assign accountable owners and approve realistic remediation deadlines.
4. Obtain and review additional evidence for controls marked Not Verified.
5. Track corrective actions through implementation and validation.
6. Document any formally approved risk acceptance.
7. Review the Statement of Applicability (SoA) to ensure that applicability decisions and implementation statuses are consistent with the assessment.

## 7. Supporting Deliverables

- `docs/assessment-scope.md` — assessment boundaries and objectives.
- `docs/assessment-methodology.md` — assessment approach, evidence criteria, and status definitions.
- `docs/selected-controls.md` — list of selected Annex A controls.
- `assessment/iso27001_gap_assessment.csv` — detailed control assessment and proposed risk ratings.
- `assessment/statement_of_applicability.csv` — selected-control applicability and preliminary treatment decisions.
- `assessment/evidence_tracking_matrix.csv` — proposed evidence requests and follow-up tracking.
- `assessment/nist_csf_mapping.csv` — preliminary cross-framework mappings.
- `docs/remediation-plan.md` — proposed remediation actions, priorities, and validation procedures.
- `docs/executive-summary.md` — high-level summary of the assessment and its limitations.

## 8. Limitations

This report describes a simulated assessment of Meridian Digital Services, a fictional organization. The findings are based on constructed scenarios and sample evidence descriptions, not on independent testing of a real organization's systems or validated organizational records.

The project covers 30 selected Annex A controls rather than the complete set of Annex A controls. Applicability decisions, implementation statuses, risk ratings, and remediation recommendations are illustrative and require validation before use in real organizational decisions.

Evidence validation, management review, confirmation of provisional cross-document references, and final quality assurance remain outstanding. The report does not establish ISO/IEC 27001 conformity or certification readiness.
