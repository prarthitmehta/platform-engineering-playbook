# Amazon Q for Development and Security

A pattern for integrating AI assistance into development, security reviews, and engineering workflows.

## Diagram

```mermaid
flowchart TD
    D[Developer] --> IDE[IDE / Developer Portal]
    IDE --> Q[Amazon Q]
    Q --> Code[Code Suggestions]
    Q --> Sec[Security Review]
    Q --> Docs[Documentation]
    Q --> Tests[Test Assistance]
    Code --> PR[Pull Request]
    Sec --> PR
    Tests --> PR
    PR --> CI[CI/CD]
    CI --> Obs[Metrics & Feedback]
```

## Use Cases

- Code generation support
- Vulnerability explanation
- Test case generation
- Documentation assistance
- Faster onboarding
