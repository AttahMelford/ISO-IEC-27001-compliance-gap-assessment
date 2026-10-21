# ISO 27001:2022 Remediation Plan

## 1. Purpose

This remediation plan defines how gaps identified during the simulated ISO 27001:2022 assessment will be prioritized, assigned, addressed, and tracked for Meridian Digital Services.

The plan is based on the findings documented in `assessment/iso27001_gap_assessment.csv`.

## 2. Remediation Priorities

| Priority | Criteria | Target Timeline |
|---|---|---|
| Critical | Severe exposure requiring immediate attention | Immediate escalation and action plan |
| High | Significant security weakness or risk to sensitive information | Within 30 days |
| Medium | Control weakness requiring corrective action | Within 60 days |
| Low | Limited-impact improvement | Within 90 days |

These timelines are proposed project targets, not verified company requirements. Actual deadlines should be approved by management based on risk, resources, and business needs.

## 3. Key Remediation Actions

| Finding | Recommended Action | Suggested Owner | Priority | Target |
|---|---|---|---|---|
| Incomplete information asset inventory | Identify missing cloud services and data assets and update the inventory | IT Operations Manager | High | 30 days |
| Inconsistent access control | Standardize access control requirements across applications | IT Operations Manager | High | 30 days |
| Incomplete access reviews | Establish periodic reviews for critical applications | IT Operations Manager | High | 30 days |
| Supplier security assessment gaps | Implement documented, risk-based supplier assessments | Vendor Risk Manager | High | 60 days |
| Incomplete incident response testing | Conduct a tabletop exercise and document lessons learned | Security Manager | High | 30 days |
| Incomplete vulnerability remediation evidence | Define remediation timelines and track vulnerabilities through closure | Security Analyst | High | 30 days |
| Inconsistent multifactor authentication | Review coverage and enforce MFA where appropriate | IT Operations Manager | High | 30 days |
| Backup restoration testing not verified | Obtain backup records and conduct documented restoration tests | IT Operations Manager | High | 30 days |
| Logging and monitoring gaps | Define logging requirements, retention periods, monitoring coverage, and alert review procedures | Security Analyst | High | 45 days |
| Secure development gaps | Incorporate security requirements and testing checkpoints into development processes | Development Manager | Medium | 60 days |

The actions above are a selected set of proposed improvements, not an exhaustive list of all assessment findings.

## 4. Remediation Workflow

1. Validate the finding and supporting evidence.
2. Confirm the risk rating and business impact.
3. Assign an accountable control owner.
4. Agree on the corrective action and target date.
5. Record progress and supporting evidence.
6. Retest the control after remediation.
7. Document closure or obtain formal risk acceptance where appropriate.

## 5. Progress Tracking

Recommended status values:

- **Open:** Action identified but work has not started.
- **In Progress:** Corrective action is underway.
- **Pending Validation:** Work is reported complete but evidence needs review.
- **Closed:** The action has been validated and closure documented.
- **Risk Accepted:** An authorized decision-maker has formally accepted the residual risk.

## 6. Validation Requirements

A remediation action should not be closed solely because an owner reports completion. The reviewer should examine supporting evidence, confirm that the corrective action addresses the original gap, and record the validation outcome.

## 7. Limitations

This plan is based on a fictional organization and simulated assessment findings. It does not represent an actual audit, an independent verification of controls, or an ISO 27001 certification decision.
