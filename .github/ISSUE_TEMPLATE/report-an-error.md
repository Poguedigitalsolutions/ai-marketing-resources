name: Report an error
description: Report a broken link, duplicate text, incorrect path, unsupported claim, outdated information, privacy concern, accessibility issue, or formatting problem.
title: "[Error Report]: "
labels:
  - bug
body:
  - type: markdown
    attributes:
      value: |
        Thank you for helping improve AI Marketing Resources.

        Please provide enough detail to locate, understand, and verify the problem.

  - type: input
    id: file-name
    attributes:
      label: File name
      description: Which file contains the issue?
      placeholder: Example: prompts/brand-voice-discovery.md
    validations:
      required: true

  - type: input
    id: section
    attributes:
      label: Section or heading
      description: Where in the file does the issue appear?
      placeholder: Example: Human Review Requirements

  - type: dropdown
    id: issue-type
    attributes:
      label: Type of issue
      options:
        - Broken link
        - Incorrect file path
        - Duplicate text
        - Missing text
        - Formatting problem
        - Typographical error
        - Unsupported claim
        - Outdated information
        - Incorrect fact
        - Privacy or confidentiality concern
        - Accessibility concern
        - Conflicting instructions
        - Other
    validations:
      required: true

  - type: textarea
    id: problem
    attributes:
      label: Describe the problem
      description: Explain what is wrong and how it appears.
      placeholder: Include the exact wording, broken link, incorrect path, or visible problem.
    validations:
      required: true

  - type: textarea
    id: impact
    attributes:
      label: Why it matters
      description: Explain how the issue could confuse users, cause an error, create risk, or reduce accessibility.
      placeholder: Describe the practical impact.
    validations:
      required: true

  - type: textarea
    id: correction
    attributes:
      label: Suggested correction
      description: Provide the corrected wording, path, link, or recommended fix.
      placeholder: Paste the proposed correction here.

  - type: textarea
    id: evidence
    attributes:
      label: Source or evidence
      description: Include any source, documentation, screenshot, or reference that supports the correction.
      placeholder: Add links, citations, or explain how the issue was verified.

  - type: dropdown
    id: urgency
    attributes:
      label: Urgency
      description: How quickly should this be reviewed?
      options:
        - Low: cosmetic or minor wording issue
        - Medium: affects clarity or usability
        - High: creates factual, privacy, accessibility, or operational risk
        - Critical: exposes sensitive information or could cause immediate harm
    validations:
      required: true

  - type: checkboxes
    id: verification
    attributes:
      label: Verification
      options:
        - label: I checked that the issue still exists in the current version.
          required: true
        - label: I included enough detail to locate the problem.
          required: true
        - label: This report does not expose private, confidential, or sensitive information.
          required: true
