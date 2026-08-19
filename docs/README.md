# OctoAcme Project Management Docs

## Overview

OctoAcme follows a structured, iterative approach to project management focused on customer value, clear ownership, and data-driven decisions. This README serves as a centralized hub and quick reference for the process documents stored in this folder.

## Process Summary

OctoAcme’s project management lifecycle is intentionally lightweight and iterative: Initiation, Planning, Execution, Release, and Retrospective. Projects start with a Project One-pager that clarifies the problem, objectives, measurable success metrics, stakeholders, timeline, and risks; the project moves to planning only after success criteria and team availability are confirmed. Planning breaks approved initiatives into a prioritized, estimable backlog with clear acceptance criteria and a Definition of Done so that work can be pulled into iterations and delivered in small, testable increments.

Execution is coordinated using a visual project board (Backlog → Ready → In Progress → In Review → QA → Done) and a disciplined PR workflow that favors small changes, linked issues, and CI-validated merges. The team cadence includes daily standups to surface progress and blockers, a weekly delivery sync to review progress and risks, sprint demos for stakeholder visibility, and monthly stakeholder updates. Escalation paths are explicit, starting with team triage and progressing to PM, Product Lead, and sponsor-level escalation for business-impacting issues.

Roles and responsibilities are clearly defined: Product Managers own outcomes and prioritization; Project Managers coordinate delivery, risks, and communications; Developers implement and test; and QA validates acceptance criteria and release readiness. Quality assurance is enforced through unit and integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA when required. Releases follow a checklist-driven process with staging verification, rollback plans, and post-deploy checks to minimize risk.

Continuous improvement is captured through structured retrospectives that produce prioritized action items fed back into the backlog. Risk is managed with a simple register (ID, impact, likelihood, owner, mitigation, status) and communicated via standard templates for weekly updates and incident triage. Together these practices aim to reduce single-person dependencies, improve discoverability of processes, and provide a consistent way for teams to operate and learn.

## Key Principles

- Customer-first: Prioritize customer value and usability
- Iterative delivery: Deliver small, testable increments
- Clear ownership: Each project has named roles with defined responsibilities
- Data-informed: Measure impact and iterate based on evidence
- Psychological safety: Encourage feedback and continuous learning

## Core Roles

- Project Manager (PM): Coordinates delivery, schedules, risks, and communications
- Product Manager (PdM): Defines outcomes, prioritizes backlog, measures success
- Developers: Implement features, collaborate on design and testability
- QA/Testing: Validate quality and acceptance criteria
- Stakeholders: Provide inputs and approvals

## Process Documents

### Project Lifecycle
1. [Project Initiation](./octoacme-project-initiation.md) - Define business need, align stakeholders, create a lightweight plan
2. [Project Planning](./octoacme-project-planning.md) - Turn an approved initiative into an actionable plan and backlog
3. [Execution & Tracking](./octoacme-execution-and-tracking.md) - Manage day-to-day execution and track progress
4. [Release & Deployment](./octoacme-release-and-deployment.md) - Standardize release process and reduce deployment risk
5. [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) - Capture learnings and drive improvements

### Cross-Cutting Concerns
- [Risk Management & Communication](./octoacme-risks-and-communication.md) - Identify, manage, and communicate risks and dependencies
- [Roles & Personas](./octoacme-roles-and-personas.md) - Detailed role definitions and responsibilities

## Quick Reference

- New project? Start with [Project Initiation](./octoacme-project-initiation.md)
- Ready to build? Review [Project Planning](./octoacme-project-planning.md)
- In execution? Reference [Execution & Tracking](./octoacme-execution-and-tracking.md)
- Going live? Follow [Release & Deployment](./octoacme-release-and-deployment.md)
- Sprint complete? Conduct [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

## How to use these docs

- Keep the Project One-pager and key artifacts in the project repo alongside these docs.
- Use the issue template `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` to request additions or updates to any process document.
- Add process-specific working materials into `.copilot/` if you want Copilot Spaces to use them as context.

## Acceptance Criteria

- [x] Content aligns with existing process docs
- [x] Update improves clarity or closes a documented gap
- [ ] Proposed content has been reviewed with stakeholders (if needed)

---

*This README was added to centralize OctoAcme process documentation and improve discoverability for team members.*
