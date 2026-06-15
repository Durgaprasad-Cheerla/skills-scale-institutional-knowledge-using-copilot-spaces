# OctoAcme Project Management

This README collects the OctoAcme project management process documents and provides a short summary of our approach so team members and stakeholders can quickly find guidance on initiation, planning, execution, release, risk management, retrospectives, and roles.

## Project Management Processes Overview

OctoAcme employs a structured, iterative project management approach designed around five core principles: **customer-first prioritization**, **iterative delivery of small, testable increments**, **clear ownership** with named Project Managers and Product Leads, **data-informed decisions** based on measurable outcomes, and **psychological safety** that encourages feedback and learning.

The project lifecycle consists of five phases:
1. **Initiation** — Validate business need, align stakeholders, and create a lightweight plan
2. **Planning** — Break work into shippable increments, identify dependencies, and align timelines
3. **Execution** — Build, test, review, and iterate with quality gates at each step
4. **Release** — Deploy to production with verification and rollback plans
5. **Close & Retrospective** — Capture learnings and convert them into actionable improvements

### Core Communication Cadence
- **Daily standups** (15 min) — Focus on progress, blockers, and dependencies
- **Twice-weekly delivery standups** — Team-level coordination and issue triage
- **Weekly PM + PdM sync** — Strategic alignment and risk review
- **Weekly stakeholder updates** — Status, metrics, and escalations
- **Sprint/milestone demos** — Show progress and gather feedback
- **Monthly stakeholder briefings** — High-level roadmap and business impact

### Quality & Execution Standards
- Small, focused pull requests (≤400 lines when possible)
- Unit tests and integration tests for new logic
- Automated CI/CD with security scanning and linting
- At least one approval required before merge
- End-to-end smoke tests before release
- Manual QA for feature acceptance when needed
- Structured deployment checklists with rollback plans

### Key Artifacts
- **Project One-pager** — Problem statement, goals, success metrics, stakeholders, timeline, risks
- **Backlog with Acceptance Criteria** — Prioritized, estimated work with clear Definition of Done
- **Risk Register** — Tracked with ID, impact, likelihood, owner, mitigation, and status
- **Release Plan** — Milestones, dependencies, and deployment windows
- **Retrospective Notes & Action Items** — Learnings converted to improvements with owners and due dates

### Roles & Responsibilities
- **Project Manager** — Coordinates delivery, manages schedules, risks, and communications
- **Product Manager** — Defines outcomes, prioritizes backlog, measures success
- **Developers** — Implement features, collaborate on design, write tests
- **QA/Testing** — Validate quality and acceptance criteria
- **Stakeholders** — Provide inputs, approvals, and business context

---

## Documentation

### Getting Started
- **[OctoAcme Project Management Overview](./octoacme-project-management-overview.md)** — Concise introduction to how OctoAcme runs projects, core roles, key artifacts, and lifecycle overview

### Project Phases
- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Steps to validate ideas, align stakeholders, and create initial plans. Use this when starting a new project.
- **[Project Planning](./octoacme-project-planning.md)** — Turn approved initiatives into actionable plans. Covers backlog creation, estimation, Definition of Done, and release planning.
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Manage day-to-day execution and track progress toward milestones. Covers team rhythm, workflows, quality standards, and blocker escalation.
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Standardize how OctoAcme releases features to production. Covers release types, pre-release requirements, deployment checklists, and rollback procedures.
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings after sprints, releases, or incidents and convert them into actionable improvements.

### Cross-Cutting Concerns
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks. Covers the Risk Register, stakeholder communication templates, and escalation paths.
- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Define typical roles (Developers, Product Managers, Project Managers) and their responsibilities, goals, and communication patterns.

---

## Quick Links

| Document | Purpose | When to Use |
|----------|---------|------------|
| [Overview](./octoacme-project-management-overview.md) | High-level introduction to OctoAcme's approach | Onboarding new team members or stakeholders |
| [Initiation](./octoacme-project-initiation.md) | Validate and authorize new work | Starting a new project or feature proposal |
| [Planning](./octoacme-project-planning.md) | Create actionable plans and backlog | After project approval, before execution begins |
| [Execution](./octoacme-execution-and-tracking.md) | Manage day-to-day delivery | During sprints and iterations |
| [Release](./octoacme-release-and-deployment.md) | Standardize production releases | Before deploying to production |
| [Retrospective](./octoacme-retrospective-and-continuous-improvement.md) | Capture and act on learnings | After sprints, releases, or incidents |
| [Risk & Communication](./octoacme-risks-and-communication.md) | Manage risks and stakeholder alignment | Throughout all project phases |
| [Roles](./octoacme-roles-and-personas.md) | Understand team responsibilities | Understanding team structure and interactions |

---

## How to Use These Docs

1. **For new team members:** Start with the [Overview](./octoacme-project-management-overview.md) and [Roles & Personas](./octoacme-roles-and-personas.md) to understand our approach and your role.
2. **For new projects:** Follow the sequence: [Initiation](./octoacme-project-initiation.md) → [Planning](./octoacme-project-planning.md) → [Execution](./octoacme-execution-and-tracking.md) → [Release](./octoacme-release-and-deployment.md) → [Retrospective](./octoacme-retrospective-and-continuous-improvement.md).
3. **For ongoing execution:** Refer to [Execution & Tracking](./octoacme-execution-and-tracking.md), [Risk Management](./octoacme-risks-and-communication.md), and team-specific docs as needed.
4. **Keep project charters and artifacts in your project repository** for easy reference and version control.

---

## Contributing to These Docs

If you'd like to propose updates, clarifications, or new content, please use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.

Our goal is to keep these docs:
- **Up-to-date** with how we actually work
- **Clear and accessible** for all team members and stakeholders
- **Actionable** with checklists and templates
- **Collaborative** — your feedback helps us improve
