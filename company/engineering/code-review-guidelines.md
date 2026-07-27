---
title: Code Review Guidelines
owner: Engineering
status: active
reviewEveryDays: 180
lastReviewed: 2026-05-11
tags:
  - engineering
  - review
  - quality
appliesTo:
  - Engineers
---

# Code Review Guidelines

Code review is part of the day-to-day quality practice at Northstar Digital. Reviews are expected to be constructive, specific, and timely so that the feedback loop helps the author improve the work rather than simply slow it down.

## Review standards

A good review should focus on correctness, maintainability, readability, and risk. Comments should identify the issue, explain the reason, and suggest a practical next step when possible. Reviewers should not use the process to enforce personal preferences unless those preferences are already part of a documented standard.

## What to look for

- Missing validation or incomplete error handling
- Security-sensitive behavior that was not considered
- Poor naming, duplicate logic, or unclear intent
- Tests that do not cover the changed behavior
- Documentation gaps that would affect future maintenance

## Expected response time

The target is to review most routine pull requests within one working day. For urgent fixes or incident work, the expectation is shorter, and the review may be completed in parallel with implementation. The review should be documented in the PR or task thread and should avoid leaving unresolved blockers without a clear owner.

## Related documents

- [Development Process](development-process.md)
- [Definition of Done](definition-of-done.md)
- [Incident Response](incident-response.md)
