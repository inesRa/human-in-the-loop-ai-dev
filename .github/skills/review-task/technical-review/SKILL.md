
---
name: technical-review
description: Review a Git branch for code quality, correctness, maintainability and engineering best practices.
---

# Technical Review

## Goal
Evaluate the technical quality of the branch independently of functional requirements.

## Process
1. Identify the current branch and target branch.
2. Inspect the complete branch diff and relevant surrounding code.
3. Review:
    - Correctness and potential bugs.
    - Architecture and design consistency.
    - Maintainability and readability.
    - Security and performance.
    - Test quality.
4. Run relevant tests and validation when possible.

## Rules
- Review actual code and its context.
- Prioritize real issues over stylistic preferences.
- Avoid speculative findings and unnecessary refactoring.
- Consider existing project conventions.
- Do not modify source code.

## Output
- **Findings:** Issue, severity, file/line, impact and recommendation.
- **Validation:** Tests executed and results.
- **Verdict:** Approved / Changes recommended.
