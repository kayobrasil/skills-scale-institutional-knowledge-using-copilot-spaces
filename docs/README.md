# OctoAcme Project Management Docs

This README centralizes the OctoAcme project management process documents. It provides a short summary of our approach and quick links to each document in the docs/ folder so team members and stakeholders can find guidance quickly.

OctoAcme runs projects through a lightweight, iterative lifecycle: initiation, planning, execution, release, and retrospective. Work begins with a Project One‑pager to capture problem, goals, success metrics and stakeholders, then moves into planning to create a prioritized backlog, acceptance criteria, estimates, and a Definition of Done. Execution uses a project board (Backlog → Ready → In Progress → In Review → QA → Done) and a disciplined PR workflow that emphasizes small, reviewable changes, linked issues, and CI validation.

Roles and responsibilities are explicit: Product Managers define outcomes and success metrics, Project Managers coordinate delivery and communications, Developers implement and test, QA validates acceptance criteria, and Stakeholders provide input and approvals. Key artifacts — Project One‑pager, roadmap/release plan, sprint backlog, risk register, acceptance criteria/DoD, and retrospective notes — should be maintained as the single sources of truth for decisions and status.

Quality and release practices prioritize automation and safety: unit and integration tests, smoke tests for critical flows, CI and security scanning, and manual QA when necessary. Releases follow checklists (pre‑release checks, staging verification, automated production deploys where possible), include drafted release notes and rollback plans, and use a clear incident playbook if a deployment causes critical issues. Continuous improvement is driven by retrospectives with prioritized action items tracked into the backlog.

## Docs (in this folder)
- docs/octoacme-project-management-overview.md
- docs/octoacme-project-initiation.md
- docs/octoacme-project-planning.md
- docs/octoacme-execution-and-tracking.md
- docs/octoacme-risks-and-communication.md
- docs/octoacme-release-and-deployment.md
- docs/octoacme-retrospective-and-continuous-improvement.md
- docs/octoacme-roles-and-personas.md

## How to use
- Link this README from the repository README and from relevant project boards.
- To propose updates to these process docs, use the issue template: .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml
- Keep these docs updated as the authoritative source for team cadence, roles, and checklists.

## Acceptance Criteria
- [x] Content aligns with existing process docs
- [x] Update improves clarity or closes a documented gap
- [ ] Proposed content has been reviewed with stakeholders (if needed)
