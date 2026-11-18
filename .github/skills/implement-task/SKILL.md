
---
name: implementation
description: Implement an approved implementation plan incrementally, using TDD and human approval gates.
---

# Implementation

## Goal
Execute the approved implementation plan through small, reviewable and independently testable increments.

## Process

1. Read the approved implementation plan and inspect the relevant code.
2. Present the next increment and wait for approval.
3. Follow TDD:
    - **Red:** Write and run a failing test. Wait for approval.
    - **Green:** Implement the minimum code to pass the test. Wait for approval.
    - **Refactor:** Improve the design while keeping tests green.
4. Run relevant tests and summarize changes, decisions and results.
5. Wait for user review and approval before proceeding.

## Rules

- Never implement an unapproved increment.
- Follow the approved plan and existing project conventions.
- Do not introduce unrelated refactoring or speculative abstractions.
- Do not silently change the implementation plan.
- If new information requires a plan change, stop and explain the impact.
- Do not commit unless explicitly requested.

## Completion

After all increments are approved and implemented, run final validation and report the overall result.
