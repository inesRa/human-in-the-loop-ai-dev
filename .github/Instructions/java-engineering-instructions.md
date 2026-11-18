
# Java Engineering Principles

Apply these principles when implementing or reviewing Java code. Use judgment; do not apply them mechanically.

## Readability and Simplicity
- Use meaningful, intention-revealing names.
- Keep methods focused and classes cohesive.
- Prefer simple solutions over unnecessary abstractions.
- Avoid excessive nesting and complexity.

## Object and API Design
- Encapsulate internal state.
- Prefer immutability where practical.
- Favor composition over inheritance when appropriate.
- Design APIs that are easy to use correctly.
- Minimize unnecessary public interfaces.

## Type Safety and Error Handling
- Prefer strong typing and generics over raw types.
- Avoid returning null when an empty result is appropriate.
- Use specific exceptions and never silently swallow failures.
- Preserve exception context when wrapping exceptions.

## Concurrency
- Minimize shared mutable state.
- Prefer established thread-safe utilities.
- Make synchronization and visibility requirements explicit.

## Testing and Refactoring
- Test observable behavior, including relevant edge cases.
- Keep tests focused and independent.
- Refactor incrementally without changing behavior.
- Avoid speculative abstractions and premature optimization.

## General
- Follow existing project conventions.
- Prioritize correctness, readability and maintainability.
- Justify significant deviations from these principles.
- Prefer modern Java language features when they improve clarity, safety or maintainability.
- Consider records, sealed classes, pattern matching, virtual threads and modern collection APIs where appropriate.
