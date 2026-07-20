# Architecture Decision Records (ADRs)
**Revision 1.0**

---

# Purpose

Architecture Decision Records (ADRs) document significant engineering decisions made throughout the FCX-01 project.

Each ADR explains **why** a decision was made. Together, they provide a permanent record of the project's engineering reasoning.

ADRs preserve design intent after the project has evolved, making it possible to understand and evaluate past decisions without relying on memory.

---

# When to Create an ADR

Create an ADR whenever a decision:

- Significantly affects the vehicle architecture.
- Changes project direction.
- Involves multiple viable alternatives.
- Has long-term engineering consequences.
- Is unlikely to be easily reversed.

Routine implementation details should not require an ADR.

---

# ADR Format

Each ADR should include the following sections.

## Title

A concise description of the decision.

---

## Status

Examples:

- Proposed
- Accepted
- Superseded
- Rejected

---

## Context

What problem or requirement prompted this decision?

---

## Alternatives Considered

Summarize the realistic alternatives evaluated.

---

## Decision

State the selected solution.

---

## Rationale

Explain why this solution was chosen.

Support conclusions with references to engineering evidence whenever possible.

---

## Consequences

Describe the expected impacts, tradeoffs, and future implications of the decision.

Both advantages and disadvantages should be documented.

---

## References

List supporting analyses, Workbook sections, Logbook entries, Technical Data, and external sources.

---

# Writing Guidelines

ADRs should:

- Be concise.
- Focus on engineering reasoning.
- Record decisions, not discussions.
- Explain tradeoffs objectively.
- Remain understandable months or years later.

Whenever practical, each ADR should be readable in a single sitting.

---

# Relationship to Other Documents

- **Engineering Workbook** defines the current design.
- **ADRs** explain why the design became that way.
- **Engineering Logbook** records when the work occurred.
- **Technical Data Library** contains the supporting engineering artifacts.

---

# Revision Policy

Once accepted, ADRs should not be rewritten to match later decisions.

If a decision changes, create a new ADR and mark the previous record as **Superseded**.

The historical engineering reasoning should always be preserved.
