body:
  - type: textarea
    attributes:
      label: Description
      description: A brief description of the feature.
    validations:
      required: true
  - type: textarea
    attributes:
      label: Motivation
      description: What is the benefit of the feature, and what problem(s) does it solve? Please include examples.
    validations:
      required: true
  - type: textarea
    attributes:
      label: Design and Implementation
      description: >
       Explain in detail:
       
       - How the feature will positively/negatively interact with existing features (if any).
       
       - How the feature should be implemented; syntax and semantics.
       
       - If the feature is a new expression/operator, specify its operator precedence and associativity.
       
       - If the feature is part of the runtime, what is the expected runtime behaviour?
       
       - Any edge cases that could occur, and how to resolve them.
    validations:
      required: true
  - type: textarea
    attributes:
      label: Rationale
      description: >
        Explain your design decisions:
        
        - Why is this the best design? Influences from other languages (if any).
        
        - What are the alternatives? Could this feature be done using GML instead?

    validations:
      required: true
  - type: textarea
    attributes:
      label: Drawbacks
      description: Why shouldnt this feature be added
    validations:
      required: true
  - type: textarea
    attributes:
      label: Unanswered Questions
      description: (Optional) Gaps in your design that you are unsure of.
    validations:
      required: false
  - type: textarea
    attributes:
      label: Future Additions
      description: (Optional) Out-of-scope additions to the feature that could be expanded upon in a future proposal.
    validations:
      required: false
