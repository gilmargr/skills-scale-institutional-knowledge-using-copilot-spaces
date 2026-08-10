# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management docs. This folder provides a single, discoverable entry point to the processes, templates, and role guidance the team uses to plan, deliver, and improve projects. The materials here are intended to speed onboarding, reduce single-person dependencies, and provide a consistent set of expectations for delivery across Initiation → Planning → Execution → Release → Retrospective.

OctoAcme runs projects with a lightweight initiation that captures the problem, success metrics, stakeholders, and a go/no‑go decision. Approved work moves into planning where teams break initiatives into shippable backlog items with clear acceptance criteria and estimates, define the Definition of Done, and map releases and milestones. Planning artifacts and a simple risk register are used to identify dependencies early and make work ready for execution.

Execution follows a board-backed workflow (Backlog → Ready → In Progress → In Review → QA → Done) with a pull request process that favors small PRs, links issues and acceptance criteria, and requires CI checks and reviewer approval. Team rhythm (daily standups, weekly delivery syncs, demos) and regular PM↔PdM coordination keep scope, dependencies, and risks visible. Roles are explicit: Product Managers define outcomes and prioritize, Project Managers coordinate delivery and escalate blockers, Developers implement and test, and QA validates acceptance criteria.

Quality is built into the lifecycle through unit and integration tests, smoke tests for critical flows, automated security scanning in CI, and manual QA where needed. Releases follow pre-release and deployment checklists (release notes, rollback plans, staging verification, post-deploy checks) and there is a clear escalation path and incident playbook. Retrospectives convert learnings into tracked action items so improvements are visible and measurable.

## Table of contents
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)

## How to use these docs
- Project leads: keep the Project One-pager and Release Plan in the repo and update the risk register weekly.
- New contributors: start with the Overview and Roles documents, then follow the lifecycle docs.
- To propose changes: use the `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` issue template to suggest edits.

## Core principles
- Customer-first — prioritize customer value and usability.
- Iterative delivery — ship small, testable increments.
- Clear ownership — each project has named PM and Product Lead.
- Data-informed decisions — measure and iterate based on evidence.
- Psychological safety — encourage feedback and learning.
