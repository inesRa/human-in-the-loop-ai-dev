
---
name: focused-interview
description: interview user about one specific responsibility or functional area to establish shared understanding
---

# Focused Interview

## Goal
Reach a detailed shared understanding of one responsibility without expanding beyond its boundaries.

## Input
A specific responsibility identified through an initial requirement or high-level interview.

## Process
1. Establish the responsibility and its boundaries.
2. Identify expected behavior.
3. Explore relevant scenarios and alternative outcomes.
4. Identify edge cases, failure conditions and business rules.
5. Clarify dependencies and constraints.
6. Identify acceptance criteria

## Interview rules
- Stay within the selected responsibility.
- Ask questions in rounds using the design-tree approach.
- Present recommended answers.
- Explore all relevant scenarios, not hypothetical or unrelated ones.
- Do not revisit settled decisions unless new information challenges them.
- Do not introduce additional responsibilities.
- Keep questions clear and avoid unnecessary cognitive overload.

## Output

Before generating the specification, read and follow:
`references/output-template.md`

Populate the template using the information established during the interview.

Do not invent missing information. Mark unknowns explicitly.

Present the specification to the user for confirmation.

Do not proceed to implementation planning until the user confirms the shared understanding.
When user confirms generate the specification under .github/focused-interview/<title>-specs.md
