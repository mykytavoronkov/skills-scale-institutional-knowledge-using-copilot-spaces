# OctoAcme Project Management Docs

Welcome to OctoAcme's centralized project management process documentation. This README helps new team members and contributors discover and navigate our project management processes, roles, and key artifacts.

## Quick Overview

OctoAcme follows an iterative, customer-focused project management approach with clear roles, lightweight artifacts, and data-informed decisions. Our process is structured around six core phases:

### 1. **Initiation**
Validate the business need and align stakeholders on outcomes before committing resources.
- Develop a Project One-pager with problem statement, goals, and success metrics
- Identify stakeholders and communication needs
- Create initial risk list and timeline
- **Decision gate:** Confirm success metrics, stakeholder alignment, and team availability

### 2. **Planning**
Turn an approved initiative into an actionable plan with a prioritized backlog.
- Conduct project kickoff with stakeholders and delivery team
- Break work into shippable increments with clear acceptance criteria
- Define Definition of Done and quality standards
- Create release plan and identify dependencies
- Estimate scope and build initial risk register

### 3. **Execution & Tracking**
Manage day-to-day execution with regular demos, clear ownership, and risk visibility.
- Run daily standups (15 min) and weekly delivery syncs
- Use project board workflow: Backlog → Ready → In Progress → In Review → QA → Done
- Maintain small PRs (≤400 lines) with clear acceptance criteria
- Run automated tests, linting, and security scans in CI
- Track velocity, burndown, and success metrics
- Escalate blockers through defined levels (team → PM → Product Lead → Sponsor)

### 4. **Risks & Communication**
Maintain transparency through a risk register and regular stakeholder updates.
- Identify, assess, and mitigate risks throughout the project
- Provide weekly status updates and milestone-based stakeholder briefings
- Follow escalation paths for business-impacting issues
- Communicate incidents with triage summary and post-incident retrospectives

### 5. **Release & Deployment**
Standardize releases to production to reduce risk and improve observability.
- Verify all acceptance criteria are met and tests pass
- Complete pre-release requirements: drafting release notes, documenting rollback plans
- Deploy to staging with smoke tests before production
- Run post-deploy verifications and announce releases
- Maintain rollback and incident playbooks

### 6. **Retrospectives & Continuous Improvement**
Capture learnings and convert them into actionable improvements.
- Hold retrospectives after each sprint, release, or milestone
- Identify what went well, what could improve, and top action items
- Track improvements with clear owners and success criteria
- Review outstanding actions in weekly PM syncs

## Core Roles

- **Project Manager (PM):** Coordinates delivery, schedules, risks, and communications
- **Product Manager (PdM):** Defines outcomes, prioritizes backlog, and measures success
- **Developers:** Implement features, collaborate on design, and maintain code quality
- **QA/Testing:** Validate quality and acceptance criteria
- **Stakeholders:** Provide inputs, approvals, and strategic direction

## Key Principles

- **Customer-first:** Prioritize customer value and usability
- **Iterative delivery:** Ship small, testable increments regularly
- **Clear ownership:** Each project has named PM and Product Lead
- **Data-informed:** Measure impact and iterate based on evidence
- **Psychological safety:** Encourage feedback and learning

## Process Documents

Access detailed guidance for each phase:

- **[Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, roles, and key artifacts
- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Steps to validate business need and align stakeholders
- **[Project Planning](./octoacme-project-planning.md)** — How to create a prioritized backlog and release plan
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Day-to-day execution, team rhythm, and quality standards
- **[Risks & Communication](./octoacme-risks-and-communication.md)** — Risk management and stakeholder communication
- **[Release & Deployment](./octoacme-release-and-deployment.md)** — Release types, pre-release checks, and rollback procedures
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Running retrospectives and tracking action items
- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Detailed role descriptions and responsibilities

## How to Use These Docs

1. **For new team members:** Start with the [Project Management Overview](./octoacme-project-management-overview.md) to understand our approach, then reference specific docs as you join projects.

2. **For project kickoffs:** Use the [Project Initiation Guide](./octoacme-project-initiation.md) and templates as your starting point.

3. **For ongoing execution:** Reference the [Execution & Tracking](./octoacme-execution-and-tracking.md) and [Risks & Communication](./octoacme-risks-and-communication.md) docs to stay aligned.

4. **For releases:** Follow the [Release & Deployment](./octoacme-release-and-deployment.md) checklist before going live.

5. **To propose updates:** Use the [Add Content to Process Docs issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) in this repository to request additions or clarifications.

## Contributing

These docs are living artifacts that evolve with our team's experience. If you notice gaps, unclear sections, or best practices to incorporate:

1. Open an issue using the "Add Content to Project Management Process Docs" template
2. Propose changes with clear rationale and example content
3. Collaborate with stakeholders to review and refine
4. Submit a PR with your updates

## Communication Cadence

- **Daily:** Team standups (15 min)
- **Weekly:** PM + PdM sync, delivery team sync, and stakeholder updates
- **Sprint/Milestone:** Planning, reviews, and retrospectives
- **Ad-hoc:** Escalations and incident communications
