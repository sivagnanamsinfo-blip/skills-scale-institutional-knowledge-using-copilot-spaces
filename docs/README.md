# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation suite. These docs provide guidance for running projects at OctoAcme—from initiation through retrospective.

## Overview

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The framework spans five core phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. During initiation, teams validate business need and create a lightweight Project One-pager that captures the problem statement, goals, success metrics, stakeholders, and initial risks. This gate-based approach ensures that only well-aligned initiatives move forward into detailed planning. In the planning phase, work is broken into shippable increments with clear acceptance criteria, dependencies are mapped, and a Definition of Done is established. Teams use prioritized backlogs, T-shirt sizing or story points, and risk registers to coordinate across functions.

The organization defines three core roles with distinct responsibilities: **Product Managers** own the product vision and prioritize the backlog; **Project Managers** coordinate delivery and manage schedules and risks; and **Developers** implement features and identify technical risks. This clear separation of ownership reduces ambiguity and enables focused decision-making. Communication flows through a consistent cadence: daily standups focused on progress and blockers, weekly PM/Product Manager syncs, twice-weekly delivery team standups, and monthly stakeholder updates. Quality assurance is embedded throughout execution: unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance.

## Quick Start

New to OctoAcme projects? Start here:

1. Read the [Project Management Overview](octoacme-project-management-overview.md) to understand our principles and roles.
2. Follow the appropriate process guide for your phase (see below).
3. Use templates and checklists from each guide to stay on track.

## Process Guides

OctoAcme projects follow a five-phase lifecycle:

| Phase | Document | Purpose |
|-------|----------|---------|
| **Initiation** | [Project Initiation Guide](octoacme-project-initiation.md) | Validate business need, align stakeholders, create a lightweight plan |
| **Planning** | [Project Planning](octoacme-project-planning.md) | Break work into shippable increments, identify dependencies and risks |
| **Execution** | [Execution & Tracking](octoacme-execution-and-tracking.md) | Manage day-to-day execution, track progress toward milestones |
| **Release** | [Release & Deployment Guide](octoacme-release-and-deployment.md) | Standardize releases and deployment to reduce risk |
| **Close** | [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and drive improvements |

## Cross-Cutting Topics

- [Risk Management & Communication](octoacme-risks-and-communication.md) — How to identify, manage, and communicate risks across all phases
- [Roles and Personas](octoacme-roles-and-personas.md) — Detailed descriptions of core project roles and responsibilities

## Key Principles

- **Customer-first**: Prioritize customer value and usability.
- **Iterative delivery**: Deliver small, testable increments.
- **Clear ownership**: Each project has a named Project Manager and Product Lead.
- **Data-informed**: Measure impact and iterate based on evidence.
- **Psychological safety**: Encourage feedback and learning.

## Core Artifacts

- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Risk Register
- Acceptance Criteria & Definition of Done
- Retrospective notes and action items

## How to Use These Docs

1. **Keep your Project Charter updated** in your project repo.
2. **Add process-specific docs** to `.copilot/` if using Copilot Spaces as your knowledge source.
3. **Use templates and checklists** from each guide to stay on track.
4. **Contribute improvements** back to this suite via the ["Add Content to Project Management Process Docs" issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml).

## Communication Cadence

- **Daily standups** — 15 minutes focused on progress, blockers, and dependencies
- **Weekly PM/PdM sync** — Alignment on priorities, risks, and decisions
- **Twice-weekly delivery standups** — Team-level coordination (or as agreed)
- **Monthly stakeholder updates** — Status, risks, and key decisions
- **Ad-hoc escalations** — As needed for blockers and dependencies

## Quality & Testing Standards

- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

---

For questions or suggestions on these processes, please create an issue using the [Process Doc Update template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml).
