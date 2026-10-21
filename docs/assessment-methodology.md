# Assessment Methodology

## 1. Purpose and Scope

This project uses a simulated assessment approach to evaluate 30 selected controls from ISO/IEC 27001:2022 Annex A for Meridian Digital Services, a fictional software and IT services company.

The purpose is to identify potential control gaps, document implementation status, assess potential risks, and recommend corrective actions.

This is a portfolio exercise, not an assessment of an actual organization.

## 2. Assessment Approach

The assessment uses a structured, control-by-control review. Each selected control is evaluated against its intended security objective using the simulated scenario, available evidence descriptions, and identified gaps.

The assessment process consists of the following steps:

1. Select 30 ISO/IEC 27001:2022 Annex A controls relevant to the simulated organization.
2. Determine the preliminary applicability of each selected control.
3. Identify the evidence needed to assess each control.
4. Review the simulated evidence descriptions and record potential deficiencies.
5. Assign an implementation status and proposed risk rating.
6. Document the selected controls in the Statement of Applicability (SoA) excerpt.
7. Map selected ISO 27001 controls to relevant NIST Cybersecurity Framework (CSF) 2.0 categories.
8. Recommend remediation actions, suggested owners, and proposed target timelines.
9. Document findings and limitations in the assessment report.

## 3. Implementation Status Definitions

Each selected control is assigned one of the following statuses:

| Status | Definition |
|---|---|
| Implemented | Available and sufficient evidence supports that the control is implemented. |
| Partially Implemented | The available information indicates that the control is implemented in part, but deficiencies remain. |
| Not Implemented | The assessment scenario indicates that the control has not been implemented. |
| Not Verified | Available information is insufficient to determine whether the control has been implemented. |

A status of Not Verified does not automatically mean that a control is absent or ineffective. Additional evidence or testing may be needed before a conclusion can be reached.

## 4. Evidence Assessment

Evidence is considered based on its relevance to the control, completeness, consistency, and ability to support the assessment conclusion.

Examples of evidence types include:

- Approved policies and procedures.
- Information asset inventories.
- Access review records.
- Supplier security assessments and agreements.
- Incident response plans and exercise records.
- Vulnerability scan and remediation reports.
- Backup and restoration test records.
- Logging, monitoring, and configuration records.

The evidence tracking matrix records proposed evidence requests, relevant control IDs, suggested evidence owners, review status, and follow-up requirements.

Evidence listed in the gap assessment represents simulated evidence descriptions for this portfolio exercise. The evidence tracking matrix contains proposed requests that have not yet been received or validated. No claim is made that the listed evidence has been independently verified.

Missing or insufficient evidence is documented as a limitation or follow-up requirement rather than automatically treated as proof that a control does not exist.

## 5. Risk Rating Methodology

Identified gaps receive proposed qualitative risk ratings of High, Medium, or Low.

The assessment considers the following factors:

- **Likelihood:** The estimated possibility that a relevant threat could exploit the identified weakness.
- **Impact:** The potential effect on confidentiality, integrity, availability, business operations, or applicable obligations.
- **Existing safeguards:** Whether available information indicates that measures exist to reduce the risk.
- **Exposure and urgency:** The sensitivity of affected assets and the need for corrective action.

The ratings are preliminary judgments for this simulated assessment. They are not based on a validated quantitative risk model or confirmed operational data.

The organization would need to validate these ratings against its risk criteria, business context, and risk acceptance requirements before making actual treatment decisions.

## 6. Gap Prioritization and Remediation

Remediation recommendations are developed from the identified gaps and proposed risk ratings.

The remediation plan provides suggested actions, potential owners, and proposed target timelines. These are planning recommendations rather than approved organizational commitments.

The proposed priority targets are:

| Priority | Proposed Target |
|---|---|
| Critical | Immediate escalation and treatment planning |
| High | Within 30 days |
| Medium | Within 60 days |
| Low | Within 90 days |

Actual remediation deadlines should be agreed upon by authorized management based on risk, available resources, operational dependencies, and business needs.

A remediation action should be closed only after supporting evidence has been reviewed and the corrective action has been validated. Where a gap remains unresolved, the outcome should be documented, including any formally approved risk acceptance.

## 7. Framework Mapping

Selected ISO/IEC 27001:2022 Annex A controls are mapped to relevant NIST CSF 2.0 functions and categories.

Each mapping includes a rationale explaining the relationship between the control and the selected NIST CSF category.

These mappings are preliminary cross-framework relationships. They do not establish that the frameworks have identical requirements, that one control automatically satisfies another framework's outcome, or that a mapping demonstrates compliance.

The mappings should be reviewed against the relevant framework definitions and the organization's actual control objectives before being used for a formal assessment.

## 8. Assessment Deliverables

The methodology supports the following project deliverables:

- `assessment/iso27001_gap_assessment.csv` — selected controls, implementation statuses, simulated gaps, risk ratings, recommendations, owners, and target dates.
- `assessment/statement_of_applicability.csv` — selected-control applicability, implementation status, evidence references, and provisional treatment decisions.
- `assessment/evidence_tracking_matrix.csv` — proposed evidence requests and follow-up tracking.
- `assessment/nist_csf_mapping.csv` — preliminary ISO 27001 and NIST CSF 2.0 mappings.
- `docs/remediation-plan.md` — proposed remediation actions, priorities, and validation procedures.
- `reports/assessment-findings.md` — summary of the simulated assessment findings.
- `docs/executive-summary.md` — summary of the project scope, key findings, and limitations.

## 9. Limitations

This methodology supports a simulated GRC portfolio project based on a fictional organization. The assessment does not involve independent testing of a real organization's controls, validated organizational evidence, formal management approval, or an external certification audit.

The project covers 30 selected Annex A controls rather than all Annex A controls. Control applicability, implementation statuses, risk ratings, and remediation recommendations are illustrative and require validation before they could support real organizational decisions.

Evidence validation, review of provisional cross-document references, and final quality assurance remain outstanding.

