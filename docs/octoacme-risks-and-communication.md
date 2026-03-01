# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level -> Scrum Master (impediment removal) -> Project Manager -> Product Lead -> Sponsor
- Change-related risks: Project Manager and Change Manager jointly assess impact; Change Manager owns stakeholder notification and CAB approval
- For security incidents, follow the security incident runbook and notify Security on-call

## Related Roles
- **Change Manager** — owns change advisory, stakeholder notification, and change log; see [Personas](./octoacme-roles-and-personas.md#change-manager)
- **Scrum Master** — first point of escalation for team-level impediments; see [Personas](./octoacme-roles-and-personas.md#scrum-master)
- **Project Manager** — owns risk register and cross-team escalation; see [Personas](./octoacme-roles-and-personas.md#project-managers)
- See also: [RACI Matrix](./octoacme-raci-matrix.md)
