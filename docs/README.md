# OctoAcme Project Management Processes

This folder contains concise process guidance for how OctoAcme runs cross-functional projects. The goal is to provide a single, shareable entry point summarizing our lifecycle, roles, rhythm, and key artifacts — with links to the detailed process docs in this directory.

Purpose
- Centralize how we initiate, plan, execute, release, and improve work.
- Make expectations, decision gates, and communication patterns explicit.
- Help onboard teammates and reduce single-person knowledge risk.

High-level lifecycle
1. Initiation — capture the problem, stakeholders, success metrics, and a one‑pager to decide go/no‑go.
2. Planning — prioritize and estimate the backlog, define Definition of Done, and create a release plan.
3. Execution &amp; Tracking — deliver in small increments, use PR and CI gates, track velocity and risks.
4. Release &amp; Deployment — follow pre-release checks, run smoke tests, and have rollback plans.
5. Retrospect &amp; Improve — run retros, create action items, and measure improvement.

Team rhythm &amp; forums
- Daily standups for progress and blockers
- Weekly delivery syncs for progress, dependencies, and risk
- Sprint/milestone demos and end-of-sprint retrospectives
- Monthly stakeholder updates as needed

Key roles
- Project Manager (PM): delivery coordination, scheduling, risk management
- Product Manager (PdM): outcomes, prioritization, acceptance criteria
- Developers &amp; QA: implementation, testing, and reviews
- Stakeholders &amp; Sponsors: approvals and business alignment

Core workflows &amp; quality
- Use the project board (Backlog → Ready → In Progress → In Review → QA → Done)
- Small PRs, link issues and acceptance criteria, run CI and security scans before review
- Automated unit/integration tests, E2E smoke tests for critical flows, manual QA when required

Risk, communication &amp; escalation
- Maintain a Risk Register (ID, impact, likelihood, owner, mitigation)
- Weekly reviews of risk and dependencies
- Escalation path: Team → PM → Product Lead → Sponsor (security incidents follow the Security runbook)

Where to find more detail
- docs/octoacme-project-management-overview.md
- docs/octoacme-project-initiation.md
- docs/octoacme-project-planning.md
- docs/octoacme-execution-and-tracking.md
- docs/octoacme-release-and-deployment.md
- docs/octoacme-risks-and-communication.md
- docs/octoacme-retrospective-and-continuous-improvement.md
- docs/octoacme-roles-and-personas.md
