# Automated Communications Approval Checklist

Use this checklist to review, test, approve, monitor, pause, correct, and retire automated communications before they reach customers, prospects, employees, partners, community members, or the public.

This resource is part of the **Brand Voice AI** methodology developed by **John M. Pogue** and **Pogue Digital Solutions, LLC**.

> Automation should increase consistency without removing judgment, consent, accountability, or the human path back into the conversation.

---

## Purpose

This checklist helps confirm that automated communications:

- Have a clear business purpose
- Serve a defined audience
- Match the customer journey stage
- Use accurate trigger logic
- Reach eligible recipients only
- Preserve brand voice
- Use personalization responsibly
- Protect confidential information
- Respect consent and communication preferences
- Include working unsubscribe or opt-out mechanisms
- Use current offers, prices, dates, and claims
- Receive human approval before activation
- Are tested with safe records
- Avoid duplicate or excessive messages
- Include failure handling
- Include escalation paths
- Can be paused immediately
- Are monitored after launch
- Can be corrected and retired

Use it for:

- Email automations
- CRM sequences
- Lead-nurture campaigns
- Welcome sequences
- Onboarding sequences
- Customer-support messages
- Renewal reminders
- Appointment reminders
- Event reminders
- SMS messages
- Chatbots
- Website chat
- Social-media automations
- Direct-message workflows
- Community notifications
- Sales follow-up
- Abandoned-form reminders
- Abandoned-cart reminders
- Internal notifications
- AI-generated responses
- Personalized campaigns
- Re-engagement campaigns
- Transactional messages
- Review requests
- Feedback requests
- Referral requests

---

# Automated Communication Review Record

## 1. Workflow Information

| Field | Information |
|---|---|
| Workflow name | [Enter name] |
| Communication type | Email / SMS / Chatbot / CRM / Social / Internal / Other |
| Business owner | [Enter name] |
| Workflow builder | [Enter name] |
| Message writer | [Enter name] |
| Data owner | [Enter name] |
| Privacy reviewer | [Enter name or “Not required”] |
| Compliance reviewer | [Enter name or “Not required”] |
| Technical reviewer | [Enter name] |
| Final approver | [Enter name and role] |
| Intended audience | [Describe audience] |
| Customer journey stage | [Enter stage] |
| Trigger | [Describe trigger] |
| Planned activation date | [Enter date] |
| Review date | [Enter date] |
| Current version | [Enter version] |
| Risk level | Low / Moderate / High / Critical |
| Status | Draft / Testing / Corrections required / Approved / Active / Paused / Retired |

---

## 2. Review Outcome

Select one:

- [ ] Approved
- [ ] Approved with conditions
- [ ] Corrections required
- [ ] Additional testing required
- [ ] Privacy review required
- [ ] Compliance review required
- [ ] Technical review required
- [ ] Workflow must remain paused
- [ ] Workflow must not be activated
- [ ] Workflow should be retired

### Review Summary

[Summarize the decision.]

### Highest-Risk Issue

[Identify the most important risk.]

### Required Corrections

- [Correction]
- [Correction]
- [Correction]

### Conditions of Approval

- [Condition]
- [Condition]
- [Condition]

---

# Part One: Communication Purpose

## 3. Business Purpose

Confirm:

- [ ] The communication has one primary purpose.
- [ ] The purpose is documented.
- [ ] The communication supports a legitimate customer or business need.
- [ ] Automation is appropriate for the task.
- [ ] A manual message would not be safer or more respectful.
- [ ] The communication is not being sent merely because the technology permits it.
- [ ] The expected outcome is defined.
- [ ] Success can be measured.
- [ ] The communication does not conceal a different sales purpose.

### Primary Purpose

[Describe.]

### Expected Outcome

[Describe.]

### Why Automation Is Appropriate

[Explain.]

---

## 4. Communication Category

Select the category:

- [ ] Transactional
- [ ] Operational
- [ ] Educational
- [ ] Marketing
- [ ] Sales
- [ ] Customer support
- [ ] Onboarding
- [ ] Retention
- [ ] Renewal
- [ ] Community
- [ ] Internal
- [ ] Safety or service interruption
- [ ] Other: [Describe]

Confirm:

- [ ] The category is labeled correctly.
- [ ] Marketing messages are not disguised as transactional messages.
- [ ] Transactional messages contain only appropriate promotional content.
- [ ] Emergency or service messages are reserved for genuine operational needs.
- [ ] The category matches the consent basis.

---

## 5. Desired Customer Action

Confirm:

- [ ] The requested action is clear.
- [ ] The requested action is reasonable.
- [ ] The audience understands what happens next.
- [ ] The action fits the journey stage.
- [ ] The message does not create unnecessary urgency.
- [ ] The message does not pressure vulnerable recipients.
- [ ] The CTA does not hide a sales step.
- [ ] A lower-commitment path exists when appropriate.
- [ ] Human contact is available when needed.

### Primary CTA

[Enter CTA.]

### Secondary CTA

[Enter CTA or “None.”]

---

# Part Two: Audience and Journey Stage

## 6. Audience Definition

Confirm:

- [ ] The primary audience is defined.
- [ ] The audience belongs in the workflow.
- [ ] Audience membership is based on reliable data.
- [ ] The workflow does not assume sensitive personal traits.
- [ ] The audience is not broader than necessary.
- [ ] Internal test users are excluded from production sends.
- [ ] Employees are excluded unless intentionally included.
- [ ] Existing customers and prospects are distinguished when necessary.
- [ ] Regional or language differences are considered.
- [ ] Vulnerable audiences receive additional review.

### Primary Audience

[Describe.]

### Excluded Audiences

- [Audience]
- [Audience]
- [Audience]

---

## 7. Customer Journey Stage

Select the primary stage:

- [ ] Discovery
- [ ] Awareness
- [ ] Problem recognition
- [ ] Education
- [ ] Evaluation
- [ ] Decision
- [ ] Purchase
- [ ] Onboarding
- [ ] Adoption
- [ ] Retention
- [ ] Renewal
- [ ] Advocacy
- [ ] Re-engagement
- [ ] Support
- [ ] Service recovery

Confirm:

- [ ] The message fits the selected stage.
- [ ] The amount of context fits the recipient’s knowledge.
- [ ] The CTA fits the stage.
- [ ] Trust is built before high-commitment requests.
- [ ] New leads do not receive advanced customer messaging.
- [ ] Existing customers do not receive prospect-only messaging.
- [ ] Service-recovery messages are not turned into promotional pitches.

### Customer Question at This Stage

[Enter question.]

### Appropriate Next Step

[Describe.]

---

## 8. Recipient Eligibility

Confirm that recipients:

- [ ] Meet the audience definition.
- [ ] Meet the journey-stage requirement.
- [ ] Have the required consent.
- [ ] Have not opted out.
- [ ] Are not suppressed.
- [ ] Are not blocked.
- [ ] Are not marked as invalid.
- [ ] Have not completed the desired action already.
- [ ] Are not enrolled in a conflicting sequence.
- [ ] Are not within a cooling-off period.
- [ ] Are not part of an excluded geography.
- [ ] Are not part of a restricted category.
- [ ] Have valid contact information.
- [ ] Have not exceeded communication-frequency limits.

---

# Part Three: Trigger Logic

## 9. Trigger Definition

Document the exact trigger:

```text
When [event or condition] occurs, enroll [eligible audience] into [workflow].
```

### Trigger Event

[Describe.]

### Trigger Source

[Enter system or data source.]

### Trigger Timing

[Describe.]

Confirm:

- [ ] The trigger is specific.
- [ ] The trigger can be tested.
- [ ] The trigger uses the correct data source.
- [ ] The trigger cannot fire from incomplete records.
- [ ] The trigger cannot fire from test activity.
- [ ] The trigger cannot fire repeatedly without purpose.
- [ ] The trigger is not based on ambiguous data.
- [ ] Delayed system updates are considered.
- [ ] Time-zone handling is documented.

---

## 10. Enrollment Rules

Confirm:

- [ ] Enrollment criteria are documented.
- [ ] Re-enrollment rules are documented.
- [ ] One-time enrollment is enforced when appropriate.
- [ ] Repeat enrollment has a clear business reason.
- [ ] Re-enrollment requires a new qualifying event.
- [ ] Existing workflow members are handled correctly.
- [ ] Manual enrollment is restricted.
- [ ] Imported records do not bypass eligibility checks.
- [ ] Backfilled historical data does not trigger unintended messages.
- [ ] Duplicate contacts are addressed.

### Re-enrollment Rule

- [ ] Never
- [ ] Once after a new event
- [ ] After a waiting period
- [ ] Repeatedly when conditions are met
- [ ] Manual approval required
- [ ] Other: [Describe]

---

## 11. Exit Rules

Confirm recipients exit when:

- [ ] They complete the desired action.
- [ ] They reply.
- [ ] They book an appointment.
- [ ] They make a purchase.
- [ ] They become a customer.
- [ ] They cancel.
- [ ] They opt out.
- [ ] Their contact information becomes invalid.
- [ ] They enter a conflicting workflow.
- [ ] A human takes ownership.
- [ ] The workflow reaches its final step.
- [ ] A risk or complaint is recorded.
- [ ] Another condition applies: [Describe]

### Immediate Exit Conditions

[List conditions.]

---

## 12. Suppression Rules

Suppress recipients who are:

- [ ] Unsubscribed
- [ ] Opted out
- [ ] Marked do not contact
- [ ] Blocked
- [ ] Bounced
- [ ] Invalid
- [ ] Complaining
- [ ] In litigation or sensitive dispute
- [ ] In an active support escalation
- [ ] In a payment dispute
- [ ] Recently contacted
- [ ] Existing customers in a prospect campaign
- [ ] Prospects in a customer-only campaign
- [ ] Employees
- [ ] Test records
- [ ] Competitors when appropriate
- [ ] Other: [Describe]

Confirm:

- [ ] Suppression updates occur before every send.
- [ ] Suppression lists are synchronized.
- [ ] Manual overrides are restricted.
- [ ] Global suppression takes priority over campaign enrollment.
- [ ] Opt-out requests take effect promptly.

---

# Part Four: Consent and Preferences

## 13. Consent Basis

Select the basis:

- [ ] Explicit opt-in
- [ ] Existing customer relationship
- [ ] Transactional necessity
- [ ] Contractual necessity
- [ ] Internal business need
- [ ] Other authorized basis: [Describe]
- [ ] Consent basis uncertain

Confirm:

- [ ] Consent is documented.
- [ ] Consent covers the communication channel.
- [ ] Consent covers the message category.
- [ ] Consent covers the sender.
- [ ] Consent has not expired where applicable.
- [ ] Imported lists have valid consent.
- [ ] Purchased lists are not used without appropriate authorization.
- [ ] Consent language was clear.
- [ ] Consent was not bundled deceptively.
- [ ] Withdrawal is possible.

---

## 14. Communication Preferences

Confirm:

- [ ] Channel preferences are respected.
- [ ] Topic preferences are respected.
- [ ] Frequency preferences are respected.
- [ ] Language preferences are respected.
- [ ] Time-zone preferences are respected.
- [ ] Accessibility preferences are respected.
- [ ] Contact-method preferences are current.
- [ ] Preference-center updates synchronize correctly.

---

## 15. Unsubscribe and Opt-Out

Confirm:

- [ ] Marketing email includes an unsubscribe mechanism.
- [ ] SMS includes appropriate opt-out instructions.
- [ ] Opt-out language is understandable.
- [ ] Opt-out does not require account login unnecessarily.
- [ ] Opt-out is processed promptly.
- [ ] Opt-out applies to the correct communication category.
- [ ] Global opt-out is available when required.
- [ ] Transactional messages are not blocked improperly.
- [ ] The unsubscribe link works.
- [ ] The confirmation page works.
- [ ] Opted-out users do not re-enter automatically.

### Tested By

[Enter name.]

### Test Date

[Enter date.]

---

# Part Five: Message Accuracy

## 16. Basic Information

Confirm:

- [ ] Sender name is correct.
- [ ] Sender address or account is correct.
- [ ] Reply address works.
- [ ] Recipient name fields work.
- [ ] Company name is correct.
- [ ] Offer name is correct.
- [ ] Product name is correct.
- [ ] Dates are correct.
- [ ] Times are correct.
- [ ] Time zones are clear.
- [ ] Locations are correct.
- [ ] Contact information is current.
- [ ] Support information is current.

---

## 17. Offer Details

Confirm:

- [ ] Offer description is current.
- [ ] Deliverables are accurate.
- [ ] Eligibility is accurate.
- [ ] Availability is current.
- [ ] Capacity claims are real.
- [ ] Deadlines are real.
- [ ] Geographic restrictions are visible.
- [ ] Customer responsibilities are visible.
- [ ] Business responsibilities are visible.
- [ ] Exclusions are visible.
- [ ] The automated message matches the landing page.

---

## 18. Pricing and Payment

Confirm:

- [ ] Price is current.
- [ ] Currency is clear.
- [ ] Payment terms are accurate.
- [ ] Fees are visible.
- [ ] Taxes are described appropriately.
- [ ] Discounts are authorized.
- [ ] Promotional expiration dates are accurate.
- [ ] Installment terms are accurate.
- [ ] Refund terms are accurate.
- [ ] The checkout page matches the message.
- [ ] AI-generated text did not invent pricing.

---

## 19. Claims

Confirm:

- [ ] Claims are supported.
- [ ] Claims match approved wording.
- [ ] Comparative claims identify their basis.
- [ ] Customer results preserve context.
- [ ] Results are not presented as guarantees.
- [ ] “Best,” “first,” “only,” and similar claims are verified.
- [ ] Testimonials are approved.
- [ ] Required disclosures remain visible.
- [ ] Short messages do not exaggerate the claim.
- [ ] AI-generated content did not invent evidence.

---

## 20. Dates and Deadlines

Confirm:

- [ ] Event dates are current.
- [ ] Registration deadlines are current.
- [ ] Offer deadlines are current.
- [ ] Renewal dates are calculated correctly.
- [ ] Appointment dates use the recipient’s time zone correctly.
- [ ] Day and date combinations match.
- [ ] Reminder timing is appropriate.
- [ ] Expired messages cannot continue sending.
- [ ] Date formatting is consistent.
- [ ] Relative terms such as “tomorrow” are generated correctly.

---

# Part Six: Brand Voice

## 21. Voice Consistency

Confirm:

- [ ] The message sounds recognizable.
- [ ] Tone fits the situation.
- [ ] Vocabulary matches the brand.
- [ ] Sentence rhythm feels natural.
- [ ] The message does not sound robotic.
- [ ] The message does not imitate another creator.
- [ ] Signature phrases are used sparingly.
- [ ] Serious situations receive serious language.
- [ ] Support messages do not sound cold.
- [ ] Sales messages do not become aggressive.
- [ ] Automated messages remain connected to human communication.

### Voice Characteristics

1. [Characteristic]
2. [Characteristic]
3. [Characteristic]
4. [Characteristic]
5. [Characteristic]

---

## 22. Generic AI Language Review

Review for phrases such as:

- “In today’s fast-paced world”
- “Unlock your potential”
- “Game-changing”
- “Revolutionary”
- “Elevate your experience”
- “Delve into”
- “Harness the power”
- “Seamlessly”
- “Take it to the next level”
- “Transformative journey”
- “It is important to note”
- “In conclusion”

Confirm:

- [ ] Generic language was removed or made specific.
- [ ] Empty transitions were removed.
- [ ] Artificial enthusiasm was reduced.
- [ ] Human judgment was added.
- [ ] The message sounds appropriate for the relationship.
- [ ] The message does not sound mass-produced.

---

## 23. Read-Aloud Review

Confirm:

- [ ] The message was read aloud.
- [ ] Personalization sounds natural.
- [ ] The CTA sounds proportionate.
- [ ] Awkward sentences were revised.
- [ ] Repetition was reduced.
- [ ] The tone fits an automated message.
- [ ] The message would not embarrass the sender if shown publicly.

---

# Part Seven: Personalization

## 24. Personalization Fields

Check all fields used:

- [ ] First name
- [ ] Last name
- [ ] Company
- [ ] Job title
- [ ] Location
- [ ] Product
- [ ] Purchase
- [ ] Appointment date
- [ ] Event
- [ ] Account status
- [ ] Customer stage
- [ ] Previous activity
- [ ] Assigned representative
- [ ] Other: [Describe]

Confirm:

- [ ] Every field is necessary.
- [ ] Every field is accurate enough for use.
- [ ] Sensitive fields are excluded.
- [ ] Personalization does not reveal hidden tracking.
- [ ] Personalization does not make inappropriate assumptions.
- [ ] Personalization is not based on protected traits.
- [ ] Default values are safe.
- [ ] Missing fields do not create broken language.
- [ ] Fallback wording is tested.

---

## 25. Fallback Values

Examples:

```text
Hello,
```

instead of:

```text
Hello [First Name],
```

Confirm:

- [ ] Blank fields use appropriate fallbacks.
- [ ] Unknown values do not appear as “null.”
- [ ] Placeholder text cannot reach recipients.
- [ ] Incorrect capitalization is handled.
- [ ] Unusual names are preserved.
- [ ] Company names are not inserted into personal fields.
- [ ] Test records cover missing data.

---

## 26. Personalization Accuracy

Confirm:

- [ ] Data comes from the correct record.
- [ ] Merged contacts do not combine unrelated people.
- [ ] Household contacts are handled correctly.
- [ ] Shared email addresses are considered.
- [ ] Company changes are reflected.
- [ ] Previous purchases are accurate.
- [ ] Appointment details are accurate.
- [ ] Assigned representatives are current.
- [ ] Personalization refreshes before send time.
- [ ] Sensitive historical activity is not exposed.

---

# Part Eight: Privacy and Confidential Information

## 27. Information Review

Check for:

- [ ] Personal email addresses
- [ ] Personal phone numbers
- [ ] Home addresses
- [ ] Account numbers
- [ ] Payment information
- [ ] Health information
- [ ] Legal information
- [ ] Passwords
- [ ] API keys
- [ ] Access tokens
- [ ] Customer-support details
- [ ] Private purchase history
- [ ] Employee information
- [ ] Confidential business information
- [ ] Other: [Describe]

Confirm:

- [ ] Only necessary information is included.
- [ ] Sensitive information is excluded.
- [ ] Confidential information is not inserted through personalization.
- [ ] Internal notes are not exposed.
- [ ] Hidden CRM fields are not mapped accidentally.
- [ ] Attachments are reviewed separately.
- [ ] Logs do not store unnecessary message content.

---

## 28. Data Minimization

Confirm:

- [ ] The workflow uses the minimum necessary data.
- [ ] Unused fields are not transferred.
- [ ] Sensitive fields are not copied between systems.
- [ ] Historical data is not included without purpose.
- [ ] AI prompts contain only necessary information.
- [ ] Test records use synthetic data.
- [ ] Data retention is documented.
- [ ] Deletion is possible.

---

## 29. Confidentiality Stop Conditions

Do not activate when:

- [ ] Passwords or credentials appear in messages.
- [ ] Private customer notes can be inserted.
- [ ] Financial information can be exposed.
- [ ] Health information lacks authorization.
- [ ] Legal information lacks authorization.
- [ ] Attachments may contain confidential material.
- [ ] Shared links expose restricted files.
- [ ] Personalization can pull from the wrong record.
- [ ] AI output can reveal private memory.
- [ ] Another critical confidentiality risk exists: [Describe]

---

# Part Nine: AI-Assisted Content

## 30. AI Instructions

Confirm:

- [ ] The AI receives the current brand-voice profile.
- [ ] The AI receives the correct audience context.
- [ ] The AI receives the correct journey stage.
- [ ] The AI receives approved offer information.
- [ ] The AI receives current source material.
- [ ] The AI is instructed not to invent facts.
- [ ] The AI is instructed not to invent claims.
- [ ] The AI is instructed not to invent stories.
- [ ] The AI is instructed not to expose confidential information.
- [ ] The AI is instructed not to send or publish without approval.
- [ ] Output constraints are documented.

---

## 31. AI Output Review

Confirm:

- [ ] Every message was reviewed by a human.
- [ ] Facts were verified.
- [ ] Links were verified.
- [ ] Claims were verified.
- [ ] Personalization was reviewed.
- [ ] Brand voice was reviewed.
- [ ] Generic AI phrasing was reviewed.
- [ ] Confidential information was reviewed.
- [ ] Hallucinated details were removed.
- [ ] The approved version is locked.
- [ ] The production workflow cannot regenerate uncontrolled text unexpectedly.

---

## 32. Dynamic AI Responses

For live AI-generated responses, confirm:

- [ ] Approved topics are defined.
- [ ] Prohibited topics are defined.
- [ ] Knowledge sources are approved.
- [ ] Retrieval respects access permissions.
- [ ] The system identifies uncertainty.
- [ ] The system does not fabricate sources.
- [ ] High-risk questions escalate to a human.
- [ ] Private customer data is isolated.
- [ ] Conversation logs are protected.
- [ ] The system can be disabled quickly.
- [ ] Ongoing sampling and review are assigned.

---

## 33. Human Approval Requirement

Select one:

- [ ] Every message requires human approval.
- [ ] Every campaign version requires approval.
- [ ] High-risk messages require approval.
- [ ] Low-risk transactional messages may send after template approval.
- [ ] Dynamic AI responses require ongoing sampling.
- [ ] Other: [Describe]

### Approval Owner

[Enter name.]

### Approval Scope

[Describe.]

---

# Part Ten: Email Automation

## 34. Email Identity

Confirm:

- [ ] Sender name is recognizable.
- [ ] Sender domain is correct.
- [ ] Reply address works.
- [ ] Replies reach a monitored inbox.
- [ ] Authentication is configured appropriately.
- [ ] The sender is authorized.
- [ ] The physical business information is included when required.
- [ ] The message does not imitate another sender.

---

## 35. Subject Line and Preview Text

Confirm:

- [ ] Subject line matches the message.
- [ ] Preview text supports the subject.
- [ ] Personalization works.
- [ ] No confidential information appears.
- [ ] No false urgency appears.
- [ ] No misleading “RE:” or “FWD:” appears.
- [ ] Capitalization is appropriate.
- [ ] Spam-like language is controlled.
- [ ] Subject and preview text were tested on mobile.

---

## 36. Email Body

Confirm:

- [ ] Opening is clear.
- [ ] Main purpose is visible.
- [ ] Paragraphs are readable.
- [ ] CTA is easy to identify.
- [ ] Links are descriptive.
- [ ] Images have alternative text.
- [ ] Plain-text version is acceptable.
- [ ] Footer information is correct.
- [ ] Unsubscribe works.
- [ ] Mobile layout is readable.
- [ ] Dark-mode presentation is acceptable where practical.

---

## 37. Email Deliverability

Confirm:

- [ ] Sender authentication is configured.
- [ ] Domain reputation is monitored.
- [ ] Bounces are handled.
- [ ] Complaints are handled.
- [ ] Invalid addresses are suppressed.
- [ ] List hygiene is maintained.
- [ ] Sending volume is reasonable.
- [ ] Sudden volume spikes are avoided.
- [ ] Test emails do not use real customer data unnecessarily.
- [ ] Deliverability monitoring is assigned.

---

# Part Eleven: SMS and Messaging

## 38. SMS Review

Confirm:

- [ ] SMS consent exists.
- [ ] Sender identity is clear.
- [ ] The message is concise.
- [ ] Timing is appropriate.
- [ ] Frequency is reasonable.
- [ ] Opt-out instructions are included when required.
- [ ] Links are trustworthy.
- [ ] No sensitive information appears.
- [ ] The message does not require unsafe action while driving.
- [ ] Replies are monitored.
- [ ] Carrier or platform requirements are considered.

---

## 39. Messaging Applications

Confirm:

- [ ] The application is approved.
- [ ] Recipient identity is correct.
- [ ] The business account is recognizable.
- [ ] Automated responses are identified when appropriate.
- [ ] Human support is available.
- [ ] Personal data is minimized.
- [ ] Attachments are reviewed.
- [ ] Group messages do not expose member information.
- [ ] Conversation retention is understood.
- [ ] Escalation rules are documented.

---

# Part Twelve: Chatbots

## 40. Chatbot Introduction

Confirm:

- [ ] The chatbot identifies itself appropriately.
- [ ] Its purpose is clear.
- [ ] Its limitations are clear when needed.
- [ ] Human support is offered.
- [ ] Consent is obtained before collecting sensitive information.
- [ ] The chatbot does not pretend to be a named human.
- [ ] The chatbot does not make unsupported promises.
- [ ] The chatbot does not provide high-risk advice beyond its scope.

---

## 41. Chatbot Conversation Design

Confirm:

- [ ] Conversation paths are documented.
- [ ] Required questions are limited.
- [ ] Free-text inputs are handled safely.
- [ ] Sensitive information is discouraged.
- [ ] Error responses are helpful.
- [ ] Repeated loops are prevented.
- [ ] The user can restart.
- [ ] The user can exit.
- [ ] The user can reach a human.
- [ ] The chatbot remembers only appropriate information.

---

## 42. Chatbot Escalation

Escalate when:

- [ ] The user requests a human.
- [ ] The issue involves payment disputes.
- [ ] The issue involves legal threats.
- [ ] The issue involves health or safety.
- [ ] The issue involves account security.
- [ ] The user appears distressed.
- [ ] The chatbot lacks confidence.
- [ ] The user repeats the question.
- [ ] The conversation becomes sensitive.
- [ ] Another condition applies: [Describe]

### Escalation Destination

[Enter team, inbox, or person.]

### Expected Response Time

[Enter time.]

---

# Part Thirteen: CRM and Sales Automation

## 43. CRM Data Review

Confirm:

- [ ] Lifecycle stage is accurate.
- [ ] Lead status is accurate.
- [ ] Customer status is accurate.
- [ ] Contact owner is current.
- [ ] Company association is correct.
- [ ] Duplicate contacts are addressed.
- [ ] Activity history is current.
- [ ] Suppression fields are current.
- [ ] Consent fields are current.
- [ ] Imported records are reviewed.

---

## 44. Sales Sequence Review

Confirm:

- [ ] Sequence purpose is clear.
- [ ] Recipient eligibility is clear.
- [ ] Messages are relevant.
- [ ] Follow-up timing is reasonable.
- [ ] The sequence stops after a reply.
- [ ] The sequence stops after booking.
- [ ] The sequence stops after opt-out.
- [ ] Human tasks are assigned.
- [ ] Personalization is accurate.
- [ ] The message does not pretend a manual action occurred when it did not.
- [ ] The sequence does not create fake familiarity.

---

## 45. Lead Handoff

Confirm:

- [ ] Handoff criteria are documented.
- [ ] The assigned representative is notified.
- [ ] The recipient is not contacted by multiple representatives.
- [ ] Automation pauses after handoff.
- [ ] Context is available to the human owner.
- [ ] Confidential notes remain internal.
- [ ] Follow-up expectations are clear.
- [ ] Unassigned leads have a fallback owner.

---

# Part Fourteen: Social and Community Automation

## 46. Social-Media Automation

Confirm:

- [ ] The correct account is selected.
- [ ] The message fits the platform.
- [ ] Mentions and tags are accurate.
- [ ] Hashtags are appropriate.
- [ ] Links work.
- [ ] Images are approved.
- [ ] Scheduled time is correct.
- [ ] Time-sensitive content expires.
- [ ] Replies and comments are monitored.
- [ ] Automation does not post identical content everywhere without purpose.
- [ ] Engagement automation does not create deceptive interactions.

---

## 47. Direct Messages

Confirm:

- [ ] The recipient has a reasonable basis to expect contact.
- [ ] The message is relevant.
- [ ] The sender is identifiable.
- [ ] The message is not disguised as a personal manual note.
- [ ] The message does not create false familiarity.
- [ ] The message does not continue after opt-out.
- [ ] Follow-up limits are defined.
- [ ] Human responses take priority.
- [ ] Sensitive conversations are escalated.

---

## 48. Community Notifications

Confirm:

- [ ] Members consented to notifications.
- [ ] Notification purpose is clear.
- [ ] Frequency is reasonable.
- [ ] Moderation events are handled carefully.
- [ ] Public and private messages are distinguished.
- [ ] Member information is protected.
- [ ] Scheduled announcements are current.
- [ ] Human moderators can intervene.
- [ ] Retired events do not continue triggering reminders.

---

# Part Fifteen: Timing and Frequency

## 49. Send Timing

Confirm:

- [ ] Send time fits the recipient’s time zone.
- [ ] Quiet hours are respected.
- [ ] Weekend timing is appropriate.
- [ ] Holiday timing is appropriate.
- [ ] Event reminders are sent early enough.
- [ ] Follow-up messages allow reasonable response time.
- [ ] Transactional messages are sent promptly.
- [ ] Delayed data does not create outdated messages.
- [ ] Daylight-saving changes are considered.
- [ ] The message will not arrive after the action is no longer possible.

---

## 50. Frequency Limits

Document limits for:

- Emails per day
- Emails per week
- SMS messages per day
- Sales follow-ups
- Reminder messages
- Community notifications
- Re-engagement attempts
- Review requests
- Other: [Describe]

### Frequency Table

| Communication Type | Maximum Frequency | Cooling-Off Period |
|---|---:|---|
| [Type] | [Limit] | [Period] |
| [Type] | [Limit] | [Period] |

Confirm:

- [ ] Global frequency limits override campaign limits.
- [ ] Multiple workflows are considered together.
- [ ] Recent manual contact is considered.
- [ ] Complaints trigger suppression.
- [ ] Recipients are not trapped in endless follow-up cycles.

---

## 51. Sequence Spacing

Confirm:

- [ ] Each message has a distinct purpose.
- [ ] Messages are spaced appropriately.
- [ ] The recipient has time to respond.
- [ ] The sequence does not repeat the same claim.
- [ ] High-pressure escalation is avoided.
- [ ] The final message ends the sequence clearly.
- [ ] Long sequences have review points.

---

# Part Sixteen: Links and Attachments

## 52. Link Review

Confirm:

- [ ] Every link opens.
- [ ] Every link points to the intended destination.
- [ ] Landing pages match the message.
- [ ] Tracking links work.
- [ ] Tracking does not expose confidential information.
- [ ] Private links are not used publicly.
- [ ] Expired pages are replaced.
- [ ] Redirects are expected.
- [ ] Mobile links work.
- [ ] Affiliate links are disclosed when required.

---

## 53. Attachment Review

Confirm:

- [ ] The attachment is necessary.
- [ ] The correct file is attached.
- [ ] The approved version is attached.
- [ ] The file name is safe.
- [ ] Confidential information is removed.
- [ ] Comments and metadata are reviewed.
- [ ] File size is reasonable.
- [ ] The file opens.
- [ ] Recipient permissions are appropriate.
- [ ] A secure link is used instead when safer.

---

## 54. Landing Page Alignment

Confirm:

- [ ] Headline matches the message.
- [ ] Offer details match.
- [ ] Pricing matches.
- [ ] Deadline matches.
- [ ] CTA matches.
- [ ] Form fields are appropriate.
- [ ] Consent language is visible.
- [ ] Privacy information is available.
- [ ] Confirmation page works.
- [ ] Tracking works.
- [ ] Mobile presentation works.

---

# Part Seventeen: Testing

## 55. Test Environment

Confirm:

- [ ] Testing occurs before activation.
- [ ] Production recipients are excluded.
- [ ] Synthetic test data is used.
- [ ] Test records cover multiple scenarios.
- [ ] Test messages are labeled.
- [ ] Test links are safe.
- [ ] Test payment actions cannot create real charges accidentally.
- [ ] Test automations cannot trigger external workflows unintentionally.
- [ ] Logs are available.

---

## 56. Required Test Records

Test at least:

- [ ] Complete record
- [ ] Missing first name
- [ ] Missing company
- [ ] Invalid email
- [ ] Opted-out contact
- [ ] Suppressed contact
- [ ] Existing customer
- [ ] New prospect
- [ ] Duplicate contact
- [ ] Different time zone
- [ ] Different language
- [ ] Recipient who completes the CTA
- [ ] Recipient who replies
- [ ] Recipient who enters a conflicting workflow
- [ ] Other: [Describe]

---

## 57. Functional Testing

Confirm:

- [ ] Trigger fires correctly.
- [ ] Ineligible contacts remain excluded.
- [ ] Suppression works.
- [ ] Re-enrollment works correctly.
- [ ] Exit rules work.
- [ ] Delays work.
- [ ] Branching logic works.
- [ ] Personalization works.
- [ ] Fallback values work.
- [ ] Links work.
- [ ] Attachments work.
- [ ] Replies route correctly.
- [ ] Unsubscribe works.
- [ ] Notifications reach owners.
- [ ] Error handling works.
- [ ] Emergency pause works.

---

## 58. Message Rendering

Test on:

- [ ] Desktop
- [ ] Mobile
- [ ] Major email clients
- [ ] Plain text
- [ ] Dark mode
- [ ] Different screen sizes
- [ ] Different operating systems
- [ ] Relevant browsers
- [ ] Relevant messaging applications

Confirm:

- [ ] Text is readable.
- [ ] Buttons are usable.
- [ ] Images load appropriately.
- [ ] Alternative text is present.
- [ ] Line breaks are correct.
- [ ] Personalization does not break formatting.

---

## 59. Test Record

| Test | Expected Result | Actual Result | Pass or Fail | Reviewer |
|---|---|---|---|---|
| Trigger | [Expected] | [Actual] | Pass / Fail | [Name] |
| Suppression | [Expected] | [Actual] | Pass / Fail | [Name] |
| Personalization | [Expected] | [Actual] | Pass / Fail | [Name] |
| Opt-out | [Expected] | [Actual] | Pass / Fail | [Name] |
| Exit rule | [Expected] | [Actual] | Pass / Fail | [Name] |

---

# Part Eighteen: Failure Handling

## 60. Failure Modes

Plan for:

- Incorrect recipient
- Incorrect personalization
- Incorrect price
- Incorrect deadline
- Broken link
- Missing attachment
- Duplicate send
- Excessive send frequency
- Trigger delay
- Trigger failure
- Suppression failure
- Opt-out failure
- CRM sync failure
- Vendor outage
- AI-generated error
- Data exposure
- Reply-routing failure
- Other: [Describe]

---

## 61. Failure Response

For each failure, document:

| Failure | Detection Method | Immediate Action | Owner |
|---|---|---|---|
| [Failure] | [Method] | [Action] | [Owner] |
| [Failure] | [Method] | [Action] | [Owner] |

Confirm:

- [ ] Errors generate notifications.
- [ ] Notifications do not expose sensitive information.
- [ ] Failed records are isolated.
- [ ] Reprocessing does not create duplicates.
- [ ] Customer-facing corrections are possible.
- [ ] The workflow can be paused quickly.
- [ ] Technical and communication owners are identified.

---

## 62. Emergency Pause

Confirm:

- [ ] A pause control exists.
- [ ] The pause control has been tested.
- [ ] More than one authorized person can pause the workflow.
- [ ] Pausing stops future sends.
- [ ] Pausing does not delete necessary records.
- [ ] Queued messages are handled.
- [ ] Restart requires approval.
- [ ] Emergency contact information is current.

### Emergency Pause Owner

[Enter name.]

### Backup Owner

[Enter name.]

### Pause Procedure Location

[Enter location.]

---

## 63. Escalation

Escalate issues involving:

- Privacy
- Security
- Legal claims
- Medical claims
- Financial claims
- Vulnerable recipients
- Customer complaints
- Public backlash
- Repeated technical failure
- Account compromise
- Incorrect high-volume sends
- Other: [Describe]

### Escalation Path

1. [Role or person]
2. [Role or person]
3. [Role or person]

---

# Part Nineteen: Approval

## 64. Review Requirements

Confirm review for:

- [ ] Business purpose
- [ ] Audience
- [ ] Journey stage
- [ ] Trigger logic
- [ ] Eligibility
- [ ] Suppression
- [ ] Consent
- [ ] Opt-out
- [ ] Accuracy
- [ ] Pricing
- [ ] Claims
- [ ] Brand voice
- [ ] Personalization
- [ ] Privacy
- [ ] Confidentiality
- [ ] AI-generated content
- [ ] Links
- [ ] Attachments
- [ ] Timing
- [ ] Frequency
- [ ] Testing
- [ ] Failure handling
- [ ] Emergency pause
- [ ] Monitoring

---

## 65. Approval Record

| Review Area | Reviewer | Decision | Date | Notes |
|---|---|---|---|---|
| Business | [Name] | Approved / Revise | [Date] | [Notes] |
| Content | [Name] | Approved / Revise | [Date] | [Notes] |
| Data | [Name] | Approved / Revise | [Date] | [Notes] |
| Privacy | [Name] | Approved / Revise | [Date] | [Notes] |
| Technical | [Name] | Approved / Revise | [Date] | [Notes] |
| Final | [Name] | Approved / Revise | [Date] | [Notes] |

---

## 66. Critical Stop Conditions

Do not activate when:

- [ ] Consent is missing.
- [ ] Opt-out does not work.
- [ ] Trigger logic is uncertain.
- [ ] Suppression does not work.
- [ ] Personalization can expose another person’s information.
- [ ] Pricing is incorrect.
- [ ] Deadlines are incorrect.
- [ ] Claims are unsupported.
- [ ] Confidential information may be exposed.
- [ ] AI output remains unreviewed.
- [ ] Duplicate sends are possible.
- [ ] Emergency pause is unavailable.
- [ ] Error monitoring is unavailable.
- [ ] Human ownership is missing.
- [ ] Another critical issue exists: [Describe]

---

## 67. Final Approval Checklist

Before activation, confirm:

- [ ] Purpose is clear.
- [ ] Audience is defined.
- [ ] Journey stage is appropriate.
- [ ] Trigger is documented.
- [ ] Enrollment rules are correct.
- [ ] Exit rules are correct.
- [ ] Suppression works.
- [ ] Consent is documented.
- [ ] Preferences are respected.
- [ ] Unsubscribe or opt-out works.
- [ ] Sender identity is correct.
- [ ] Reply routing works.
- [ ] Message content is accurate.
- [ ] Offer details are current.
- [ ] Pricing is current.
- [ ] Claims are supported.
- [ ] Dates and deadlines are correct.
- [ ] Brand voice is recognizable.
- [ ] Personalization is necessary.
- [ ] Fallback values work.
- [ ] Privacy is protected.
- [ ] Confidential information is excluded.
- [ ] AI-generated content received human review.
- [ ] Links work.
- [ ] Attachments are approved.
- [ ] Landing pages match.
- [ ] Timing is appropriate.
- [ ] Frequency limits are configured.
- [ ] Duplicate prevention works.
- [ ] Test records passed.
- [ ] Failure handling works.
- [ ] Escalation is documented.
- [ ] Emergency pause works.
- [ ] Monitoring is assigned.
- [ ] Final human approval is recorded.

---

## 68. Final Decision

Select one:

- [ ] Approved
- [ ] Approved with conditions
- [ ] Approved for limited release
- [ ] Additional testing required
- [ ] Revision required
- [ ] Privacy review required
- [ ] Compliance review required
- [ ] Workflow must remain paused
- [ ] Workflow must not be activated

### Decision Summary

[Explain.]

### Conditions

- [Condition]
- [Condition]
- [Condition]

### Approved By

[Enter name.]

### Approval Date

[Enter date.]

### Approved Version

[Enter version.]

### Activation Date

[Enter date.]

### Next Review Date

[Enter date.]

---

# Part Twenty: Launch and Monitoring

## 69. Limited Release

Consider a limited release when:

- The audience is large
- The workflow is new
- AI generates dynamic content
- Personalization is complex
- Multiple systems are involved
- The message is high risk
- The trigger is difficult to simulate
- Other: [Describe]

Confirm:

- [ ] Pilot audience is defined.
- [ ] Pilot size is limited.
- [ ] Pilot users are representative.
- [ ] Monitoring is active.
- [ ] Expansion requires approval.
- [ ] Pause criteria are documented.

---

## 70. Launch Monitoring

Monitor:

- Delivery
- Bounces
- Complaints
- Opt-outs
- Replies
- Clicks
- Conversions
- Duplicate sends
- Incorrect personalization
- Broken links
- Trigger errors
- Exit failures
- Suppression failures
- Customer confusion
- Support volume
- Other: [Describe]

### Monitoring Owner

[Enter name.]

### Monitoring Period

[Enter period.]

---

## 71. Pause Thresholds

Pause the workflow when:

- Complaint rate exceeds [threshold]
- Bounce rate exceeds [threshold]
- Duplicate messages are detected
- Incorrect personalization is detected
- Pricing or deadline errors are detected
- Opt-out failures are detected
- Confidential information is exposed
- Trigger logic behaves unexpectedly
- Customer harm is possible
- Other: [Describe]

---

## 72. Performance Review

| Metric | Target | Actual | Interpretation |
|---|---:|---:|---|
| Delivery rate | [Target] | [Actual] | [Interpretation] |
| Reply rate | [Target] | [Actual] | [Interpretation] |
| Click rate | [Target] | [Actual] | [Interpretation] |
| Conversion rate | [Target] | [Actual] | [Interpretation] |
| Opt-out rate | [Target] | [Actual] | [Interpretation] |
| Complaint rate | [Target] | [Actual] | [Interpretation] |

Confirm:

- [ ] Success metrics match the communication purpose.
- [ ] High engagement is not treated as proof of customer value automatically.
- [ ] Complaint and opt-out data receive attention.
- [ ] Qualitative feedback is reviewed.
- [ ] Performance does not override ethical or privacy concerns.

---

# Part Twenty-One: Corrections

## 73. Correction Process

When an error is found:

1. Pause the workflow when necessary.
2. Confirm the error.
3. Identify affected recipients.
4. Stop queued messages.
5. Correct the source template.
6. Correct personalization or logic.
7. Test the correction.
8. Approve the new version.
9. Notify affected recipients when appropriate.
10. Record the correction.
11. Review the root cause.
12. Prevent recurrence.

---

## 74. Correction Record

| Date | Error | Recipients Affected | Correction | Approved By |
|---|---|---:|---|---|
| [Date] | [Error] | [Number] | [Correction] | [Name] |
| [Date] | [Error] | [Number] | [Correction] | [Name] |

---

## 75. Customer Correction Message

A correction message should explain:

- What was incorrect
- What the correct information is
- Whether the recipient needs to act
- Whether any personal information was affected
- How to reach a human
- What has been done to prevent recurrence

### Approved Correction Language

[Enter text.]

---

# Part Twenty-Two: Version Control

## 76. Version Naming

Use a consistent format:

```text
[workflow-name]_v[version]_[date]
```

Example:

```text
customer-welcome-sequence_v1.2_2026-08-02
```

Confirm:

- [ ] Every active workflow has a version.
- [ ] Message templates have versions.
- [ ] Logic changes create a new version.
- [ ] Approved versions are identifiable.
- [ ] Draft and production versions are separated.
- [ ] Retired versions are archived.
- [ ] Rollback is possible.

---

## 77. Change Log

| Version | Date | Change | Reason | Approved By |
|---|---|---|---|---|
| 1.0 | [Date] | Initial release | Workflow launch | [Name] |
| [Version] | [Date] | [Change] | [Reason] | [Name] |

---

## 78. Change Approval

Require reapproval when changing:

- Trigger logic
- Enrollment rules
- Exit rules
- Suppression rules
- Audience
- Consent basis
- Message purpose
- Offer details
- Pricing
- Claims
- Personalization fields
- AI instructions
- Send timing
- Frequency
- Links
- Attachments
- Vendor or system
- Other: [Describe]

---

# Part Twenty-Three: Refresh and Retirement

## 79. Scheduled Review

Review the workflow when:

- Offers change
- Pricing changes
- Deadlines change
- Leadership changes
- Sender information changes
- Consent rules change
- Privacy practices change
- Platform features change
- CRM fields change
- AI instructions change
- Customer questions change
- Performance declines
- Complaints increase
- Links break
- Other: [Describe]

### Review Frequency

- [ ] Monthly
- [ ] Quarterly
- [ ] Every six months
- [ ] Annually
- [ ] Before every campaign
- [ ] When a material change occurs
- [ ] Other: [Describe]

---

## 80. Retirement Conditions

Retire the workflow when:

- The offer is unavailable
- The audience no longer exists
- The trigger is obsolete
- The workflow duplicates another workflow
- Consent is no longer valid
- The message is outdated
- The workflow creates excessive complaints
- The workflow no longer supports the customer journey
- The technology is unsupported
- The workflow cannot be monitored safely
- Other: [Describe]

---

## 81. Retirement Checklist

Confirm:

- [ ] New enrollments are stopped.
- [ ] Queued messages are reviewed.
- [ ] Active recipients are handled.
- [ ] Replacement communication is documented.
- [ ] Links are redirected when appropriate.
- [ ] Documentation is archived.
- [ ] Credentials are revoked when unnecessary.
- [ ] Vendor access is removed.
- [ ] Data retention is reviewed.
- [ ] The retirement decision is recorded.

### Retirement Date

[Enter date.]

### Retirement Owner

[Enter name.]

---

## 82. Quick Automated Communications Approval Checklist

Use this abbreviated version for low-risk workflows.

### Purpose and Audience

- [ ] Purpose clear
- [ ] Audience defined
- [ ] Journey stage appropriate
- [ ] CTA appropriate

### Logic

- [ ] Trigger tested
- [ ] Enrollment rules correct
- [ ] Exit rules correct
- [ ] Suppression works
- [ ] Duplicate prevention works

### Consent

- [ ] Consent documented
- [ ] Preferences respected
- [ ] Opt-out works

### Content

- [ ] Sender correct
- [ ] Message accurate
- [ ] Pricing current
- [ ] Dates current
- [ ] Claims supported
- [ ] Brand voice reviewed

### Personalization

- [ ] Fields necessary
- [ ] Fields accurate
- [ ] Fallbacks work
- [ ] Sensitive data excluded

### AI

- [ ] AI instructions current
- [ ] Facts verified
- [ ] Human review completed
- [ ] Production output controlled

### Technical

- [ ] Links work
- [ ] Attachments correct
- [ ] Reply routing works
- [ ] Timing correct
- [ ] Frequency limits configured

### Safety

- [ ] Privacy reviewed
- [ ] Confidentiality reviewed
- [ ] Failure handling tested
- [ ] Escalation documented
- [ ] Emergency pause tested

### Final

- [ ] Test records passed
- [ ] Final version locked
- [ ] Monitoring assigned
- [ ] Human approval recorded

---

## 83. Version History

| Version | Date | Author | Change | Reason | Approved By |
|---|---|---|---|---|---|
| 1.0 | [Date] | [Name] | Initial checklist | Checklist creation | [Name] |
| [Version] | [Date] | [Name] | [Change] | [Reason] | [Name] |

---

## Important Principle

Automation should handle repetition, not responsibility.

Every automated message still belongs to the organization that designed, approved, and sent it.

---

## Related Resources

- [AI-Generated Content Review Checklist](ai-generated-content-review-checklist.md)
- [Prompt Preparation Checklist](prompt-preparation-checklist.md)
- [Article Publishing Checklist](article-publishing-checklist.md)
- [Lead Magnet Creation Checklist](lead-magnet-creation-checklist.md)
- [Long-Form Content Repurposing Checklist](long-form-content-repurposing-checklist.md)
- [Brand Consistency Evaluation Checklist](brand-consistency-evaluation-checklist.md)
- [Fact and Source Verification Checklist](fact-and-source-verification-checklist.md)
- [Confidential Information Protection Checklist](confidential-information-protection-checklist.md)
- [Approval Workflow Template](../templates/approval-workflow-template.md)
- [Standard Operating Procedure Template](../templates/standard-operating-procedure-template.md)
- [Email Campaign Development Prompt](../prompts/email-campaigns.md)
- [Marketing Automation Workflow Prompt](../prompts/marketing-automation-workflow.md)
- [Human Review and Editing Prompt](../prompts/human-review-and-editing.md)
- [Prompt Development and Testing Prompt](../prompts/prompt-development-and-testing.md)
- [Brand Voice AI](https://github.com/poguedigitalsolutions/brand-voice-ai)
- [AI Marketing Resources](https://github.com/poguedigitalsolutions/ai-marketing-resources)
- [Brand Voice AI Skool](https://www.skool.com/companyvoiceai-6106/about)
- [Pogue Digital Solutions, LLC](https://poguedigitalsolutions.com)

---

## Copyright

Copyright © John M. Pogue and Pogue Digital Solutions, LLC.

All rights reserved unless otherwise stated.
