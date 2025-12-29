# ATLAS Governance Principles

## 1. Purpose of These Principles

This document defines the **operational governance principles** of ATLAS.

While the Project Constitution establishes non-negotiable boundaries,
these principles define **how governance is exercised, enforced, and verified**
across all stages of the pipeline.

These principles operationalize the constraints defined in the ATLAS Project Constitution.

They are binding.
They apply to:
- analysis
- design
- planning
- execution
- verification
- governance review

Governance in ATLAS is not advisory.  
It is executable.

These principles were shaped by observing how well-intentioned systems fail
when governance is treated as guidance instead of an enforceable constraint.



## 2. Governance as a First-Class Execution Concern

Governance is not a final review step.

Every stage in ATLAS:
- operates under governance constraints,
- produces governance-relevant artifacts,
- and is subject to governance validation.

No stage is exempt.  
No stage is trusted by default.

Any violation at any stage constitutes a **governance failure**.



## 3. Source Priority Principle

All decisions and actions must respect strict source priority.

Authoritative sources, in order:

1. Project Constitution  
2. PIPELINE_IDENTITY.md  
3. Finalized Requirements (post-ambiguity resolution)  
4. Approved Architectural Decisions  
5. Implementation Plans  
6. Execution and Validation Evidence  

Lower-priority sources must never override higher-priority ones.

Any deviation from this order is a **governance failure**.



## 4. Explicit Authority Principle

Each stage has a clearly defined authority boundary.

A stage may:
- operate only within its defined role,
- consume only authorized inputs,
- and produce only defined outputs.

A stage may not:
- compensate for missing information,
- reinterpret upstream intent,
- silently resolve inconsistencies,
- or assume responsibility outside its mandate.

Any authority overreach must be escalated or routed backward.
Unresolved overreach is a **governance failure**.



## 5. No-Implicit-Completion Principle

ATLAS prohibits implicit completion.

This includes:
- filling gaps with assumptions,
- continuing execution despite unresolved ambiguity,
- inferring intent from context, history, or precedent.

If required information is missing:
- the pipeline must stop, or
- route backward for clarification.

Proceeding “as best as possible” is explicitly prohibited.
Doing so constitutes a **governance failure**.



## 6. Traceability Enforcement Principle

Every artifact must be traceable to its authoritative source.

This includes:
- requirements
- decisions
- plans
- executions
- tests
- approvals

Traceability is enforced structurally, not socially.

An untraceable artifact is invalid,
regardless of perceived correctness or usefulness,
and represents a **governance failure**.



## 7. Evidence-First Validation Principle

All claims must be supported by evidence.

This applies to:
- correctness
- completeness
- compliance
- success

Assertions without evidence are treated as unresolved states,
not as acceptable risk.

Treating unsupported assertions as valid
constitutes a **governance failure**.



## 8. Failure Visibility Principle

Failure is not exceptional.

Failures must be:
- explicitly detected,
- clearly classified,
- documented as first-class artifacts,
- and routed appropriately.

Silent failure handling, auto-repair, or hidden fallback behavior
violates governance and constitutes a **governance failure**.



## 9. Routing Discipline Principle

ATLAS resolves issues through routing, not improvisation.

When a problem is detected:
- it must be routed to the stage authorized to resolve it,
- not absorbed by the current stage.

Forward progress without resolution is prohibited
and constitutes a **governance failure**.



## 10. Minimal Surface Principle

Each stage and tool must expose the minimal surface necessary
to fulfill its responsibility.

Unnecessary flexibility increases governance risk.

Minimality is treated as a governance control,
not as a limitation.

Violation of minimal surface constraints
constitutes a **governance failure**.



## 11. Tool Governance Principle

Tools are governance-constrained entities.

A tool may:
- provide context,
- validate structure,
- collect evidence.

A tool may not:
- make decisions,
- infer intent,
- execute changes autonomously,
- bypass validation or approval gates.

Tool output must never be treated as authoritative intent.

Any tool that violates these constraints
constitutes a **governance failure**.



## 12. Governance Gates Principle

Governance gates are mandatory decision points.

A gate may:
- approve progression,
- approve with conditions,
- require rework,
- or block progression entirely.

Gates do not optimize.  
They judge compliance.

Bypassing a gate or softening its decision
constitutes a **governance failure**.



## 13. Non-Delegation of Responsibility Principle

Governance responsibility cannot be delegated to:
- models,
- tools,
- orchestration layers,
- or automation logic.

Humans define governance.  
The pipeline enforces it.

Any attempt to externalize or automate governance authority
constitutes a **governance failure**.



## 14. Evolution Under Governance Principle

All evolution must occur under governance.

Changes must:
- be explicitly proposed,
- justified against existing rules,
- evaluated for risk,
- and approved through governance mechanisms.

Undocumented, informal, or implicit evolution
is prohibited and constitutes a **governance failure**.



## 15. Final Governance Statement

ATLAS does not rely on intelligence to remain safe.

It relies on governance.

Any system that depends on “smart behavior”
instead of enforceable constraints
is incompatible with ATLAS.

These principles are binding.