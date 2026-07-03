# OctoAcme Project Management Docs

This README centralizes OctoAcme's project management process documents and provides a short summary of our processes to help new teammates and contributors get started.

## Overview

OctoAcme follows an iterative, customer-focused project management approach with clear roles and lightweight artifacts. Our goal is to deliver value in small, testable increments while maintaining transparency, psychological safety, and data-informed decision-making across all projects.

Projects move through five phases: **Initiation → Planning → Execution & Tracking → Release → Retrospective**. Each phase has dedicated guidance, checklists, and templates to keep the team aligned.

## Process Summary

### 1. Initiation
Validate and authorize new work before investing in planning. Capture the problem, identify stakeholders, define success metrics, and decide whether to proceed. Minimum deliverable: a **Project One-pager** with a problem statement, SMART objective, success metrics, and a high-level timeline.

### 2. Planning
Turn an approved initiative into an actionable backlog and delivery plan. Activities include running a kickoff meeting, creating a prioritized backlog with acceptance criteria, estimating work (T-shirt sizing or story points), defining the Definition of Done, and mapping milestones and dependencies.

### 3. Execution & Tracking
Manage day-to-day delivery and track progress toward milestones. The team follows a regular rhythm of daily standups, weekly delivery syncs, and sprint demos. Work is tracked on a project board (Backlog → Ready → In Progress → In Review → QA → Done). Small PRs (≤ 400 lines), CI checks, and at least one approval are required before merging.

### 4. Risks & Communication
Identify, assess, and monitor risks continuously. Maintain a **Risk Register** with impact, likelihood, owner, and mitigation. Communicate status weekly using a standard template and follow clear escalation paths: Team → PM → Product Lead → Sponsor.

### 5. Release & Deployment
Standardize how features reach production. Pre-release requirements include passing CI and security scans, drafted release notes, smoke tests, and a rollback plan. Deployments use automated pipelines with post-deploy verification and stakeholder announcements.

### 6. Retrospective & Continuous Improvement
After each sprint, release, or major milestone, capture what went well, what could be improved, and 2–3 prioritized action items with owners and due dates. Track action items in the project backlog and review progress in weekly PM syncs.

## Roles

| Role | Responsibility |
|---|---|
| **Project Manager (PM)** | Coordinates delivery, schedules, risks, and communications |
| **Product Manager (PdM)** | Defines outcomes, prioritizes backlog, measures success |
| **Developers** | Implement features, write tests, participate in design and code reviews |
| **QA/Testing** | Validate quality and acceptance criteria |
| **Stakeholders** | Provide inputs and approvals |

## Process Documents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risks & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

## How to Use

- Browse individual process docs for detailed guidance, checklists, and templates.
- To propose additions or updates to any process document, use the [Add Content to Process Docs](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.
- Keep the Project Charter and key artifacts updated in the project repo under `docs/`.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
