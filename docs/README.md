# OctoAcme Project Management Docs

## Overview

OctoAcme project teams deliver value by following an iterative process with clear roles, measurable outcomes, and continuous improvement at every phase. Work is structured from ideation through planning, execution, release, and retrospectives, with strong risk management practices and transparent communication.

### Core Principles
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

### Project Lifecycle

OctoAcme follows a five-phase approach to every project:

1. **Initiation** — Validate business need, confirm stakeholder alignment, and establish success metrics through a lightweight One-pager before committing resources.

2. **Planning** — Break approved work into shippable increments with defined acceptance criteria, map dependencies, identify risks, and create a prioritized backlog with a release timeline.

3. **Execution** — Deliver iteratively using daily standups, project boards, small pull requests, and automated testing. Track progress and surface blockers through structured team rhythm and communication.

4. **Release** — Move features to production with comprehensive pre-deployment checks, including passing CI/CD, security scans, smoke tests, and documented rollback plans.

5. **Close & Retrospective** — Capture learnings, identify improvements, and feed validated insights back into continuous refinement of processes and practices.

### Key Roles

- **Project Managers** coordinate delivery, manage schedules, risks, and communications to keep teams aligned and on track.
- **Product Managers** own the vision, prioritize the backlog, and measure outcomes through research and metrics.
- **Developers** implement features, collaborate on design and testability, and maintain code quality through tests and reviews.
- **QA/Testing** validates quality and acceptance criteria.
- **Stakeholders** provide inputs, approvals, and business context.

### Quality & Execution Standards

- Small pull requests (≤400 lines when possible)
- At least one approval required before merge
- Automated CI/CD with linting, unit tests, integration tests, and security scanning
- Manual QA and smoke tests for critical flows
- Clear Definition of Done for all work
- Weekly risk reviews and blocker escalation

### Communication Cadence

- **Daily**: Team standups (15 min) — progress, blockers, dependencies
- **Weekly**: PM + Product Manager sync for alignment
- **Twice-weekly**: Delivery team standups (or as agreed)
- **Monthly**: Stakeholder updates
- **Ad-hoc**: Risk escalation and incident communication

## Docs Index

- **[Project Management Overview](octoacme-project-management-overview.md)** — Introduction to OctoAcme's approach, roles, key artifacts, and lifecycle overview.

- **[Project Initiation Guide](octoacme-project-initiation.md)** — Steps to validate business need, align stakeholders, and confirm go/no-go for planning.

- **[Project Planning](octoacme-project-planning.md)** — How to break work into shippable increments, estimate, identify dependencies, and create a release plan.

- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day team rhythm, project board workflows, PR practices, quality standards, and blocker escalation.

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Risk register maintenance, lifecycle, stakeholder communication templates, and escalation paths.

- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Release types, pre-release requirements, deployment checklist, rollback playbook, and release notes template.

- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — How to run retrospectives, track action items, and build a culture of continuous improvement.

- **[Roles and Personas](octoacme-roles-and-personas.md)** — Detailed definitions of Developer, Product Manager, and Project Manager responsibilities, goals, and typical communication patterns.

---

## How to Use These Docs

- **New team members**: Start with [Project Management Overview](octoacme-project-management-overview.md), then browse the docs that match your role.
- **Starting a new project**: Follow the [Project Initiation Guide](octoacme-project-initiation.md), then [Project Planning](octoacme-project-planning.md).
- **During execution**: Refer to [Execution & Tracking](octoacme-execution-and-tracking.md) and [Risk Management & Communication](octoacme-risks-and-communication.md).
- **Preparing for release**: Use the [Release & Deployment Guide](octoacme-release-and-deployment.md).
- **After milestones**: Run a retrospective using [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md).

## Contributing to These Docs

To propose updates or additions to the project management process docs, please create an issue using the **"Add Content to Project Management Process Docs"** template (stored in `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml`). This helps us track improvements collaboratively and ensure changes align with team consensus.