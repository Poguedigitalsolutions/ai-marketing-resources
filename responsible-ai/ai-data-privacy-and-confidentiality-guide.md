# AI Data Privacy and Confidentiality Guide

Use this guide to identify, classify, minimize, protect, review, store, remove, and govern information used in AI-assisted marketing systems.

This guide is part of the **Brand Voice AI** methodology developed by **John M. Pogue** and **Pogue Digital Solutions, LLC**.

> Data should not enter an AI system merely because someone can paste, upload, connect, or retrieve it. Every piece of information should have a legitimate purpose, an approved destination, and a responsible human owner.

---

## Guide Purpose

The AI Data Privacy and Confidentiality Guide helps organizations:

- Identify personal information
- Identify sensitive information
- Identify confidential information
- Identify restricted information
- Identify proprietary information
- Classify data before use
- Apply data minimization
- Review tool approval
- Review vendor practices
- Review data retention
- Review storage
- Review model-training use
- Review deletion options
- Review access controls
- Distinguish public data from internal data
- Distinguish confidential data from prohibited data
- Anonymize information
- Redact information
- Protect customer information
- Protect employee information
- Protect credentials
- Protect account information
- Protect health information
- Protect legal information
- Protect financial information
- Review uploaded files
- Review screenshots
- Review transcripts
- Review CRM notes
- Review private messages
- Review retrieval systems
- Review custom GPTs
- Review AI agents
- Review automations
- Review generated outputs
- Respond to incidents
- Correct exposed information
- Notify affected parties where appropriate
- Delete data where required
- Escalate material risks
- Renew approval when tools, vendors, models, permissions, or data uses change

This guide may be used for:

- Customer research
- Market research
- CRM analysis
- Brand voice development
- Content generation
- Content editing
- Email marketing
- Social-media publishing
- Advertising
- Personalization
- Customer support
- Sales enablement
- Analytics
- Reporting
- Custom GPTs
- Retrieval-augmented generation systems
- AI agents
- Automation workflows
- Knowledge bases
- Uploaded files
- Connected data sources

---

# Privacy and Confidentiality Overview

```text
Define the business purpose
        ↓
Identify the data
        ↓
Classify the data
        ↓
Minimize, redact, or anonymize
        ↓
Confirm tool and vendor approval
        ↓
Confirm permission, access, storage, retention, and deletion
        ↓
Use the data
        ↓
Review generated outputs
        ↓
Human approval
        ↓
Monitor access and exposure
        ↓
Correct, notify, delete, escalate, or retire
```

---

# Data Review Record

## 1. Activity Information

| Field | Information |
|---|---|
| Activity name | [Enter name] |
| Business purpose | [Describe purpose] |
| Marketing function | [Enter function] |
| Primary audience | [Describe audience] |
| People represented in the data | [Describe] |
| AI tool or model | [Enter tool] |
| Vendor | [Enter vendor] |
| Data sources | [List sources] |
| Data owner | [Enter name] |
| Activity owner | [Enter name] |
| Privacy reviewer | [Enter name] |
| Security reviewer | [Enter name] |
| Final approver | [Enter name and role] |
| Risk level | Low / Moderate / High / Prohibited |
| Current version | [Enter version] |
| Status | Proposed / Review / Approved / Active / Paused / Retired |

---

## 2. Data Decision

Select one:

- [ ] Approved
- [ ] Approved with conditions
- [ ] Data minimization required
- [ ] Redaction required
- [ ] Anonymization required
- [ ] Permission required
- [ ] Tool approval required
- [ ] Vendor review required
- [ ] Security review required
- [ ] Legal or compliance review required
- [ ] Storage revision required
- [ ] Retention revision required
- [ ] Deletion required
- [ ] Pause
- [ ] Prohibit
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

# Phase One: Define the Business Purpose

## 3. Purpose Statement

Use:

```text
The data will be used to:
[Describe the specific activity]

The intended benefit is:
[Describe the benefit]

The people affected are:
[Describe]

The output will be used for:
[Describe]
```

---

## 4. Purpose Review

Confirm:

- [ ] Purpose is specific.
- [ ] Purpose is legitimate.
- [ ] AI use is appropriate.
- [ ] Data use is necessary.
- [ ] The activity cannot reasonably use less data.
- [ ] The intended benefit is documented.
- [ ] Possible harm is considered.
- [ ] The purpose does not quietly expand beyond approval.

---

# Phase Two: Identify the Data

## 5. Data Source Categories

Possible sources:

- Public websites
- Approved public documents
- Internal documents
- Customer interviews
- Survey responses
- CRM records
- Customer-support records
- Email messages
- Private messages
- Meeting transcripts
- Call recordings
- Screenshots
- Uploaded files
- Analytics platforms
- Advertising platforms
- Sales systems
- Employee records
- Partner records
- Third-party datasets
- Connected applications
- AI-generated outputs

---

## 6. Data Inventory

| Data Element | Source | Person or Organization Represented | Purpose |
|---|---|---|---|
| [Data] | [Source] | [Person or organization] | [Purpose] |
| [Data] | [Source] | [Person or organization] | [Purpose] |
| [Data] | [Source] | [Person or organization] | [Purpose] |

---

## 7. Data Identification Review

Confirm:

- [ ] Every source is identified.
- [ ] Every data category is identified.
- [ ] People represented are identified.
- [ ] Data ownership is identified.
- [ ] Permission status is identified.
- [ ] Sensitive fields are identified.
- [ ] Generated data is distinguished from source data.
- [ ] Hidden metadata is considered.

---

# Phase Three: Classify the Data

## 8. Public Data

Examples:

- Public website pages
- Public press releases
- Public product descriptions
- Public social posts
- Public reports
- Approved public marketing materials

Public availability does not automatically mean unrestricted reuse.

---

## 9. Internal Data

Examples:

- Internal procedures
- Internal marketing plans
- Internal campaign results
- Draft documents
- Internal brand guidelines
- Internal meeting notes
- Nonpublic operational data

---

## 10. Confidential Data

Examples:

- Customer records
- Employee records
- Customer lists
- Private pricing
- Contract information
- Nonpublic performance data
- Proprietary processes
- Internal strategy
- Unreleased products
- Private research
- Private correspondence

---

## 11. Restricted Data

Examples:

- Financial account information
- Health information
- Legal case information
- Authentication information
- Government identifiers
- Precise location
- Sensitive demographic information
- Security information
- Highly sensitive customer records

---

## 12. Prohibited Data

Examples may include:

- Passwords
- Authentication tokens
- Private keys
- Complete payment-card information
- Information the tool is not approved to receive
- Data used without authorization
- Data prohibited by law, contract, or policy
- Information whose risk cannot be controlled adequately

---

## 13. Data Classification Record

| Data Element | Classification | Sensitivity | Decision |
|---|---|---|---|
| [Data] | Public / Internal / Confidential / Restricted / Prohibited | Low / Moderate / High | Use / Redact / Anonymize / Remove |
| [Data] | Public / Internal / Confidential / Restricted / Prohibited | Low / Moderate / High | Use / Redact / Anonymize / Remove |

---

## 14. Classification Review

Confirm:

- [ ] Public data is still reviewed for usage restrictions.
- [ ] Internal data is not treated as public.
- [ ] Confidential data has additional controls.
- [ ] Restricted data has specialist review.
- [ ] Prohibited data is excluded.
- [ ] Classification is documented.
- [ ] Data can be reclassified when conditions change.

---

# Phase Four: Apply Data Minimization

## 15. Data Minimization Questions

Ask:

- Is this data necessary?
- Can the activity use fewer fields?
- Can names be removed?
- Can identifiers be replaced?
- Can exact values become ranges?
- Can the analysis use aggregated data?
- Can a representative sample be used?
- Can the task be completed without uploading the entire file?
- Can the output be created from approved summaries instead?

---

## 16. Data Minimization Record

| Original Data | Reduced Version | Reason |
|---|---|---|
| [Original] | [Reduced] | [Reason] |
| [Original] | [Reduced] | [Reason] |

---

## 17. Minimization Review

Confirm:

- [ ] Only necessary data is used.
- [ ] Unused fields are removed.
- [ ] Unnecessary identifiers are removed.
- [ ] Full files are avoided where excerpts are sufficient.
- [ ] Aggregation is used where practical.
- [ ] Sensitive data is not included for convenience.
- [ ] Reduced data still supports the purpose.

---

# Phase Five: Redact and Anonymize

## 18. Redaction

Redaction removes or obscures specific information.

Examples:

- Names
- Email addresses
- Phone numbers
- Account numbers
- Addresses
- Customer IDs
- Credentials
- Signatures
- Private URLs

---

## 19. Anonymization

Anonymization removes or transforms identifying information so the person cannot reasonably be identified from the remaining data.

Possible methods:

- Removing direct identifiers
- Generalizing locations
- Replacing dates with ranges
- Aggregating responses
- Replacing names with participant IDs
- Removing rare combinations of attributes
- Separating identity records from content records

---

## 20. Redaction and Anonymization Record

| Original Information | Method | Final Form |
|---|---|---|
| [Information] | Redacted / Anonymized / Aggregated | [Final form] |
| [Information] | Redacted / Anonymized / Aggregated | [Final form] |

---

## 21. Re-identification Review

Ask:

- Could the person still be identified from context?
- Could several fields be combined to identify them?
- Is the sample so small that identity is obvious?
- Does a quotation reveal identity?
- Does a screenshot contain identifying details?
- Does metadata retain hidden identifiers?
- Could another connected system restore identity?

---

# Phase Six: Review Tool and Vendor Approval

## 22. Tool Review Areas

Review:

- Intended use
- Data handling
- Data storage
- Data retention
- Model-training use
- Human review by the vendor
- Subprocessors
- Encryption
- Access controls
- Export options
- Deletion options
- Audit logs
- Geographic storage
- Security incidents
- Contract terms
- Policy changes

---

## 23. Tool Review Record

| Tool | Approved Data | Prohibited Data | Owner | Status |
|---|---|---|---|---|
| [Tool] | [Data] | [Data] | [Owner] | Approved / Restricted / Prohibited |
| [Tool] | [Data] | [Data] | [Owner] | Approved / Restricted / Prohibited |

---

## 24. Vendor Review

Confirm:

- [ ] Vendor identity is verified.
- [ ] Data-handling terms are reviewed.
- [ ] Retention terms are understood.
- [ ] Training use is understood.
- [ ] Deletion options are understood.
- [ ] Security controls are reviewed.
- [ ] Subprocessors are considered.
- [ ] Access is limited.
- [ ] Contractual restrictions are followed.
- [ ] Vendor changes trigger renewed review.

---

# Phase Seven: Review Storage and Retention

## 25. Storage Record

| Data | Storage Location | Access | Encryption |
|---|---|---|---|
| [Data] | [Location] | [Roles] | Yes / No |
| [Data] | [Location] | [Roles] | Yes / No |

---

## 26. Retention Record

| Data | Retention Period | Deletion Trigger | Owner |
|---|---|---|---|
| [Data] | [Period] | [Trigger] | [Owner] |
| [Data] | [Period] | [Trigger] | [Owner] |

---

## 27. Storage and Retention Review

Confirm:

- [ ] Storage location is approved.
- [ ] Access is limited.
- [ ] Encryption is used where appropriate.
- [ ] Retention is defined.
- [ ] Data is not retained indefinitely without reason.
- [ ] Deletion is possible.
- [ ] Backup copies are considered.
- [ ] Exported copies are tracked.
- [ ] Temporary working files are removed.
- [ ] Retention changes require approval.

---

# Phase Eight: Review Model-Training Use

## 28. Training-Use Questions

Ask:

- Will the vendor use inputs to improve models?
- Will outputs be retained?
- Can training use be disabled?
- Does the agreement permit training?
- Does the data owner permit training?
- Could confidential information enter a future model?
- Are customer permissions broad enough?
- Are deletion requests honored?

---

## 29. Training-Use Record

| Tool | Training Use | Opt-Out Available | Decision |
|---|---|---|---|
| [Tool] | Yes / No / Unclear | Yes / No | Approved / Restricted / Prohibited |
| [Tool] | Yes / No / Unclear | Yes / No | Approved / Restricted / Prohibited |

---

## 30. Training-Use Review

Confirm:

- [ ] Training use is understood.
- [ ] Opt-out status is confirmed.
- [ ] Permission covers the use.
- [ ] Confidential data is excluded where required.
- [ ] Restricted data is excluded.
- [ ] Policy changes trigger renewed approval.
- [ ] Data owners understand the implications.

---

# Phase Nine: Review Access Controls

## 31. Access Roles

Possible roles:

- Data owner
- Activity owner
- Analyst
- Content creator
- Reviewer
- Approver
- System administrator
- Vendor administrator
- Auditor

---

## 32. Access-Control Record

| Role | Access Level | Business Need | Status |
|---|---|---|---|
| [Role] | View / Edit / Export / Delete / Admin | [Need] | Approved / Remove |
| [Role] | View / Edit / Export / Delete / Admin | [Need] | Approved / Remove |

---

## 33. Access Review

Confirm:

- [ ] Access is role-based.
- [ ] Access follows least-privilege principles.
- [ ] Former users are removed.
- [ ] Shared accounts are avoided.
- [ ] Export permissions are limited.
- [ ] Deletion authority is controlled.
- [ ] Administrative access is monitored.
- [ ] Access reviews occur regularly.
- [ ] Audit logs are preserved.

---

# Phase Ten: Review Uploaded Files

## 34. File Types

Review:

- Documents
- PDFs
- Spreadsheets
- Presentations
- Images
- Audio
- Video
- Archives
- Exports
- Database files
- Transcripts
- Scanned records

---

## 35. Uploaded-File Review

Confirm:

- [ ] File owner is known.
- [ ] File purpose is defined.
- [ ] Sensitive contents are identified.
- [ ] Hidden sheets are reviewed.
- [ ] Comments are reviewed.
- [ ] Track changes are reviewed.
- [ ] Metadata is reviewed.
- [ ] Embedded files are reviewed.
- [ ] Private links are removed.
- [ ] Credentials are removed.
- [ ] Only necessary pages or sections are uploaded.
- [ ] Retention and deletion are defined.

---

# Phase Eleven: Review Screenshots and Images

## 36. Screenshot Risks

Screenshots may expose:

- Names
- Email addresses
- Phone numbers
- Account numbers
- Browser tabs
- File names
- Private messages
- Internal URLs
- Notifications
- Profile pictures
- Customer information
- Location data
- Metadata

---

## 37. Screenshot Review

Confirm:

- [ ] Entire image is inspected.
- [ ] Background information is reviewed.
- [ ] Browser tabs are reviewed.
- [ ] Notifications are reviewed.
- [ ] Names are approved or removed.
- [ ] Contact details are removed.
- [ ] Private URLs are removed.
- [ ] Account details are removed.
- [ ] Metadata is removed where appropriate.
- [ ] Redaction cannot be easily reversed.

---

# Phase Twelve: Review Transcripts and Recordings

## 38. Transcript and Recording Risks

Review for:

- Names
- Contact information
- Health details
- Financial details
- Legal concerns
- Employee information
- Customer complaints
- Private strategy
- Sensitive stories
- Unapproved quotations
- Background conversations

---

## 39. Transcript Review

Confirm:

- [ ] Recording permission is documented.
- [ ] Transcription purpose is approved.
- [ ] Speaker identities are handled appropriately.
- [ ] Sensitive passages are removed.
- [ ] Quotations are verified.
- [ ] Reconstructed text is labeled.
- [ ] Access is limited.
- [ ] Retention is defined.
- [ ] AI use is included in permission where required.

---

# Phase Thirteen: Review CRM Notes and Customer Records

## 40. CRM Data Risks

CRM systems may contain:

- Personal contact information
- Purchase history
- Support history
- Private notes
- Employee observations
- Inferred traits
- Health information
- Financial information
- Family information
- Sensitive objections
- Complaints
- Disputes

---

## 41. CRM Review

Confirm:

- [ ] Only required fields are used.
- [ ] Free-text notes are reviewed carefully.
- [ ] Sensitive traits are excluded.
- [ ] Inferred traits are labeled.
- [ ] Private observations are not used as verified facts.
- [ ] Permission supports the use.
- [ ] Tool is approved for CRM data.
- [ ] Outputs do not expose customer records.
- [ ] Automated decisions receive appropriate review.

---

# Phase Fourteen: Review Private Messages and Email

## 42. Private Communication Risks

Private messages may contain:

- Personal disclosures
- Contact information
- Business secrets
- Health concerns
- Financial concerns
- Legal concerns
- Family information
- Credentials
- Attachments
- Sensitive opinions

---

## 43. Private Communication Review

Confirm:

- [ ] Use is necessary.
- [ ] Permission is appropriate.
- [ ] Only relevant excerpts are used.
- [ ] Identifying information is removed.
- [ ] Attachments are reviewed separately.
- [ ] Quotations are not published without approval.
- [ ] AI use does not violate reasonable expectations.
- [ ] Retention is limited.
- [ ] Generated summaries preserve context.

---

# Phase Fifteen: Protect Credentials and Account Information

## 44. Prohibited Credential Types

Do not enter:

- Passwords
- One-time codes
- API keys
- Private keys
- Authentication tokens
- Recovery codes
- Secret questions
- Session cookies
- Complete payment-card details
- Bank-account credentials
- Administrative access links

---

## 45. Credential Incident Response

When credentials enter an unapproved system:

1. Stop the activity.
2. Notify the security owner.
3. Revoke or rotate the credential.
4. Remove the data where possible.
5. Review logs and exposure.
6. Document the incident.
7. Update controls.
8. Reapprove the workflow before reuse.

---

# Phase Sixteen: Protect Health, Legal, and Financial Information

## 46. Health Information

Use additional review for:

- Diagnoses
- Treatments
- Medications
- Medical records
- Disability information
- Insurance information
- Appointment information
- Health-related customer stories

---

## 47. Legal Information

Use additional review for:

- Case details
- Attorney communications
- Settlement information
- Court records
- Contracts
- Disputes
- Regulatory investigations
- Privileged communications

---

## 48. Financial Information

Use additional review for:

- Account balances
- Transaction history
- Credit information
- Tax records
- Loan information
- Payment details
- Investment information
- Income information
- Debt information

---

## 49. High-Sensitivity Review

Confirm:

- [ ] Specialized review is assigned.
- [ ] Tool approval is explicit.
- [ ] Data is minimized.
- [ ] Identifiers are removed where possible.
- [ ] Access is restricted.
- [ ] Retention is limited.
- [ ] Human approval is documented.
- [ ] Outputs cannot reveal the source information.
- [ ] Legal or compliance requirements are addressed.

---

# Phase Seventeen: Review Retrieval Systems

## 50. Retrieval-System Risks

Review:

- Incorrect document permissions
- Retrieval across restricted collections
- Stale confidential information
- Retired documents
- Hidden metadata
- Cross-customer exposure
- Private citations
- Unauthorized source display
- Overly broad search access
- Generated summaries that reveal protected details

---

## 51. Retrieval-System Record

| System | Data Collections | Access Rules | Status |
|---|---|---|---|
| [System] | [Collections] | [Rules] | Approved / Revise |
| [System] | [Collections] | [Rules] | Approved / Revise |

---

## 52. Retrieval Review

Confirm:

- [ ] Collections are approved.
- [ ] Access boundaries are tested.
- [ ] Customer data is separated appropriately.
- [ ] Restricted documents are excluded.
- [ ] Retired documents are removed.
- [ ] Citations respect permissions.
- [ ] Generated outputs are reviewed for exposure.
- [ ] Access changes trigger testing.
- [ ] Audit logs are available.

---

# Phase Eighteen: Review Custom GPTs and AI Agents

## 53. Custom GPT Risks

Review:

- Uploaded knowledge files
- Shared links
- Conversation retention
- User access
- File permissions
- Prompt instructions
- Generated citations
- Sensitive retrieval
- Exported conversations

---

## 54. AI Agent Risks

Review:

- Connected applications
- Write permissions
- Email access
- Calendar access
- CRM access
- File access
- Automated messages
- Data transfers
- Deletion authority
- Escalation behavior

---

## 55. GPT and Agent Review

Confirm:

- [ ] Knowledge files are approved.
- [ ] Permissions are limited.
- [ ] Connections are documented.
- [ ] Write actions require approval where appropriate.
- [ ] Sensitive systems are restricted.
- [ ] Outputs are monitored.
- [ ] Logs are preserved.
- [ ] Access can be revoked.
- [ ] Retired files are removed.
- [ ] Model or tool changes trigger review.

---

# Phase Nineteen: Review Generated Outputs

## 56. Output Exposure Risks

Generated outputs may:

- Repeat private information
- Infer sensitive attributes
- Reveal confidential strategy
- Expose customer records
- Combine harmless fields into identifying profiles
- Present internal notes as public facts
- Quote private messages
- Cite restricted documents
- Include hidden file names or URLs

---

## 57. Output Review

Confirm:

- [ ] Personal information is removed.
- [ ] Confidential information is removed.
- [ ] Restricted details are removed.
- [ ] Sensitive inferences are reviewed.
- [ ] Quotations are approved.
- [ ] Citations are appropriate.
- [ ] File names and URLs are safe.
- [ ] Output audience is appropriate.
- [ ] Human approval is recorded.

---

# Phase Twenty: Define Incident Response

## 58. Incident Categories

### Minor

Examples:

- Noncritical internal information exposed internally
- Accidental inclusion of a low-risk identifier
- Incorrect access label caught before publication

### Material

Examples:

- Customer information exposed to an unauthorized person
- Confidential document indexed incorrectly
- Sensitive data entered into an unapproved tool
- Private message quoted publicly

### Critical

Examples:

- Credentials exposed
- Restricted health or financial information exposed
- Large-scale customer-record exposure
- Cross-customer data leakage
- Security information exposed
- Ongoing automated disclosure

---

## 59. Incident Response Workflow

```text
Identify the incident
        ↓
Stop the activity
        ↓
Restrict access
        ↓
Classify severity
        ↓
Notify privacy and security owners
        ↓
Preserve evidence
        ↓
Remove, revoke, rotate, or delete
        ↓
Assess notification obligations
        ↓
Correct related outputs and systems
        ↓
Document and reapprove
```

---

## 60. Incident Record

| Field | Information |
|---|---|
| Incident | [Describe] |
| Discovery date | [Date] |
| Data involved | [Describe] |
| People affected | [Describe] |
| Systems affected | [Describe] |
| Severity | Minor / Material / Critical |
| Immediate action | [Describe] |
| Notification required | Yes / No / Review |
| Deletion completed | Yes / No |
| Credentials rotated | Yes / No / Not applicable |
| Approved by | [Name] |

---

# Phase Twenty-One: Correct and Notify

## 61. Correction Actions

Possible actions:

- Remove the output
- Replace the output
- Redact information
- Delete uploaded data
- Revoke access
- Rotate credentials
- Correct permissions
- Remove indexed documents
- Update automations
- Update retrieval systems
- Notify affected people
- Notify vendors
- Notify regulators or legal counsel where required

---

## 62. Notification Record

| Audience | Reason | Channel | Approved By |
|---|---|---|---|
| [Audience] | [Reason] | [Channel] | [Name] |
| [Audience] | [Reason] | [Channel] | [Name] |

---

## 63. Notification Principles

Communication should:

- Be accurate
- Be timely
- Explain what happened
- Explain what information was involved
- Explain what was done
- Explain what the affected person should do
- Avoid minimizing material harm
- Avoid speculative claims
- Provide a contact path

---

# Phase Twenty-Two: Delete Data

## 64. Deletion Triggers

Delete when:

- Purpose is complete
- Retention period ends
- Permission is withdrawn
- Data was uploaded accidentally
- Tool use is no longer approved
- A customer requests deletion where applicable
- An incident requires deletion
- Data is duplicated unnecessarily
- The workflow is retired

---

## 65. Deletion Record

| Data | System | Deletion Date | Verified By |
|---|---|---|---|
| [Data] | [System] | [Date] | [Name] |
| [Data] | [System] | [Date] | [Name] |

---

## 66. Deletion Review

Confirm:

- [ ] Primary copy is removed.
- [ ] Uploaded copy is removed.
- [ ] Exported copy is removed.
- [ ] Temporary copy is removed.
- [ ] Retrieval index is updated.
- [ ] Automation cache is updated.
- [ ] Backup handling is documented.
- [ ] Deletion is verified.
- [ ] Audit record is preserved.

---

# Phase Twenty-Three: Escalate Privacy Risks

## 67. Escalation Triggers

Escalate when:

- Data classification is uncertain
- Permission is unclear
- Restricted data is involved
- Credentials are exposed
- Cross-customer exposure is possible
- Large-scale exposure occurs
- Vendor behavior is unclear
- Deletion cannot be confirmed
- Legal obligations may apply
- A vulnerable person may be harmed
- The system continues exposing information

---

## 68. Escalation Record

| Trigger | First Contact | Final Authority | Response Time |
|---|---|---|---|
| [Trigger] | [Contact] | [Authority] | [Time] |
| [Trigger] | [Contact] | [Authority] | [Time] |

---

# Phase Twenty-Four: Renew Approval

## 69. Reapproval Triggers

Require renewed approval when changing:

- Business purpose
- Data source
- Data category
- Data sensitivity
- Permission
- Tool
- Vendor
- Model
- Storage location
- Retention period
- Training use
- Access controls
- Retrieval system
- Agent permissions
- Automation level
- Audience
- Output destination
- Deletion process
- Legal or policy requirements

---

## 70. Change Record

| Element | Approved Version | Changed Version | Reapproval Required |
|---|---|---|---|
| [Element] | [Approved] | [Changed] | Yes / No |
| [Element] | [Approved] | [Changed] | Yes / No |

---

# Phase Twenty-Five: Use AI Responsibly in Privacy Review

## 71. Approved AI Uses

AI may assist with:

- Identifying possible personal information
- Identifying possible credentials
- Grouping data categories
- Comparing versions
- Preparing preliminary redaction lists
- Identifying possible permission gaps
- Summarizing access records
- Identifying possible retention conflicts
- Preparing incident timelines

---

## 72. Prohibited AI Uses

AI should not:

- Approve its own data access
- Decide permission exists
- Decide data is anonymous without review
- Decide legal obligations
- Delete evidence automatically
- Notify affected people without approval
- Override privacy reviewers
- Reveal sensitive information during review
- Expand data use without approval
- Retain prohibited data

---

## 73. AI Privacy Review Record

| AI Task | Tool | Approved Inputs | Human Reviewer |
|---|---|---|---|
| [Task] | [Tool] | [Inputs] | [Reviewer] |
| [Task] | [Tool] | [Inputs] | [Reviewer] |

---

# Phase Twenty-Six: Score the Data Practice

## 74. Scoring Scale

Use:

- 5: Strong and complete
- 4: Effective with minor gaps
- 3: Mixed
- 2: Weak
- 1: Unsafe, unauthorized, or missing

---

## 75. Privacy and Confidentiality Scorecard

| Area | Score | Evidence | Required Action |
|---|---:|---|---|
| Business purpose | [1–5] | [Evidence] | [Action] |
| Data inventory | [1–5] | [Evidence] | [Action] |
| Data classification | [1–5] | [Evidence] | [Action] |
| Data minimization | [1–5] | [Evidence] | [Action] |
| Redaction | [1–5] | [Evidence] | [Action] |
| Anonymization | [1–5] | [Evidence] | [Action] |
| Permission | [1–5] | [Evidence] | [Action] |
| Tool approval | [1–5] | [Evidence] | [Action] |
| Vendor review | [1–5] | [Evidence] | [Action] |
| Storage | [1–5] | [Evidence] | [Action] |
| Retention | [1–5] | [Evidence] | [Action] |
| Training use | [1–5] | [Evidence] | [Action] |
| Access controls | [1–5] | [Evidence] | [Action] |
| Uploaded-file controls | [1–5] | [Evidence] | [Action] |
| Screenshot controls | [1–5] | [Evidence] | [Action] |
| Transcript controls | [1–5] | [Evidence] | [Action] |
| CRM controls | [1–5] | [Evidence] | [Action] |
| Credential protection | [1–5] | [Evidence] | [Action] |
| High-sensitivity protection | [1–5] | [Evidence] | [Action] |
| Retrieval controls | [1–5] | [Evidence] | [Action] |
| Agent controls | [1–5] | [Evidence] | [Action] |
| Output review | [1–5] | [Evidence] | [Action] |
| Incident response | [1–5] | [Evidence] | [Action] |
| Notification | [1–5] | [Evidence] | [Action] |
| Deletion | [1–5] | [Evidence] | [Action] |
| Escalation | [1–5] | [Evidence] | [Action] |
| Reapproval | [1–5] | [Evidence] | [Action] |
| Responsible AI assistance | [1–5] | [Evidence] | [Action] |

### Total Score

[Enter score.]

---

# Phase Twenty-Seven: Approve the Data Use

## 76. Final Approval Checklist

Confirm:

- [ ] Business purpose is defined.
- [ ] Data inventory is complete.
- [ ] Data classification is complete.
- [ ] Prohibited data is excluded.
- [ ] Data is minimized.
- [ ] Redaction is complete.
- [ ] Anonymization is reviewed.
- [ ] Permission is documented.
- [ ] Tool is approved.
- [ ] Vendor is reviewed.
- [ ] Storage is approved.
- [ ] Retention is defined.
- [ ] Training use is understood.
- [ ] Access is restricted.
- [ ] Retrieval systems are reviewed.
- [ ] Agents and automations are reviewed.
- [ ] Generated outputs are reviewed.
- [ ] Incident response is available.
- [ ] Deletion is available.
- [ ] Escalation is available.
- [ ] Exact version is identified.
- [ ] Final approver has authority.

---

## 77. Final Approval Statement

Use:

```text
I reviewed the exact data use described in this record, including its purpose, sources, classification, permissions, tool, vendor, storage, retention, access, training use, outputs, controls, and deletion process.

I approve this use:
[Approval decision]

Conditions:
[Conditions]
```

### Final Approver

[Name and role.]

### Approval Date

[Date.]

---

## 78. Critical Stop Conditions

Do not proceed when:

- [ ] Purpose is unclear.
- [ ] Data source is unknown.
- [ ] Classification is incomplete.
- [ ] Prohibited data is included.
- [ ] Permission is missing.
- [ ] Tool approval is missing.
- [ ] Vendor handling is unclear.
- [ ] Sensitive data is not minimized.
- [ ] Storage is unapproved.
- [ ] Access cannot be controlled.
- [ ] Deletion is unavailable where required.
- [ ] Incident response is unavailable.
- [ ] Final approval is missing.
- [ ] Another critical issue exists: [Describe]

---

# Phase Twenty-Eight: Pause or Retire the Data Practice

## 79. Pause Triggers

Pause when:

- Permission is questioned
- Vendor terms change
- Tool behavior changes
- Access controls fail
- Deletion cannot be confirmed
- Monitoring fails
- Data classification changes
- An incident occurs
- A reviewer objects
- A legal or policy question appears

---

## 80. Retirement Triggers

Retire when:

- Purpose no longer exists
- Data use is no longer authorized
- Tool is no longer approved
- Vendor risk becomes unacceptable
- Data cannot be protected adequately
- Deletion requirements cannot be met
- A safer process replaces it
- Required oversight is unavailable
- Repeated incidents occur

---

## 81. Retirement Record

| Field | Information |
|---|---|
| Data practice | [Describe] |
| Retirement reason | [Reason] |
| Retirement date | [Date] |
| Approved by | [Name] |
| Replacement | [Process or “None”] |
| Data deleted | Yes / No |
| Access removed | Yes / No |
| Automation disabled | Yes / No |
| Retrieval disabled | Yes / No |
| Archive location | [Location] |

---

# Quick AI Data Privacy and Confidentiality Guide

## Define

- [ ] Business purpose defined
- [ ] Activity owner assigned
- [ ] Data owner assigned
- [ ] People represented identified
- [ ] Tool identified
- [ ] Vendor identified

## Classify

- [ ] Public data identified
- [ ] Internal data identified
- [ ] Confidential data identified
- [ ] Restricted data identified
- [ ] Prohibited data excluded
- [ ] Sensitivity documented

## Minimize

- [ ] Unnecessary fields removed
- [ ] Identifiers removed
- [ ] Redaction completed
- [ ] Anonymization reviewed
- [ ] Aggregation considered
- [ ] Full-file upload avoided where possible

## Approve

- [ ] Permission confirmed
- [ ] Tool approved
- [ ] Vendor reviewed
- [ ] Storage approved
- [ ] Retention defined
- [ ] Training use understood
- [ ] Access controlled
- [ ] Final approval recorded

## Protect

- [ ] Credentials excluded
- [ ] Account information protected
- [ ] Health information protected
- [ ] Legal information protected
- [ ] Financial information protected
- [ ] Screenshots reviewed
- [ ] Transcripts reviewed
- [ ] CRM notes reviewed
- [ ] Private messages reviewed

## Control

- [ ] Retrieval systems reviewed
- [ ] Custom GPTs reviewed
- [ ] Agents reviewed
- [ ] Automations reviewed
- [ ] Generated outputs reviewed
- [ ] Audit logs preserved

## Respond

- [ ] Incident process available
- [ ] Correction process available
- [ ] Notification process available
- [ ] Deletion process available
- [ ] Escalation path available
- [ ] Reapproval triggers defined

## Continue

- [ ] Access reviewed regularly
- [ ] Retention reviewed regularly
- [ ] Vendor changes monitored
- [ ] Tool changes monitored
- [ ] Version history preserved
- [ ] Retirement process available

---

# Governance

## 82. Ownership

| Responsibility | Owner |
|---|---|
| Privacy policy | [Name] |
| Data ownership | [Name] |
| Data classification | [Name] |
| Tool approval | [Name] |
| Vendor review | [Name] |
| Security | [Name] |
| Access control | [Name] |
| Storage | [Name] |
| Retention | [Name] |
| Training-use review | [Name] |
| Retrieval systems | [Name] |
| AI agents | [Name] |
| Automations | [Name] |
| Incident response | [Name] |
| Notification | [Name] |
| Deletion | [Name] |
| Escalation | [Name] |
| Audit | [Name] |
| Retirement | [Name] |
| Final approval | [Name] |

---

## 83. Version Naming

Use:

```text
[activity-name]_ai-data-privacy-review_v[version]_[date]
```

Example:

```text
customer-interview-analysis_ai-data-privacy-review_v1.0_2026-08-04
```

---

## 84. Changes Requiring Reapproval

Require reapproval when changing:

- Business purpose
- Data source
- Data category
- Data sensitivity
- Permission
- Tool
- Vendor
- Model
- Storage
- Retention
- Training use
- Access controls
- Retrieval system
- Agent permissions
- Automation
- Audience
- Output destination
- Deletion process
- Other: [Describe]

---

## 85. Version History

| Version | Date | Author | Change | Reason | Approved By |
|---|---|---|---|---|---|
| 1.0 | [Date] | [Name] | Initial guide | Guide creation | [Name] |
| [Version] | [Date] | [Name] | [Change] | [Reason] | [Name] |

---

## Important Principle

Privacy is not achieved by hiding the spreadsheet after every system has copied it.

Confidentiality is not preserved by trusting that nobody will ask the AI the wrong question.

Protection begins before the upload.

It asks what data is truly needed, who owns it, who permitted its use, where it will travel, how long it will remain, who can retrieve it, and what happens when the system produces something it should never have revealed.

AI may help identify possible sensitive information, compare permissions, organize inventories, and flag risky fields.

A human must still decide whether the data should enter the system at all.

---

## Related Resources

### Responsible AI

- [Responsible AI Marketing Principles](responsible-ai-marketing-principles.md)
- [AI Use Risk Classification Guide](ai-use-risk-classification-guide.md)
- [Human Approval and Oversight Guide](human-approval-and-oversight-guide.md)

### Frameworks

- [Human Approval Before Execution Framework](../frameworks/human-approval-before-execution.md)
- [Context Before Creation Framework](../frameworks/context-before-creation.md)
- [Brand Voice AI Foundation Framework](../frameworks/brand-voice-ai-foundation.md)

### Checklists

- [Confidential Information Protection Checklist](../checklists/confidential-information-protection-checklist.md)
- [AI-Generated Content Review Checklist](../checklists/ai-generated-content-review-checklist.md)
- [Fact and Source Verification Checklist](../checklists/fact-and-source-verification-checklist.md)
- [Automated Communications Approval Checklist](../checklists/automated-communications-approval-checklist.md)

### Templates

- [Approval Workflow Template](../templates/approval-workflow-template.md)
- [Standard Operating Procedure Template](../templates/standard-operating-procedure-template.md)
- [Customer Interview Template](../templates/customer-interview-template.md)

### Workflows

- [Knowledge Ingestion and Grounding Workflow](../workflows/knowledge-ingestion-and-grounding-workflow.md)
- [Customer Research Workflow](../workflows/customer-research-workflow.md)
- [Content Review Workflow](../workflows/content-review-workflow.md)
- [Email Development Workflow](../workflows/email-development-workflow.md)
- [Social Media Publishing Workflow](../workflows/social-media-publishing-workflow.md)

### Content Strategy

- [Content Editing Guide](../content-strategy/content-editing-guide.md)
- [Content Publication Readiness Guide](../content-strategy/content-publication-readiness-guide.md)
- [Content Refresh and Retirement Guide](../content-strategy/content-refresh-and-retirement-guide.md)

### Projects

- [AI Marketing Resources](https://github.com/poguedigitalsolutions/ai-marketing-resources)
- [Brand Voice AI Skool](https://www.skool.com/companyvoiceai-6106/about)
- [Pogue Digital Solutions, LLC](https://poguedigitalsolutions.com)

---

## Copyright

Copyright © John M. Pogue and Pogue Digital Solutions, LLC.

All rights reserved unless otherwise stated.
