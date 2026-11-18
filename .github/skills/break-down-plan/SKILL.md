
---
name: make plan 
description: Break down the implementation into atmic tasks
---

# Planning

## Goal
Produce a complete technical implementation plan before any code changes.

## Process

1. Inspect the relevant codebase, architecture and existing conventions.
2. Map confirmed requirements to technical changes.
3. Identify affected components, dependencies and risks.
4. Define the simplest implementation approach.
5. Decompose the work into ordered, atomic increments.
6. Verify requirement coverage and execution order.

## Planning Rules

- Prefer small, coherent and independently testable increments.
- Prefer vertical functional slices over arbitrary layer-based splitting.
- Make increments independently committable whenever possible.
- Include relevant test cases in each increment.
- Avoid unnecessary abstractions and speculative requirements.
- Document assumptions and unresolved questions.
- Do not modify source code or start implementation.

## Output

Read `references/implementation-plan-template.md` and use it to produce the complete plan.

Present the plan for user approval. Do not proceed to implementation without explicit approval.
