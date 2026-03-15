# OctoAcme — Project Management Overview

OctoAcme runs projects with an outcome-focused, iterative approach that prioritizes clear ownership and measurable outcomes. Projects move through a lightweight lifecycle—initiation, planning, execution, release, and close/retrospective—using compact artifacts (Project One-pager, roadmap, backlog, risk register, release notes) to capture scope, success metrics, milestones, and risks. Initiation validates the problem and success criteria; planning breaks approved initiatives into shippable increments with estimates, a Definition of Done, and an explicit release plan.

Work is executed via a standard backlog-and-board workflow (Backlog → Ready → In Progress → In Review → QA → Done). Backlog items must include acceptance criteria before being pulled into work. The pull request process emphasizes small, well-scoped PRs, linked issues and acceptance criteria, automated CI (tests, linting, security scans) before review, and at least one approval before merging. Releases are categorized (patch/minor/major) and follow a pre-release checklist (smoke tests, rollback plan, and release notes) to minimize risk during rollouts.

Roles are defined so responsibilities and decision-making are clear: Product Managers (PdM) own the problem and success metrics; Project Managers (PM) coordinate delivery, schedules, risks, and stakeholder updates; Developers implement and test features; QA validates acceptance criteria and testing; Stakeholders provide inputs and approvals. Communication cadence includes daily standups, a weekly PM–PdM sync, sprint demos/reviews, and monthly stakeholder updates. Templates and artifacts (one-pagers, weekly status, release notes) act as single sources of truth for status and decisions.

Quality assurance and risk management are embedded throughout delivery. Automated unit, integration, and smoke tests are required for critical flows; CI enforces tests and security scanning; manual QA is used for acceptance when needed. Risks are tracked in a Risk Register (ID, impact, likelihood, owner, mitigation) and reviewed in weekly syncs. Continuous improvement is enforced through timeboxed retrospectives that produce prioritized action items tracked into the backlog.

Core artifacts and where to find detailed docs
- Project Overview: octoacme-project-management-overview.md
  - https://github.com/karlodegrano/skills-scale-institutional-knowledge-using-copilot-spaces/blob/main/docs/octoacme-project-management-overview.md
- Project Initiation / One-pager: octoacme-project-initiation.md
  - https://github.com/karlodegrano/skills-scale-institutional-knowledge-using-copilot-spaces/blob/main/docs/octoacme-project-initiation.md
- Project Planning: octoacme-project-planning.md
  - https://github.com/karlodegrano/skills-scale-institutional-knowledge-using-copilot-spaces/blob/main/docs/octoacme-project-planning.md
- Execution & Tracking: octoacme-execution-and-tracking.md
  - https://github.com/karlodegrano/skills-scale-institutional-knowledge-using-copilot-spaces/blob/main/docs/octoacme-execution-and-tracking.md
- Release & Deployment Guide: octoacme-release-and-deployment.md
  - https://github.com/karlodegrano/skills-scale-institutional-knowledge-using-copilot-spaces/blob/main/docs/octoacme-release-and-deployment.md
- Risk Management & Communication: octoacme-risks-and-communication.md
  - https://github.com/karlodegrano/skills-scale-institutional-knowledge-using-copilot-spaces/blob/main/docs/octoacme-risks-and-communication.md
- Retrospective & Continuous Improvement: octoacme-retrospective-and-continuous-improvement.md
  - https://github.com/karlodegrano/skills-scale-institutional-knowledge-using-copilot-spaces/blob/main/docs/octoacme-retrospective-and-continuous-improvement.md
- Personas / Roles: octoacme-roles-and-personas.md
  - https://github.com/karlodegrano/skills-scale-institutional-knowledge-using-copilot-spaces/blob/main/docs/octoacme-roles-and-personas.md

How to propose changes to these process docs
- To request content updates or add new process docs, open an issue using the process doc template:
  - https://github.com/karlodegrano/skills-scale-institutional-knowledge-using-copilot-spaces/blob/main/.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml

Notes
- This README is intended as a high-level entry point. For decisions, timelines, and current status, consult the project-specific README and the project board in the relevant repo.
