# Detector Methodology

WhiteBox detectors are designed to turn planning observations into repeatable, reviewable product evidence.

A detector is not a prompt, a shortcut, or a one-off conclusion. It is a governed research object that identifies a planning signal, tests it against structured samples, searches for failure cases, and records the boundary where the signal does or does not hold.

## 1. Detector Hypothesis

Every detector starts with a clear hypothesis.

Examples:

- A household with high net worth but low liquidity may still face retirement stress.
- A property-heavy balance sheet can mask short-term solvency weakness.
- A conservative allocation can reduce volatility while increasing long-horizon shortfall risk.
- An insurance premium commitment can become a cash-flow constraint even when protection need is valid.

The hypothesis must state the expected signal and the conditions under which it might appear.

## 2. Sample Design

Detector samples should be controlled.

The sample design should specify:

- household archetype
- market context
- income and expense assumptions
- asset structure
- liability structure
- planning objective
- scenario variables
- expected output class

Public examples must use fictional and sanitized data only.

## 3. Evidence Generation

Detector evidence should come from structured model execution, not narrative judgment alone.

Evidence should record:

- input fingerprint
- scenario identity
- model path
- output class
- key metrics
- no-mutation audit
- failure or blocked reason
- review status

Exploratory detector output remains research evidence until promoted.

## 4. Replication

A detector signal should be replicated before it is trusted.

Replication can include:

- rerunning the same sample
- using an independent execution package
- changing seeds or market paths
- testing adjacent household cases
- checking whether the signal survives data-shape changes

Replication is not proof of universal truth. It is evidence that the result is not just an execution accident.

## 5. Counterexample Search

WhiteBox treats counterexamples as product assets.

A detector should be challenged with cases that could invalidate, narrow, or reverse the signal.

Counterexample search asks:

- When does the signal disappear?
- When does the opposite conclusion appear?
- Which variable caused the change?
- Is the detector measuring the intended mechanism?
- Is the boundary economically meaningful?

## 6. Boundary Classification

A detector should describe its boundary.

Possible boundary outcomes:

- robust signal
- narrow signal
- mechanism evidence only
- insufficient evidence
- counterexample found
- market-assumption dependent
- expert-review required
- not suitable for product promotion

This protects users from treating early research as client-ready advice.

## 7. Expert Review

Human expert review is required before product promotion.

Experts should review:

- financial interpretation
- local market realism
- insurance and planning suitability
- advisor communication risk
- whether the detector could mislead a household

The review should not silently rewrite the evidence. It should accept, reject, narrow, or request more tests.

## 8. Promotion

Detector promotion means a research signal is ready to become part of the product experience.

Promotion requires:

- clear hypothesis
- controlled evidence
- replication
- counterexample review
- boundary notes
- no-mutation audit
- expert review
- public-safe documentation if published

Until then, detector results remain research output.
