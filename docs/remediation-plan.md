# ISO 27001:2022 Remediation Plan

## 1. Purpose

This remediation plan defines how gaps identified during the simulated ISO/IEC 27001:2022 assessment will be prioritized, assigned, addressed, and tracked for Meridian Digital Services, a fictional software and IT services company.

The plan is based on the findings documented in `assessment/iso27001_gap_assessment.csv`. It provides proposed corrective actions, suggested owners, target timelines, and validation requirements.

This is a proposed remediation plan. Actions, owners, and timelines have not been approved or implemented by an actual organization.

## 2. Remediation Priorities

| Priority | Criteria | Proposed Target |
|---|---|---|
| Critical | Severe exposure requiring immediate management attention | Immediate escalation and treatment planning |
| High | Significant security weakness or potential risk to sensitive information | Within 30 days |
| Medium | Control weakness requiring corrective action | Within 60 days |
| Low | Limited-impact improvement opportunity | Within 90 days |

These are proposed project targets, not verified company requirements. Management should approve actual deadlines based on risk, business impact, available resources, and operational needs.

The target is to complete remediation or establish an approved treatment plan within the proposed period. Some technical changes may require additional time, testing, or formal risk acceptance.

## 3. Key Remediation Actions

The following actions address selected findings from the gap assessment. They are not an exhaustive list of all identified gaps.

| Finding | Recommended Action | Suggested Owner | Priority | Proposed Target |
|---|---|---|---|---|
| Incomplete information security policy approval and review records | Establish documented policy ownership, approval, and periodic review procedures | Security Manager | Medium | 30 days |
| Incomplete threat intelligence review process | Establish a process for reviewing relevant threat intelligence and documenting decisions and actions | Security Analyst | Medium | 60 days |
| Incomplete information asset inventory | Identify missing cloud services and data assets and update the inventory | IT Operations Manager | High | 30 days |
| Inconsistent access control requirements | Standardize access control requirements across applications and document implementation expectations | IT Operations Manager | High | 30 days |
| Incomplete access reviews | Establish periodic access reviews for critical applications and retain review records | IT Operations Manager | High | 30 days |
| Supplier security assessment gaps | Implement documented, risk-based supplier security assessments | Vendor Risk Manager | High | 60 days |
| Incomplete supplier security clauses | Review supplier agreements and define appropriate information security requirements | Legal and Compliance Manager | Medium | 60 days |
| Incomplete cloud security responsibilities | Document cloud security responsibilities and establish periodic configuration and risk reviews | Cloud Operations Manager | High | 45 days |
| Incident response exercise evidence unavailable | Conduct a tabletop exercise, document results, and track lessons learned | Security Manager | High | 30 days |
| Incomplete ICT recovery testing | Define recovery objectives and conduct documented recovery tests | IT Operations Manager | High | 60 days |
| Inconsistent personnel screening documentation | Define role-based screening requirements consistent with applicable law and retain appropriate records | Human Resources Manager | Medium | 60 days |
| Incomplete security awareness training records | Implement periodic awareness training and track completion | Human Resources Manager | Medium | 30 days |
| Incomplete employee transfer and termination access records | Establish a documented process for reviewing and removing access when employment or responsibilities change | Human Resources Manager | High | 30 days |
| Incomplete remote working security guidance | Update remote working requirements and communicate them to personnel | Security Manager | Medium | 60 days |
| Incomplete security event reporting guidance | Publish reporting instructions and provide employee awareness guidance | Security Manager | Medium | 45 days |
| Physical security boundaries not fully documented | Document protected areas and review physical access requirements | Facilities Manager | Medium | 60 days |
| Incomplete visitor authorization records | Standardize visitor authorization, entry logging, and record retention | Facilities Manager | Medium | 45 days |
| Physical security monitoring not verified | Review monitoring coverage and obtain evidence to assess implementation | Facilities Manager | Medium | 60 days |
| Inconsistent clear desk and clear screen practices | Communicate requirements and conduct periodic compliance checks | Facilities Manager | Low | 60 days |
| Incomplete equipment protection requirements | Document equipment siting and protection requirements and review implementation | IT Operations Manager | Medium | 60 days |
| Incomplete privileged access reviews | Review privileged accounts, validate business justification, and document approval and periodic review | IT Operations Manager | High | 30 days |
| Inconsistent multifactor authentication coverage | Review MFA coverage and enforce MFA for appropriate accounts and applications | IT Operations Manager | High | 30 days |
| Vulnerability remediation evidence incomplete | Define remediation timelines, track corrective actions, and retain closure evidence | Security Analyst | High | 30 days |
| Secure configuration baselines incomplete | Define approved configuration baselines for critical systems and review deviations | IT Operations Manager | Medium | 60 days |
| Backup restoration testing not verified | Obtain backup records and conduct documented restoration tests | IT Operations Manager | High | 30 days |
| Inconsistent logging and retention requirements | Define logging requirements, retention periods, and review procedures | Security Analyst | High | 45 days |
| Incomplete monitoring coverage and alert review records | Define monitoring coverage and document alert review procedures | Security Analyst | High | 45 days |
| Cryptographic controls not verified | Validate encryption coverage, cryptographic requirements, and key management practices; document supporting evidence | Security Manager | High | 60 days |
| Secure development practices not consistently documented | Integrate security requirements and testing checkpoints into development processes | Development Manager | Medium | 60 days |
| Incomplete change approval and testing evidence | Standardize change approvals, testing, and implementation records | IT Operations Manager | Medium | 45 days |

**Timeline note:** The proposed targets above are planning targets. Where a target differs from the target recorded in the gap assessment, the discrepancy should be reconciled during management review before the remediation plan is approved.

## 4. Remediation Workflow

Each remediation action should follow a documented process:

1. **Validate the finding:** Review available evidence and confirm that the gap is accurately described.
2. **Assess risk:** Confirm the risk rating, affected assets, business impact, and potential consequences.
3. **Assign ownership:** Identify an accountable owner responsible for coordinating the corrective action.
4. **Define the treatment:** Document the planned action, required resources, dependencies, and proposed target date.
5. **Track progress:** Record status updates, delays, decisions, and supporting evidence.
6. **Validate remediation:** Review evidence and test whether the corrective action addresses the original gap.
7. **Document the outcome:** Record closure, remaining issues, or formally approved risk acceptance.

## 5. Progress Tracking

The following status values are recommended for tracking remediation actions:

| Status | Definition |
|---|---|
| Open | The action has been identified but work has not started |
| In Progress | Corrective work is underway |
| Pending Validation | The owner reports completion, but supporting evidence or testing is awaiting review |
| Closed | The corrective action has been validated and closure documented |
| Risk Accepted | An authorized decision-maker has formally accepted the residual risk |

A reported completion should not automatically change an action to Closed. Closure requires documented validation by an appropriate reviewer.

## 6. Validation Requirements

Remediation validation should establish whether the action addresses the original finding and whether the revised control is operating as intended.

Depending on the control, validation may include:

- Reviewing approved policies and procedures.
- Inspecting access review and account management records.
- Examining supplier assessments and contractual requirements.
- Reviewing vulnerability remediation and change management records.
- Inspecting backup restoration test results.
- Reviewing logging, monitoring, and alert handling evidence.
- Checking encryption and key management configurations.
- Examining security training records and incident response exercise results.

The reviewer should document the evidence examined, the validation outcome, any remaining gaps, and the closure decision.

## 7. Risk Acceptance and Escalation

If a remediation action cannot be completed within its target period, the owner should document the reason, remaining exposure, interim safeguards, and a revised target date.

Any decision to accept residual risk should be documented and approved by an authorized decision-maker. Risk acceptance should not be treated as equivalent to remediation or successful control implementation.

Critical or urgent risks should be escalated promptly for management review. No critical finding is assumed to have been identified in this simulated assessment solely because a Critical priority category is defined in this plan.

## 8. Supporting Project Documents

This plan should be used alongside the following project files:

- `assessment/iso27001_gap_assessment.csv` — records the selected controls, simulated findings, risk ratings, and recommendations.
- `assessment/statement_of_applicability.csv` — records control applicability, implementation status, and provisional treatment decisions.
- `assessment/evidence_tracking_matrix.csv` — tracks proposed evidence requests and their review status.
- `assessment/nist_csf_mapping.csv` — documents preliminary mappings between selected ISO 27001 controls and NIST CSF 2.0 categories.
- `reports/assessment-findings.md` — summarizes the simulated assessment findings.

## 9. Limitations

This plan is based on a fictional organization and simulated assessment findings. It does not represent an actual audit, independent verification of organizational controls, management approval, or an ISO 27001 certification decision.

The project covers selected Annex A controls rather than every Annex A control. Evidence validation, management review, and final cross-document quality review remain outstanding.

