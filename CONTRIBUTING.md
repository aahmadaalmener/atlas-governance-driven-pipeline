# Contributing to ATLAS

ATLAS is governed by explicit constraints.

This document is a participation gate.
It defines the conditions under which contributions are admissible,
and the boundaries that must not be weakened.


Before proceeding, it is important to understand that ATLAS is not a conventional open-source project.  
It is a governance-driven, multi-stage AI pipeline architecture designed to demonstrate disciplined system thinking, not rapid iteration or feature experimentation.

Contributions are welcome — but only when they strengthen the system’s structural integrity.



## Purpose of This Document

This document acts as a governance gate.
Contributions that conflict with the Project Constitution are invalid by definition.


Its role is not to maximize contributions, but to ensure that any contribution:
- preserves architectural intent,
- respects stage boundaries,
- and maintains traceability and decision accountability.

If you are looking for a flexible framework or a playground for experimentation, ATLAS is not the right project.



## What ATLAS Is — and Is Not

ATLAS **is**:
- a governed, multi-stage processing pipeline,
- a proof of system-level architectural thinking,
- a design that favors determinism, traceability, and controlled execution.

ATLAS **is not**:
- a rapid-customization framework,
- a general-purpose AI agent,
- a prompt collection,
- an optimization-first or speed-first system.

These constraints are intentional and non-negotiable.


## Who Should Contribute

Contributions are appropriate from individuals who:
- think in terms of systems, not isolated components,
- understand governance as a design requirement,
- are comfortable working within strict boundaries,
- value explicit responsibilities over flexible behavior.

Typical good-fit contributors include:
- system architects,
- senior engineers,
- governance-oriented designers,
- technical reviewers focused on correctness and clarity.


## Who Should Not Contribute

This project is **not suitable** for contributions that aim to:
- collapse or merge pipeline stages,
- bypass governance or validation gates,
- introduce implicit behavior or “smart defaults”,
- optimize for speed at the expense of traceability,
- turn ATLAS into a plug-and-play tool.

Such contributions will be rejected by design, regardless of technical quality.


## Contribution Types and Review Strictness

All contributions fall into one of the following categories:

1. **Documentation**
   - Clarifications
   - Terminology consistency
   - Structural explanations  
   Review strictness: Low → Medium

2. **Examples / Case Studies**
   - Demonstrations of governed behavior
   - Explicit failure or refusal cases  
   Review strictness: Medium

3. **Stage Definitions**
   - Prompt clarifications
   - Output model refinements
   - Responsibility boundary tightening  
   Review strictness: High

4. **Governance Rules**
   - Gate logic clarification
   - Validation strengthening  
   Review strictness: Very High

5. **Tooling (Context Only)**
   - Structural inspection tools
   - Read-only analysis helpers  
   Review strictness: Very High

Any contribution outside these categories will be rejected.


## Non-Negotiable Rules

The following rules apply to **all** contributions:

- No stage may be skipped, merged, or implicitly compensated for.
- No stage may take responsibility for another stage’s failure.
- No execution may occur without explicit admissibility.
- No missing intent may be inferred or invented.
- No contribution may weaken traceability.

Breaking any of these rules is considered an architectural violation.


## Required Contribution Structure

Every contribution **must** include the following information:

- **Scope**  
  What is being changed, and where.

- **Rationale**  
  Why this change is necessary from a governance or structural perspective.

- **Affected Stages**  
  Explicitly list all impacted stages (directly or indirectly).

- **Traceability Impact**  
  How this change preserves or improves decision traceability.

- **Governance Impact**  
  Which rules, gates, or constraints are touched.

- **Non-Goals**  
  What this contribution explicitly does *not* attempt to do.

Contributions missing any of these sections will not be reviewed.


## Pull Request Template (Required)

All pull requests must follow this structure:


### Scope

### Rationale

### Affected Stages

### Traceability Impact

### Governance Impact

### Non-Goals


Pull requests that do not follow this template will be closed without review.


## Stage-Specific Changes

When modifying a specific stage:

- Changes must be isolated to that stage’s directory.
- Output contracts must remain explicit and versioned.
- Any downstream documentation or examples must be updated.
- If new ambiguity is discovered, the change must route backward rather than compensating forward.

Stages are not allowed to “repair” upstream uncertainty.


## Tooling Contributions

Tooling is permitted **only** as context providers.

Tools must:
- observe structure,
- expose absence,
- report state.

Tools must **never**:
- make decisions,
- score outcomes,
- select “best” options,
- influence execution paths.

If a tool influences behavior, it is not a tool — it is a stage, and will be rejected.


## Documentation Contributions

Documentation must:
- reflect constraints accurately,
- avoid marketing language,
- avoid simplifications that dilute governance,
- use consistent terminology.

Introducing ambiguous or promotional language is grounds for rejection.


## Examples and Case Studies

Examples are encouraged when they:
- demonstrate refusal or blocking,
- show routing back as a valid outcome,
- include explicit intent, constraints, and failure points.

Examples that only show “successful execution” without governance signals will not be accepted.


## Governance Gate Checklist

A contribution must pass **all** of the following checks:

- Preserves stage responsibility boundaries
- Does not introduce implicit behavior
- Improves or maintains traceability
- Respects governance gates
- Aligns with project constitution and principles

Failure on any single check results in rejection.


## Review and Acceptance

All contributions are reviewed from a governance perspective first.

Rejection does **not** imply:
- low technical quality,
- lack of skill,
- poor intent.

It means the contribution does not fit the architectural contract of ATLAS.

There is no obligation to accept any contribution.


## Final Note

ATLAS is deliberately constrained.

It is not designed to be flexible.
It is designed to be **defensible**.

If you are comfortable operating within clear limits, your contribution is welcome.
If not, this project will not adapt — by design.
