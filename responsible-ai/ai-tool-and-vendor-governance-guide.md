# AI Tool and Vendor Governance Guide

Use this guide to evaluate, approve, restrict, monitor, renew, suspend, and retire AI tools and vendors used in marketing, customer communication, research, automation, analytics, and content systems.

This guide is part of the **Brand Voice AI** methodology developed by **John M. Pogue** and **Pogue Digital Solutions, LLC**.

> An AI tool should not enter the organization simply because it is impressive, inexpensive, popular, or connected by one cheerful button. Convenience is not governance.

---

## Guide Purpose

The AI Tool and Vendor Governance Guide helps organizations:

- Define the business purpose for an AI tool
- Evaluate tools before approval
- Evaluate vendors before approval
- Review data handling
- Review data storage
- Review data retention
- Review model-training use
- Review deletion options
- Review access controls
- Review security
- Review subprocessors
- Review geographic processing
- Review privacy practices
- Review model limitations
- Review reliability
- Review explainability
- Review export options
- Review auditability
- Review vendor support
- Review pricing
- Review ownership
- Review licensing
- Review contractual terms
- Review policy changes
- Define approved uses
- Define restricted uses
- Define prohibited uses
- Control integrations
- Control connectors
- Control plugins
- Control APIs
- Control AI agents
- Control write permissions
- Control automated actions
- Assign tool ownership
- Assign reviewers
- Assign approvers
- Assign renewal dates
- Assign monitoring responsibilities
- Reassess tools after model updates
- Reassess tools after incidents
- Reassess tools after vendor changes
- Reassess tools after expanded use
- Suspend tools when controls fail
- Retire tools that no longer meet requirements
- Prevent convenience from outrunning judgment

This guide may be used for:

- Generative AI platforms
- Custom GPTs
- AI assistants
- AI agents
- Retrieval systems
- Image-generation tools
- Video-generation tools
- Audio-generation tools
- Transcription tools
- Translation tools
- Analytics platforms
- Marketing automation tools
- Customer-support platforms
- Sales-enablement tools
- CRM extensions
- Browser extensions
- Plugins
- Connectors
- APIs
- Data-enrichment tools
- Recommendation systems
- Personalization systems
- Advertising tools
- Research tools
- Content-management integrations

---

# Tool and Vendor Governance Overview

```text
Define the business purpose
        ↓
Identify intended users, data, actions, and affected people
        ↓
Review the tool and vendor
        ↓
Classify risk
        ↓
Define approved, restricted, and prohibited uses
        ↓
Review integrations, access, and automation
        ↓
Human approval
        ↓
Pilot and test
        ↓
Activate with monitoring
        ↓
Renew, restrict, suspend, replace, or retire
```

---

# Tool Review Record

## 1. Tool Information

| Field | Information |
|---|---|
| Tool name | [Enter name] |
| Vendor | [Enter vendor] |
| Product version | [Enter version] |
| Model name | [Enter model] |
| Model version | [Enter version or “Unknown”] |
| Business purpose | [Describe purpose] |
| Marketing function | [Enter function] |
| Intended users | [Describe users] |
| People affected | [Describe] |
| Data used | [Describe] |
| Outputs produced | [Describe] |
| Connected systems | [List systems] |
| Automation level | Assistive / Recommendatory / Conditional / Autonomous |
| Customer-facing | Yes / No |
| Risk level | Low / Moderate / High / Prohibited |
| Tool owner | [Enter name] |
| Vendor owner | [Enter name] |
| Privacy reviewer | [Enter name] |
| Security reviewer | [Enter name] |
| Legal or contract reviewer | [Enter name] |
| Final approver | [Enter name and role] |
| Approval date | [Enter date] |
| Renewal date | [Enter date] |
| Current status | Proposed / Pilot / Approved / Restricted / Suspended / Retired |

---

## 2. Governance Decision

Select one:

- [ ] Approved
- [ ] Approved for pilot
- [ ] Approved with restrictions
- [ ] Approved for internal use only
- [ ] Approved for public data only
- [ ] Approved without write access
- [ ] Approved without customer-facing use
- [ ] Additional privacy review required
- [ ] Additional security review required
- [ ] Additional legal or contract review required
- [ ] Additional testing required
- [ ] Vendor clarification required
- [ ] Restricted
- [ ] Suspended
- [ ] Prohibited
- [ ] Retired

### Decision Summary

[Explain.]

### Approved Uses

- [Use]
- [Use]
- [Use]

### Restricted Uses

- [Use]
- [Use]
- [Use]

### Prohibited Uses

- [Use]
- [Use]
- [Use]

### Required Controls

- [Control]
- [Control]
- [Control]

---

# Phase One: Define the Business Purpose

## 3. Purpose Statement

Use:

```text
The organization is considering this tool to:
[Describe the specific task]

The intended benefit is:
[Describe the benefit]

The current process is:
[Describe the current process]

The reason AI may be appropriate is:
[Explain]

The decision this review must support is:
Approve / Restrict / Reject / Pilot / Replace
```

---

## 4. Purpose Review

Confirm:

- [ ] Purpose is specific.
- [ ] Purpose is legitimate.
- [ ] Intended users are identified.
- [ ] Affected people are identified.
- [ ] Expected benefit is documented.
- [ ] Possible harm is documented.
- [ ] A non-AI alternative was considered.
- [ ] The tool is not being adopted merely because it is fashionable.
- [ ] The proposed use matches organizational values.
- [ ] Success can be measured.

---

# Phase Two: Define the Intended Use

## 5. Intended-Use Categories

Possible uses:

- Brainstorming
- Research assistance
- Summarization
- Content drafting
- Editing
- Image generation
- Video generation
- Audio generation
- Translation
- Transcription
- Customer communication
- Personalization
- Segmentation
- Lead scoring
- Customer support
- Analytics
- Reporting
- Automation
- Recommendation
- Record updates
- Publishing
- Other: [Describe]

---

## 6. Intended-Use Record

| Use | User Group | Data Used | Output or Action |
|---|---|---|---|
| [Use] | [Users] | [Data] | [Output] |
| [Use] | [Users] | [Data] | [Output] |
| [Use] | [Users] | [Data] | [Output] |

---

## 7. Use-Boundary Review

Confirm:

- [ ] Intended uses are documented.
- [ ] Restricted uses are documented.
- [ ] Prohibited uses are documented.
- [ ] Customer-facing uses are identified.
- [ ] High-risk uses are identified.
- [ ] Autonomous actions are identified.
- [ ] Data boundaries are documented.
- [ ] Approval boundaries are documented.
- [ ] Users know what the tool may not do.

---

# Phase Three: Review the Vendor

## 8. Vendor Information

| Field | Information |
|---|---|
| Legal vendor name | [Enter name] |
| Website | [Enter URL] |
| Headquarters | [Enter location] |
| Service region | [Enter region] |
| Contracting entity | [Enter entity] |
| Support contact | [Enter contact] |
| Security contact | [Enter contact] |
| Privacy contact | [Enter contact] |
| Incident contact | [Enter contact] |

---

## 9. Vendor Review Areas

Review:

- Company stability
- Ownership
- Reputation
- Security history
- Privacy history
- Incident history
- Support quality
- Documentation quality
- Transparency
- Subprocessors
- Contract terms
- Data-processing terms
- Change-notification practices
- Product roadmap
- Exit options

---

## 10. Vendor Review Record

| Review Area | Finding | Risk |
|---|---|---|
| Company stability | [Finding] | Low / Moderate / High |
| Security history | [Finding] | Low / Moderate / High |
| Privacy history | [Finding] | Low / Moderate / High |
| Support | [Finding] | Low / Moderate / High |
| Transparency | [Finding] | Low / Moderate / High |
| Contract terms | [Finding] | Low / Moderate / High |
| Exit options | [Finding] | Low / Moderate / High |

---

## 11. Vendor Review

Confirm:

- [ ] Vendor identity is verified.
- [ ] Vendor contact information is current.
- [ ] Vendor policies are available.
- [ ] Security documentation is available.
- [ ] Privacy documentation is available.
- [ ] Incident reporting process is available.
- [ ] Support process is understood.
- [ ] Contracting entity is identified.
- [ ] Vendor changes trigger renewed review.

---

# Phase Four: Review Data Handling

## 12. Data Categories

Review whether the tool receives:

- Public data
- Internal data
- Confidential data
- Restricted data
- Personal information
- Customer information
- Employee information
- Financial information
- Health information
- Legal information
- Authentication information
- Proprietary information
- Uploaded files
- Connected-system data
- Generated outputs

---

## 13. Data-Handling Record

| Data Type | Purpose | Vendor Handling | Decision |
|---|---|---|---|
| [Data] | [Purpose] | [Handling] | Approved / Restricted / Prohibited |
| [Data] | [Purpose] | [Handling] | Approved / Restricted / Prohibited |
| [Data] | [Purpose] | [Handling] | Approved / Restricted / Prohibited |

---

## 14. Data-Handling Review

Confirm:

- [ ] Data categories are documented.
- [ ] Data purpose is documented.
- [ ] Data minimization is applied.
- [ ] Prohibited data is excluded.
- [ ] Sensitive data has additional review.
- [ ] Data-processing locations are known.
- [ ] Data transfers are understood.
- [ ] Generated outputs are classified.
- [ ] Users understand data restrictions.

---

# Phase Five: Review Storage and Retention

## 15. Storage Questions

Ask:

- Where are inputs stored?
- Where are outputs stored?
- Where are logs stored?
- Where are uploaded files stored?
- Which countries or regions are involved?
- Is data encrypted?
- Are backups created?
- Are temporary files retained?
- Can the organization choose storage locations?

---

## 16. Retention Questions

Ask:

- How long are prompts retained?
- How long are files retained?
- How long are outputs retained?
- How long are logs retained?
- Can retention be shortened?
- Can retention be disabled?
- Are backups included in deletion?
- What happens after account closure?

---

## 17. Storage and Retention Record

| Data | Storage Location | Retention Period | Decision |
|---|---|---|---|
| [Data] | [Location] | [Period] | Approved / Revise |
| [Data] | [Location] | [Period] | Approved / Revise |

---

## 18. Storage and Retention Review

Confirm:

- [ ] Storage location is approved.
- [ ] Retention is understood.
- [ ] Retention matches the business purpose.
- [ ] Data is not retained indefinitely without reason.
- [ ] Backups are considered.
- [ ] Account closure behavior is understood.
- [ ] Retention changes trigger review.
- [ ] Deletion can be verified where required.

---

# Phase Six: Review Model-Training Use

## 19. Training-Use Questions

Ask:

- Are prompts used to train models?
- Are files used to train models?
- Are outputs used to improve services?
- Can training use be disabled?
- Is opt-out available?
- Does the contract override public policy?
- Are enterprise settings different?
- Are subprocessors involved?
- Can vendor staff review inputs?

---

## 20. Training-Use Record

| Data Type | Training Use | Opt-Out | Decision |
|---|---|---|---|
| [Data] | Yes / No / Unclear | Available / Unavailable | Approved / Restricted / Prohibited |
| [Data] | Yes / No / Unclear | Available / Unavailable | Approved / Restricted / Prohibited |

---

## 21. Training-Use Review

Confirm:

- [ ] Training use is understood.
- [ ] Opt-out status is documented.
- [ ] Enterprise terms are reviewed where applicable.
- [ ] Sensitive data is excluded where required.
- [ ] Confidential data is excluded where required.
- [ ] Human vendor review is understood.
- [ ] Policy changes trigger renewed approval.
- [ ] Users know whether their inputs may train models.

---

# Phase Seven: Review Security

## 22. Security Review Areas

Review:

- Encryption in transit
- Encryption at rest
- Authentication
- Multi-factor authentication
- Role-based access
- Single sign-on
- Audit logs
- Security testing
- Vulnerability management
- Incident response
- Backup security
- Administrative access
- Data isolation
- Tenant isolation
- API security
- Secure deletion

---

## 23. Security Record

| Control | Vendor Capability | Status |
|---|---|---|
| Encryption in transit | [Capability] | Approved / Revise |
| Encryption at rest | [Capability] | Approved / Revise |
| Multi-factor authentication | [Capability] | Approved / Revise |
| Role-based access | [Capability] | Approved / Revise |
| Audit logs | [Capability] | Approved / Revise |
| Incident response | [Capability] | Approved / Revise |
| Tenant isolation | [Capability] | Approved / Revise |

---

## 24. Security Review

Confirm:

- [ ] Authentication controls are sufficient.
- [ ] Administrative access is controlled.
- [ ] Audit logs are available.
- [ ] Data isolation is understood.
- [ ] Incident process is documented.
- [ ] Security contact is available.
- [ ] Credentials can be revoked.
- [ ] API keys can be rotated.
- [ ] Security changes trigger review.
- [ ] High-risk use has specialist approval.

---

# Phase Eight: Review Subprocessors and Connected Services

## 25. Subprocessor Questions

Ask:

- Which subprocessors receive data?
- What role does each subprocessor perform?
- Where does each subprocessor operate?
- Can the list change?
- Is change notification available?
- Can the organization object?
- Do subprocessors use data for training?
- Do they retain data independently?

---

## 26. Subprocessor Record

| Subprocessor | Purpose | Data Received | Risk |
|---|---|---|---|
| [Name] | [Purpose] | [Data] | Low / Moderate / High |
| [Name] | [Purpose] | [Data] | Low / Moderate / High |

---

## 27. Subprocessor Review

Confirm:

- [ ] Subprocessors are identified.
- [ ] Roles are understood.
- [ ] Data flows are documented.
- [ ] Geographic locations are considered.
- [ ] Change notification is monitored.
- [ ] New subprocessors trigger review where required.
- [ ] Restricted data remains protected.

---

# Phase Nine: Review Model Capabilities and Limitations

## 28. Capability Review

Review:

- Supported inputs
- Supported outputs
- Context limits
- File limits
- Language support
- Image support
- Audio support
- Retrieval support
- Tool use
- Automation
- API access
- Export capability
- Version control

---

## 29. Limitation Review

Review:

- Hallucinations
- Source fabrication
- Inconsistent outputs
- Stale knowledge
- Bias
- Accessibility gaps
- Context loss
- Prompt sensitivity
- Long-document failure
- Calculation errors
- Citation errors
- Tool-use errors
- Automation errors
- Unpredictable updates

---

## 30. Capability and Limitation Record

| Capability or Limitation | Evidence | Operational Effect |
|---|---|---|
| [Item] | [Evidence] | [Effect] |
| [Item] | [Evidence] | [Effect] |
| [Item] | [Evidence] | [Effect] |

---

## 31. Limitation Review

Confirm:

- [ ] Limitations are documented.
- [ ] Users are trained on limitations.
- [ ] High-risk claims require verification.
- [ ] Outputs require human review.
- [ ] Unsupported automation is disabled.
- [ ] Model changes trigger renewed testing.
- [ ] Limitations influence approved uses.

---

# Phase Ten: Review Reliability

## 32. Reliability Areas

Test:

- Output consistency
- Availability
- Response time
- File handling
- Citation behavior
- Retrieval accuracy
- API stability
- Integration stability
- Rate limits
- Error handling
- Recovery behavior
- Version changes

---

## 33. Reliability Test Record

| Test | Expected Result | Actual Result | Status |
|---|---|---|---|
| [Test] | [Expected] | [Actual] | Pass / Fail |
| [Test] | [Expected] | [Actual] | Pass / Fail |
| [Test] | [Expected] | [Actual] | Pass / Fail |

---

## 34. Reliability Review

Confirm:

- [ ] Core use cases are tested.
- [ ] Failure behavior is tested.
- [ ] Rate limits are understood.
- [ ] Service availability is acceptable.
- [ ] Recovery process is available.
- [ ] Users know what to do when the tool fails.
- [ ] Critical workflows have fallback procedures.

---

# Phase Eleven: Review Explainability and Auditability

## 35. Explainability Questions

Ask:

- Can users understand how the output was produced?
- Can the organization identify the source material?
- Can recommendations be explained?
- Can decisions be challenged?
- Can output changes be traced?
- Can the organization identify the model and version?
- Can the organization identify the prompt and workflow?

---

## 36. Auditability Questions

Ask:

- Are logs available?
- Are user actions recorded?
- Are model actions recorded?
- Are approvals recorded?
- Are connected actions recorded?
- Can records be exported?
- Can records be retained?
- Can records be searched?

---

## 37. Explainability and Auditability Record

| Requirement | Capability | Status |
|---|---|---|
| Source traceability | [Capability] | Strong / Mixed / Weak |
| Model identification | [Capability] | Strong / Mixed / Weak |
| Prompt history | [Capability] | Strong / Mixed / Weak |
| Action logs | [Capability] | Strong / Mixed / Weak |
| Approval logs | [Capability] | Strong / Mixed / Weak |
| Export | [Capability] | Strong / Mixed / Weak |

---

# Phase Twelve: Review Export and Deletion

## 38. Export Review

Confirm:

- [ ] Data can be exported.
- [ ] Outputs can be exported.
- [ ] Logs can be exported.
- [ ] Configuration can be documented.
- [ ] Export format is usable.
- [ ] Export does not expose unnecessary data.
- [ ] Exit from the vendor is possible.

---

## 39. Deletion Review

Confirm:

- [ ] User data can be deleted.
- [ ] Uploaded files can be deleted.
- [ ] Outputs can be deleted.
- [ ] Account data can be deleted.
- [ ] Deletion timing is documented.
- [ ] Backup handling is understood.
- [ ] Deletion can be verified.
- [ ] Vendor support is available for deletion problems.

---

## 40. Export and Deletion Record

| Item | Export Available | Deletion Available | Status |
|---|---|---|---|
| [Item] | Yes / No | Yes / No | Approved / Revise |
| [Item] | Yes / No | Yes / No | Approved / Revise |

---

# Phase Thirteen: Review Ownership and Licensing

## 41. Ownership Questions

Ask:

- Who owns the input?
- Who owns the output?
- What rights does the vendor receive?
- Can the vendor reuse outputs?
- Can customers publish outputs?
- Are commercial rights granted?
- Are restrictions attached to media?
- Are third-party rights involved?

---

## 42. Licensing Questions

Ask:

- What license applies?
- Are commercial uses permitted?
- Are attribution requirements present?
- Are geographic restrictions present?
- Are duration restrictions present?
- Are model-specific restrictions present?
- Are open-source components involved?
- Are third-party assets included?

---

## 43. Ownership and Licensing Record

| Asset or Data | Owner | License | Restrictions |
|---|---|---|---|
| [Item] | [Owner] | [License] | [Restrictions] |
| [Item] | [Owner] | [License] | [Restrictions] |

---

## 44. Ownership Review

Confirm:

- [ ] Input ownership is clear.
- [ ] Output rights are clear.
- [ ] Commercial use is permitted.
- [ ] Attribution requirements are understood.
- [ ] Third-party rights are reviewed.
- [ ] Synthetic-media rights are reviewed.
- [ ] Licensing changes trigger renewed review.

---

# Phase Fourteen: Review Pricing and Commercial Terms

## 45. Pricing Areas

Review:

- Subscription price
- Per-user price
- Usage fees
- API fees
- Storage fees
- Overage fees
- Training fees
- Support fees
- Cancellation fees
- Renewal increases
- Minimum commitments
- Currency and tax treatment

---

## 46. Commercial-Term Record

| Cost Area | Current Cost | Risk |
|---|---:|---|
| Subscription | [Cost] | Low / Moderate / High |
| Usage | [Cost] | Low / Moderate / High |
| Storage | [Cost] | Low / Moderate / High |
| Support | [Cost] | Low / Moderate / High |
| Exit | [Cost] | Low / Moderate / High |

---

## 47. Commercial Review

Confirm:

- [ ] Total cost is understood.
- [ ] Variable costs are estimated.
- [ ] Overage risk is understood.
- [ ] Renewal terms are documented.
- [ ] Cancellation terms are documented.
- [ ] Vendor lock-in is considered.
- [ ] Business value justifies the cost.
- [ ] Pricing changes trigger review.

---

# Phase Fifteen: Review Contractual Terms

## 48. Contract Areas

Review:

- Data-processing terms
- Confidentiality
- Ownership
- Licensing
- Indemnification
- Liability
- Warranty
- Service levels
- Security obligations
- Incident notification
- Subprocessors
- Termination
- Data return
- Data deletion
- Audit rights
- Policy changes
- Governing law

---

## 49. Contract Review Record

| Contract Area | Finding | Required Action |
|---|---|---|
| Data handling | [Finding] | [Action] |
| Confidentiality | [Finding] | [Action] |
| Ownership | [Finding] | [Action] |
| Liability | [Finding] | [Action] |
| Incident notification | [Finding] | [Action] |
| Termination | [Finding] | [Action] |

---

## 50. Contract Review

Confirm:

- [ ] Contracting entity is correct.
- [ ] Data-processing terms are acceptable.
- [ ] Confidentiality terms are acceptable.
- [ ] Ownership terms are acceptable.
- [ ] Liability terms are reviewed.
- [ ] Incident-notification terms are reviewed.
- [ ] Termination rights are understood.
- [ ] Data-return and deletion terms are understood.
- [ ] Contract changes trigger reapproval.

---

# Phase Sixteen: Define Approved, Restricted, and Prohibited Uses

## 51. Approved Uses

Use when:

- Business purpose is documented
- Tool is appropriate
- Data is approved
- Risk is controlled
- Human review is available
- Required monitoring is active

---

## 52. Restricted Uses

Restrictions may include:

- Internal use only
- Public data only
- No personal data
- No confidential data
- No customer-facing output
- No autonomous action
- No write access
- No publishing
- No regulated claims
- No synthetic likenesses
- Pilot use only
- Defined user group only

---

## 53. Prohibited Uses

Prohibit uses involving:

- Unauthorized data
- Credentials
- Deceptive impersonation
- Unsupported high-risk claims
- Uncontrolled autonomous action
- Vulnerable-audience exploitation
- Prohibited discrimination
- Unsafe data transfers
- Unapproved system access
- Activities violating law, contract, policy, or values

---

## 54. Use-Control Record

| Use | Classification | Required Control |
|---|---|---|
| [Use] | Approved / Restricted / Prohibited | [Control] |
| [Use] | Approved / Restricted / Prohibited | [Control] |
| [Use] | Approved / Restricted / Prohibited | [Control] |

---

# Phase Seventeen: Review Integrations and Connectors

## 55. Integration Types

Review:

- CRM connectors
- Email connectors
- Calendar connectors
- File-storage connectors
- Social-media connectors
- Advertising connectors
- Analytics connectors
- Payment connectors
- Customer-support connectors
- Database connectors
- Webhooks
- APIs
- Browser extensions
- Plugins

---

## 56. Integration Record

| Integration | Access | Data Flow | Status |
|---|---|---|---|
| [Integration] | Read / Write / Delete / Admin | [Flow] | Approved / Restricted |
| [Integration] | Read / Write / Delete / Admin | [Flow] | Approved / Restricted |

---

## 57. Integration Review

Confirm:

- [ ] Integration purpose is documented.
- [ ] Permissions are minimized.
- [ ] Write access is justified.
- [ ] Delete access is justified.
- [ ] Administrative access is restricted.
- [ ] Data flows are documented.
- [ ] Credentials are secured.
- [ ] Logs are available.
- [ ] Integration can be disconnected.
- [ ] Changes trigger renewed review.

---

# Phase Eighteen: Review APIs

## 58. API Review Areas

Review:

- Authentication
- Key storage
- Rate limits
- Usage limits
- Logging
- Error handling
- Data payloads
- Output retention
- Versioning
- Deprecation
- Write permissions
- Cost controls
- Monitoring
- Incident response

---

## 59. API Record

| API | Permission | Data | Owner |
|---|---|---|---|
| [API] | Read / Write / Delete | [Data] | [Owner] |
| [API] | Read / Write / Delete | [Data] | [Owner] |

---

## 60. API Review

Confirm:

- [ ] Keys are stored securely.
- [ ] Keys can be rotated.
- [ ] Permissions are minimized.
- [ ] Usage is monitored.
- [ ] Rate limits are understood.
- [ ] Cost limits are configured.
- [ ] API version changes are monitored.
- [ ] Errors do not expose sensitive data.
- [ ] Write actions require appropriate approval.

---

# Phase Nineteen: Review AI Agents and Write Permissions

## 61. Agent Capabilities

Agents may:

- Search data
- Read files
- Draft content
- Send messages
- Update records
- Create events
- Publish content
- Change campaigns
- Delete data
- Trigger workflows
- Call APIs
- Connect systems

---

## 62. Agent-Permission Record

| Capability | Permission | Human Approval |
|---|---|---|
| Read | Allowed / Restricted | [Requirement] |
| Write | Allowed / Restricted | [Requirement] |
| Send | Allowed / Restricted | [Requirement] |
| Publish | Allowed / Restricted | [Requirement] |
| Delete | Allowed / Restricted | [Requirement] |
| Purchase | Allowed / Prohibited | [Requirement] |
| Change records | Allowed / Restricted | [Requirement] |

---

## 63. Agent Review

Confirm:

- [ ] Agent purpose is specific.
- [ ] Permissions are minimal.
- [ ] Write access is restricted.
- [ ] Delete access is highly restricted.
- [ ] High-impact actions require human approval.
- [ ] Transaction limits are defined.
- [ ] Stop conditions are defined.
- [ ] Logs are preserved.
- [ ] Human override exists.
- [ ] Agent can be disabled quickly.
- [ ] Unexpected behavior triggers suspension.

---

# Phase Twenty: Pilot and Test

## 64. Pilot Scope

Define:

- Number of users
- Number of outputs
- Data categories
- Channels
- Time period
- Approved use cases
- Prohibited use cases
- Monitoring frequency
- Stop conditions
- Success measures

---

## 65. Pilot Record

| Field | Information |
|---|---|
| Pilot start date | [Date] |
| Pilot end date | [Date] |
| Users | [List] |
| Use cases | [List] |
| Data allowed | [List] |
| Data prohibited | [List] |
| Monitoring owner | [Name] |
| Stop authority | [Name] |

---

## 66. Pilot Test Areas

Test:

- Accuracy
- Reliability
- Privacy
- Security
- Accessibility
- Bias
- Disclosure
- Integration behavior
- Permission boundaries
- Logging
- Export
- Deletion
- Support response
- Cost behavior
- Failure recovery

---

## 67. Pilot Review

Confirm:

- [ ] Pilot scope is limited.
- [ ] Test users are trained.
- [ ] Prohibited data is excluded.
- [ ] High-risk actions are disabled.
- [ ] Monitoring is active.
- [ ] Stop conditions are tested.
- [ ] Results are documented.
- [ ] Approval is not assumed from successful demonstrations.
- [ ] Final production approval is separate.

---

# Phase Twenty-One: Train Users

## 68. Required Training Topics

Users should understand:

- Approved uses
- Restricted uses
- Prohibited uses
- Data classifications
- Privacy
- Confidentiality
- Source verification
- Model limitations
- Human approval
- Accessibility
- Bias
- Disclosure
- Incident reporting
- Credential protection
- Integration boundaries
- Version changes

---

## 69. Training Record

| User | Training Completed | Date | Access Approved |
|---|---|---|---|
| [Name] | Yes / No | [Date] | Yes / No |
| [Name] | Yes / No | [Date] | Yes / No |

---

## 70. Training Review

Confirm:

- [ ] Training is role-specific.
- [ ] Training includes practical examples.
- [ ] Data restrictions are clear.
- [ ] Incident reporting is explained.
- [ ] Users know how to stop unsafe use.
- [ ] Access is not granted before training.
- [ ] Refresher training is scheduled.
- [ ] Material tool changes trigger new training.

---

# Phase Twenty-Two: Assign Ownership

## 71. Ownership Matrix

| Responsibility | Owner |
|---|---|
| Business purpose | [Name] |
| Tool ownership | [Name] |
| Vendor relationship | [Name] |
| Data governance | [Name] |
| Privacy | [Name] |
| Security | [Name] |
| Legal or contract review | [Name] |
| User access | [Name] |
| Integrations | [Name] |
| APIs | [Name] |
| Agents | [Name] |
| Training | [Name] |
| Monitoring | [Name] |
| Incidents | [Name] |
| Renewal | [Name] |
| Retirement | [Name] |
| Final approval | [Name] |

---

# Phase Twenty-Three: Monitor the Tool and Vendor

## 72. Monitoring Areas

Monitor:

- Model updates
- Policy updates
- Pricing changes
- Contract changes
- Security incidents
- Privacy incidents
- Subprocessor changes
- Reliability
- Accuracy
- Bias
- Accessibility
- Support quality
- User complaints
- Data exposure
- Unauthorized integrations
- Agent behavior
- Cost spikes
- Approval bypass

---

## 73. Monitoring Record

| Signal | Threshold | Owner | Response |
|---|---|---|---|
| [Signal] | [Threshold] | [Owner] | [Response] |
| [Signal] | [Threshold] | [Owner] | [Response] |

---

## 74. Monitoring Frequency

Select:

- [ ] Every use
- [ ] Daily
- [ ] Weekly
- [ ] Monthly
- [ ] Quarterly
- [ ] Annual
- [ ] Event-based
- [ ] Continuous technical monitoring

---

# Phase Twenty-Four: Reassess After Change

## 75. Reassessment Triggers

Reassess when:

- Tool changes
- Model changes
- Vendor changes
- Pricing changes
- Policy changes
- Contract changes
- Data use expands
- Sensitive data is added
- Customer-facing use begins
- Automation increases
- New integration is added
- Write access is added
- Agent permissions expand
- Security incident occurs
- Privacy incident occurs
- Reliability declines
- Ownership changes
- Legal requirements change

---

## 76. Change Record

| Element | Approved State | Changed State | Reapproval Required |
|---|---|---|---|
| [Element] | [Approved] | [Changed] | Yes / No |
| [Element] | [Approved] | [Changed] | Yes / No |

---

## 77. Reassessment Review

Confirm:

- [ ] Change is documented.
- [ ] Previous approval is suspended where required.
- [ ] Risk is reclassified.
- [ ] New data use is reviewed.
- [ ] New integrations are reviewed.
- [ ] New permissions are reviewed.
- [ ] Users receive updated training.
- [ ] Monitoring is updated.
- [ ] Final approval is renewed.

---

# Phase Twenty-Five: Renew Approval

## 78. Renewal Review

At renewal, review:

- Continued business purpose
- Actual usage
- Unapproved usage
- Data categories
- Vendor performance
- Security
- Privacy
- Reliability
- Model changes
- Pricing
- Contract terms
- Support
- User feedback
- Incidents
- Monitoring results
- Alternative tools
- Exit readiness

---

## 79. Renewal Record

| Field | Information |
|---|---|
| Previous approval date | [Date] |
| Renewal review date | [Date] |
| Current business purpose | [Purpose] |
| Current users | [Users] |
| Current data | [Data] |
| Current risk | [Risk] |
| Incidents since approval | [List] |
| Material vendor changes | [List] |
| Renewal decision | Renew / Restrict / Suspend / Replace / Retire |
| Next renewal date | [Date] |
| Approved by | [Name] |

---

# Phase Twenty-Six: Suspend the Tool

## 80. Suspension Triggers

Suspend when:

- Security incident occurs
- Privacy incident occurs
- Data use becomes unclear
- Vendor terms become unacceptable
- Model behavior changes materially
- Tool reliability fails
- Automation acts outside approval
- Write permissions are misused
- Required monitoring fails
- Required reviewer is unavailable
- Contract expires
- Pricing becomes uncontrolled
- Subprocessor risk changes
- Legal concerns arise

---

## 81. Suspension Actions

Possible actions:

- Disable user access
- Revoke API keys
- Disconnect integrations
- Disable agents
- Disable write permissions
- Stop automated publishing
- Freeze new uploads
- Export records
- Preserve logs
- Notify users
- Begin reassessment

---

## 82. Suspension Record

| Field | Information |
|---|---|
| Tool | [Name] |
| Suspension reason | [Reason] |
| Suspension date | [Date] |
| Suspended by | [Name] |
| Access disabled | Yes / No |
| Integrations disabled | Yes / No |
| API keys revoked | Yes / No |
| Agents disabled | Yes / No |
| Data preserved | Yes / No |
| Reassessment owner | [Name] |

---

# Phase Twenty-Seven: Retire the Tool

## 83. Retirement Triggers

Retire when:

- Business purpose no longer exists
- Vendor no longer meets requirements
- Tool is no longer secure
- Data use is no longer permitted
- Reliability remains inadequate
- Repeated incidents occur
- Required controls cannot be maintained
- A safer tool replaces it
- Contract terms become unacceptable
- Pricing exceeds responsible value
- Export or deletion is inadequate
- Human oversight is unavailable

---

## 84. Retirement Plan

Include:

- Replacement tool
- Data export
- Data deletion
- Account closure
- Integration removal
- API-key revocation
- Agent shutdown
- User notification
- Workflow migration
- Archive location
- Contract termination
- Final audit

---

## 85. Retirement Record

| Field | Information |
|---|---|
| Tool | [Name] |
| Vendor | [Vendor] |
| Retirement reason | [Reason] |
| Retirement date | [Date] |
| Approved by | [Name] |
| Replacement | [Tool or “None”] |
| Data exported | Yes / No |
| Data deleted | Yes / No |
| Integrations removed | Yes / No |
| API keys revoked | Yes / No |
| Agents disabled | Yes / No |
| Accounts closed | Yes / No |
| Archive location | [Location] |

---

# Tool and Vendor Governance Scorecard

## 86. Scoring Scale

Use:

- 5: Strong and complete
- 4: Effective with minor gaps
- 3: Mixed
- 2: Weak
- 1: Unsafe, unacceptable, or missing

---

## 87. Scorecard

| Area | Score | Evidence | Required Action |
|---|---:|---|---|
| Business purpose | [1–5] | [Evidence] | [Action] |
| Intended-use clarity | [1–5] | [Evidence] | [Action] |
| Vendor stability | [1–5] | [Evidence] | [Action] |
| Vendor transparency | [1–5] | [Evidence] | [Action] |
| Data handling | [1–5] | [Evidence] | [Action] |
| Storage | [1–5] | [Evidence] | [Action] |
| Retention | [1–5] | [Evidence] | [Action] |
| Training use | [1–5] | [Evidence] | [Action] |
| Security | [1–5] | [Evidence] | [Action] |
| Subprocessors | [1–5] | [Evidence] | [Action] |
| Model limitations | [1–5] | [Evidence] | [Action] |
| Reliability | [1–5] | [Evidence] | [Action] |
| Explainability | [1–5] | [Evidence] | [Action] |
| Auditability | [1–5] | [Evidence] | [Action] |
| Export | [1–5] | [Evidence] | [Action] |
| Deletion | [1–5] | [Evidence] | [Action] |
| Ownership | [1–5] | [Evidence] | [Action] |
| Licensing | [1–5] | [Evidence] | [Action] |
| Pricing | [1–5] | [Evidence] | [Action] |
| Contract terms | [1–5] | [Evidence] | [Action] |
| Use restrictions | [1–5] | [Evidence] | [Action] |
| Integration controls | [1–5] | [Evidence] | [Action] |
| API controls | [1–5] | [Evidence] | [Action] |
| Agent controls | [1–5] | [Evidence] | [Action] |
| Pilot testing | [1–5] | [Evidence] | [Action] |
| User training | [1–5] | [Evidence] | [Action] |
| Ownership | [1–5] | [Evidence] | [Action] |
| Monitoring | [1–5] | [Evidence] | [Action] |
| Renewal process | [1–5] | [Evidence] | [Action] |
| Suspension readiness | [1–5] | [Evidence] | [Action] |
| Retirement readiness | [1–5] | [Evidence] | [Action] |

### Total Score

[Enter score.]

---

# Final Approval

## 88. Final Approval Checklist

Confirm:

- [ ] Business purpose is defined.
- [ ] Intended users are identified.
- [ ] Affected people are identified.
- [ ] Intended uses are documented.
- [ ] Restricted uses are documented.
- [ ] Prohibited uses are documented.
- [ ] Data handling is reviewed.
- [ ] Storage is reviewed.
- [ ] Retention is reviewed.
- [ ] Training use is reviewed.
- [ ] Security is reviewed.
- [ ] Subprocessors are reviewed.
- [ ] Model limitations are documented.
- [ ] Reliability is tested.
- [ ] Explainability is reviewed.
- [ ] Auditability is reviewed.
- [ ] Export is reviewed.
- [ ] Deletion is reviewed.
- [ ] Ownership is reviewed.
- [ ] Licensing is reviewed.
- [ ] Pricing is reviewed.
- [ ] Contract terms are reviewed.
- [ ] Integrations are reviewed.
- [ ] APIs are reviewed.
- [ ] Agent permissions are reviewed.
- [ ] Pilot testing is complete.
- [ ] Users are trained.
- [ ] Monitoring is assigned.
- [ ] Renewal date is assigned.
- [ ] Suspension process exists.
- [ ] Retirement process exists.
- [ ] Final approver has authority.

---

## 89. Final Approval Statement

Use:

```text
I reviewed the AI tool and vendor described in this record, including its business purpose, intended uses, data handling, storage, retention, training practices, security, subprocessors, model limitations, reliability, ownership, licensing, pricing, contracts, integrations, APIs, agents, monitoring, and retirement controls.

I approve this tool for:
[Approved use]

Restrictions:
[Restrictions]

Prohibited uses:
[Prohibited uses]

Approval expires:
[Date or condition]
```

### Final Approver

[Name and role.]

### Approval Date

[Date.]

---

## 90. Critical Stop Conditions

Do not approve when:

- [ ] Business purpose is unclear.
- [ ] Vendor identity is unclear.
- [ ] Data handling is unclear.
- [ ] Retention is unacceptable.
- [ ] Training use is unacceptable.
- [ ] Security review is incomplete.
- [ ] Sensitive data controls are missing.
- [ ] Subprocessors are unknown.
- [ ] Required deletion is unavailable.
- [ ] Ownership or licensing is unacceptable.
- [ ] High-risk automation lacks human approval.
- [ ] Write permissions are uncontrolled.
- [ ] Monitoring is unavailable.
- [ ] Contract terms are unacceptable.
- [ ] Final approval is missing.
- [ ] Another critical issue exists: [Describe]

---

# Quick AI Tool and Vendor Governance Guide

## Define

- [ ] Business purpose defined
- [ ] Intended users identified
- [ ] Affected people identified
- [ ] Intended uses documented
- [ ] Restricted uses documented
- [ ] Prohibited uses documented
- [ ] Risk classified

## Review Vendor

- [ ] Vendor identity verified
- [ ] Vendor stability reviewed
- [ ] Privacy history reviewed
- [ ] Security history reviewed
- [ ] Support reviewed
- [ ] Subprocessors reviewed
- [ ] Change-notification process reviewed

## Review Data

- [ ] Data categories identified
- [ ] Data minimized
- [ ] Storage reviewed
- [ ] Retention reviewed
- [ ] Training use reviewed
- [ ] Access controls reviewed
- [ ] Deletion reviewed
- [ ] Export reviewed

## Review Tool

- [ ] Capabilities reviewed
- [ ] Limitations reviewed
- [ ] Reliability tested
- [ ] Explainability reviewed
- [ ] Auditability reviewed
- [ ] Failure behavior tested
- [ ] Fallback process available

## Review Commercial Terms

- [ ] Ownership reviewed
- [ ] Licensing reviewed
- [ ] Pricing reviewed
- [ ] Overage risk reviewed
- [ ] Contract terms reviewed
- [ ] Exit options reviewed
- [ ] Vendor lock-in considered

## Control Connections

- [ ] Integrations reviewed
- [ ] Connectors reviewed
- [ ] Plugins reviewed
- [ ] APIs reviewed
- [ ] Keys secured
- [ ] Write access restricted
- [ ] Delete access restricted
- [ ] Agents reviewed
- [ ] Human approval gates active

## Activate

- [ ] Pilot completed
- [ ] Users trained
- [ ] Tool owner assigned
- [ ] Vendor owner assigned
- [ ] Monitoring owner assigned
- [ ] Renewal date assigned
- [ ] Final approval recorded

## Continue

- [ ] Model updates monitored
- [ ] Vendor updates monitored
- [ ] Incidents monitored
- [ ] Pricing monitored
- [ ] Policies monitored
- [ ] Reassessment triggers defined
- [ ] Suspension process available
- [ ] Retirement process available

---

# Governance

## 91. Governance Ownership

| Responsibility | Owner |
|---|---|
| AI-tool policy | [Name] |
| Tool ownership | [Name] |
| Vendor management | [Name] |
| Data governance | [Name] |
| Privacy | [Name] |
| Security | [Name] |
| Legal or contract review | [Name] |
| Licensing review | [Name] |
| Pricing review | [Name] |
| Integration approval | [Name] |
| API approval | [Name] |
| Agent approval | [Name] |
| User access | [Name] |
| Training | [Name] |
| Monitoring | [Name] |
| Incident response | [Name] |
| Renewal | [Name] |
| Suspension | [Name] |
| Retirement | [Name] |
| Final approval | [Name] |

---

## 92. Version Naming

Use:

```text
[tool-name]_ai-tool-vendor-review_v[version]_[date]
```

Example:

```text
marketing-content-assistant_ai-tool-vendor-review_v1.0_2026-08-04
```

---

## 93. Changes Requiring Reapproval

Require reapproval when changing:

- Business purpose
- Intended users
- Intended use
- Data source
- Data classification
- Vendor
- Tool
- Model
- Model version
- Storage
- Retention
- Training use
- Subprocessor
- Contract
- Pricing model
- Ownership term
- License
- Integration
- API permission
- Agent permission
- Automation level
- Customer-facing use
- Risk classification
- Monitoring plan
- Other: [Describe]

---

## 94. Version History

| Version | Date | Author | Change | Reason | Approved By |
|---|---|---|---|---|---|
| 1.0 | [Date] | [Name] | Initial guide | Guide creation | [Name] |
| [Version] | [Date] | [Name] | [Change] | [Reason] | [Name] |

---

## Important Principle

A tool can be excellent at what it does and still be wrong for the organization.

It may store too much.

Retain too long.

Train on the wrong information.

Hide the wrong limitation.

Charge unpredictably.

Connect too deeply.

Write where it should only read.

Act where it should only recommend.

Or change quietly while the approval record sleeps.

AI may help compare features, organize policies, summarize contracts, and identify review questions.

It cannot approve its own vendor, define its own boundaries, or decide that convenience outweighs responsibility.

A human must still decide whether the tool deserves access, which doors it may open, which doors must remain locked, and when it is time to show the software politely to the exit.

---

## Related Resources

### Responsible AI

- [Responsible AI Marketing Principles](responsible-ai-marketing-principles.md)
- [AI Use Risk Classification Guide](ai-use-risk-classification-guide.md)
- [Human Approval and Oversight Guide](human-approval-and-oversight-guide.md)
- [AI Data Privacy and Confidentiality Guide](ai-data-privacy-and-confidentiality-guide.md)
- [AI Bias, Inclusion, and Accessibility Guide](ai-bias-inclusion-and-accessibility-guide.md)
- [AI Transparency and Disclosure Guide](ai-transparency-and-disclosure-guide.md)
- [AI Incident Response and Correction Guide](ai-incident-response-and-correction-guide.md)

### Frameworks

- [Human Approval Before Execution Framework](../frameworks/human-approval-before-execution.md)
- [Context Before Creation Framework](../frameworks/context-before-creation.md)
- [Brand Voice AI Foundation Framework](../frameworks/brand-voice-ai-foundation.md)

### Checklists

- [Confidential Information Protection Checklist](../checklists/confidential-information-protection-checklist.md)
- [Automated Communications Approval Checklist](../checklists/automated-communications-approval-checklist.md)
- [AI-Generated Content Review Checklist](../checklists/ai-generated-content-review-checklist.md)
- [Fact and Source Verification Checklist](../checklists/fact-and-source-verification-checklist.md)

### Templates

- [Approval Workflow Template](../templates/approval-workflow-template.md)
- [Standard Operating Procedure Template](../templates/standard-operating-procedure-template.md)
- [Marketing Report Template](../templates/marketing-report-template.md)

### Workflows

- [Knowledge Ingestion and Grounding Workflow](../workflows/knowledge-ingestion-and-grounding-workflow.md)
- [Content Review Workflow](../workflows/content-review-workflow.md)
- [Campaign Planning Workflow](../workflows/campaign-planning-workflow.md)
- [Performance Reporting Workflow](../workflows/performance-reporting-workflow.md)

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
