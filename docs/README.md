# OctoAcme Project Management Documentation

## Overview

OctoAcme follows an integrated project management approach that combines clear governance, iterative delivery, and continuous improvement. This documentation suite provides guidance for managing projects from initiation through closure.

## Framework Summary

OctoAcme employs a structured, lifecycle-based approach to project management that spans five key phases: Initiation, Planning, Execution, Release, and Retrospective. The process is grounded in customer-first principles, iterative delivery, and clear ownership. During **Initiation**, teams validate business need and align stakeholders around a Project One-pager that captures the problem statement, measurable goals, success metrics, and initial timeline. This phase culminates in a decision gate where stakeholders must confirm priority and team availability before proceeding.

Once approved, the **Planning phase** breaks work into shippable increments with prioritized backlogs, acceptance criteria, and a Definition of Done. Teams use T-shirt sizing or story points for estimation and maintain a Risk Register to track dependencies and mitigation strategies. Execution and delivery are coordinated through a structured rhythm of daily standups (15 minutes), weekly delivery syncs, and sprint-based iterations managed on GitHub Projects boards.

Quality assurance is embedded throughout—unit tests for new logic, integration tests where applicable, end-to-end smoke tests before release, and security scanning in CI pipelines. Teams track velocity and burndown metrics, monitor success indicators, and escalate blockers through a three-level system: team-level triage in standups, PM escalation to Product Leads, and sponsor-level escalation for business-impacting issues. Each project concludes with a retrospective to capture learnings and convert them into prioritized action items, reinforcing a culture of continuous improvement across the organization.

## Quick Start

- **New to OctoAcme projects?** Start with [Project Management Overview](octoacme-project-management-overview.md)
- **Starting a new project?** See [Project Initiation Guide](octoacme-project-initiation.md)
- **Ready to plan execution?** Follow [Project Planning](octoacme-project-planning.md)

## Process Documentation

### Project Lifecycle

1. **[Project Initiation](octoacme-project-initiation.md)** — Validate business need, align stakeholders, decide go/no-go
2. **[Project Planning](octoacme-project-planning.md)** — Break work into shippable increments, identify risks and dependencies
3. **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Manage day-to-day delivery, track progress, maintain quality
4. **[Release & Deployment](octoacme-release-and-deployment.md)** — Standardize release process, reduce risk, improve observability
5. **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings, implement improvements

### Cross-Cutting Guidance

- **[Roles & Personas](octoacme-roles-and-personas.md)** — Clarify responsibilities of Project Managers, Product Managers, Developers, and QA
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks; escalation paths; status templates

## Core Roles

| Role | Responsibility | Key Focus |
|------|-----------------|-----------|
| **Project Manager** | Coordinates delivery, manages schedules, risks, and communications | On-time delivery, risk mitigation, stakeholder alignment |
| **Product Manager** | Defines outcomes, prioritizes backlog, measures success | Customer value, data-driven decisions, product vision |
| **Developer** | Implements features, collaborates on design and testing | Code quality, test coverage, maintainability |
| **QA/Testing** | Validates quality and acceptance criteria | Quality assurance, test coverage, acceptance validation |

## Key Artifacts

- Project Charter / One-pager
- Risk Register
- Release Plan and Roadmap
- Sprint/Iteration Backlog
- Definition of Done
- Retrospective notes and action items
- Weekly Status Reports
- Release Notes

## Communication Cadence

- **Daily standups (15 min)** — progress, blockers, dependencies
- **Weekly PM + PdM sync** — alignment and risk review
- **Twice-weekly delivery team standups** (or as agreed)
- **Monthly stakeholder updates** — progress against metrics and timeline
- **Ad-hoc escalations** — as needed for blockers or business-impacting issues

## Quality & Testing Standards

- Unit tests for all new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI pipelines
- Manual QA for feature acceptance when needed
- PR requirements: ≤400 lines, issue link, acceptance criteria, passing CI, at least one approval

## Contributing to These Docs

To request updates or add new content to these process documents, use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.

## Getting Started with Your First Project

1. Review the [Project Management Overview](octoacme-project-management-overview.md) to understand the framework
2. Use the [Project Initiation Guide](octoacme-project-initiation.md) to kickstart your project with a One-pager
3. Reference the [Roles & Personas](octoacme-roles-and-personas.md) to ensure clear accountability
4. Follow the [Project Planning](octoacme-project-planning.md) template to create your backlog and timeline
5. Use [Execution & Tracking](octoacme-execution-and-tracking.md) for day-to-day delivery management
6. Reference [Risk Management & Communication](octoacme-risks-and-communication.md) for escalations and status updates
7. Use [Release & Deployment](octoacme-release-and-deployment.md) when preparing for production
8. Conduct a [Retrospective](octoacme-retrospective-and-continuous-improvement.md) to capture learnings and drive improvements
