# OctoAcme Project Management Docs

This directory contains the core project management guidance for OctoAcme. It is intended to provide a clear, shared starting point for project initiation, planning, execution, risk management, release, and continuous improvement.

## Overview of OctoAcme project management processes

OctoAcme follows a structured lifecycle from idea to delivery and reflection. New work begins with initiation, where the team confirms the business need, identifies stakeholders, and creates a lightweight project one-pager with goals, metrics, milestones, resources, and early risks. Once the initiative is approved, the team moves into planning, creating a prioritized backlog, clarifying acceptance criteria, estimating work, and defining the release timeline and milestones. Execution then focuses on iterating in smaller, testable increments with regular standups, periodic reviews, and clear ownership for delivery.

The operating model emphasizes defined roles and accountability across the team. Product leaders define customer value and success metrics, project managers coordinate schedules, risks, dependencies, and communications, and developers and QA partners work together to build, validate, and release quality work. This cross-functional model helps the team align around outcomes, reduce ambiguity, and ensure that each project has a named owner for progress, decisions, and escalation.

Communication is treated as a core project discipline. OctoAcme uses weekly PM/Product syncs, team standups, milestone updates, and stakeholder briefings to keep work visible and risks managed early. The team also maintains a risk register and escalation path that moves from local triage to project leadership and, when necessary, sponsor-level attention for issues with broader business impact. Clear status updates and a single source of truth for project documentation help stakeholders stay informed and reduce confusion.

Quality assurance is built into the workflow rather than bolted on at the end. Teams are expected to use working agreements such as small PRs with acceptance criteria, required reviews, and CI checks for tests, linting, and security scans. New functionality should include unit and integration tests where relevant, and critical paths should be validated with smoke tests and manual QA before release. After deployment, the team reviews outcomes, captures lessons learned, and tracks improvements in retrospectives to strengthen the process over time.

## Process documents

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)

## Quick navigation by project phase

- Initiation: project need, stakeholders, one-pager, go/no-go decision
- Planning: backlog, estimates, DoD, release milestones, dependencies
- Execution: standups, PRs, reviews, tracking, blocker escalation
- Release: validation, smoke tests, deployment, post-release verification
- Improvement: retrospective, action items, lessons learned

## Related resources

- [.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)

This README serves as the landing page for the project management playbook and should be updated as the process evolves.
