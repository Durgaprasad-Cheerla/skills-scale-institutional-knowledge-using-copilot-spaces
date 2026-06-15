# OctoAcme Project Management

Welcome to the OctoAcme project management documentation. This folder contains the core process guides, templates, and best practices used to run OctoAcme projects successfully.

## Project Management Processes Summary

OctoAcme operates on a structured, customer-first project lifecycle that emphasizes **iterative delivery, clear ownership, and data-informed decisions**. The organization applies five distinct phases—Initiation, Planning, Execution, Release, and Retrospective—to all cross-functional projects.

**Core Principles:**
- Customer-first: prioritize customer value and usability
- Iterative delivery: deliver small, testable increments
- Clear ownership: each project has a named Project Manager (PM) and Product Manager (PdM)
- Data-informed decisions: measure impact and iterate based on evidence
- Psychological safety: encourage feedback and learning

**Communication Cadence:**
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery syncs — show progress, updates, and flagged risks
- Weekly PM/PdM alignment — sync on strategy and priorities
- Monthly stakeholder updates — communicate status and impact
- Sprint demos and retrospectives — celebrate wins and capture learnings

**Key Artifacts:**
- Project One-pager (Problem, Goal, Success Metrics)
- Roadmap and Release Plan with milestones
- Prioritized Backlog with acceptance criteria
- Risk Register (ID, Description, Impact, Mitigation)
- Retrospective notes and action items

**Execution Model:**
- Small PRs (≤400 lines) with clear acceptance criteria and issue links
- Automated CI (tests, linting, security scanning) before review
- Minimum one approval before merge
- Unit, integration, and end-to-end smoke tests for critical flows
- Manual QA for feature acceptance when needed

**Risk & Escalation:**
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

---

## Process Documents

Use these guides to understand how OctoAcme runs projects at each stage of the lifecycle:

### [Project Management Overview](./octoacme-project-management-overview.md)
High-level introduction to OctoAcme's approach, roles, and key artifacts. **Start here** if you're new to the organization.

### [Project Initiation Guide](./octoacme-project-initiation.md)
Steps to validate and authorize new work, align stakeholders, and create a lightweight plan. Includes the Project One-pager template and initiation checklist.

### [Project Planning](./octoacme-project-planning.md)
Turn an approved initiative into an actionable plan and backlog. Covers kickoff, backlog creation, estimation, Definition of Done, dependencies, and risk management.

### [Execution & Tracking](./octoacme-execution-and-tracking.md)
Guidance for managing day-to-day execution, team rhythm, workflows, quality assurance, and blocker escalation.

### [Risk Management & Communication](./octoacme-risks-and-communication.md)
How to identify, manage, and communicate risks, dependencies, and stakeholder updates. Includes the Risk Register template and escalation paths.

### [Release & Deployment Guide](./octoacme-release-and-deployment.md)
Standardize how OctoAcme releases features to production. Covers pre-release requirements, deployment checklist, rollback procedures, and release notes.

### [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
Capture learnings after each sprint, release, or milestone. Includes retrospective structure, action item tracking, and continuous improvement practices.

### [Roles & Personas](./octoacme-roles-and-personas.md)
Definitions of typical roles (Developers, Product Managers, Project Managers) and their responsibilities, goals, and communication patterns.

---

## How to Use These Docs

- **For new team members:** Start with [Project Management Overview](./octoacme-project-management-overview.md), then read through the phase-specific guides relevant to your role.
- **For project kicks:** Use [Project Initiation Guide](./octoacme-project-initiation.md) and [Project Planning](./octoacme-project-planning.md) to set up your project.
- **During execution:** Reference [Execution & Tracking](./octoacme-execution-and-tracking.md) and [Risk Management & Communication](./octoacme-risks-and-communication.md) for daily guidance.
- **At release time:** Follow [Release & Deployment Guide](./octoacme-release-and-deployment.md) to ensure a safe, smooth rollout.
- **After each milestone:** Use [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) to capture learnings and improve.

---

## Contributing to Process Docs

Found a gap, clarity issue, or best practice to add? Please use the [Process Doc Update issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose changes.

All process improvements should:
- Align with existing docs and OctoAcme principles
- Close a documented gap or improve clarity
- Be reviewed with relevant stakeholders when appropriate
