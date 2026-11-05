# OctoAcme Project Management Docs

This repository contains the core project management guidance for OctoAcme, a lightweight but structured framework for initiating, planning, delivering, and improving cross-functional work. The process is designed to align teams around a clear problem definition, measurable outcomes, and repeatable execution practices. Work begins with validation of the business need and the creation of a project one-pager, followed by planning, backlog prioritization, and milestone definition. The goal is to keep work focused on customer value while reducing ambiguity, delivery risk, and stakeholder confusion.

The core workflow follows a lifecycle of initiation, planning, execution, release, and retrospective. During initiation, teams confirm the problem, stakeholders, success metrics, and resources; during planning, they create an actionable backlog, estimate scope, define acceptance criteria, and identify dependencies and risks. Execution uses a project board to track progress through stages such as Backlog, Ready, In Progress, In Review, QA, and Done. Delivery is supported by daily standups, weekly syncs, demos, and periodic escalation when blockers or cross-team dependencies arise.

OctoAcme assigns clear ownership across a small set of roles: the Project Manager coordinates delivery, schedules, risk, and communication; the Product Manager defines outcomes and prioritizes work; developers build and test features; QA validates acceptance and quality; and stakeholders review progress and provide decisions. This role clarity helps teams move quickly while maintaining accountability and transparency. Communication is structured around regular check-ins, risk updates, and a single source of truth for project status, with escalation paths designed to bring issues to the right level of decision-making when needed.

Quality is built into OctoAcme’s operating model through standards for testing, review, and release readiness. Pull requests should be small where possible, include issue links and acceptance criteria, and pass automated tests and lint checks before approval. The team expects unit tests for new logic, integration and smoke testing for critical flows, security scanning in CI, and manual QA where appropriate. Releases require validation against acceptance criteria, deployment checks, rollback planning, and post-deploy verification. After each sprint, milestone, or incident, OctoAcme reinforces continuous improvement through retrospectives that convert lessons learned into action items and next steps.

## Documents in this folder

- [OctoAcme Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)
