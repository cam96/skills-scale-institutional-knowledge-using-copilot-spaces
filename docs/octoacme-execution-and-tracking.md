# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — facilitated by Scrum Master; focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone — Scrum Master facilitates; Product Manager accepts/rejects stories

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup; Scrum Master owns impediment removal
- Level 2: Scrum Master escalates to Project Manager for cross-team coordination
- Level 3: Project Manager escalates to Product Lead and dependent teams
- Level 4: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled (Scrum Master facilitates)
- [ ] Risk register updated weekly
- [ ] Impediment log maintained by Scrum Master

## Related Roles
- **Scrum Master** — facilitates ceremonies and resolves impediments; see [Personas](./octoacme-roles-and-personas.md#scrum-master)
- See also: [RACI Matrix — Execution phase](./octoacme-raci-matrix.md#lifecycle-phase-execution)
