# AI Bias, Inclusion, and Accessibility Guide

Use this guide to identify, evaluate, reduce, document, monitor, and govern bias, exclusion, and accessibility risks in AI-assisted marketing systems.

This guide is part of the **Brand Voice AI** methodology developed by **John M. Pogue** and **Pogue Digital Solutions, LLC**.

> Fairness is not achieved by asking whether the system treats everyone exactly the same. It begins by asking who is represented, who is missing, who faces additional barriers, and who may carry the consequences when the system is wrong.

---

## Guide Purpose

The AI Bias, Inclusion, and Accessibility Guide helps organizations:

- Identify bias in source data
- Identify bias in prompts
- Identify bias in generated outputs
- Identify bias in targeting
- Identify bias in personalization
- Identify bias in automation
- Review representation
- Review stereotypes
- Review exclusion
- Review assumptions
- Review harmful defaults
- Review historical bias
- Review source-data bias
- Review audience segmentation
- Distinguish segmentation from unfair treatment
- Test outputs across audience groups
- Preserve minority viewpoints
- Preserve contradictions
- Review disability access
- Review language access
- Review age-related assumptions
- Review gender assumptions
- Review racial and ethnic assumptions
- Review religious assumptions
- Review geographic assumptions
- Review income assumptions
- Review educational assumptions
- Review technology-access barriers
- Review text accessibility
- Review image accessibility
- Review video accessibility
- Review audio accessibility
- Review form accessibility
- Review table accessibility
- Review interface accessibility
- Assign reviewers
- Document findings
- Escalate material harm
- Reapprove systems after material changes
- Use AI for preliminary review without allowing it to certify itself as fair, inclusive, or accessible

This guide may be used for:

- Content generation
- Content editing
- Advertising
- Audience targeting
- Personalization
- Customer segmentation
- Lead scoring
- Recommendation systems
- Customer research
- Market research
- Social-media publishing
- Email marketing
- Customer support
- Sales enablement
- Synthetic media
- AI agents
- Custom GPTs
- Retrieval systems
- Marketing automation
- Analytics
- Reporting
- Websites
- Landing pages
- Forms
- Videos
- Podcasts
- Presentations
- Learning materials

---

# Bias, Inclusion, and Accessibility Overview

```text
Define the activity and affected audience
        ↓
Identify source data, prompts, models, and automation
        ↓
Review representation, assumptions, stereotypes, and exclusions
        ↓
Review segmentation and differential treatment
        ↓
Test across audience groups
        ↓
Review text, image, video, audio, form, table, and interface accessibility
        ↓
Document findings and limitations
        ↓
Human review
        ↓
Approve, revise, restrict, pause, or prohibit
        ↓
Monitor outcomes
        ↓
Reapprove, correct, or retire
```

---

# Review Record

## 1. Activity Information

| Field | Information |
|---|---|
| Activity name | [Enter name] |
| Business purpose | [Describe purpose] |
| Marketing function | [Enter function] |
| Primary audience | [Describe audience] |
| Secondary audiences | [Describe] |
| People directly affected | [Describe] |
| People indirectly affected | [Describe] |
| AI tool or model | [Enter tool] |
| Data sources | [List sources] |
| Prompt or workflow | [Identify] |
| Automation level | Assistive / Recommendatory / Conditional / Autonomous |
| Output type | [Describe output] |
| Customer-facing | Yes / No |
| Activity owner | [Enter name] |
| Bias and inclusion reviewer | [Enter name] |
| Accessibility reviewer | [Enter name] |
| Subject-matter reviewer | [Enter name] |
| Final approver | [Enter name and role] |
| Risk level | Low / Moderate / High / Prohibited |
| Current version | [Enter version] |
| Status | Proposed / Review / Approved / Active / Paused / Retired |

---

## 2. Review Decision

Select one:

- [ ] Approved
- [ ] Approved with conditions
- [ ] Additional testing required
- [ ] Representation revision required
- [ ] Bias revision required
- [ ] Inclusion revision required
- [ ] Accessibility revision required
- [ ] Targeting revision required
- [ ] Personalization revision required
- [ ] Automation reduction required
- [ ] Specialist review required
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

# Phase One: Define the Activity and Audience

## 3. Activity Description

Use:

```text
The AI-supported activity will:
[Describe]

It will use:
[Describe data and systems]

It will produce or influence:
[Describe output, recommendation, ranking, message, or action]

It may affect:
[Describe people, groups, or communities]
```

---

## 4. Audience Record

| Audience Group | Intended Use | Potential Effect |
|---|---|---|
| [Group] | [Use] | [Effect] |
| [Group] | [Use] | [Effect] |
| [Group] | [Use] | [Effect] |

---

## 5. Audience Review

Confirm:

- [ ] Primary audience is defined.
- [ ] Secondary audiences are considered.
- [ ] Unintended audiences are considered.
- [ ] Vulnerable audiences are identified.
- [ ] Audience diversity is considered.
- [ ] Language access is considered.
- [ ] Disability access is considered.
- [ ] Technology access is considered.
- [ ] Potential exclusion is documented.

---

# Phase Two: Identify Bias Sources

## 6. Possible Bias Sources

Bias may enter through:

- Historical data
- Incomplete data
- Unequal representation
- Biased labels
- Biased customer notes
- Biased research questions
- Biased prompts
- Biased examples
- Biased benchmarks
- Model training data
- Human assumptions
- Targeting rules
- Personalization logic
- Automation conditions
- Platform data
- Missing accessibility requirements
- Poor translation
- Proxy variables
- Feedback loops

---

## 7. Bias Source Record

| Source | Possible Bias | Affected Group | Risk |
|---|---|---|---|
| [Source] | [Bias] | [Group] | Low / Moderate / High |
| [Source] | [Bias] | [Group] | Low / Moderate / High |
| [Source] | [Bias] | [Group] | Low / Moderate / High |

---

## 8. Bias Source Review

Confirm:

- [ ] Historical bias is considered.
- [ ] Missing groups are identified.
- [ ] Label quality is reviewed.
- [ ] Human assumptions are documented.
- [ ] Proxy variables are identified.
- [ ] Platform data limitations are considered.
- [ ] Feedback loops are considered.
- [ ] Data imbalance is documented.
- [ ] Source limitations remain visible.

---

# Phase Three: Review Representation

## 9. Representation Categories

Review representation across:

- Race
- Ethnicity
- Gender
- Age
- Disability
- Religion
- Language
- Geography
- Income
- Education
- Family structure
- Employment status
- Business size
- Technology access
- Customer journey stage
- Other relevant characteristics

---

## 10. Representation Record

| Group | Present | Quality of Representation | Required Action |
|---|---|---|---|
| [Group] | Yes / No | Strong / Mixed / Weak | [Action] |
| [Group] | Yes / No | Strong / Mixed / Weak | [Action] |
| [Group] | Yes / No | Strong / Mixed / Weak | [Action] |

---

## 11. Representation Review Questions

Ask:

- Who appears?
- Who is absent?
- Who appears only in negative examples?
- Who appears only in supporting roles?
- Who is treated as the default?
- Who is treated as an exception?
- Are examples representative?
- Are images diverse without becoming tokenistic?
- Are minority viewpoints included?
- Are contradictions preserved?

---

# Phase Four: Review Stereotypes and Assumptions

## 12. Common Assumption Areas

Review assumptions about:

- Intelligence
- Technical ability
- Financial capacity
- Education
- Family roles
- Leadership
- Communication style
- Work ethic
- Health
- Disability
- Language proficiency
- Technology access
- Purchasing power
- Risk tolerance
- Cultural behavior
- Religious practice

---

## 13. Stereotype Record

| Statement or Output | Assumption | Potential Harm | Required Action |
|---|---|---|---|
| [Output] | [Assumption] | [Harm] | [Action] |
| [Output] | [Assumption] | [Harm] | [Action] |

---

## 14. Stereotype Review

Confirm:

- [ ] People are not reduced to demographic traits.
- [ ] Cultural groups are not treated as uniform.
- [ ] Disability is not framed automatically as tragedy.
- [ ] Age is not treated as a proxy for ability.
- [ ] Income is not treated as a proxy for intelligence.
- [ ] Language differences are not treated as incompetence.
- [ ] Gender roles are not assumed.
- [ ] Religion is not generalized.
- [ ] Geography is not used as a crude character judgment.

---

# Phase Five: Review Exclusion and Harmful Defaults

## 15. Exclusion Questions

Ask:

- Who cannot use the output?
- Who cannot access the channel?
- Who cannot understand the language?
- Who cannot complete the form?
- Who may be excluded by device requirements?
- Who may be excluded by payment method?
- Who may be excluded by location?
- Who may be excluded by assumptions in the CTA?
- Who may be excluded by platform targeting?
- Who may be excluded unintentionally by automation?

---

## 16. Default Review

Review defaults involving:

- Language
- Currency
- Time zone
- Location
- Device
- Reading level
- Communication method
- Identity fields
- Form requirements
- Image representation
- Caption availability
- Audio availability
- Contact method

---

## 17. Exclusion Record

| Default or Requirement | Group Affected | Effect | Required Change |
|---|---|---|---|
| [Default] | [Group] | [Effect] | [Change] |
| [Default] | [Group] | [Effect] | [Change] |

---

# Phase Six: Distinguish Segmentation From Unfair Treatment

## 18. Legitimate Segmentation

Segmentation may be appropriate when it:

- Supports a real customer need
- Uses relevant criteria
- Improves usefulness
- Does not rely on prohibited proxies
- Does not deny access unfairly
- Does not exploit vulnerability
- Remains explainable
- Can be reviewed and challenged

---

## 19. Unfair Differential Treatment

Concern may arise when a system:

- Offers different prices without supportable reasons
- Excludes groups from opportunities
- Targets vulnerable people with pressure
- Uses sensitive traits unnecessarily
- Uses proxy variables for protected traits
- Provides lower-quality service to certain groups
- Creates unequal access
- Reinforces historical disadvantage
- Cannot explain why groups are treated differently

---

## 20. Segmentation Review Record

| Segment Criterion | Business Reason | Fairness Risk | Decision |
|---|---|---|---|
| [Criterion] | [Reason] | Low / Moderate / High | Keep / Revise / Remove |
| [Criterion] | [Reason] | Low / Moderate / High | Keep / Revise / Remove |

---

## 21. Segmentation Review

Confirm:

- [ ] Criteria are relevant.
- [ ] Sensitive traits are avoided unless formally justified.
- [ ] Proxy variables are reviewed.
- [ ] Different treatment is explainable.
- [ ] Different treatment is proportionate.
- [ ] Vulnerable groups are not exploited.
- [ ] People can reach a human.
- [ ] Appeals or corrections are possible where appropriate.

---

# Phase Seven: Review Prompt Bias

## 22. Prompt Risks

Prompts may introduce bias through:

- Loaded assumptions
- Narrow examples
- Exclusionary audience descriptions
- Harmful stereotypes
- Implied demographic defaults
- Unbalanced evidence
- Missing minority viewpoints
- Pressure to produce certainty
- Instructions to optimize only for conversion
- Instructions to ignore accessibility

---

## 23. Prompt Review Record

| Prompt Element | Bias Risk | Revision |
|---|---|---|
| [Element] | [Risk] | [Revision] |
| [Element] | [Risk] | [Revision] |

---

## 24. Prompt Review

Confirm:

- [ ] Audience is described respectfully.
- [ ] Prompt does not assume one universal customer.
- [ ] Prompt includes relevant accessibility needs.
- [ ] Prompt preserves contradictions.
- [ ] Prompt does not instruct the system to exploit vulnerability.
- [ ] Prompt does not prioritize conversion over safety.
- [ ] Prompt requests evidence.
- [ ] Prompt allows uncertainty.

---

# Phase Eight: Review Output Bias

## 25. Output Review Areas

Review:

- Language
- Examples
- Images
- Recommendations
- Rankings
- Personalization
- Tone
- Assumptions
- Omitted groups
- Stereotypes
- Differential treatment
- Accessibility
- Calls to action

---

## 26. Output Review Record

| Output Element | Issue | Affected Group | Required Action |
|---|---|---|---|
| [Element] | [Issue] | [Group] | [Action] |
| [Element] | [Issue] | [Group] | [Action] |

---

## 27. Output Bias Review

Confirm:

- [ ] Language is respectful.
- [ ] Examples are balanced.
- [ ] Minority viewpoints remain visible.
- [ ] Stereotypes are removed.
- [ ] Assumptions are labeled.
- [ ] Recommendations do not unfairly exclude.
- [ ] Personalization remains appropriate.
- [ ] Accessibility needs are included.
- [ ] Human review is documented.

---

# Phase Nine: Review Targeting and Personalization

## 28. Targeting Risks

Review:

- Sensitive traits
- Proxy traits
- Geographic exclusion
- Income-based exclusion
- Disability-based exclusion
- Age-based assumptions
- Predatory targeting
- Vulnerable audience targeting
- Platform lookalike models
- Historical conversion bias

---

## 29. Personalization Risks

Review:

- Sensitive inferences
- Unequal offers
- Unequal service quality
- Overly invasive messaging
- Incorrect assumptions
- Hidden profiling
- Manipulative urgency
- Personalization without consent
- Automated decisions without recourse

---

## 30. Targeting and Personalization Record

| Rule or Model | Intended Purpose | Risk | Required Control |
|---|---|---|---|
| [Rule] | [Purpose] | Low / Moderate / High | [Control] |
| [Rule] | [Purpose] | Low / Moderate / High | [Control] |

---

## 31. Targeting Review

Confirm:

- [ ] Targeting purpose is legitimate.
- [ ] Sensitive traits are reviewed.
- [ ] Proxy variables are reviewed.
- [ ] Vulnerable groups are not exploited.
- [ ] Exclusion is supportable.
- [ ] Audience can understand the offer.
- [ ] Personalization is not deceptive.
- [ ] Human review exists.
- [ ] Monitoring can detect unequal outcomes.

---

# Phase Ten: Test Across Audience Groups

## 32. Test Groups

Select groups relevant to the activity:

- Different age groups
- Different gender identities
- Different racial or ethnic groups
- Different languages
- Different literacy levels
- Different disability needs
- Different geographic regions
- Different income levels
- Different education levels
- Different device types
- Different connection speeds
- Different customer journey stages

---

## 33. Test Record

| Test Group | Test Scenario | Result | Required Action |
|---|---|---|---|
| [Group] | [Scenario] | Pass / Mixed / Fail | [Action] |
| [Group] | [Scenario] | Pass / Mixed / Fail | [Action] |
| [Group] | [Scenario] | Pass / Mixed / Fail | [Action] |

---

## 34. Comparative Testing Questions

Ask:

- Does one group receive lower-quality output?
- Does one group receive more negative language?
- Does one group receive fewer opportunities?
- Does one group receive higher pressure?
- Does one group face more errors?
- Does one group face more inaccessible content?
- Does one group receive less relevant recommendations?
- Does one group experience longer delays?
- Does one group have fewer ways to reach a human?

---

# Phase Eleven: Preserve Minority Viewpoints and Contradictions

## 35. Evidence Preservation

Do not collapse research into one dominant opinion when:

- Segments disagree
- Minority groups report distinct barriers
- Accessibility needs differ
- Geographic experiences differ
- Customer journey stages differ
- Outcomes vary
- Source evidence conflicts
- Confidence is limited

---

## 36. Minority-Viewpoint Record

| Viewpoint | Group | Evidence | Decision |
|---|---|---|---|
| [Viewpoint] | [Group] | [Evidence] | Preserve / Investigate / Remove |
| [Viewpoint] | [Group] | [Evidence] | Preserve / Investigate / Remove |

---

## 37. Contradiction Review

Confirm:

- [ ] Contradictions remain visible.
- [ ] Minority viewpoints are not erased by majority counts.
- [ ] Small samples are labeled.
- [ ] Uncertainty is preserved.
- [ ] The final recommendation does not pretend universal agreement.
- [ ] AI summaries were checked for flattening.

---

# Phase Twelve: Review Text Accessibility

## 38. Text Accessibility Areas

Review:

- Heading hierarchy
- Plain language
- Paragraph length
- Sentence complexity
- Acronyms
- Technical language
- Link text
- Instructions
- Lists
- Tables
- Contrast
- Font size
- Mobile readability

---

## 39. Text Accessibility Review

Confirm:

- [ ] Heading levels are logical.
- [ ] Important information is easy to find.
- [ ] Technical terms are defined.
- [ ] Acronyms are explained.
- [ ] Link text is descriptive.
- [ ] Instructions are ordered.
- [ ] Paragraphs are readable.
- [ ] Tables are understandable.
- [ ] Font size is appropriate.
- [ ] Mobile presentation is usable.

---

# Phase Thirteen: Review Image Accessibility

## 40. Image Accessibility Areas

Review:

- Alternative text
- Text embedded in images
- Contrast
- Color dependence
- Image captions
- Representation
- Decorative images
- Charts
- Diagrams
- Screenshots

---

## 41. Image Review

Confirm:

- [ ] Informative images have alternative text.
- [ ] Decorative images are identified.
- [ ] Text in images is repeated in accessible text.
- [ ] Color is not the only communication method.
- [ ] Contrast is sufficient.
- [ ] Charts have written explanations.
- [ ] Screenshots are described.
- [ ] AI-generated images are reviewed for stereotypes.
- [ ] Visual representation is intentional.

---

# Phase Fourteen: Review Video Accessibility

## 42. Video Accessibility Areas

Review:

- Captions
- Transcripts
- Audio descriptions
- Visual text
- Speaker identification
- Flashing content
- Pace
- Contrast
- Controls
- Mobile playback

---

## 43. Video Review

Confirm:

- [ ] Captions are present.
- [ ] Captions are accurate.
- [ ] Captions are synchronized.
- [ ] Speaker changes are clear.
- [ ] Important visual information is described.
- [ ] Transcript is available where appropriate.
- [ ] Visual text remains readable.
- [ ] Flashing content is reviewed.
- [ ] Playback controls are usable.
- [ ] Mobile playback works.

---

# Phase Fifteen: Review Audio Accessibility

## 44. Audio Accessibility Areas

Review:

- Transcript
- Speaker identification
- Sound quality
- Background noise
- Pace
- Pronunciation
- Language access
- Download access
- Playback controls

---

## 45. Audio Review

Confirm:

- [ ] Transcript is available where appropriate.
- [ ] Speakers are identified.
- [ ] Audio is understandable.
- [ ] Background noise is controlled.
- [ ] Pace is appropriate.
- [ ] Important terms are pronounced clearly.
- [ ] Playback controls work.
- [ ] Alternative access is available.

---

# Phase Sixteen: Review Forms

## 46. Form Accessibility Areas

Review:

- Field labels
- Instructions
- Error messages
- Required fields
- Keyboard access
- Screen-reader compatibility
- Color dependence
- Time limits
- Identity fields
- Mobile use

---

## 47. Form Review

Confirm:

- [ ] Every field has a label.
- [ ] Instructions are clear.
- [ ] Required fields are identified.
- [ ] Errors explain how to correct the problem.
- [ ] Keyboard navigation works.
- [ ] Color is not the only error signal.
- [ ] Time limits are reasonable.
- [ ] Identity fields are necessary.
- [ ] Mobile completion works.
- [ ] Users can request assistance.

---

# Phase Seventeen: Review Tables and Data Visualizations

## 48. Table Review

Confirm:

- [ ] Column headings are clear.
- [ ] Row headings are clear.
- [ ] Reading order is logical.
- [ ] Complex tables have summaries.
- [ ] Abbreviations are defined.
- [ ] Mobile view remains usable.
- [ ] Screen-reader use is considered.

---

## 49. Visualization Review

Confirm:

- [ ] Chart purpose is clear.
- [ ] Data labels are available.
- [ ] Color is not the only differentiator.
- [ ] Patterns or labels support interpretation.
- [ ] Written explanation is included.
- [ ] Scales are not misleading.
- [ ] Missing data is visible.
- [ ] AI-generated charts were checked for accuracy.

---

# Phase Eighteen: Review Interfaces and Automated Experiences

## 50. Interface Review Areas

Review:

- Keyboard navigation
- Focus order
- Labels
- Buttons
- Contrast
- Error handling
- Time limits
- Human support
- Language selection
- Mobile use
- Screen-reader compatibility
- Automation disclosure

---

## 51. Interface Review

Confirm:

- [ ] Interface is navigable.
- [ ] Controls are labeled.
- [ ] Focus order is logical.
- [ ] Errors are understandable.
- [ ] Human assistance is available.
- [ ] Automated interaction is disclosed where appropriate.
- [ ] Language options are available where needed.
- [ ] Mobile use works.
- [ ] Users can exit or stop automation.
- [ ] Users can challenge or correct information.

---

# Phase Nineteen: Assign Reviewers

## 52. Reviewer Types

Possible reviewers:

- Activity owner
- Bias and inclusion reviewer
- Accessibility reviewer
- Subject-matter expert
- Data owner
- Privacy reviewer
- User-experience reviewer
- Language reviewer
- Community representative
- Legal or compliance reviewer
- Final approver

---

## 53. Reviewer Matrix

| Review Area | Reviewer | Required |
|---|---|---|
| Representation | [Name] | Yes / No |
| Stereotypes | [Name] | Yes / No |
| Segmentation | [Name] | Yes / No |
| Targeting | [Name] | Yes / No |
| Personalization | [Name] | Yes / No |
| Text accessibility | [Name] | Yes / No |
| Image accessibility | [Name] | Yes / No |
| Video accessibility | [Name] | Yes / No |
| Form accessibility | [Name] | Yes / No |
| Interface accessibility | [Name] | Yes / No |
| Final approval | [Name] | Yes |

---

# Phase Twenty: Document Findings

## 54. Finding Structure

Use:

```text
Finding:
[Describe]

Affected Group:
[Describe]

Evidence:
[Describe]

Potential Harm:
[Describe]

Confidence:
High / Medium / Low

Required Action:
[Describe]
```

---

## 55. Finding Record

| Finding | Affected Group | Confidence | Action |
|---|---|---|---|
| [Finding] | [Group] | High / Medium / Low | [Action] |
| [Finding] | [Group] | High / Medium / Low | [Action] |

---

## 56. Documentation Review

Confirm:

- [ ] Finding is specific.
- [ ] Evidence is attached.
- [ ] Affected groups are identified.
- [ ] Potential harm is described.
- [ ] Confidence is appropriate.
- [ ] Minority viewpoints remain visible.
- [ ] Required action is assigned.
- [ ] Reviewer name and date are recorded.

---

# Phase Twenty-One: Escalate Material Harm

## 57. Escalation Triggers

Escalate when:

- A group receives materially worse outcomes
- A vulnerable group may be harmed
- Discriminatory targeting appears
- Sensitive traits are used without approval
- Accessibility failure blocks access
- Automation creates repeated unequal treatment
- Synthetic media reinforces harmful stereotypes
- A legal or compliance concern appears
- A reviewer cannot resolve the issue
- Monitoring reveals persistent harm

---

## 58. Escalation Record

| Trigger | First Contact | Final Authority | Response Time |
|---|---|---|---|
| [Trigger] | [Contact] | [Authority] | [Time] |
| [Trigger] | [Contact] | [Authority] | [Time] |

---

# Phase Twenty-Two: Use AI Responsibly in Review

## 59. Approved AI Uses

AI may assist with:

- Identifying possible stereotypes
- Identifying missing representation
- Comparing outputs across groups
- Identifying accessibility omissions
- Preparing preliminary test cases
- Summarizing reviewer findings
- Identifying inconsistent treatment
- Comparing versions
- Preparing alt-text drafts
- Preparing caption drafts

---

## 60. Prohibited AI Uses

AI should not:

- Certify itself as fair
- Certify itself as accessible
- Approve its own output
- Decide that discrimination is acceptable
- Erase minority viewpoints
- Invent accessibility testing
- Replace affected-community input
- Decide legal compliance
- Ignore contradictory evidence
- Override human reviewers
- Continue operating after material harm is identified

---

## 61. AI Review Record

| AI Task | Tool | Human Reviewer | Status |
|---|---|---|---|
| [Task] | [Tool] | [Name] | Approved / Revise |
| [Task] | [Tool] | [Name] | Approved / Revise |

---

# Phase Twenty-Three: Monitor Outcomes

## 62. Monitoring Signals

Monitor:

- Complaint patterns
- Conversion differences
- Error differences
- Response-quality differences
- Accessibility failures
- Drop-off differences
- Rejection differences
- Service-quality differences
- Support requests
- Human override rates
- Harm reports
- Unexpected exclusions

---

## 63. Monitoring Record

| Signal | Group | Threshold | Response |
|---|---|---|---|
| [Signal] | [Group] | [Threshold] | [Response] |
| [Signal] | [Group] | [Threshold] | [Response] |

---

## 64. Monitoring Review

Confirm:

- [ ] Monitoring owner is assigned.
- [ ] Group-level outcomes are reviewed where appropriate.
- [ ] Small samples are labeled.
- [ ] Privacy is protected.
- [ ] Complaints are recorded.
- [ ] Accessibility failures are tracked.
- [ ] Unequal outcomes trigger review.
- [ ] Model or tool changes trigger testing.
- [ ] Monitoring informs reapproval.

---

# Phase Twenty-Four: Reapprove After Change

## 65. Reapproval Triggers

Require renewed review when changing:

- Business purpose
- Audience
- Targeting criteria
- Personalization logic
- Data source
- Model
- Tool
- Prompt
- Workflow
- Automation level
- Language
- Geography
- Format
- Accessibility requirements
- Interface
- CTA
- Offer
- Monitoring method
- Risk classification

---

## 66. Change Record

| Element | Approved Version | Changed Version | Reapproval Required |
|---|---|---|---|
| [Element] | [Approved] | [Changed] | Yes / No |
| [Element] | [Approved] | [Changed] | Yes / No |

---

# Phase Twenty-Five: Score the Activity

## 67. Scoring Scale

Use:

- 5: Strong and complete
- 4: Effective with minor gaps
- 3: Mixed
- 2: Weak
- 1: Harmful, exclusionary, or inaccessible

---

## 68. Bias, Inclusion, and Accessibility Scorecard

| Area | Score | Evidence | Required Action |
|---|---:|---|---|
| Audience definition | [1–5] | [Evidence] | [Action] |
| Affected-group identification | [1–5] | [Evidence] | [Action] |
| Bias-source review | [1–5] | [Evidence] | [Action] |
| Representation | [1–5] | [Evidence] | [Action] |
| Stereotype control | [1–5] | [Evidence] | [Action] |
| Exclusion review | [1–5] | [Evidence] | [Action] |
| Harmful-default review | [1–5] | [Evidence] | [Action] |
| Segmentation fairness | [1–5] | [Evidence] | [Action] |
| Prompt review | [1–5] | [Evidence] | [Action] |
| Output review | [1–5] | [Evidence] | [Action] |
| Targeting review | [1–5] | [Evidence] | [Action] |
| Personalization review | [1–5] | [Evidence] | [Action] |
| Cross-group testing | [1–5] | [Evidence] | [Action] |
| Minority-viewpoint preservation | [1–5] | [Evidence] | [Action] |
| Text accessibility | [1–5] | [Evidence] | [Action] |
| Image accessibility | [1–5] | [Evidence] | [Action] |
| Video accessibility | [1–5] | [Evidence] | [Action] |
| Audio accessibility | [1–5] | [Evidence] | [Action] |
| Form accessibility | [1–5] | [Evidence] | [Action] |
| Table accessibility | [1–5] | [Evidence] | [Action] |
| Interface accessibility | [1–5] | [Evidence] | [Action] |
| Reviewer coverage | [1–5] | [Evidence] | [Action] |
| Documentation | [1–5] | [Evidence] | [Action] |
| Escalation | [1–5] | [Evidence] | [Action] |
| Monitoring | [1–5] | [Evidence] | [Action] |
| Reapproval | [1–5] | [Evidence] | [Action] |
| Responsible AI assistance | [1–5] | [Evidence] | [Action] |

### Total Score

[Enter score.]

---

# Phase Twenty-Six: Approve the Activity

## 69. Final Approval Checklist

Confirm:

- [ ] Activity is defined.
- [ ] Audience is defined.
- [ ] Affected groups are identified.
- [ ] Bias sources are reviewed.
- [ ] Representation is reviewed.
- [ ] Stereotypes are reviewed.
- [ ] Exclusion is reviewed.
- [ ] Segmentation is reviewed.
- [ ] Targeting is reviewed.
- [ ] Personalization is reviewed.
- [ ] Cross-group testing is complete.
- [ ] Minority viewpoints are preserved.
- [ ] Text accessibility is reviewed.
- [ ] Image accessibility is reviewed.
- [ ] Video accessibility is reviewed.
- [ ] Audio accessibility is reviewed.
- [ ] Forms are reviewed.
- [ ] Tables are reviewed.
- [ ] Interfaces are reviewed.
- [ ] Material findings are resolved.
- [ ] Monitoring is defined.
- [ ] Exact version is identified.
- [ ] Final approver has authority.

---

## 70. Final Approval Statement

Use:

```text
I reviewed the exact AI-supported activity described in this record, including its audience, affected groups, data, prompts, outputs, targeting, personalization, accessibility, testing, findings, controls, and monitoring plan.

I approve this activity:
[Decision]

Conditions:
[Conditions]
```

### Final Approver

[Name and role.]

### Approval Date

[Date.]

---

## 71. Critical Stop Conditions

Do not proceed when:

- [ ] Audience is unclear.
- [ ] Affected groups are not identified.
- [ ] Material bias remains unresolved.
- [ ] Harmful stereotypes remain.
- [ ] Vulnerable groups may be exploited.
- [ ] Accessibility failure blocks access.
- [ ] Cross-group testing is incomplete where required.
- [ ] Required reviewer is unavailable.
- [ ] Monitoring is unavailable.
- [ ] Final approval is missing.
- [ ] Another critical issue exists: [Describe]

---

# Phase Twenty-Seven: Pause or Retire the Activity

## 72. Pause Triggers

Pause when:

- Material bias is reported
- Accessibility fails
- A vulnerable group may be harmed
- Targeting changes
- Personalization changes
- Model behavior changes
- Monitoring fails
- Required reviewer becomes unavailable
- A legal or compliance concern appears
- Complaints reveal unequal treatment

---

## 73. Retirement Triggers

Retire when:

- Bias cannot be controlled
- Accessibility cannot be achieved
- The activity reinforces persistent harm
- Targeting cannot be justified
- Data remains unrepresentative
- A safer process replaces it
- Required oversight is unavailable
- The business purpose no longer exists
- Repeated incidents continue

---

## 74. Retirement Record

| Field | Information |
|---|---|
| Activity | [Enter activity] |
| Retirement reason | [Describe] |
| Retirement date | [Date] |
| Approved by | [Name] |
| Replacement | [Process or “None”] |
| Automation disabled | Yes / No |
| Access disabled | Yes / No |
| Retrieval disabled | Yes / No |
| Archive location | [Location] |

---

# Quick AI Bias, Inclusion, and Accessibility Guide

## Define

- [ ] Activity defined
- [ ] Audience defined
- [ ] Affected groups identified
- [ ] Tool identified
- [ ] Data identified
- [ ] Prompt identified
- [ ] Automation level identified

## Review Bias

- [ ] Historical bias reviewed
- [ ] Data imbalance reviewed
- [ ] Representation reviewed
- [ ] Stereotypes reviewed
- [ ] Assumptions reviewed
- [ ] Exclusion reviewed
- [ ] Harmful defaults reviewed
- [ ] Proxy variables reviewed

## Review Treatment

- [ ] Segmentation reviewed
- [ ] Targeting reviewed
- [ ] Personalization reviewed
- [ ] Vulnerable audiences reviewed
- [ ] Unequal service reviewed
- [ ] Appeals or human access reviewed

## Test

- [ ] Audience groups selected
- [ ] Test scenarios defined
- [ ] Outputs compared
- [ ] Errors compared
- [ ] Opportunities compared
- [ ] Accessibility compared
- [ ] Findings documented

## Review Accessibility

- [ ] Text reviewed
- [ ] Images reviewed
- [ ] Video reviewed
- [ ] Audio reviewed
- [ ] Forms reviewed
- [ ] Tables reviewed
- [ ] Interfaces reviewed
- [ ] Mobile use reviewed

## Protect

- [ ] Minority viewpoints preserved
- [ ] Contradictions preserved
- [ ] Material harm escalated
- [ ] Human reviewers assigned
- [ ] AI review treated as preliminary
- [ ] Final approval remains human

## Continue

- [ ] Monitoring active
- [ ] Reapproval triggers defined
- [ ] Complaint process available
- [ ] Pause process available
- [ ] Retirement process available
- [ ] Version history preserved

---

# Governance

## 75. Ownership

| Responsibility | Owner |
|---|---|
| Bias policy | [Name] |
| Inclusion review | [Name] |
| Accessibility policy | [Name] |
| Data review | [Name] |
| Prompt review | [Name] |
| Targeting review | [Name] |
| Personalization review | [Name] |
| Cross-group testing | [Name] |
| Text accessibility | [Name] |
| Visual accessibility | [Name] |
| Audio and video accessibility | [Name] |
| Form accessibility | [Name] |
| Interface accessibility | [Name] |
| Monitoring | [Name] |
| Escalation | [Name] |
| Reapproval | [Name] |
| Retirement | [Name] |
| Final approval | [Name] |

---

## 76. Version Naming

Use:

```text
[activity-name]_bias-inclusion-accessibility-review_v[version]_[date]
```

Example:

```text
customer-email-personalization_bias-inclusion-accessibility-review_v1.0_2026-08-04
```

---

## 77. Changes Requiring Reapproval

Require reapproval when changing:

- Business purpose
- Audience
- Targeting criteria
- Personalization method
- Data source
- Model
- Tool
- Prompt
- Workflow
- Automation level
- Language
- Geography
- Format
- Interface
- Offer
- CTA
- Accessibility requirement
- Monitoring method
- Risk classification
- Other: [Describe]

---

## 78. Version History

| Version | Date | Author | Change | Reason | Approved By |
|---|---|---|---|---|---|
| 1.0 | [Date] | [Name] | Initial guide | Guide creation | [Name] |
| [Version] | [Date] | [Name] | [Change] | [Reason] | [Name] |

---

## Important Principle

Bias does not always arrive wearing a warning label.

Sometimes it enters as a missing example.

A convenient default.

A targeting rule inherited from old results.

A form that assumes every person fits the same categories.

A video without captions.

A customer journey designed only for people with fast internet, perfect eyesight, fluent English, and endless patience.

AI may help identify patterns, compare outputs, flag stereotypes, draft captions, and suggest accessibility improvements.

It cannot certify itself as fair.

It cannot decide that an excluded group does not matter.

A human must still ask who benefits, who is burdened, who is missing, what barriers remain, and whether the system deserves permission to continue.

---

## Related Resources

### Responsible AI

- [Responsible AI Marketing Principles](responsible-ai-marketing-principles.md)
- [AI Use Risk Classification Guide](ai-use-risk-classification-guide.md)
- [Human Approval and Oversight Guide](human-approval-and-oversight-guide.md)
- [AI Data Privacy and Confidentiality Guide](ai-data-privacy-and-confidentiality-guide.md)

### Frameworks

- [Human Approval Before Execution Framework](../frameworks/human-approval-before-execution.md)
- [Context Before Creation Framework](../frameworks/context-before-creation.md)
- [Brand Voice AI Foundation Framework](../frameworks/brand-voice-ai-foundation.md)

### Checklists

- [AI-Generated Content Review Checklist](../checklists/ai-generated-content-review-checklist.md)
- [Brand Consistency Evaluation Checklist](../checklists/brand-consistency-evaluation-checklist.md)
- [Confidential Information Protection Checklist](../checklists/confidential-information-protection-checklist.md)
- [Automated Communications Approval Checklist](../checklists/automated-communications-approval-checklist.md)

### Workflows

- [Customer Research Workflow](../workflows/customer-research-workflow.md)
- [Content Review Workflow](../workflows/content-review-workflow.md)
- [Social Media Publishing Workflow](../workflows/social-media-publishing-workflow.md)
- [Email Development Workflow](../workflows/email-development-workflow.md)
- [Campaign Planning Workflow](../workflows/campaign-planning-workflow.md)

### Content Strategy

- [Content Editing Guide](../content-strategy/content-editing-guide.md)
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
