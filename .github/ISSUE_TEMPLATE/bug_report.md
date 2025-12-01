---
name: Bug Report
about: Report a reproducible bug in the project
title: "Bug: [Describe bug concisely]"
labels: "bug"
assignees: "chirag127"

body:
  - type: markdown
    attributes:
      value: | # Use '|' for multi-line strings in YAML
        Please provide a clear and concise description of the bug.
        Also, include as much detail as possible to help us reproduce and fix it.
        Thank you for helping improve **TabFlow-Digital-Journey-Mapper-Browser-Extension**!

  - type: input
    id: environment
    attributes:
      label: Environment
      placeholder: "Browser (e.g., Chrome 127, Firefox 120), OS (e.g., Windows 11, macOS Sonoma), Extension Version (if known)"
    validations:
      required: true

  - type: textarea
    id: steps_to_reproduce
    attributes:
      label: Steps to Reproduce
      placeholder: "Provide a step-by-step guide that could reproduce the bug. Be specific."
      value: |
        1. 
        2. 
        3. 

    validations:
      required: true

  - type: textarea
    id: expected_behavior
    attributes:
      label: Expected Behavior
      placeholder: "What did you expect to happen?"
    validations:
      required: true

  - type: textarea
    id: actual_behavior
    attributes:
      label: Actual Behavior
      placeholder: "What actually happened? Please include any error messages."
    validations:
      required: true

  - type: textarea
    id: additional_context
    attributes:
      label: Additional Context
      placeholder: "Screenshots, logs, or any other context that helps explain the bug. For privacy, please ensure no sensitive data is shared.
      
      If you have specific browser console logs, please include them here.
      
      You can attach screenshots by dragging and dropping them into this field."
    validations:
      required: false

  - type: markdown
    attributes:
      value: | # Use '|' for multi-line strings in YAML
        **Verification & Compliance:**
        - All reports must adhere to the [Contributing Guidelines](https://github.com/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension/blob/main/.github/CONTRIBUTING.md).
        - Ensure no sensitive personal data is included.
        - Check [Known Issues](https://github.com/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension/issues?q=is%3Aopen+is%3Aissue+label%3Abug) to avoid duplicates.
        - For detailed architectural guidance and AI agent directives, refer to our [AGENTS.md](https://github.com/chirag127/TabFlow-Digital-Journey-Mapper-Browser-Extension/blob/main/AGENTS.md).

        *This template has been generated following the Apex Technical Authority protocols for the `TabFlow-Digital-Journey-Mapper-Browser-Extension` repository.*