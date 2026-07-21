# Public Architecture

WhiteBox separates financial planning into a small number of public-facing concepts. This document is intentionally high level and does not describe private implementation details.

## 1. Financial State

WhiteBox begins with a household financial state: income, expenses, assets, liabilities, insurance context, family structure, and known commitments.

The key principle is that a plan should distinguish confirmed facts from hypothetical assumptions.

## 2. Planner

The planner organizes goals, constraints, priorities, and tradeoffs before scenario analysis.

It asks questions such as:

- What is the household trying to change?
- Which constraints matter?
- Which assumptions are uncertain?
- Which scenario should be tested?
- What needs expert review?

## 3. Scenario Analysis

Scenario analysis explores controlled what-if cases, such as retirement timing, education funding, property decisions, liquidity stress, insurance planning, and family responsibility.

The goal is not to produce a magical answer. The goal is to make assumptions, tradeoffs, and risk boundaries visible.

## 4. Detector Research

Detector research is an experimental layer for finding repeatable planning signals and boundary cases.

Detectors are inspired by expert cognition: experienced advisors often recognize patterns, exceptions, and anomalies before they can fully formalize them. WhiteBox studies whether these patterns can be made more structured, repeatable, and reviewable.

## 5. Advisor Explanation

WhiteBox aims to support advisor-grade explanation:

- what was calculated
- what assumptions were used
- what remains exploratory
- what remains uncertain
- what the advisor should review
