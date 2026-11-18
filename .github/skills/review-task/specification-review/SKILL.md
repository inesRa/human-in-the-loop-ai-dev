
---
name: specification-review
description: Review a Git branch against confirmed requirements and acceptance criteria to identify missing or incorrect behavior.
---

# Specification Review

## Goal
Verify that the implementation matches the agreed specifications.

## Process
1. Identify the current branch and target branch.
2. Inspect the complete branch diff.
3. Read the confirmed specifications.
4. Verify each requirement and acceptance criterion.
5. Identify missing, incorrect or out-of-scope behavior.

## Rules
- Review actual implementation
- Check relevant scenarios and alternative flows.
- Do not assume missing behavior is implemented.
- Report only actionable discrepancies.
- Do not modify source code.

## Output
- **Coverage:** Requirements satisfied or missing.
- **Findings:** Issue, severity, file/line and recommendation.
- **Out-of-scope changes:** Unexpected behavior or modifications.
- **Verdict:** Specification compliant / Changes required.
