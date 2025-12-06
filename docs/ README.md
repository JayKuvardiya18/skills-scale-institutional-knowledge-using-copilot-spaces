```markdown
# OctoAcme Project Management — Overview

This folder contains OctoAcme's project management process documents. These guidelines are intended to make cross-functional delivery predictable, transparent, and repeatable by defining who does what, how decisions are made, and how we validate quality before shipping.

OctoAcme uses a lightweight, staged lifecycle: Initiation (one-pager, stakeholder alignment), Planning (backlog, estimates, Definition of Done), Execution (iterative delivery using project boards and small PRs), Release (deployment checklist, smoke tests, rollback plan), and Close & Retrospective (capture learnings and action items). Work is tracked on a project board with columns such as Backlog, Ready, In Progress, In Review, QA, and Done; acceptance criteria are attached to backlog items and PRs to ensure alignment.

Key personas are clearly defined to maintain ownership and accountability: Product Managers (define outcomes and success metrics), Project Managers (coordinate delivery, schedule, and risk), Developers (implement, test, document), QA/Testers (validate acceptance criteria and perform manual testing when required), and Stakeholders (provide inputs and approvals). This role clarity reduces single-person dependencies and helps with faster decision-making.

Communication is multi-channel and cadence-driven: daily standups for the delivery team, weekly syncs between PM and Product, monthly stakeholder updates, and ad-hoc escalations. Quality assurance is a mix of automated and manual practices: unit and integration tests required for new logic, CI-enforced linting and security scans, end-to-end smoke tests for critical flows, and manual QA where acceptance criteria call for it. The docs in this folder provide detailed templates, checklists, and playbooks to support these workflows.
```
