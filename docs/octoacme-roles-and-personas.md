# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional operational & cross-functional personas

The following personas are commonly involved in projects and help reduce friction across planning, execution, release, and post-release analysis. Add these as subsections for clarity on ownership and handoffs.

### Delivery Engineer
Role summary: Focuses on CI/CD pipelines, automation, and deployment reliability.

Responsibilities:
- Maintain and improve build, test, and deployment pipelines
- Triage and fix automation failures blocking delivery
- Implement and maintain deployment gates, rollout strategies, and observability best practices
- Improve pipeline efficiency and feedback loops

Interaction with existing roles:
- Works closely with Developers to ensure PRs meet CI requirements and get timely feedback
- Coordinates with Release Manager on deployment windows, runbooks, and rollback plans
- Informs PM about pipeline-related delivery risks and timelines

When to involve:
- Design and implementation of CI/CD assets
- When deployment/automation issues block delivery
- During release planning and staging verification

Example deliverables:
- Pipeline definitions, deployment runbooks, observability checks

---

### Release Manager
Role summary: Owns release coordination, cutoff decisions, and stakeholder communications for releases.

Responsibilities:
- Coordinate release timelines and sign-offs across teams
- Draft and publish release notes and stakeholder communications
- Ensure rollback and mitigation plans are in place and tested
- Maintain release calendar and enforce release readiness criteria

Interaction with existing roles:
- Works with PM and PdM to confirm scope for a release and communicate priorities
- Coordinates with Delivery Engineer for runbooks and deployment verification
- Notifies Stakeholders and Support about release details and triage expectations

When to involve:
- Release planning, cutover decisions, and post-deploy verification

Example deliverables:
- Release notes, cutover checklists, post-deploy verification logs

---

### Security Liaison
Role summary: Single point of contact between the Security team and project team for security reviews and incident communication.

Responsibilities:
- Coordinate security reviews and threat modeling during planning
- Ensure security findings are tracked, prioritized, and remediated
- Assist with incident communication and coordinate security triage
- Surface compliance or policy requirements relevant to the project

Interaction with existing roles:
- Works with Developers on fixes, with PM to prioritize security remediation, and escalates high-severity issues to Product Lead or Security on-call
- Partners with QA to validate security-related acceptance criteria

When to involve:
- During planning for threat modeling and secure design reviews
- When vulnerabilities or security incidents are discovered

Example deliverables:
- Security review notes, remediation plans, incident summaries

---

### Product Operations (ProdOps)
Role summary: Operationalizes product processes, metrics, and launch readiness.

Responsibilities:
- Maintain dashboards and success-metric definitions
- Coordinate feature flagging, experiments, and telemetry needs
- Help define metrics and validate instrumentation
- Manage launch readiness checklists and cross-team coordination for scale

Interaction with existing roles:
- Partners with PdM on success metrics, with Data Analyst for instrumentation, and with PM to track readiness and rollout plans
- Works with Release Manager to manage staged rollouts or experiments

When to involve:
- During planning for metrics, experiments, and release readiness

Example deliverables:
- Dashboards, instrumentation spec, feature-flag rollout plans

---

### UX Researcher
Role summary: Ensures user research informs requirements and validates UX changes.

Responsibilities:
- Run usability tests and research sessions
- Provide actionable insights to PdM and Designers
- Validate acceptance criteria related to UX and accessibility

Interaction with existing roles:
- Works with PdM to shape user-facing requirements and with Developers/QA to validate implementations
- Helps prioritize research-backed improvements

When to involve:
- During discovery, before major UX changes, and during acceptance testing for user-critical flows

Example deliverables:
- Research reports, usability findings, UX validation checklist

---

### Data Analyst
Role summary: Supports metric definition, measurement, and result interpretation.

Responsibilities:
- Define event instrumentation needed for success metrics
- Create dashboards and run analyses post-release
- Advise on experiment design and metric reliability
- Validate data integrity and alert on metric regressions

Interaction with existing roles:
- Works with ProdOps and PdM to set metrics, with Developers to implement instrumentation, and with PM to report outcomes and inform next steps

When to involve:
- During planning for metrics and instrumentation, and post-release analysis

Example deliverables:
- Instrumentation spec, dashboards, analysis reports

---

## Cross-references and Handoffs

- Each persona should be linked to relevant checklists (release, security, QA) and decision logs.
- For responsibilities that cross multiple roles, the document should indicate primary owner and supporting contacts to avoid ambiguity.
- Add contact tags or OWNERS-like pointers if a single point of contact is required for escalation.
