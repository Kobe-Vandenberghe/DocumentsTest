---
title: Development Process
owner: Engineering
status: active
reviewEveryDays: 180
lastReviewed: 2026-06-08
tags:
  - engineering
  - delivery
  - process
appliesTo:
  - Engineers
  - Project leads
---

# Development Process

Northstar Digital uses a lightweight delivery process that balances speed with accountability. The general expectation is that a feature or bug fix moves from idea to implementation through a short sequence of planning, coding, review, and validation before it is handed over to the project team.

## Team workflow

1. Capture the requirement in a tracker or project document.
2. Confirm acceptance criteria with the project lead or product owner.
3. Implement the change in a branch and keep commits focused.
4. Submit the work for review using the expectations in [Code Review Guidelines](code-review-guidelines.md).
5. Run validation steps and record any follow-up items.

## Delivery norms

Engineering teams should keep dependencies visible, document assumptions, and avoid silent scope drift. In practice, this means raising a question early when a requirement is ambiguous or when a technical choice may cause future maintenance cost. The company also expects developers to share relevant notes with the project team so that the transition from build to support is smoother.

## Quality expectations

The team uses the [Definition of Done](definition-of-done.md) as a shared baseline. That document is not meant to be a bureaucratic barrier; it is intended to ensure that work is understandable, testable, and safe to release. A project may require additional checks for security, accessibility, or client-specific compliance.

## Related documents

- [Code Review Guidelines](code-review-guidelines.md)
- [Definition of Done](definition-of-done.md)
- [Release Process](release-process.md)
