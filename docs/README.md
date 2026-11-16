# OctoAcme Project Management Docs

This repository contains the core project management guidance used by OctoAcme to initiate, plan, deliver, and improve work across cross-functional teams. The process docs provide a consistent, shareable source of truth for project execution and onboarding.

## Process Summary

OctoAcme follows a structured lifecycle that begins with project initiation and approval. New work is validated through a project one-pager that captures the problem, goals, success metrics, stakeholders, timeline, and early risks. Once the need is clear and stakeholders align, the team moves into planning, where work is broken into prioritized backlog items with assigned ownership, acceptance criteria, estimates, and a clear Definition of Done. This gives the team a shared understanding of scope, outcomes, and dependencies.

During execution, teams use a project board with stages such as Backlog, Ready, In Progress, In Review, QA, and Done. Work is delivered in small increments, supported by standups, weekly syncs, and sprint or milestone reviews. The PM coordinates timelines, risks, and status; the Product Manager defines priorities and outcomes; developers implement and test; QA validates acceptance; and stakeholders provide input and approvals. Risks and blockers are tracked and escalated from the team to the PM, Product Lead, and sponsor as needed.

Quality is built into delivery through testing, review, and release gates. Teams write unit tests for new logic, add integration tests where applicable, run end-to-end smoke tests for critical flows, and use CI checks for linting and security scanning. Manual QA is used when needed. Pull requests should be small and well-scoped, link to issues and acceptance criteria, and receive at least one approval before merge, subject to team policy. Releases require acceptance criteria to be met, passing CI and security scans, release notes, smoke tests, and a rollback or mitigation plan.

After a sprint, release, milestone, or incident, OctoAcme uses retrospectives to capture lessons and track owned action items. Teams monitor outcomes and project metrics, review risks, communicate release status, and follow up on improvements. This feedback loop helps refine processes and improve delivery over time.

## Documentation Index

- [OctoAcme Project Management Overview](./octoacme-project-management-overview.md)
- [OctoAcme Project Initiation Guide](./octoacme-project-initiation.md)
- [OctoAcme Project Planning](./octoacme-project-planning.md)
- [OctoAcme Execution & Tracking](./octoacme-execution-and-tracking.md)
- [OctoAcme Risk Management & Communication](./octoacme-risks-and-communication.md)
- [OctoAcme Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [OctoAcme Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [OctoAcme Roles & Personas](./octoacme-roles-and-personas.md)

## Related Issue Template

- [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)
