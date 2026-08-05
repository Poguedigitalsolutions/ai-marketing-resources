name: Suggest a resource
description: Propose a new prompt, template, checklist, framework, workflow, guide, or responsible AI resource.
title: "[Resource Suggestion]: "
labels:
  - enhancement
body:
  - type: markdown
    attributes:
      value: |
        Thank you for suggesting a resource for AI Marketing Resources.

        Please provide enough detail to evaluate the idea, avoid duplication, and understand the human-review and responsible AI requirements.

  - type: input
    id: proposed-title
    attributes:
      label: Proposed title
      description: What should the resource be called?
      placeholder: Example: Customer Testimonial Approval Checklist
    validations:
      required: true

  - type: dropdown
    id: proposed-folder
    attributes:
      label: Proposed folder
      description: Where should this resource live?
      options:
        - prompts
        - templates
        - checklists
        - frameworks
        - workflows
        - customer-research
        - content-strategy
        - responsible-ai
        - root documentation
        - not sure
    validations:
      required: true

  - type: textarea
    id: problem
    attributes:
      label: Problem it solves
      description: Describe the practical problem this resource should help solve.
      placeholder: Explain the current gap, difficulty, or recurring need.
    validations:
      required: true

  - type: textarea
    id: audience
    attributes:
      label: Intended audience
      description: Who would benefit from this resource?
      placeholder: Founders, consultants, marketers, agencies, educators, small businesses, or another group.
    validations:
      required: true

  - type: textarea
    id: existing-gap
    attributes:
      label: Why existing resources do not already solve it
      description: Identify related resources and explain what is missing.
      placeholder: Link related files or describe the gap.
    validations:
      required: true

  - type: dropdown
    id: recommended-format
    attributes:
      label: Recommended format
      options:
        - Prompt
        - Template
        - Checklist
        - Framework
        - Workflow
        - Guide
        - Example
        - Documentation
        - Not sure
    validations:
      required: true

  - type: textarea
    id: sources
    attributes:
      label: Sources or evidence
      description: List any research, standards, customer evidence, examples, or source material that should support the resource.
      placeholder: Include links, citations, or explain what still needs verification.

  - type: textarea
    id: human-review
    attributes:
      label: Human review requirements
      description: What must a person verify, approve, or decide?
      placeholder: Accuracy, brand voice, privacy, legal review, accessibility, final approval, or other requirements.
    validations:
      required: true

  - type: textarea
    id: risks
    attributes:
      label: Risks or limitations
      description: Identify possible misuse, privacy concerns, bias, unsupported claims, or other limitations.
      placeholder: Explain the main risks and safeguards.

  - type: textarea
    id: related-resources
    attributes:
      label: Related repository resources
      description: Link any files that connect to this suggestion.
      placeholder: Example: prompts/customer-avatar-research.md

  - type: checkboxes
    id: final-check
    attributes:
      label: Final check
      options:
        - label: I searched the repository for similar resources.
          required: true
        - label: This suggestion does not include private, confidential, or proprietary information.
          required: true
        - label: I understand that AI-generated material must be reviewed by a person before inclusion.
          required: true
