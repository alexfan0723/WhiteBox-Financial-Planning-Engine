# WhiteBox Planning Engine

WhiteBox is a financial planning intelligence system designed for the mainland China market.

It combines deterministic financial modeling, planner-led scenario reasoning, detector-based evidence discovery, and advisor-grade reporting. The system is built with input from local financial planning, insurance, household balance-sheet, and retirement-planning practitioners.

WhiteBox is not a chatbot that guesses financial answers. It is an auditable planning engine: every formal number should come from a governed model path, every recommendation should be traceable to structured facts and assumptions, and every exploratory result should stay clearly separated from formal planning output.

## What WhiteBox Builds

- A current financial state engine for household facts, assets, liabilities, cash flow, protection, and long-horizon planning capacity.
- A planner that turns goals, constraints, tradeoffs, and client priorities into structured planning tasks.
- A scenario simulation engine for controlled what-if analysis across retirement, education, property, insurance, liquidity, and family responsibility cases.
- A detector system that searches for repeatable planning patterns, counterexamples, and boundary conditions before productizing them.
- A report layer that turns verified model output into advisor/client-facing planning material.

## Frontier Direction

WhiteBox is focused on planner and detector innovation:

- Planner-first reasoning: goals and constraints are represented as structured planning objects before simulation.
- Detector-led research: planning patterns are not promoted from anecdotes; they pass through evidence, replication, counterexample, and boundary review.
- Explicit uncertainty handling: exploratory, preview, research, and formal outputs are separated by design.
- Local market adaptation: tax, insurance, housing, family responsibility, liquidity, and retirement assumptions are designed for mainland China instead of copied from overseas planning templates.
- Human expert loop: domain experts participate in product design, evidence review, and boundary decisions.

## Financial Theory Foundation

WhiteBox modeling draws from:

- household balance-sheet planning
- lifecycle finance
- cash-flow and liability matching
- Monte Carlo-style long-horizon risk analysis
- retirement income sustainability
- liquidity and solvency stress testing
- insurance protection gap analysis
- scenario planning and decision science

The system treats financial planning as a governed model problem, not a text-generation problem. Language models may help extract, organize, and explain information, but they must not invent formal financial numbers or decide official planning eligibility.

## Public Repository Scope

This repository is a public-safe project shell. It contains external-facing architecture notes, interface schemas, example payloads, testing conventions, and contribution rules.

It intentionally does not include:

- private production code
- customer data
- deployment bindings
- proprietary prompts
- unreleased model internals
- internal evidence packages
- vendor-specific MVP implementation details

## Status

Early public-safe repository draft. The first goal is to define clear public language, collaboration boundaries, and interface contracts before any production implementation is published.

## License

All rights reserved unless a later license file explicitly states otherwise.
