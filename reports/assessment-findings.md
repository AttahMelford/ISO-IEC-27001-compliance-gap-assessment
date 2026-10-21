# ISO 27001:2022 Assessment Findings Report

## 1. Report Overview

**Organization:** Meridian Digital Services (fictional)  
**Assessment Type:** Simulated ISO 27001:2022 Annex A control assessment  
**Framework:** ISO/IEC 27001:2022  
**Controls Assessed:** 30 selected Annex A controls  
**Assessment Status:** Portfolio exercise — simulated findings

## 2. Assessment Objective

The objective was to evaluate the simulated implementation status of selected information security controls, document potential gaps, identify areas requiring further evidence, and recommend corrective actions.

The assessment is a learning exercise. It is not an independent audit, a complete ISO 27001 conformity assessment, or a certification decision.

## 3. Assessment Approach

The assessment used a structured gap assessment covering organizational, people, physical, and technological controls.

Each selected control was documented with its assessment objective, implementation status, evidence reviewed, identified gap, risk rating, recommendation, suggested control owner, target date, and preliminary NIST CSF mapping.

The assessment records are maintained in `assessment/iso27001_gap_assessment.csv`.

## 4. Key Observations

The simulated assessment identified improvement opportunities in the following areas:

### Asset Management
The sample asset inventory did not establish that all cloud services and information assets were recorded. A more complete and regularly maintained inventory is recommended.

### Identity and Access Management
Access control requirements and access reviews were not consistently documented across applications. Privileged access and multifactor authentication also require further attention.

### Supplier and Cloud Security
Supplier security assessments, contractual security requirements, and cloud security responsibilities need more consistent documentation and review.

### Incident Response and Business Continuity
Incident response exercise records and recovery testing evidence were incomplete or unavailable. Testing should be documented to demonstrate preparedness and recovery capability.

### Vulnerability Management and Technical Security
The simulated evidence indicated gaps in vulnerability remediation records, secure configuration baselines, logging, monitoring, and secure development practices.

### Evidence and Assurance
For selected controls, available information was insufficient to verify implementation. These controls require additional evidence before their status can be confidently confirmed.

## 5. Implementation Status Interpretation

The assessment uses the following statuses:

- **Implemented:** Evidence supports that the control is implemented.
- **Partially Implemented:** Some control activities exist, but gaps remain.
- **Not Implemented:** The control has not been implemented.
- **Not Verified:** Available evidence is insufficient to determine implementation status.

A status of **Not Verified** does not automatically mean the control is absent. It means further evidence is needed.

## 6. Recommended Management Actions

1. Validate the findings and confirm risk ratings with relevant control owners.
2. Prioritize high-risk gaps involving assets, access, vulnerabilities, incident response, and recovery.
3. Assign accountable owners and approve realistic remediation deadlines.
4. Request and review additional evidence for controls marked Not Verified.
5. Track corrective actions through closure and retain validation records.
6. Review the Statement of Applicability to ensure applicability decisions and implementation statuses remain consistent with the assessment.

## 7. Supporting Deliverables

- `docs/assessment-scope.md` — assessment boundaries and objectives.
- `docs/assessment-methodology.md` — assessment approach and status definitions.
- `docs/selected-controls.md` — list of selected Annex A controls.
- `assessment/iso27001_gap_assessment.csv` — detailed control assessment.
- `assessment/statement_of_applicability.csv` — applicability decisions and treatment requirements.
- `assessment/evidence_tracking_matrix.csv` — evidence requests and review tracking.
- `assessment/nist_csf_mapping.csv` — preliminary ISO 27001 and NIST CSF mapping.
- `docs/remediation-plan.md` — proposed corrective actions and tracking approach.

## 8. Limitations

This report describes a simulated assessment of a fictional organization. The observations are based on constructed scenarios and sample evidence descriptions, not on access to a real company's systems or verified organizational records. The findings should not be interpreted as proof of actual control effectiveness or ISO 27001 certification readiness.
