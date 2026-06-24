# OctoAcme Project Management Docs

This folder contains OctoAcme's project management process documents. The README lists each doc with a short description and link.

Docs:
- [octoacme-project-management-overview.md](https://github.com/moosernator/skills-scale-institutional-knowledge-using-copilot-spaces/blob/main/docs/octoacme-project-management-overview.md) — High-level overview of principles, roles, and lifecycle.
- [octoacme-project-initiation.md](https://github.com/moosernator/skills-scale-institutional-knowledge-using-copilot-spaces/blob/main/docs/octoacme-project-initiation.md) — Steps and templates for initiating a project.
- [octoacme-project-planning.md](https://github.com/moosernator/skills-scale-institutional-knowledge-using-copilot-spaces/blob/main/docs/octoacme-project-planning.md) — Planning activities, backlog template, and checklists.
- [octoacme-execution-and-tracking.md](https://github.com/moosernator/skills-scale-institutional-knowledge-using-copilot-spaces/blob/main/docs/octoacme-execution-and-tracking.md) — Day-to-day execution guidance, workflows, and checklists.
- [octoacme-risks-and-communication.md](https://github.com/moosernator/skills-scale-institutional-knowledge-using-copilot-spaces/blob/main/docs/octoacme-risks-and-communication.md) — Risk register and communication templates.
- [octoacme-release-and-deployment.md](https://github.com/moosernator/skills-scale-institutional-knowledge-using-copilot-spaces/blob/main/docs/octoacme-release-and-deployment.md) — Release types, checklist, and rollback playbook.
- [octoacme-retrospective-and-continuous-improvement.md](https://github.com/moosernator/skills-scale-institutional-knowledge-using-copilot-spaces/blob/main/docs/octoacme-retrospective-and-continuous-improvement.md) — Retrospective process and tracking improvements.
- [octoacme-roles-and-personas.md](https://github.com/moosernator/skills-scale-institutional-knowledge-using-copilot-spaces/blob/main/docs/octoacme-roles-and-personas.md) — Role descriptions and responsibilities.

## Project management processes summary

OctoAcme follows a lightweight, iterative project management approach focused on clear outcomes, small increments of delivery, and a single source of truth for artifacts such as project one-pagers, roadmaps, release plans, and a risk register. Projects begin with an initiation phase where a one-pager, stakeholder alignment, and initial risk and resource planning establish whether work should proceed into planning. Planning translates approved initiatives into prioritized backlogs with acceptance criteria, a Definition of Done, estimates, and a release/milestone map.

Execution is managed through a project board (Backlog → Ready → In Progress → In Review → QA → Done) and a disciplined pull request process—small PRs where possible, issue links and acceptance criteria in PR descriptions, automated CI and lint checks before review, and required approvals. Releases are checklist-driven with staging verification, smoke tests, rollback plans, and release notes. Incidents use a clear rollback and triage playbook followed by a blameless retrospective.

Personas and communication are explicit: a named Project Manager coordinates delivery and communications while a Product Manager owns outcomes and prioritization; developers, QA, and stakeholders have well-defined responsibilities. The team follows a regular cadence of daily standups, weekly delivery syncs, demos at milestone ends, weekly PM/PdM syncs, and monthly stakeholder updates. Quality is enforced through unit and integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA as needed. Retrospectives convert learnings into prioritized action items that feed back into the backlog.
