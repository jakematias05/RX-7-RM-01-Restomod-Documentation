# Engineering Workbook
**Revision 1.0**

---

# Purpose

The Engineering Workbook is the living technical description of FCX-01.

It represents the project's current engineering baseline and serves as the primary technical reference throughout development.

Unlike the Engineering Logbook, which records engineering work chronologically, or the Architecture Decision Records (ADRs), which preserve the reasoning behind significant decisions, the Engineering Workbook describes the vehicle **as it is currently designed**.

At any point during the project, this workbook should answer the question:

> **"What is the current engineering definition of FCX-01?"**

---

# Objectives

The Engineering Workbook exists to:

- Document the current vehicle architecture
- Define subsystem requirements
- Record subsystem interfaces
- Summarize engineering analyses
- Capture accepted trade studies
- Track subsystem design maturity
- Provide a concise technical reference for collaborators

The workbook is not intended to preserve obsolete concepts or historical discussion. Superseded designs belong in the Engineering Logbook or Architecture Decision Records.

---

# Guiding Principles

The Engineering Workbook should always reflect the project's accepted engineering baseline.

Information should be:

- Current
- Concise
- Technically accurate
- Well organized
- Supported by evidence
- Easy to navigate

The workbook is intended to communicate the current state of the design—not every idea considered throughout development.

---

# Organization

The Engineering Workbook is organized into subsystem directories.

Each subsystem contains the documentation necessary to define the current design of that portion of the vehicle.

As the project develops, subsystem folders may also contain supporting analyses, calculations, references, CAD data, images, and other engineering artifacts.

The workbook should scale naturally with project complexity while maintaining a consistent organizational structure.

---

# Standard Subsystem Format

Subsystem documents should generally follow a consistent structure.

## Purpose

What is this subsystem intended to accomplish?

---

## Requirements

Applicable project requirements.

Reference requirement identifiers where appropriate.

---

## Current Design

Describe the accepted engineering solution.

Avoid documenting obsolete concepts.

---

## Interfaces

Describe interactions with other vehicle systems.

Examples include:

- Mechanical interfaces
- Electrical interfaces
- Software interfaces
- Packaging constraints
- Thermal interactions
- Manufacturing dependencies

---

## Engineering Analysis

Summarize calculations, simulations, trade studies, or supporting engineering work.

Detailed analyses should be referenced rather than duplicated.

---

## Design Maturity

Document:

- Current Design Maturity Level (DML)
- Outstanding engineering questions
- Known technical risks

---

## Validation Plan

Describe how the subsystem will be validated.

Examples include:

- Inspection
- Measurement
- Simulation
- Bench testing
- Vehicle testing

---

## References

List supporting references used by the subsystem.

Examples include:

- Manufacturer documentation
- SAE papers
- Engineering textbooks
- Technical forum discussions
- Build documentation
- Industry standards
- Internal analyses

Engineering decisions should reference the evidence supporting them whenever practical.

---

# Confidence Labels

Engineering information should use the project's standard confidence levels.

- **Requirement** — Accepted project objective or constraint.
- **Assumption** — Reasonable estimate requiring future verification.
- **Hypothesis** — Engineering concept requiring validation.
- **Analysis** — Supported through engineering calculation or simulation.
- **Test Result** — Validated through physical measurement or experimentation.

Confidence labels should be applied wherever uncertainty exists.

---

# Writing Style

The workbook should prioritize engineering clarity over completeness.

When writing:

- State conclusions before explanations.
- Use concise technical language.
- Avoid unnecessary repetition.
- Reference supporting documents instead of duplicating them.
- Prefer tables over long prose when appropriate.
- Clearly distinguish facts from assumptions.

Documentation should remain approachable to future collaborators with no prior knowledge of FCX-01.

---

# Relationship to Other Documents

| Document | Purpose |
|----------|---------|
| Project Charter | Defines how the project operates. |
| Engineering Workbook | Defines the current engineering baseline. |
| Architecture Decision Records | Explain why significant decisions were made. |
| Engineering Logbook | Records engineering work chronologically. |
| Technical Data Library | Stores engineering artifacts and supporting files. |
| Final Engineering Report | Documents the completed vehicle and project. |

---

# Revision Policy

The Engineering Workbook is expected to evolve continuously throughout the project.

Whenever accepted engineering decisions modify the current vehicle baseline, the relevant workbook documentation should be updated accordingly.

The Engineering Workbook should always reflect the latest accepted engineering definition of FCX-01.
