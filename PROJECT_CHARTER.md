# FCX-01 Project Charter
**Revision 1.0**

---

# 1. Project Overview

FCX-01 is an engineering-driven restomod based on the Mazda FC RX-7.

The purpose of the project is to develop a vehicle that feels like a modern factory evolution of the FC chassis while documenting the engineering process with the rigor of a professional vehicle development program.

The completed vehicle is only one outcome of the project. Equally important is producing clear, well-reasoned engineering documentation that explains not only **what** decisions were made, but **why** they were made.

The project also serves as a case study in AI-assisted engineering collaboration. Throughout development, engineering interactions between human collaborators and AI will be documented and reflected upon to better understand where AI contributes meaningfully, where it falls short, and how it can best support engineering work in small teams.

This project is intended to serve as:

- A personal engineering project
- A platform for collaboration with other engineers
- A demonstration of disciplined systems engineering
- A case study in AI-assisted engineering
- A professional portfolio piece

---

# 2. Project Goals

The project is guided by the following primary goals.

## Primary Goals

- Balanced and predictable handling
- Daily-driver reliability
- OEM-quality refinement
- Track-day capability
- Cost-conscious engineering
- Long-term maintainability
- Serviceable design
- Cohesive vehicle integration

## Secondary Goals

- Approximately 300–400 horsepower
- Modern automatic transmission with paddle shifting
- Modern electronic integration
- Lightweight construction
- Improved aerodynamic efficiency
- OEM+ styling

The project does **not** seek to maximize horsepower, lap times, or visual impact at the expense of the vehicle as a complete system.

---

# 3. Project Operating Principles

These principles guide every engineering decision throughout the project.

## Think at the Vehicle Level

No subsystem exists in isolation.

Every engineering decision should improve the complete vehicle rather than optimize a single component.

## Requirements Drive Design

Project requirements define the solution.

Components should be selected because they satisfy project requirements—not because they are popular, inexpensive, or familiar.

## Engineering Before Preference

Every engineering decision shall be supported by evidence.

Acceptable forms of evidence include:

- Engineering calculations
- Simulation
- Physical testing
- Experimental measurement
- Manufacturer specifications
- Published technical literature
- Industry standards
- Documented engineering experience
- Well-supported community experience

Engineering documentation should cite the evidence supporting significant decisions.

If sufficient evidence does not yet exist, the idea shall be documented as a **Hypothesis** and accompanied by a validation plan.

Personal preference is appropriate only when multiple solutions satisfy the engineering requirements to an equivalent degree.

## Document the Reasoning

Every significant engineering decision should answer four questions:

1. What problem does this solve?
2. Why is this the preferred solution?
3. What alternatives were considered?
4. How will this decision be validated?

Future engineering work should never depend on memory alone.

## Embrace Revision

Changing a design because better evidence becomes available is good engineering.

The objective is not to defend previous decisions, but to continuously improve the vehicle.

---

# 4. Project Decision Hierarchy

Engineering decisions often involve tradeoffs.

When objectives conflict, decisions should generally prioritize:

1. Safety
2. Engineering correctness
3. Vehicle-level performance
4. Reliability
5. Maintainability
6. Manufacturability
7. Cost
8. Refinement and user experience
9. Performance metrics
10. Appearance

Exceptions are acceptable but should be documented and justified.

---

# 5. Documentation Philosophy

Documentation exists to support engineering—not bureaucracy.

Its purpose is to make future engineering work easier.

Every document should help another engineer quickly understand the current state of the project and the reasoning behind it.

Documentation should be:

- Clear
- Concise
- Technically accurate
- Revision controlled
- Easy to navigate
- Focused on engineering reasoning

The objective is to capture decisions, assumptions, evidence, and results without creating unnecessary paperwork.

---

# 6. Project Organization

The project is organized into five primary repositories of knowledge.

## Engineering Workbook

The living description of the vehicle.

Contains requirements, subsystem designs, trade studies, interfaces, design maturity, and validation plans.

Represents the current engineering state of the project.

## Architecture Decision Records (ADRs)

A permanent record of significant engineering decisions.

Each ADR documents:

- Context
- Alternatives considered
- Final decision
- Supporting evidence
- Consequences
- Validation approach

## Engineering Logbook

A chronological journal of engineering work.

Entries summarize:

- Work completed
- Discoveries
- Design reviews
- Problems encountered
- Decisions made
- Next steps

Serves as the project's engineering notebook.

## Technical Data Library

Contains engineering artifacts, including:

- CAD
- Manufacturing drawings
- Analysis
- Simulation
- Test data
- Calibration files
- Photographs
- Supplier documentation

## Final Engineering Report

A polished summary of the completed project.

Documents the final vehicle and the engineering process that produced it.

---

# 7. Confidence Levels

Not all engineering information has the same level of certainty.

Project documentation should identify the confidence associated with significant information.

## Requirement

A project objective or design constraint.

Considered authoritative until intentionally revised.

## Assumption

A reasonable estimate used in the absence of complete information.

Expected to evolve as better information becomes available.

## Hypothesis

An engineering idea that has not yet been validated.

Requires additional analysis or testing.

## Analysis

Supported through engineering calculations or simulation.

Should be verified where practical.

## Test Result

Validated through physical measurement or experimentation.

Represents the highest level of confidence.

---

# 8. Engineering Collaboration

FCX-01 is developed through collaboration between human engineers and AI-assisted engineering tools.

Human engineers remain responsible for defining requirements, exercising engineering judgment, approving design decisions, and validating the completed vehicle.

AI serves as an engineering collaborator by assisting with:

- Brainstorming
- Systems engineering
- Design reviews
- Trade studies
- Technical writing
- Documentation
- Technical organization
- Engineering calculations
- Knowledge synthesis

The objective of this collaboration is to improve engineering quality, strengthen documentation, encourage constructive disagreement, and increase development efficiency without replacing human engineering judgment.

Engineering collaboration is itself a subject of this project. The process will be documented to better understand the strengths, limitations, and best practices of AI-assisted engineering within a small development team.

---

# 9. Design Review

Engineering review exists to improve engineering decisions—not simply approve them.

Both human collaborators and AI reviewers are expected to:

- Identify inconsistencies
- Challenge assumptions
- Suggest alternatives
- Identify technical risks
- Request additional evidence
- Improve documentation
- Consider subsystem interactions
- Maintain alignment with project goals

Constructive disagreement is encouraged whenever supported by sound engineering reasoning.

Better evidence should always take precedence over previous conclusions.

---

# 10. Engineering Workflow

Engineering work generally follows the following cycle:

```text
Requirements
      ↓
Concept Development
      ↓
Trade Study
      ↓
Architecture Selection
      ↓
Design
      ↓
Engineering Review
      ↓
Prototype
      ↓
Testing
      ↓
Documentation Update
      ↓
Repeat
```

Engineering is an iterative process.

Each development cycle should improve both the vehicle and the project's documentation.

---

# 11. Daily Retrospectives

At the conclusion of each engineering session, the project team shall conduct a brief retrospective.

The primary purpose of the retrospective is to improve future engineering work within FCX-01. Reflection is considered part of the engineering process and is intended to continuously improve the quality, efficiency, and robustness of future engineering decisions.

Both human collaborators and AI should participate in the retrospective.

Human collaborators should reflect on topics such as:

- Engineering decisions that could have been approached differently
- Assumptions that should be challenged
- Information that was missing
- Opportunities to improve documentation
- Opportunities to improve future engineering sessions

AI should similarly reflect on its own contribution to the engineering process, including:

- Where it provided meaningful engineering value
- Where it introduced unnecessary complexity
- Where its recommendations were weak or unsupported
- Where additional analysis should have been requested
- How it can better support future engineering work on FCX-01

The purpose of AI reflection is not to evaluate AI for its own sake, but to improve its effectiveness as an engineering collaborator throughout the life of the project.

Retrospectives should remain objective and evidence-based. Both successful and unsuccessful interactions are valuable if they improve future engineering work.

Observations from these retrospectives also contribute to the project's broader case study investigating AI-assisted engineering collaboration. However, the case study is considered a secondary outcome of maintaining a disciplined engineering process rather than the primary objective of the retrospectives.

The detailed retrospective template and documentation format are maintained within the Engineering Collaboration documentation.

---

# 12. Version Control

The Git repository is the project's single source of truth.

Current project documentation shall always reflect the latest accepted engineering decisions.

Engineering discussions, brainstorming sessions, and AI conversations support the development process but are not considered authoritative until incorporated into the project documentation.

---

# 13. Design Reviews

Significant design changes should be reviewed before implementation.

Reviews should consider:

- Requirements compliance
- Vehicle-level effects
- Interfaces with other subsystems
- Manufacturability
- Maintainability
- Reliability
- Cost
- Risk
- Validation strategy

Design reviews should improve the project rather than simply approve it.

---

# 14. Long-Term Vision

FCX-01 is intended to demonstrate that disciplined engineering practices, modern digital tools, and AI-assisted collaboration can enable a small team to execute a vehicle development program with the rigor typically associated with much larger organizations.

Success will be measured not only by the completed vehicle, but also by the quality, transparency, reproducibility, and technical integrity of the engineering process used to create it.

The project aims to produce a vehicle that reflects thoughtful systems engineering and a documented body of work that demonstrates how human expertise and AI collaboration can be combined effectively in complex engineering projects.
