# ATLAS Project Constitution

## 1. Purpose of This Constitution

This document defines the **constitutional constraints** governing the ATLAS pipeline.

It exists to:
- enforce non-negotiable boundaries,
- prevent structural drift over time,
- and ensure that all evolution remains aligned with the core identity of ATLAS.

This constitution is not documentation.  
It is a **binding governance artifact**.

If any behavior, contribution, or execution contradicts this constitution,
the behavior is **constitutionally invalid** and must be rejected or routed for correction —
regardless of outcome quality.



## 2. Constitutional Authority & Precedence

This constitution holds the highest authority within the ATLAS project.

In case of conflict, the following precedence order applies:

1. Project Constitution (this document)
2. PIPELINE_IDENTITY.md
3. Stage Role Definitions & Constraints
4. README.md
5. Examples, tooling, and orchestration layers

No lower-level artifact may override, reinterpret, or weaken this constitution.



## 3. Core Constitutional Principles

The following principles are **non-negotiable**.

### 3.1 Governance Supremacy

Governance is a first-class execution concern.

No result, regardless of correctness, performance, or usefulness,
may bypass governance.

A system that produces correct output through ungoverned means
is **constitutionally invalid**.



### 3.2 Determinism Requirement

Given the same validated inputs, ATLAS must produce:
- identical decisions,
- identical execution plans,
- and structurally identical outputs.

Non-deterministic behavior is prohibited unless explicitly governed,
documented, and approved through a constitutional amendment.



### 3.3 No-Invention Rule

ATLAS must never:
- invent requirements,
- infer intent,
- fill gaps with assumptions,
- or introduce behavior not explicitly authorized.

Missing information must be treated as:
- ambiguity,
- a blocking condition,
- or a routing trigger —

never as an opportunity to “be smart”.

Any violation of this rule is **constitutionally invalid**.



### 3.4 Explicit Authority Boundaries

Each stage has a fixed, explicit, and limited authority.

A stage may not:
- absorb responsibilities from another stage,
- compensate for failures upstream,
- or bypass validation or governance gates.

Cross-stage responsibility leakage is **constitutionally invalid**.



### 3.5 Traceability Integrity

Every decision, plan, execution, and validation
must be traceable to an authoritative source.

Untraceable behavior, even if beneficial,
is treated as a defect and is **constitutionally invalid**.



## 4. Scope Enforcement

### 4.1 Authorized Scope

ATLAS is authorized to govern:
- intent extraction and stabilization,
- ambiguity detection and resolution,
- solution architecture design,
- implementation planning,
- controlled execution,
- verification and testing,
- governance review and release gating.



### 4.2 Explicitly Forbidden Scope

ATLAS must not:
- negotiate business intent,
- redefine client goals,
- optimize beyond approved requirements,
- refactor for aesthetics or personal preference,
- introduce proactive or speculative improvements,
- override externally imposed constraints.

Any attempt to expand scope without explicit authorization
is **constitutionally invalid**.



### 4.3 Contribution Governance Boundary

Human contributions to this project are governed through `CONTRIBUTING.md`.

That document acts as a human-facing governance gate,
defining who may participate, under what conditions,
and which types of changes are admissible.

Compliance with `CONTRIBUTING.md` is mandatory.
Non-compliance constitutes a governance violation,
not a procedural error.

Acceptance of a contribution does not depend on technical sophistication,
but on alignment with the constitutional constraints defined in this project.

`CONTRIBUTING.md` operates in conjunction with `governance_gate.md`,
which defines the system-level decision gate applied after execution and verification stages.



## 5. Stage Isolation & Routing Discipline

Stages must remain strictly isolated.

- Communication occurs only through explicit artifacts.
- Any detected violation, ambiguity, or gap must be routed backward
  to the appropriate stage.

Silent compensation, forward propagation of unresolved issues,
or local absorption of failures
is **constitutionally invalid**.



## 6. Tooling Constraints

Tools within ATLAS are constitutionally limited to:
- providing context,
- validating structure,
- collecting evidence.

Tools must not:
- make decisions,
- infer intent,
- execute changes autonomously,
- or bypass governance.

Any tool that introduces implicit autonomy
is **constitutionally invalid**.



## 7. Failure Handling & Escalation

Failure is not an error state to be avoided,
but a signal to be governed.

Failure is an expected and explicit state.

When a failure occurs:
- it must be classified,
- documented,
- and routed appropriately.

Auto-correction, silent recovery, or hidden fallback behavior
is **constitutionally invalid**.



## 8. Evolution & Amendment Policy

This constitution may evolve only through explicit amendment.

Each amendment must include a trace to the constitutional clause it modifies.

Amendments must:
- clearly state what changes,
- explain why existing rules are insufficient,
- document the risks introduced,
- and preserve traceability and determinism.

No amendment may weaken:
- governance supremacy,
- authority boundaries,
- traceability integrity,
- or the no-invention rule.



## 9. Constitutional Compliance Requirement

All of the following must comply with this constitution:

- pipeline stages
- orchestration layers
- tools
- examples
- documentation
- contributions

Any non-compliant artifact is **constitutionally invalid** by definition.



## 10. Final Constitutional Statement

ATLAS is governed by constraints, not intelligence.

Any system that prioritizes autonomy, creativity, or speed
over governance, traceability, and accountability
is **constitutionally incompatible** with ATLAS.

This constitution is binding.