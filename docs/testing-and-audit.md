# Testing and Audit

WhiteBox tests should prove both calculation behavior and boundary behavior.

## Minimum Audit Fields

Formal or near-formal outputs should include:

- output_class
- source_path
- calculation_authority
- input_fingerprint
- assumptions_fingerprint
- mutation_flags
- fallback_used
- precision_policy
- eligibility_status
- reason_code

## No-Mutation Audit

Research and preview runs should prove that they did not mutate formal output.

Example fields:

- formal_metrics_written: false
- route_mutated: false
- ranking_mutated: false
- confirmed_facts_mutated: false
- fallback_used: false

## Test Categories

- schema validation
- sanitized fixture validation
- no-mutation audit
- double-count prevention
- missing-input behavior
- preview/formal separation
- market-assumption documentation
- detector replication checks

## Failure Behavior

When required data is missing, the system should fail closed with a reason code instead of producing a plausible but unsupported result.
