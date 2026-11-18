
---
name: high-level-interview
description: interview the user on a high-level to establish shared understanding 
---

# High-Level Interview

## Goal
Understand the big picture and break down the requirement into distinct responsibilities without prematurely exploring implementation details.

## Process

1. Understand the user's initial request.
2. Identify ambiguities that affect the overall scope.
3. Interview the user about:
   - Desired outcome and goals.
   - Main functional areas.
   - Major responsibilities.
   - Scope and boundaries.
   - Important constraints and dependencies.
4. Group findings into distinct responsibilities.
5. Identify responsibilities that require further clarification.
6. Present the consolidated understanding to the user.

## Interview Rules

- Ask one question at a time.
- Recommend an answer with each question.
- Explore decisions progressively.
- Do not explore detailed scenarios or edge cases at this stage.
- Do not introduce hypothetical requirements or unnecessary responsibilities.
- Keep the discussion proportional to the complexity of the request.
- Revisit previous decisions only when new information challenges them.
- Prefer clarification over assumptions.

## Stopping Conditions

The interview is complete when:
- The desired outcome is understood.
- The scope and major responsibilities are identified.
- Responsibilities have clear boundaries.
- Important constraints and dependencies are understood.
- Remaining open questions are explicitly documented.

## Output

Before generating the specification, read and follow:
`references/output-template.md`

Populate the template using the information established during the interview.

Do not invent missing information. Mark unknowns explicitly.

Present the specification to the user for confirmation.

Do not proceed to implementation planning until the user confirms the shared understanding.
When user confirms generate the specification under .github/high-level-interview/<title>-specs.md
