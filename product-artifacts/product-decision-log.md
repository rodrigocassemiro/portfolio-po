# Product Decision Log

A sample of concise decision records used to preserve context, alternatives and revisit conditions.

## Decision 001 — Human Review Is Mandatory for AI Flags

**Context:** AI analysis can produce false positives and may influence consequential employee decisions.

**Decision:** Treat every model output as a potential issue. An authorized reviewer must confirm or reject it before operational action.

**Alternatives considered:**

- Automatic issue confirmation
- Confidence threshold without human review
- Human review only for selected categories

**Why:** Human validation supports fairness, explainability, correction and auditability.

**Trade-off:** Lower automation rate and continued reviewer effort.

**Revisit when:** Never for disciplinary decisions without a new legal, ethical and product-governance assessment.

---

## Decision 002 — Begin with a Small Versioned Rule Set

**Context:** Quality and compliance policies can be complex, ambiguous and frequently updated.

**Decision:** Pilot a small number of high-value rules with a named owner, version and effective date.

**Alternatives considered:**

- Launch with the complete policy library
- Use an unrestricted language model prompt
- Start with individual employee scoring

**Why:** A narrow scope enables measurable evaluation, clearer evidence and safer tuning.

**Trade-off:** Limited initial coverage.

**Revisit when:** Pilot rules meet agreed accuracy and operational-value thresholds.

---

## Decision 003 — Manual Visit Confirmation in Marketplace MVP

**Context:** Full calendar synchronization adds integration and data-quality risk before the visit workflow is validated.

**Decision:** Allow customers to request a visit and notify the broker, while keeping confirmation manual in the first release.

**Alternatives considered:**

- Full real-time calendar integration
- No scheduling capability
- Operations-only scheduling

**Why:** This completes the customer journey sooner and produces evidence for later automation.

**Trade-off:** Temporary operational workload and slower confirmation.

**Revisit when:** Volume, no-show patterns and reliable availability data justify automation.

---

## Decision Record Template

- **Date**
- **Owner**
- **Context**
- **Decision**
- **Alternatives**
- **Evidence**
- **Trade-offs**
- **Risks and mitigations**
- **Revisit condition**
