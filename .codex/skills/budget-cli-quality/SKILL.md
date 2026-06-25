# budget-cli-quality

## When to use
Use this skill for the Python CSV-based budget CLI app in this repository.

## Purpose
Apply the project rules consistently when planning, implementing, or reviewing changes.

## Rules to enforce
- Write tests before implementation.
- Keep type hints on all functions and methods.
- Keep each function at 50 lines or less.
- Keep cyclomatic complexity at 10 or below.
- Run `qa_engineer` review before committing.
- Prefer small, single-purpose changes.

## Review checklist
- Are new behaviors covered by tests?
- Are edge cases covered?
- Does any function exceed the complexity target?
- Does any function look too long or too multi-purpose?
- Are CSV parsing and transaction calculations deterministic and testable?

## Recommended workflow
1. Write failing tests first.
2. Implement the smallest code change that makes tests pass.
3. Run quality review through `qa_engineer`.
4. Fix issues found by the review.
5. Commit the feature once it is complete.
