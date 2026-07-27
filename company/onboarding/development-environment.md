---
title: Development Environment
owner: Engineering
status: active
reviewEveryDays: 180
lastReviewed: 2026-04-24
tags:
  - onboarding
  - engineering
  - tools
appliesTo:
  - Engineers
  - Developers
---

# Development Environment

Northstar Digital uses a standardized but flexible setup for engineering work. Most teams rely on Git-based version control, a shared cloud workspace, and project-specific local environments. Developers are expected to use the standard toolchain unless a project requires a documented exception.

## Standard setup

- GitHub or an equivalent hosted repository service
- A local IDE with linting and formatting enabled
- A current Node.js or Python runtime depending on project requirements
- Access to the shared environment for staging and test deployments
- A password manager and MFA setup through the company policy

## Working expectations

Before a developer starts contributing to a client project, the team lead should confirm that the repository access, environment variables, and expected branch naming conventions are in place. Engineers should also keep their local development environment aligned with the project documentation so that onboarding and handoff remain smooth.

## Notes on local differences

Some teams still maintain older local scripts for legacy projects, and those scripts are not always documented well. This creates occasional confusion when engineers move between projects. The engineering handbook is meant to reduce that friction, but it does not yet cover every historical exception.

## Related documents

- [Development Process](../engineering/development-process.md)
- [Code Review Guidelines](../engineering/code-review-guidelines.md)
- [Security Training](security-training.md)
