# OctoAcme Project Management Documentation

## Overview
OctoAcme runs projects with a lightweight, iterative management approach that emphasizes clear outcomes, repeatable artifacts, and visible progress. Work begins with a Project One-pager to capture the problem, objective, success metrics, stakeholders, and a high‑level timeline; after approval the team moves into planning to break work into shippable increments, estimate scope, and define a Definition of Done. Core artifacts — the one‑pager, prioritized backlog, release plan, risk register, and acceptance criteria — live in the repo (docs/) and drive execution so decisions and status have a single source of truth.

Execution uses a simple project board workflow (Backlog → Ready → In Progress → In Review → QA → Done) and a disciplined pull‑request process: small PRs where possible, an issue link and acceptance criteria in every description, automated CI/linting/security checks before review, and at least one approval required to merge. Sprint and iteration planning are timeboxed, items must meet the DoD to be pulled in, and release flow follows a checklist (staging smoke tests, automated production pipeline when available, post‑deploy verification and release notes). Rollback and incident playbooks are specified so teams can quickly restore service and run a blameless post‑incident retrospective.

Roles and responsibilities are explicit: Product Managers define outcomes, prioritize the backlog, and measure success; Project Managers coordinate delivery, schedules, risks, and communications; Developers implement and test features and participate in reviews; QA/Testing validate acceptance criteria and run integration and smoke tests. These personas are used consistently in planning, reviews, and retrospectives so ownership is clear and single‑person dependencies are minimized.

Communication is frequent and structured: daily standups for progress and blockers, a weekly delivery sync and PM+PdM alignment, and monthly stakeholder updates with ad‑hoc escalations as needed. Risk and dependency management use a simple register (impact, likelihood, owner, mitigation) reviewed at weekly syncs; escalation paths are tiered from team triage up to sponsor level. Continuous improvement is enforced through retrospectives after sprints, releases, or incidents, with prioritized action items tracked back into the backlog so process changes are measured and iteratively adopted.

## Project Lifecycle (quick)
1. Initiation — One-pager and go/no-go
2. Planning — Backlog, estimates, DoD
3. Execution — Build, test, review, iterate
4. Release — Deploy, verify, announce
5. Close & Retrospective — Capture learnings

## Documents in this folder
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)

## Issue templates
- [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)

## Quick links
- New to OctoAcme? Start with the Project Management Overview
- Starting a new project? Follow the Project Initiation Guide
- Preparing for release? Check the Release & Deployment Guide
