# WhiteBox Financial Planning Engine

![WhiteBox social cover](assets/social-cover.png)

[简体中文](README.zh-CN.md)

WhiteBox is a financial planning intelligence system designed for the mainland China market.

It combines deterministic financial modeling, planner-led scenario reasoning, detector-based evidence discovery, and advisor-grade reporting. The system is built with input from local financial planning, insurance, household balance-sheet, and retirement-planning practitioners.

WhiteBox is not a chatbot that guesses financial answers. It is an auditable planning engine: every formal number should come from a governed model path, every recommendation should be traceable to structured facts and assumptions, and every exploratory result should stay clearly separated from formal planning output.

## Problem

Financial planning is usually trapped between two weak forms:

- static calculators that cannot reason across goals, constraints, family structure, liquidity, insurance, property, and retirement timing
- language-only assistants that can sound fluent while hiding assumptions, inventing numbers, or mixing exploratory output with formal advice

WhiteBox is designed for the middle ground: structured reasoning with auditable calculations.

## Why WhiteBox

WhiteBox treats financial planning as a governed model problem. The system separates confirmed facts, hypothetical assumptions, planning objectives, simulation results, detector evidence, and advisor-facing explanations.

This separation matters because a household plan is not a single answer. It is a chain of facts, assumptions, constraints, tradeoffs, and reviewable model results.

## What WhiteBox Studies and Builds

- household financial state modeling across assets, liabilities, cash flow, protection, and long-horizon planning capacity
- planner-led reasoning that turns goals, constraints, tradeoffs, and client priorities into structured planning tasks
- controlled scenario analysis across retirement, education, property, insurance, liquidity, and family responsibility cases
- experimental detector research for repeatable planning patterns, counterexamples, and boundary conditions
- advisor-grade explanation that keeps assumptions and calculation status visible

## Core Innovation

WhiteBox is focused on planner and detector innovation.

Planner-first reasoning means that goals and constraints should be represented as structured planning objects before scenario analysis.

Detector research is currently experimental. We use "detector" to describe a research direction: finding repeatable planning signals, boundary cases, and counterexamples before turning them into product features.

The detector idea is partly inspired by cognitive science's view of expertise: experts do not only apply rules; they recognize meaningful patterns, notice anomalies, and understand the boundary conditions of a judgment. WhiteBox explores how a financial planning system can assist that kind of expert pattern recognition without pretending that early research evidence is final advice.

## Market Focus

WhiteBox is grounded in mainland China household planning.

The system is designed around local realities such as property-heavy household balance sheets, family responsibility, education funding, insurance product context, retirement income uncertainty, liquidity constraints, and advisor-client review workflows.

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

## Articles

WhiteBox publishes public-safe bilingual notes on financial planning theory, planner-first reasoning, experimental detector research, and mainland China market context.

- [Offshore Trust Tax: From Legal Title to Control and Benefit](docs/articles/offshore-trust-tax-principles.md)
- [A Goal Is Not Funded by a Number Alone: Matching Money to Time](docs/articles/goals-need-time.md)
- [A Home Is an Asset, Not a Spending Plan](docs/articles/property-is-not-spending-plan.md)
- [Debt Has a Timeline: Plan the Repayment Path, Not Just the Balance](docs/articles/debt-has-a-timeline.md)
- [Insurance in Household Planning: Read Today's Balance Sheet, Then Tomorrow's Paths](docs/articles/insurance-protection-liquidity.md)
- [Insurance in Household Planning: Keep Three Questions Separate](docs/articles/insurance-protection-liquidity-commitments.md)
- [Before Optimizing: Make the Household's Constraints Explicit](docs/articles/constraints-before-optimization.md)
- [Before a Recommendation: Why Financial Planning Starts with Scenarios](docs/articles/scenarios-before-recommendation.md)
- [Financial Planning Is Not One Answer, But an Auditable Reasoning Chain](docs/articles/auditable-reasoning-chain.md)
- [Before a Conclusion: Why Financial Planning Needs Counterexamples](docs/articles/counterexamples-before-conclusions.md)
- [Before a Signal: Check What the Plan Does Not Yet Know](docs/articles/before-a-signal.md)
- [When Assets Are Not Enough: A Fictional Household Case on Liquidity, Timing, and Trade-offs](docs/articles/when-assets-are-not-enough.md)

See the full [Articles Index](docs/articles/README.md).

## Foundation Docs

- [Theory Foundation](docs/theory-foundation.md)
- [Detector Methodology](docs/detector-methodology.md)
- [Mainland China Market Orientation](docs/mainland-china-market.md)
- [Roadmap](ROADMAP.md)

## Roadmap

See [ROADMAP.md](ROADMAP.md).

## Public Repository Scope

This repository is a public-facing project shell. It contains external-facing positioning, theory notes, market orientation, and high-level research methodology.

It intentionally does not include:

- private production code
- customer data
- deployment bindings
- proprietary prompts
- unreleased model internals
- internal evidence packages
- vendor-specific MVP implementation details

## Status

Early public-facing repository. The first goal is to define clear public language, theory foundations, and research direction before any implementation code is published.

## License

All rights reserved unless a later license file explicitly states otherwise.

- [From Expert Experience to Reviewable Questions: What a Planning Detector Can and Cannot Do](docs/articles/expert-experience-to-reviewable-questions.md)