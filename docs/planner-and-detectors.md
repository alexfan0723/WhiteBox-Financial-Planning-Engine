# Planner and Detectors

WhiteBox's frontier work is centered on the planner and detector system.

## Planner

The planner is responsible for turning human financial goals into structured planning tasks.

It should answer:

- What is the client trying to change?
- Which facts are already confirmed?
- Which assumptions are hypothetical?
- Which constraints matter?
- Which conflicts require clarification?
- Which simulations should run?
- Which candidates are comparable?

The planner should not rely on free-form text alone. It should preserve typed values, units, provenance, confirmation status, and planning intent.

## Detector System

Detectors are research-to-product bridges.

A detector looks for a repeatable financial planning signal, such as:

- a hidden liquidity boundary
- a retirement timing pattern
- a property-driven solvency constraint
- an insurance protection gap
- a family responsibility stress point
- a planning recommendation that fails under counterexample pressure

## Promotion Path

A detector candidate should move through:

1. Hypothesis
2. Controlled sample design
3. Model execution
4. Replication
5. Counterexample search
6. Boundary classification
7. Expert review
8. Product promotion decision

Until promotion, detector output is research evidence, not client-ready advice.

## Why This Matters

Financial planning products often overfit to single examples. WhiteBox treats repeatability, failure cases, and boundary conditions as first-class product requirements.
