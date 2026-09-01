# Product Metrics Framework

A practical framework for connecting product work to outcomes instead of reporting only features delivered.

## Metrics Hierarchy

| Level | Question | Marketplace Example | AI Quality Example |
|---|---|---|---|
| Business outcome | What organizational result should improve? | Completed rental journeys | Safer, more efficient quality operations |
| Product outcome | What user behavior or capability should change? | More qualified users progress to confirmed visits | Reviewers validate relevant calls faster |
| Leading indicator | What changes early? | Interest-to-visit-request rate | Eligible calls pre-screened and reviewer queue adoption |
| Guardrail | What must not deteriorate? | Lead quality, cancellations, privacy incidents | False positives, appeals, privacy and access incidents |
| Delivery health | Can the team deliver safely? | Cycle time and escaped defects | Processing reliability and rule-release quality |

## Marketplace Metric Tree

**Business outcome:** increase completed rental journeys

- Property discovery
  - Search-to-detail rate
  - Relevant-result engagement
- Intent
  - Detail-to-interest rate
  - Eligible lead creation rate
- Visit
  - Interest-to-request rate
  - Request-to-confirmation rate
  - No-show rate
- Qualification and contract
  - Time to qualification
  - Time to signed contract
- Guardrails
  - Duplicate leads
  - Customer complaints
  - Consent and privacy incidents

## AI Quality Metric Tree

**Business outcome:** improve quality-review efficiency and risk visibility

- Coverage and speed
  - Eligible calls processed
  - Median review time
  - Time to validated finding
- Analysis quality
  - Precision and recall by rule and language
  - False-positive rate
  - Reviewer agreement rate
- Operational impact
  - Findings converted to coaching
  - Knowledge or policy improvements
  - Repeat issue rate
- Guardrails
  - Appeal and correction rate
  - Transcription disparity across languages or accents
  - Unauthorized access and retention incidents
  - Processing failures

## Metric Definition Template

For every KPI, document:

- Name and decision it supports
- Formula and unit
- Data source and owner
- Segments and exclusions
- Baseline
- Target and timeframe
- Review cadence
- Known limitations
- Guardrail relationship

## Product Review Questions

- Did the intended user behavior change?
- What evidence supports causality?
- Which segment benefited or was harmed?
- Did a guardrail deteriorate?
- What decision will this metric change?
- Should we continue, adjust or stop the initiative?
