# OctoAcme Project Management Docs

This README is the central index for OctoAcme's project management documentation.

## Process Overview

OctoAcme uses a lightweight, iterative lifecycle: initiation, planning, execution, release, and retrospective improvement. Initiation establishes a project one-pager with the problem, SMART goal, success metrics, stakeholders, timeline, and initial risks before approval to proceed. Planning turns the approved initiative into a prioritized, estimated backlog with acceptance criteria, a Definition of Done, explicit owners, dependencies, and release milestones.

Clear roles keep delivery accountable. Project Managers coordinate schedules, resources, risks, dependencies, and communications. Product Managers define outcomes, prioritize the roadmap and backlog, and measure customer and business value. Developers design, implement, test, and review changes while helping estimate work and identify technical risks. QA/testing contributors validate quality and acceptance criteria, while stakeholders provide input and approvals.

Execution stays visible through a project board moving work from Backlog through Ready, In Progress, In Review, QA, and Done. Regular standups, weekly delivery syncs, and sprint or milestone demos surface progress and blockers. Weekly or milestone-based stakeholder updates summarize progress, next steps, risks, and decisions needed, with a project README or release document serving as the single source of truth for status. Teams maintain a risk register with owners and mitigations, review it weekly, and escalate blockers from team triage through the Project Manager and Product Lead to the sponsor when needed.

Quality assurance runs throughout delivery: unit tests for new logic, integration tests where applicable, critical-flow smoke tests, CI linting and security scans, and manual QA when needed. Small pull requests link issues and acceptance criteria, pass automated checks before review, and require at least one approval or the team's equivalent policy before merging. Release readiness includes satisfied acceptance criteria, passing checks, release notes, and a rollback plan; staging smoke tests and production verification support safe deployment. Retrospectives after sprints, releases, milestones, or incidents turn lessons into two or three prioritized improvements with owners and due dates, tracked in the backlog and reviewed in weekly PM syncs.

## Documentation Index

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
