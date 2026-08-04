# AI Use Risk Classification Guide

Use this guide to classify AI-supported marketing activities as low, moderate, or high risk before data is entered, content is generated, automation is activated, or customer-facing action occurs.

This guide is part of the **Brand Voice AI** methodology developed by **John M. Pogue** and **Pogue Digital Solutions, LLC**.

> Risk classification is not a label applied after the workflow is built. It is the gate that determines whether the workflow should exist, what controls it needs, and where human judgment must remain firmly in charge.

---

## Guide Purpose

The AI Use Risk Classification Guide helps organizations:

- Identify the exact AI-supported activity
- Define the business purpose
- Identify the people affected
- Review audience vulnerability
- Review data sensitivity
- Review claim sensitivity
- Review automation level
- Review scale
- Review reversibility
- Review possible harm
- Classify activities as low, moderate, or high risk
- Define required controls
- Define prohibited conditions
- Assign reviewers
- Assign approvers
- Assign monitoring owners
- Define escalation paths
- Define stop conditions
- Reclassify risk when conditions change
- Document decisions
- Preserve approval records
- Use AI for preliminary assessment without allowing it to approve itself
- Pause or retire unsafe practices

This guide may be used for:

- Content generation
- Content editing
- Customer research
- Market research
- Personalization
- Email marketing
- Social-media publishing
- Advertising
- Lead generation
- Customer segmentation
- Lead scoring
- Recommendation systems
- Customer support
- Sales enablement
- Synthetic media
- AI agents
- Custom GPTs
- Retrieval systems
- Marketing automation
- Analytics
- Reporting
- Predictive models
- Customer-facing assistants

---

# Risk Classification Overview

```text
Define the activity
        ↓
Define the people affected
        ↓
Review data, claims, automation, scale, reversibility, and harm
        ↓
Identify existing controls
        ↓
Assign preliminary risk level
        ↓
Apply required safeguards
        ↓
Human review
        ↓
Human approval
        ↓
Activate and monitor
        ↓
Reclassify, pause, correct, or retire
```

---

# Risk Classification Record

## 1. Activity Information

| Field | Information |
|---|---|
| Activity name | [Enter name] |
| Business purpose | [Describe purpose] |
| Marketing function | [Enter function] |
| Primary audience | [Describe audience] |
| People directly affected | [Describe] |
| People indirectly affected | [Describe] |
| AI tool or model | [Enter tool] |
| Data sources | [List sources] |
| Automation level | Assistive / Recommendatory / Conditional / Autonomous |
| Output type | [Describe output] |
| Customer-facing | Yes / No |
| Publication or activation channel | [Enter channel] |
| Activity owner | [Enter name] |
| Privacy reviewer | [Enter name] |
| Subject-matter reviewer | [Enter name] |
| Bias reviewer | [Enter name] |
| Accessibility reviewer | [Enter name] |
| Final approver | [Enter name and role] |
| Current version | [Enter version] |
| Current risk level | Low / Moderate / High / Prohibited |
| Status | Proposed / Review / Approved / Active / Paused / Retired |

---

## 2. Classification Decision

Select one:

- [ ] Low risk
- [ ] Moderate risk
- [ ] High risk
- [ ] Prohibited
- [ ] Additional information required
- [ ] Specialist review required
- [ ] Privacy review required
- [ ] Legal or compliance review required
- [ ] Bias review required
- [ ] Accessibility review required
- [ ] Automation reduction required
- [ ] Pause
- [ ] Retire

### Decision Summary

[Explain.]

### Required Controls

- [Control]
- [Control]
- [Control]

### Stop Conditions

- [Condition]
- [Condition]
- [Condition]

---

# Phase One: Define the Activity

## 3. Activity Description

Use:

```text
The AI-supported activity will:
[Describe the action]

It will use:
[Describe the data]

It will produce or influence:
[Describe the output or decision]

It may affect:
[Describe people or systems]
```

---

## 4. Business Purpose Review

Confirm:

- [ ] Business purpose is specific.
- [ ] Purpose is legitimate.
- [ ] AI is appropriate for the purpose.
- [ ] A simpler non-AI method was considered.
- [ ] The activity supports a real customer or business need.
- [ ] The activity is not being created merely because automation is available.
- [ ] The intended benefit is documented.
- [ ] The expected harm is considered.

---

## 5. Scope Review

Document:

| Element | Scope |
|---|---|
| Number of people affected | [Estimate] |
| Number of messages or outputs | [Estimate] |
| Geographic scope | [Describe] |
| Duration | [Describe] |
| Frequency | [Describe] |
| Channels | [List] |
| Business units | [List] |
| External partners | [List] |

---

# Phase Two: Identify the People Affected

## 6. Affected Groups

Review:

- Prospects
- Customers
- Employees
- Contractors
- Partners
- Community members
- Children
- Older adults
- People with disabilities
- People with limited language access
- Financially vulnerable people
- People facing medical concerns
- People facing legal concerns
- Other potentially vulnerable groups

---

## 7. Affected-People Record

| Group | How They Are Affected | Vulnerability Level |
|---|---|---|
| [Group] | [Impact] | Low / Moderate / High |
| [Group] | [Impact] | Low / Moderate / High |
| [Group] | [Impact] | Low / Moderate / High |

---

## 8. Vulnerability Review

Ask:

- Can the audience easily understand the AI’s role?
- Can the audience challenge or correct the output?
- Can the audience reach a human?
- Could the audience be pressured?
- Could the audience misunderstand advice as professional guidance?
- Could the audience face financial, medical, legal, emotional, or reputational harm?
- Could exclusion or discrimination occur?
- Could a person be targeted because of vulnerability?

---

# Phase Three: Review Data Sensitivity

## 9. Data Categories

### Low-Sensitivity Data

Examples:

- Public product information
- Public brand guidelines
- Public website content
- Approved public marketing materials
- Nonpersonal performance summaries

### Moderate-Sensitivity Data

Examples:

- Internal marketing plans
- Customer segments
- CRM notes without highly sensitive details
- Nonpublic campaign results
- Internal brand documentation
- Customer behavior data

### High-Sensitivity Data

Examples:

- Personal identifiers
- Financial information
- Health information
- Legal information
- Authentication data
- Private messages
- Customer records
- Employee records
- Precise location
- Sensitive demographic attributes
- Confidential strategy
- Security information

---

## 10. Data Sensitivity Record

| Data Type | Source | Sensitivity | Permission |
|---|---|---|---|
| [Data] | [Source] | Low / Moderate / High | Approved / Missing |
| [Data] | [Source] | Low / Moderate / High | Approved / Missing |
| [Data] | [Source] | Low / Moderate / High | Approved / Missing |

---

## 11. Data Review

Confirm:

- [ ] Data is necessary.
- [ ] Data is approved.
- [ ] Data is minimized.
- [ ] Sensitive fields are removed where possible.
- [ ] Tool is approved for the data.
- [ ] Retention is defined.
- [ ] Access is controlled.
- [ ] Data may be deleted where required.
- [ ] AI training use is understood.
- [ ] Restricted information is excluded.

---

# Phase Four: Review Claim Sensitivity

## 12. Claim Categories

### Low-Sensitivity Claims

Examples:

- General educational statements
- Internal summaries
- Noncomparative descriptions
- Approved brand messaging

### Moderate-Sensitivity Claims

Examples:

- Product comparisons
- Performance statements
- Market interpretations
- Customer outcome summaries
- Recommendations

### High-Sensitivity Claims

Examples:

- Legal guidance
- Medical guidance
- Financial guidance
- Safety claims
- Regulated claims
- Guarantees
- Claims affecting employment
- Claims affecting eligibility
- Claims affecting access to services
- Claims that could cause material harm

---

## 13. Claim Record

| Claim Type | Example | Sensitivity | Required Review |
|---|---|---|---|
| [Type] | [Example] | Low / Moderate / High | [Review] |
| [Type] | [Example] | Low / Moderate / High | [Review] |

---

## 14. Claim Review

Confirm:

- [ ] Claims are necessary.
- [ ] Claims are supportable.
- [ ] Sources are available.
- [ ] Certainty matches evidence.
- [ ] Limitations remain visible.
- [ ] Specialized review is assigned where needed.
- [ ] AI cannot publish high-risk claims without approval.
- [ ] Guarantees are prohibited unless formally authorized.

---

# Phase Five: Review Automation Level

## 15. Automation Levels

### Assistive

AI prepares work for a human.

Examples:

- Brainstorming
- Outlining
- Drafting
- Summarization
- Editing suggestions

### Recommendatory

AI recommends an action, but a human decides.

Examples:

- Suggested segment
- Suggested response
- Suggested next step
- Suggested content priority

### Conditional

AI acts after defined conditions or approval.

Examples:

- Scheduled publication after approval
- Approved email sequence
- Rule-based response using approved content

### Autonomous

AI acts without immediate human approval.

Examples:

- Sending messages
- Publishing content
- Changing customer records
- Adjusting offers
- Making decisions at scale

---

## 16. Automation Record

| Function | Automation Level | Human Control |
|---|---|---|
| [Function] | Assistive / Recommendatory / Conditional / Autonomous | [Control] |
| [Function] | Assistive / Recommendatory / Conditional / Autonomous | [Control] |

---

## 17. Automation Review

Confirm:

- [ ] Automation level is documented.
- [ ] Human override exists.
- [ ] Approval cannot be bypassed.
- [ ] Stop conditions exist.
- [ ] Logs are preserved.
- [ ] Errors can be corrected.
- [ ] Customers can reach a human where appropriate.
- [ ] High-risk autonomous action is prohibited unless formally governed.
- [ ] Scale matches the controls available.

---

# Phase Six: Review Scale

## 18. Scale Factors

Review:

- Number of people affected
- Number of outputs
- Frequency
- Number of channels
- Number of markets
- Number of languages
- Number of automated decisions
- Speed of execution
- Ability to spread or replicate errors

---

## 19. Scale Record

| Scale Factor | Level | Risk Impact |
|---|---|---|
| Audience size | Small / Medium / Large | Low / Moderate / High |
| Output frequency | Low / Medium / High | Low / Moderate / High |
| Channel count | Low / Medium / High | Low / Moderate / High |
| Execution speed | Low / Medium / High | Low / Moderate / High |
| Error propagation | Low / Medium / High | Low / Moderate / High |

---

## 20. Scale Review

Confirm:

- [ ] Scale is documented.
- [ ] Controls match the scale.
- [ ] Monitoring can detect errors quickly.
- [ ] Rollback can occur quickly.
- [ ] Large-scale actions require stronger approval.
- [ ] High-volume automation is tested before expansion.
- [ ] Small pilots are used where appropriate.

---

# Phase Seven: Review Reversibility

## 21. Reversibility Questions

Ask:

- Can the action be stopped?
- Can the message be withdrawn?
- Can the data change be reversed?
- Can the customer be corrected?
- Can the publication be removed?
- Can access be restored?
- Can harm continue after the system stops?
- Can affected people appeal or challenge the outcome?

---

## 22. Reversibility Record

| Action | Reversible | Time to Reverse | Residual Harm |
|---|---|---|---|
| [Action] | Yes / Partly / No | [Time] | Low / Moderate / High |
| [Action] | Yes / Partly / No | [Time] | Low / Moderate / High |

---

## 23. Reversibility Review

Confirm:

- [ ] Rollback method exists.
- [ ] Correction method exists.
- [ ] Reversal authority is clear.
- [ ] Affected people can be notified.
- [ ] Records are preserved.
- [ ] Irreversible actions receive higher scrutiny.
- [ ] Residual harm is considered.

---

# Phase Eight: Review Potential Harm

## 24. Harm Categories

Review potential:

- Financial harm
- Legal harm
- Medical harm
- Safety harm
- Privacy harm
- Reputational harm
- Emotional harm
- Discrimination
- Exclusion
- Manipulation
- Deception
- Loss of access
- Loss of opportunity
- Customer confusion
- Brand damage

---

## 25. Harm Record

| Potential Harm | Likelihood | Severity | Control |
|---|---|---|---|
| [Harm] | Low / Moderate / High | Low / Moderate / High | [Control] |
| [Harm] | Low / Moderate / High | Low / Moderate / High | [Control] |
| [Harm] | Low / Moderate / High | Low / Moderate / High | [Control] |

---

## 26. Harm Review

Confirm:

- [ ] Likelihood is assessed.
- [ ] Severity is assessed.
- [ ] Vulnerable groups are considered.
- [ ] Cumulative harm is considered.
- [ ] Indirect harm is considered.
- [ ] Controls reduce risk meaningfully.
- [ ] Residual risk is documented.
- [ ] High residual harm triggers escalation.

---

# Phase Nine: Review Transparency

## 27. Transparency Questions

Ask:

- Does the audience know AI is involved?
- Could the audience reasonably believe a human created or approved the output?
- Could automation materially affect trust?
- Is synthetic media involved?
- Is personalization involved?
- Is the disclosure understandable?
- Is disclosure legally or platform-required?

---

## 28. Transparency Record

| AI Role | Disclosure Needed | Approved Language |
|---|---|---|
| [Role] | Yes / No / Conditional | [Language] |
| [Role] | Yes / No / Conditional | [Language] |

---

## 29. Transparency Review

Confirm:

- [ ] Automated interactions are not falsely presented as human.
- [ ] Synthetic media is labeled where appropriate.
- [ ] AI assistance is disclosed where material.
- [ ] Disclosure matches actual practice.
- [ ] Disclosure is understandable.
- [ ] Disclosure is visible.
- [ ] Human review is not exaggerated.

---

# Phase Ten: Assign the Preliminary Risk Level

## 30. Low-Risk Classification

Typical characteristics:

- Public or low-sensitivity data
- Internal or noncustomer-facing use
- Assistive automation
- Low scale
- Easily reversible output
- Low potential harm
- No regulated claims
- Human review before use

Examples:

- Brainstorming
- Internal outlines
- Grammar suggestions
- Formatting
- Summarizing approved public materials

---

## 31. Moderate-Risk Classification

Typical characteristics:

- Customer-facing output
- Moderate-sensitivity data
- Recommendatory or conditional automation
- Meaningful scale
- Some personalization
- Material claims
- Reversible but potentially harmful errors
- Required human approval and monitoring

Examples:

- Public content drafts
- Personalized email drafts
- Customer segmentation
- Performance summaries
- Scheduled social content
- Customer-facing recommendations

---

## 32. High-Risk Classification

Typical characteristics:

- Sensitive data
- Vulnerable audiences
- Regulated claims
- Autonomous action
- Large scale
- Limited reversibility
- Significant potential harm
- Decisions affecting access, opportunity, or treatment
- Synthetic media involving real people
- Legal, medical, financial, political, employment, or safety implications

Examples:

- Automated financial recommendations
- Medical marketing claims
- Employment-related scoring
- High-volume automated outreach
- Synthetic spokesperson content
- Sensitive audience targeting
- Automated eligibility decisions

---

## 33. Prohibited Classification

Use when:

- The purpose is deceptive
- Consent is absent
- Data use is unauthorized
- The workflow impersonates a real person deceptively
- Harm cannot be controlled
- Bias cannot be reduced adequately
- Required human oversight is unavailable
- The tool cannot safely handle the data
- The activity violates law, policy, contract, or organizational values

---

# Phase Eleven: Apply the Classification Matrix

## 34. Risk Matrix

| Factor | Low | Moderate | High |
|---|---|---|---|
| Audience vulnerability | Low | Some vulnerability | High vulnerability |
| Data sensitivity | Public or low | Internal or personal | Highly sensitive |
| Claim sensitivity | General | Material | Regulated or high-stakes |
| Automation | Assistive | Recommendatory or conditional | Autonomous |
| Scale | Small | Moderate | Large |
| Reversibility | Easy | Partial | Difficult or impossible |
| Potential harm | Minimal | Meaningful | Severe |
| Transparency need | Low | Moderate | High |
| Human review | Basic | Required | Specialist and final authority |

---

## 35. Preliminary Scorecard

Use:

- 1: Low
- 2: Moderate
- 3: High

| Factor | Score | Evidence |
|---|---:|---|
| Audience vulnerability | [1–3] | [Evidence] |
| Data sensitivity | [1–3] | [Evidence] |
| Claim sensitivity | [1–3] | [Evidence] |
| Automation level | [1–3] | [Evidence] |
| Scale | [1–3] | [Evidence] |
| Reversibility | [1–3] | [Evidence] |
| Potential harm | [1–3] | [Evidence] |
| Transparency need | [1–3] | [Evidence] |
| Monitoring complexity | [1–3] | [Evidence] |

### Total Score

[Enter score.]

Suggested interpretation:

- 9–13: Low risk
- 14–20: Moderate risk
- 21–27: High risk

A single critical factor may justify a higher classification regardless of total score.

---

# Phase Twelve: Define Controls by Risk Level

## 36. Low-Risk Controls

Require:

- Approved tool
- Approved data
- Basic human review
- Version control
- No sensitive information
- No autonomous execution
- Basic documentation

---

## 37. Moderate-Risk Controls

Require:

- Approved business purpose
- Data review
- Source verification
- Privacy review
- Bias review where relevant
- Accessibility review
- Human approval before execution
- Monitoring
- Correction process
- Version history
- Rollback capability

---

## 38. High-Risk Controls

Require:

- Executive or designated authority approval
- Specialist review
- Legal or compliance review where relevant
- Privacy review
- Security review
- Bias and inclusion review
- Accessibility review
- Restricted data access
- Restricted tool access
- Pilot testing
- Enhanced monitoring
- Audit logs
- Human override
- Rollback plan
- Incident response
- Clear disclosure
- Scheduled reclassification
- Documented residual risk acceptance

---

## 39. Required-Control Record

| Control | Required | Owner | Status |
|---|---|---|---|
| Human approval | Yes / No | [Owner] | Complete / Missing |
| Source verification | Yes / No | [Owner] | Complete / Missing |
| Privacy review | Yes / No | [Owner] | Complete / Missing |
| Bias review | Yes / No | [Owner] | Complete / Missing |
| Accessibility review | Yes / No | [Owner] | Complete / Missing |
| Specialist review | Yes / No | [Owner] | Complete / Missing |
| Monitoring | Yes / No | [Owner] | Complete / Missing |
| Rollback plan | Yes / No | [Owner] | Complete / Missing |
| Incident response | Yes / No | [Owner] | Complete / Missing |

---

# Phase Thirteen: Define Stop Conditions

## 40. Universal Stop Conditions

Stop the activity when:

- Business purpose is unclear
- Data permission is missing
- Tool approval is missing
- Required reviewer is unavailable
- Material facts cannot be verified
- Sensitive information may be exposed
- Bias risk remains uncontrolled
- Accessibility failure is material
- Human approval is missing
- Wrong version is selected
- Automation behaves unexpectedly
- Monitoring is unavailable
- Rollback is unavailable for material-risk activity

---

## 41. Activity-Specific Stop Conditions

| Condition | Detection Method | Response |
|---|---|---|
| [Condition] | [Method] | [Response] |
| [Condition] | [Method] | [Response] |
| [Condition] | [Method] | [Response] |

---

# Phase Fourteen: Assign Reviewers and Approvers

## 42. Review Roles

Possible reviewers:

- Activity owner
- Marketing strategist
- Subject-matter expert
- Privacy reviewer
- Security reviewer
- Legal or compliance reviewer
- Bias and inclusion reviewer
- Accessibility reviewer
- Data owner
- Automation owner
- Executive approver

---

## 43. Review Matrix

| Review Area | Reviewer | Required for Risk Level |
|---|---|---|
| Strategy | [Name] | Low / Moderate / High |
| Data | [Name] | Low / Moderate / High |
| Privacy | [Name] | Moderate / High |
| Security | [Name] | Moderate / High |
| Subject matter | [Name] | Moderate / High |
| Bias and inclusion | [Name] | Moderate / High |
| Accessibility | [Name] | Moderate / High |
| Legal or compliance | [Name] | High |
| Final approval | [Name] | All |

---

## 44. Approval Record

| Reviewer | Decision | Conditions | Date |
|---|---|---|---|
| [Name] | Approve / Revise / Reject | [Conditions] | [Date] |
| [Name] | Approve / Revise / Reject | [Conditions] | [Date] |

---

# Phase Fifteen: Define Monitoring

## 45. Monitoring Signals

Monitor:

- Factual errors
- Customer complaints
- Privacy incidents
- Bias signals
- Accessibility failures
- Unexpected outputs
- Automation failures
- Poor-fit targeting
- Unintended audience effects
- Corrections
- Human override frequency
- Tool or model changes

---

## 46. Monitoring Record

| Signal | Threshold | Owner | Response |
|---|---|---|---|
| [Signal] | [Threshold] | [Owner] | [Response] |
| [Signal] | [Threshold] | [Owner] | [Response] |

---

## 47. Monitoring Frequency

Select:

- [ ] Every output
- [ ] Daily
- [ ] Weekly
- [ ] Monthly
- [ ] Quarterly
- [ ] Event-based
- [ ] Continuous system monitoring

Higher-risk activities require more frequent review.

---

# Phase Sixteen: Define Escalation

## 48. Escalation Triggers

Escalate when:

- Risk level may be underestimated
- Sensitive information is exposed
- A vulnerable group may be harmed
- A regulated claim appears
- Automation acts outside approved boundaries
- A customer reports material harm
- Bias or discrimination appears
- Synthetic media may mislead
- Reversal is difficult
- A required reviewer rejects the activity

---

## 49. Escalation Record

| Trigger | First Contact | Final Authority | Response Time |
|---|---|---|---|
| [Trigger] | [Contact] | [Authority] | [Time] |
| [Trigger] | [Contact] | [Authority] | [Time] |

---

# Phase Seventeen: Reclassify Risk

## 50. Reclassification Triggers

Reclassify when:

- Business purpose changes
- Audience changes
- A vulnerable audience is added
- Data source changes
- Data sensitivity increases
- Tool or model changes
- Automation increases
- Scale increases
- Claim type changes
- New regulations apply
- Monitoring reveals harm
- A material incident occurs
- Reversibility decreases
- Human oversight decreases

---

## 51. Reclassification Record

| Field | Previous | Current |
|---|---|---|
| Business purpose | [Previous] | [Current] |
| Audience | [Previous] | [Current] |
| Data | [Previous] | [Current] |
| Tool or model | [Previous] | [Current] |
| Automation level | [Previous] | [Current] |
| Scale | [Previous] | [Current] |
| Potential harm | [Previous] | [Current] |
| Risk level | [Previous] | [Current] |

---

## 52. Reclassification Review

Confirm:

- [ ] Trigger is documented.
- [ ] Previous approval is suspended where required.
- [ ] New controls are identified.
- [ ] Reviewers are reassigned.
- [ ] Monitoring is updated.
- [ ] Final approval is renewed.
- [ ] Version history is updated.

---

# Phase Eighteen: Use AI Responsibly in Classification

## 53. Approved AI Uses

AI may assist with:

- Organizing activity details
- Identifying possible risk factors
- Comparing the activity to approved examples
- Preparing a preliminary score
- Identifying missing information
- Suggesting questions for reviewers
- Summarizing control requirements
- Comparing versions

---

## 54. Prohibited AI Uses

AI should not:

- Approve its own risk level
- Make the final classification
- Accept residual risk
- Invent permission
- Invent compliance
- Invent safety controls
- Ignore missing information
- Override a reviewer
- Activate the workflow
- Remove stop conditions
- Decide that specialist review is unnecessary

---

## 55. AI Use Record

| AI Task | Tool | Approved Inputs | Human Reviewer |
|---|---|---|---|
| [Task] | [Tool] | [Inputs] | [Reviewer] |
| [Task] | [Tool] | [Inputs] | [Reviewer] |

---

## 56. AI Classification Review

Confirm:

- [ ] AI output is treated as preliminary.
- [ ] Risk factors were verified.
- [ ] Missing information remains visible.
- [ ] High-risk indicators were not averaged away.
- [ ] Human reviewers made the final decision.
- [ ] Residual risk acceptance is human.
- [ ] Final approval is documented.

---

# Phase Nineteen: Approve the Classification

## 57. Final Classification Checklist

Confirm:

- [ ] Activity is defined
- [ ] Business purpose is defined
- [ ] Affected people are identified
- [ ] Audience vulnerability is reviewed
- [ ] Data sensitivity is reviewed
- [ ] Claim sensitivity is reviewed
- [ ] Automation level is reviewed
- [ ] Scale is reviewed
- [ ] Reversibility is reviewed
- [ ] Potential harm is reviewed
- [ ] Transparency is reviewed
- [ ] Controls are defined
- [ ] Stop conditions are defined
- [ ] Monitoring is defined
- [ ] Escalation is defined
- [ ] Required reviewers completed review
- [ ] Final approver has authority
- [ ] Exact version is identified

---

## 58. Final Approval Statement

Use:

```text
I reviewed the exact AI-supported activity described in this record, including its purpose, audience, data, claims, automation, scale, reversibility, potential harm, controls, and monitoring plan.

I approve the classification as:
[Risk level]

Conditions:
[Conditions]
```

### Final Approver

[Name and role.]

### Approval Date

[Date.]

---

## 59. Critical Approval Stop Conditions

Do not approve when:

- [ ] Activity remains unclear.
- [ ] Affected people are not identified.
- [ ] Data permission is missing.
- [ ] Required controls are missing.
- [ ] Monitoring is unavailable.
- [ ] Rollback is unavailable where needed.
- [ ] Required specialist review is incomplete.
- [ ] Human approval can be bypassed.
- [ ] Residual risk is unacceptable.
- [ ] Final authority is missing.
- [ ] Another critical issue exists: [Describe]

---

# Phase Twenty: Pause or Retire the Activity

## 60. Pause Triggers

Pause when:

- New information changes the risk
- Monitoring fails
- Required reviewer becomes unavailable
- Tool behavior changes
- Model behavior changes
- Permission is questioned
- Data use is questioned
- A material error occurs
- Controls fail
- A complaint indicates possible harm

---

## 61. Retirement Triggers

Retire when:

- Purpose no longer exists
- Risk cannot be controlled
- Data use is no longer permitted
- Tool is no longer approved
- Harm persists
- Bias cannot be reduced
- Required oversight is unavailable
- A safer process replaces it
- Legal or policy requirements prohibit it
- Maintenance exceeds responsible value

---

## 62. Retirement Record

| Field | Information |
|---|---|
| Activity | [Enter activity] |
| Risk level | [Enter risk] |
| Retirement reason | [Describe] |
| Retirement date | [Date] |
| Approved by | [Name] |
| Replacement | [Enter replacement or “None”] |
| Data disposition | [Describe] |
| Automation disabled | Yes / No |
| Access disabled | Yes / No |
| Retrieval disabled | Yes / No |
| Archive location | [Location] |

---

# Quick AI Use Risk Classification Guide

## Define

- [ ] Activity defined
- [ ] Business purpose defined
- [ ] Audience defined
- [ ] Affected people identified
- [ ] Tool identified
- [ ] Data identified
- [ ] Output identified
- [ ] Automation level identified

## Assess

- [ ] Audience vulnerability reviewed
- [ ] Data sensitivity reviewed
- [ ] Claim sensitivity reviewed
- [ ] Scale reviewed
- [ ] Reversibility reviewed
- [ ] Potential harm reviewed
- [ ] Transparency reviewed
- [ ] Existing controls reviewed

## Classify

- [ ] Low risk considered
- [ ] Moderate risk considered
- [ ] High risk considered
- [ ] Prohibited use considered
- [ ] Critical factors reviewed
- [ ] Preliminary score recorded

## Control

- [ ] Required controls assigned
- [ ] Human approval required
- [ ] Stop conditions defined
- [ ] Monitoring defined
- [ ] Rollback defined
- [ ] Correction process defined
- [ ] Escalation path defined

## Approve

- [ ] Required reviewers completed review
- [ ] Conditions resolved
- [ ] Exact version identified
- [ ] Final risk level approved
- [ ] Approval recorded

## Continue

- [ ] Monitoring active
- [ ] Reclassification triggers defined
- [ ] Pause process available
- [ ] Retirement process available
- [ ] Version history maintained

---

# Governance

## 63. Ownership

| Responsibility | Owner |
|---|---|
| Risk framework | [Name] |
| Activity ownership | [Name] |
| Business purpose | [Name] |
| Data governance | [Name] |
| Privacy | [Name] |
| Security | [Name] |
| Subject-matter accuracy | [Name] |
| Bias and inclusion | [Name] |
| Accessibility | [Name] |
| Automation | [Name] |
| Monitoring | [Name] |
| Escalation | [Name] |
| Incident response | [Name] |
| Reclassification | [Name] |
| Retirement | [Name] |
| Final approval | [Name] |

---

## 64. Version Naming

Use:

```text
[activity-name]_ai-risk-classification_v[version]_[date]
```

Example:

```text
customer-email-personalization_ai-risk-classification_v1.0_2026-08-04
```

---

## 65. Changes Requiring Reapproval

Require reapproval when changing:

- Business purpose
- Audience
- Affected groups
- Data source
- Data sensitivity
- Tool
- Model
- Prompt
- Workflow
- Automation level
- Scale
- Claim type
- Disclosure
- Monitoring
- Rollback capability
- Reviewer
- Risk level
- Other: [Describe]

---

## 66. Version History

| Version | Date | Author | Change | Reason | Approved By |
|---|---|---|---|---|---|
| 1.0 | [Date] | [Name] | Initial classification guide | Guide creation | [Name] |
| [Version] | [Date] | [Name] | [Change] | [Reason] | [Name] |

---

## Important Principle

Risk is not determined by how impressive the AI appears.

It is determined by what the system touches.

Who it affects.

What data it uses.

What claims it makes.

How quickly it acts.

How difficult it is to reverse.

And what happens when it is wrong.

AI may help organize the questions and surface possible warning signs.

It cannot grant itself permission to proceed.

A human must still decide whether the purpose is legitimate, the controls are sufficient, the residual risk is acceptable, and the activity should exist at all.

---

## Related Resources

### Responsible AI

- [Responsible AI Marketing Principles](responsible-ai-marketing-principles.md)

### Frameworks

- [Human Approval Before Execution Framework](../frameworks/human-approval-before-execution.md)
- [Context Before Creation Framework](../frameworks/context-before-creation.md)
- [Brand Voice AI Foundation Framework](../frameworks/brand-voice-ai-foundation.md)

### Checklists

- [AI-Generated Content Review Checklist](../checklists/ai-generated-content-review-checklist.md)
- [Fact and Source Verification Checklist](../checklists/fact-and-source-verification-checklist.md)
- [Confidential Information Protection Checklist](../checklists/confidential-information-protection-checklist.md)
- [Automated Communications Approval Checklist](../checklists/automated-communications-approval-checklist.md)

### Workflows

- [Knowledge Ingestion and Grounding Workflow](../workflows/knowledge-ingestion-and-grounding-workflow.md)
- [Content Review Workflow](../workflows/content-review-workflow.md)
- [Campaign Planning Workflow](../workflows/campaign-planning-workflow.md)
- [Social Media Publishing Workflow](../workflows/social-media-publishing-workflow.md)
- [Email Development Workflow](../workflows/email-development-workflow.md)

### Content Strategy

- [Content Publication Readiness Guide](../content-strategy/content-publication-readiness-guide.md)
- [Content Performance Review Guide](../content-strategy/content-performance-review-guide.md)
- [Content Refresh and Retirement Guide](../content-strategy/content-refresh-and-retirement-guide.md)

### Projects

- [AI Marketing Resources](https://github.com/poguedigitalsolutions/ai-marketing-resources)
- [Brand Voice AI Skool](https://www.skool.com/companyvoiceai-6106/about)
- [Pogue Digital Solutions, LLC](https://poguedigitalsolutions.com)

---

## Copyright

Copyright © John M. Pogue and Pogue Digital Solutions, LLC.

All rights reserved unless otherwise stated.
