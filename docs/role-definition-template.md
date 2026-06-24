# Role / Persona Definition Template

Use this template when adding new personas to docs/octoacme-roles-and-personas.md so entries are consistent and actionable.

- Role name: (e.g., Delivery Engineer)
- Role summary: (1-2 sentence summary of primary focus)
- Responsibilities:
  - (List main responsibilities; use actionable verbs)
- Interaction with existing roles:
  - (Who they work with and how; include handoff points)
- When to involve:
  - (Planning, execution, release, incident, etc.)
- Example deliverables:
  - (Typical artifacts or outputs)
- Acceptance criteria / readiness checks:
  - (How the team knows this role has completed a responsibility)
- Suggested contacts / escalation:
  - (Optional: contact or team to escalate to)

Example:

- Role name: Delivery Engineer
- Role summary: Focuses on CI/CD pipelines, automation, and deployment reliability.
- Responsibilities:
  - Maintain and improve build, test, and deployment pipelines
  - Triage and fix automation failures blocking delivery
- Interaction with existing roles:
  - Works with Developers on CI requirements; coordinates with Release Manager on deployments
- When to involve:
  - During CI design, release planning, and when automation blocks delivery
- Example deliverables:
  - Pipeline definitions, runbooks, monitoring checks
- Acceptance criteria:
  - Pipelines green for mainline branch; runbook exists and is tested
