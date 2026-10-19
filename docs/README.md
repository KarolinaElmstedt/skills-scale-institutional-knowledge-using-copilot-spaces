# OctoAcme Project Management Docs

This README indexes the OctoAcme project management process documents and provides a concise summary of the project management processes used across our projects. It’s intended as a single source of truth to help teammates and stakeholders quickly find process guidance, onboarding material, and links to the detailed artifacts in docs/.

OctoAcme runs an iterative, artifact-driven lifecycle that begins with a lightweight initiation step and moves through planning, execution, release, and continuous improvement. New initiatives are validated with a Project One-pager (problem, goals, success metrics) and an initiation checklist to confirm stakeholders and team availability. Planning breaks approved work into prioritized backlog items with explicit acceptance criteria and a Definition of Done so scope and quality expectations are clear.

Day-to-day execution uses a simple project board (Backlog → Ready → In Progress → In Review → QA → Done) and a disciplined pull request workflow that favors small PRs, links to the originating issue and acceptance criteria, and requires CI (tests, linting, and security scans) before review. Team cadence includes daily standups for blockers, weekly delivery syncs for progress and risks, sprint demos, and regular PM+PdM alignment. Escalation paths are documented so blockers move quickly from team-level triage up to Product Lead and Sponsor when needed.

Roles are explicit: Project Managers coordinate delivery, Product Managers own outcomes and prioritization, Developers build and test, and QA validates acceptance. Quality is enforced through layered practices—unit and integration tests, smoke/end-to-end checks for critical flows, security scanning in CI, and manual QA where needed—plus pre-release checklists and rollback plans for production deployments. Retrospectives capture learnings and turn them into tracked action items that feed back into the backlog and process docs.

Links to process documents

- docs/octoacme-project-management-overview.md
- docs/octoacme-project-initiation.md
- docs/octoacme-project-planning.md
- docs/octoacme-execution-and-tracking.md
- docs/octoacme-release-and-deployment.md
- docs/octoacme-retrospective-and-continuous-improvement.md
- docs/octoacme-risks-and-communication.md
- docs/octoacme-roles-and-personas.md

Suggested next steps

- Add a link to this README from the repository root README.md.
- Optionally reference this README in .copilot/ to make it available to Copilot Spaces.
- Review the summary with stakeholders and mark issue #2 when complete.
