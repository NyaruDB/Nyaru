name: Bug report
description: Report incorrect or unexpected behavior of Nyaru
labels: [bug, need repro]
body:
  - type: markdown
    attributes:
      value: |
        Use Discord for questions: https://go.nyaru.xyz
  - type: textarea
    id: description
    attributes:
      label: Issue description
      description: |
        Describe the issue in as much detail as possible.

        Tip: You can attach images or log files by clicking this area to highlight it and then dragging files into it.
      placeholder: |
        Steps to reproduce with below sample:
        1. do thing x,
        2. do thing in app client,
        3. observe behavior,
        4. expected y to happen, but z happened,
        5. attach the behavior of nyaru
    validations:
      required: true
  - type: input
    id: os
    attributes:
      label: Client Info
      description: Which OS does your application run on? What is your discord version?
  - type: dropdown
    id: priority
    attributes:
      label: Priority this issue should have
      description: Please be realistic. If you need to elaborate on your reasoning, please use the Issue description field above.
      options:
        - Low (slightly annoying)
        - Medium (should be fixed soon)
        - High (immediate attention needed)
    validations:
      required: true
