# OctoAcme — RACI Responsibility Assignment Matrix

## Purpose
Map project lifecycle phases to roles so that ownership, accountability, and collaboration are explicit. Use this template at the start of each project or when onboarding new team members.

**RACI Key**
| Letter | Meaning |
|--------|---------|
| **R** | **Responsible** — Does the work |
| **A** | **Accountable** — Final decision-maker; single owner per activity |
| **C** | **Consulted** — Provides input before or during the activity |
| **I** | **Informed** — Kept up to date on outcomes |

---

## Lifecycle Phase: Initiation

| Activity | Dev | Product Mgr | Project Mgr | Scrum Master | UX Designer | Tech Writer | Change Mgr | Business Analyst | Stakeholders / QA |
|---|---|---|---|---|---|---|---|---|---|
| Define problem statement & vision | I | A/R | C | I | C | I | I | C | C |
| Identify stakeholders | I | C | A/R | I | I | I | C | C | I |
| Create project charter / one-pager | I | C | A/R | I | I | R | I | C | I |
| Elicit initial business requirements | I | C | I | I | C | I | I | A/R | R |
| Approve project initiation | I | C | C | I | I | I | I | I | A |

---

## Lifecycle Phase: Planning

| Activity | Dev | Product Mgr | Project Mgr | Scrum Master | UX Designer | Tech Writer | Change Mgr | Business Analyst | Stakeholders / QA |
|---|---|---|---|---|---|---|---|---|---|
| Prioritize and groom backlog | C | A/R | C | R | C | I | I | R | C |
| Define acceptance criteria | R | C | I | C | C | I | I | A/R | C |
| Estimate scope and capacity | A/R | C | C | R | C | I | I | C | I |
| Create release plan & milestones | C | C | A/R | C | I | I | C | I | I |
| Produce user flows & wireframes | I | C | I | I | A/R | I | I | C | C |
| Identify and document risks | C | C | A/R | C | I | I | C | C | I |
| Define Definition of Done | R | C | C | A/R | I | I | I | C | C |
| Set up docs structure | I | I | C | I | I | A/R | I | I | I |

---

## Lifecycle Phase: Execution

| Activity | Dev | Product Mgr | Project Mgr | Scrum Master | UX Designer | Tech Writer | Change Mgr | Business Analyst | Stakeholders / QA |
|---|---|---|---|---|---|---|---|---|---|
| Sprint planning & ceremonies | R | C | C | A/R | I | I | I | C | I |
| Feature development | A/R | I | I | C | C | I | I | C | I |
| Design handoff & review | C | I | I | I | A/R | I | I | C | I |
| Remove impediments | C | C | C | A/R | I | I | I | I | I |
| Update risk register | C | C | A/R | C | I | I | C | C | I |
| Draft technical documentation | C | I | I | I | I | A/R | I | C | I |
| Conduct code & design reviews | A/R | I | I | I | R | I | I | I | C |
| Track velocity & burndown | I | I | C | A/R | I | I | I | I | I |

---

## Lifecycle Phase: Release

| Activity | Dev | Product Mgr | Project Mgr | Scrum Master | UX Designer | Tech Writer | Change Mgr | Business Analyst | Stakeholders / QA |
|---|---|---|---|---|---|---|---|---|---|
| Prepare change request & CAB submission | C | C | C | I | I | C | A/R | C | I |
| Draft and publish release notes | C | C | I | I | I | A/R | C | I | I |
| Stakeholder change notification | I | C | C | I | I | C | A/R | I | R |
| UAT / acceptance sign-off | I | C | C | I | C | I | I | C | A/R |
| Deploy to staging & smoke test | A/R | I | C | I | I | I | I | I | R |
| Production deployment | A/R | I | C | I | I | I | C | I | I |
| Post-deploy verification | R | I | C | I | I | I | C | I | R |
| Rollback execution (if needed) | A/R | I | C | I | I | I | C | I | C |

---

## Lifecycle Phase: Retrospective

| Activity | Dev | Product Mgr | Project Mgr | Scrum Master | UX Designer | Tech Writer | Change Mgr | Business Analyst | Stakeholders / QA |
|---|---|---|---|---|---|---|---|---|---|
| Facilitate retrospective | C | C | C | A/R | I | I | I | I | I |
| Capture action items | C | C | C | A/R | I | R | I | I | I |
| Update process documentation | C | C | C | I | I | A/R | C | C | I |
| Measure & report success metrics | I | A/R | C | I | I | I | I | C | C |
| Archive project artifacts | I | I | A/R | I | I | R | C | C | I |

---

## Related Roles
All roles referenced in this matrix are defined in [OctoAcme Personas](./octoacme-roles-and-personas.md).

## How to Use This Template
1. Copy this file and rename it for your project (e.g., `project-x-raci.md`).
2. Adjust activities to match your project's specific needs.
3. Replace generic role names with actual team member names where appropriate.
4. Review the RACI with all stakeholders at project kickoff and update as the team evolves.
5. Reference this matrix during retrospectives to identify ownership gaps or overloads.
