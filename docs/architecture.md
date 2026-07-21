# Public Architecture

WhiteBox separates financial planning into governed layers. Each layer has a distinct responsibility and a clear boundary.

## 1. Intake and Fact Structuring

This layer converts advisor/client information into structured financial facts.

It covers household members, income, expenses, assets, liabilities, insurance, goals, and known commitments. A fact is not treated as formal until it is confirmed, traceable, and assigned to the correct planning category.

## 2. Current Financial State Engine

This layer computes the household's current financial position.

It is responsible for:

- household balance-sheet structure
- cash-flow capacity
- existing asset and liability treatment
- protection and liquidity context
- planning readiness signals

It does not generate recommendations by itself.

## 3. Planner

The planner turns goals and constraints into structured planning tasks.

It is responsible for:

- objective normalization
- constraint handling
- priority and conflict management
- candidate planning paths
- asking clarifying questions when required

The planner should own reasoning about what should be tested before the simulation engine runs.

## 4. Scenario Simulation Engine

This layer runs controlled what-if analysis.

It is responsible for:

- retirement timing changes
- education funding cases
- property purchase or sale cases
- insurance planning scenarios
- liquidity stress cases
- family responsibility cases
- market and income shock analysis

It does not reinterpret natural language or silently rewrite facts.

## 5. Detector System

The detector system searches for repeatable planning signals.

A detector candidate must pass through:

- evidence generation
- replication
- counterexample search
- boundary review
- human expert review
- no-mutation checks

Detector output remains research evidence until it is explicitly promoted.

## 6. Report Layer

The report layer converts verified model output into advisor/client-facing material.

It explains:

- what was calculated
- what assumptions were used
- what is formal versus exploratory
- what remains uncertain
- what the advisor should review

It must not fabricate missing numbers or mutate calculation-layer results.
