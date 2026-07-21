# Governance

WhiteBox governance exists to prevent financial mistakes, not to slow ordinary research.

## Risk Levels

### Level 1: Public-Safe Preparation

Examples:

- documentation
- schemas
- sanitized examples
- mock tests
- public architecture notes

These can proceed after owner, scope, and output path are recorded.

### Level 2: Isolated Functional Work

Examples:

- standalone tools
- validators
- non-production prototypes
- research harnesses

These require accepted scope, target files, and review boundaries before implementation.

### Level 3: Core or Production Work

Examples:

- formal financial calculation logic
- production deployment paths
- official metric eligibility
- customer-facing output generation
- model pathways that affect household assets, liabilities, lifecycle gap, or risk measures

These require full change control, review, tests, rollback planning, and explicit approval.

## Output Classes

WhiteBox separates outputs into classes:

- research: exploratory evidence only
- preview: scenario or illustrative output
- formal: governed calculation output
- client-ready: advisor-reviewed delivery material

No lower class may be described as a higher class without an explicit promotion gate.

## Model Boundary

Language models may:

- extract facts
- normalize wording
- summarize structured output
- produce client-friendly explanations

Language models must not:

- invent formal financial numbers
- decide formal eligibility
- silently change confirmed facts
- rank planning candidates without governed planner logic
- convert preview output into formal output
