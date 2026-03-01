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

## Stakeholders / QA

### Role Summary
Stakeholders represent business, customer, or operational interests and validate that delivered work meets requirements. QA Engineers ensure quality through systematic testing and sign-off.

### Responsibilities
- Review and accept or reject completed work against acceptance criteria
- Provide feedback on usability, compliance, and business fit
- Raise defects and participate in UAT cycles
- Approve release readiness from a business/quality perspective

### Goals
- Ensure delivered software meets business and quality expectations
- Reduce production defects and post-release issues

### Typical Communication
- Sprint reviews and demos
- UAT feedback reports
- Sign-off and release approval communications

---

## Scrum Master

### Role Summary
The Scrum Master is a servant-leader who facilitates agile ceremonies, removes impediments, and coaches the team on agile practices. They act as a shield between the delivery team and external distractions.

### Responsibilities
- Facilitate sprint ceremonies: planning, daily standup, review, and retrospective
- Identify and actively remove team impediments and blockers
- Coach the team on agile/scrum practices and continuous improvement
- Track and communicate team velocity and sprint health
- Protect the team from unplanned interruptions during a sprint

### Goals
- Maximize team flow and delivery predictability
- Foster a culture of continuous improvement
- Ensure ceremonies are productive and timeboxed

### Typical Communication
- Daily standups and sprint ceremonies (facilitator role)
- Impediment logs shared with Project Manager and Product Manager
- Sprint health reports and retrospective action summaries

### Interactions with Other Roles
- **Developers**: Coaches on agile practices; surfaces and resolves blockers identified in daily standups.
- **Product Managers**: Coordinates backlog refinement sessions; ensures user stories are ready (Definition of Ready met) before sprint planning.
- **Project Managers**: Shares sprint health and velocity data; escalates impediments that require cross-team coordination.
- **Stakeholders / QA**: Facilitates sprint reviews; ensures stakeholder feedback is captured and fed back into the backlog.
- **Business Analyst**: Collaborates to ensure stories are well-defined with clear acceptance criteria before sprint planning.

---

## UX Designer

### Role Summary
UX Designers create user-centered designs — including flows, wireframes, and interactive prototypes — that translate product requirements into intuitive, accessible experiences.

### Responsibilities
- Conduct user research and usability testing to inform design decisions
- Produce user flows, wireframes, and high-fidelity prototypes
- Define interaction patterns and ensure accessibility (WCAG compliance)
- Own the design handoff to engineering (annotated specs, design tokens)
- Participate in sprint reviews to validate implemented features against design intent

### Goals
- Deliver designs that meet user needs and business objectives
- Reduce rework by providing clear, implementation-ready design artifacts
- Ensure consistent and accessible user experience across the product

### Typical Communication
- Design reviews and critiques with Product Manager and Developers
- Usability test reports shared with Product Manager and Stakeholders
- Design system documentation and Figma/design-tool handoff links

### Interactions with Other Roles
- **Product Managers**: Receives feature briefs and success metrics; provides design alternatives and usability insights that inform product decisions. Artifact: design brief → wireframes/prototypes.
- **Developers**: Conducts design handoff sessions with annotated specs; answers implementation questions; reviews built features for design fidelity. Artifact: design spec → implemented UI.
- **Business Analyst**: Collaborates on user flows and acceptance scenarios to ensure designs cover all documented requirements.
- **Stakeholders / QA**: Presents prototypes for early feedback; incorporates UAT feedback into design iterations.
- **Technical Writer**: Coordinates on in-app copy, error messages, and help content to ensure consistent terminology.

---

## Technical Writer

### Role Summary
Technical Writers create and maintain clear, accurate documentation for both internal teams and external audiences, ensuring knowledge is accessible and up to date across the product lifecycle.

### Responsibilities
- Author and maintain process docs, onboarding guides, API references, and release notes
- Ensure documentation versioning and change history are tracked
- Collaborate with all roles to gather accurate information and validate correctness
- Review docs for readability, completeness, and consistency
- Maintain the `docs/` directory structure and cross-linking between documents

### Goals
- Reduce onboarding time and support burden through self-service documentation
- Ensure documentation keeps pace with product and process changes
- Maintain a single source of truth for team knowledge

### Typical Communication
- Documentation review cycles with relevant role owners
- Release notes drafts circulated to Product Manager and Change Manager before publication
- Async written collaboration via PRs and comments on docs

### Interactions with Other Roles
- **Developers**: Interviews developers to document APIs, technical architecture, and operational runbooks. Reviews draft docs with engineering for accuracy.
- **Product Managers**: Aligns on release note content and feature descriptions; receives feature briefs as input for user-facing documentation.
- **Project Managers**: Maintains process documentation (such as this file) in sync with project practices; documents decisions and meeting outcomes.
- **UX Designers**: Coordinates on UI copy, tooltip text, and help content; ensures in-product language matches documentation.
- **Change Manager**: Drafts change communication notices and post-release announcements; coordinates timing with the Change Manager.
- **Stakeholders / QA**: Publishes release notes and known-issue lists; incorporates QA feedback on documentation gaps.

---

## Change Manager

### Role Summary
The Change Manager owns the change advisory process for major releases and significant process shifts. They coordinate stakeholder approvals, communicate impact, and maintain the change log to ensure controlled, low-risk delivery.

### Responsibilities
- Own and facilitate the Change Advisory Board (CAB) process for major changes
- Communicate impact, timelines, and rollback plans to all affected stakeholders
- Maintain the change log, approval status, and post-change review records
- Identify and mitigate adoption risks associated with process or product changes
- Coordinate with support and operations teams to prepare for incoming changes

### Goals
- Minimize business disruption from releases and process changes
- Ensure all changes have documented approvals and rollback plans
- Build stakeholder confidence through transparent, timely communication

### Typical Communication
- Change request submissions and CAB meeting notes
- Pre-release change notifications to stakeholders and support teams
- Post-change review summaries

### Interactions with Other Roles
- **Project Managers**: Receives the release schedule and scope from Project Manager; aligns change windows and approval deadlines. Artifact: release plan → change request.
- **Product Managers**: Reviews feature scope and risk level; ensures business stakeholders are informed of major product changes before release.
- **Developers**: Consults on rollback feasibility and deployment window constraints; reviews release notes for technical accuracy.
- **Technical Writer**: Collaborates on change communication drafts and post-release announcements; provides content for the change log.
- **Stakeholders / QA**: Presents change plans for approval; captures sign-off. Notifies support and operations of upcoming changes and expected impact.

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business needs and technical delivery. They define detailed requirements, model process flows, and validate that delivered solutions meet the original business intent.

### Responsibilities
- Elicit, document, and validate business and functional requirements
- Create process flow diagrams, use cases, and acceptance scenarios
- Conduct impact assessments for new feature proposals and change requests
- Facilitate requirements workshops with stakeholders and the delivery team
- Maintain requirements traceability from business need to delivered feature

### Goals
- Ensure requirements are clear, complete, and testable before development begins
- Reduce scope creep and rework by front-loading requirements clarity
- Provide a traceable link between business objectives and delivered features

### Typical Communication
- Requirements documents and process flow diagrams shared with Product Manager and Developers
- Impact assessment reports for significant change requests
- Acceptance scenario walkthroughs with QA and Stakeholders

### Interactions with Other Roles
- **Product Managers**: Translates product vision into detailed, testable requirements; contributes to backlog grooming with prioritized user stories. Artifact: product brief → detailed requirements.
- **Developers**: Provides detailed acceptance criteria and process flows; answers requirements questions during sprint; participates in story kick-offs. Artifact: requirements spec → implementation.
- **Scrum Master**: Ensures stories meet the Definition of Ready before sprint planning; works with Scrum Master to schedule requirements workshops.
- **Stakeholders / QA**: Runs requirements walkthroughs for stakeholder sign-off; produces acceptance scenarios used by QA for test coverage.
- **Change Manager**: Provides impact assessments that inform change risk ratings and CAB submissions.
- **UX Designer**: Shares process flows and use cases to inform design decisions; reviews wireframes to ensure design covers all documented scenarios.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [RACI Matrix](./octoacme-raci-matrix.md) for a responsibility assignment matrix mapping all roles to project lifecycle phases.

