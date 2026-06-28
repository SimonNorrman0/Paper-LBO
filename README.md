# Paper LBO — Hypothetical Firm

A self-built LBO model constructed using a fictional company and self-created assumptions, designed to learn and practice core leveraged buyout mechanics from scratch.

## Purpose

Built as a learning exercise to understand how an LBO works end-to-end — from entry valuation and capital structure through to exit returns. The focus was on getting the mechanics right rather than modelling a real deal.

## What the model covers

| Section | Detail |
|---|---|
| Entry valuation | LTM EBITDA × entry multiple, existing net debt bridge to equity value |
| Sources & uses | Three-tranche capital structure with leverage and equity contribution ratios |
| Capital structure | Revolving credit facility, Term Loan B (1% mandatory amortisation), Senior Notes (bullet) |
| Operating model | Five-year P&L with declining revenue growth, flat margins throughout |
| Free cash flow | Levered FCF build: net income + D&A − CapEx − ΔNWC |
| Debt waterfall | Minimum cash retention → mandatory TLB amort → revolver sweep → TLB optional paydown |
| Returns | MOIC and IRR at exit, sensitivity table across entry and exit multiples |

## Assumptions

All financial inputs — historicals, growth rates, margins, and capital structure terms — are hypothetical and created by the author solely for the purpose of learning LBO mechanics.

## Key outputs

| Metric | Value |
|---|---|
| Entry multiple | 7.5x EV/EBITDA |
| Exit multiple | 7.5x EV/EBITDA |
| Hold period | 5 years |
| MOIC | 2.36x |
| IRR | 18.7% |

## Skills practised

- Structuring a three-tranche LBO capital stack
- Building a debt repayment waterfall with mandatory vs. optional paydown logic
- Linking FCF to the debt schedule and computing levered returns
- Sensitivity analysis across entry and exit multiples
