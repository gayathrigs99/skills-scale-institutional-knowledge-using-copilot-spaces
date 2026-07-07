# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management knowledge base. This directory contains comprehensive guides and process documents that standardize how OctoAcme runs projects, manages teams, and delivers value.

## Purpose

These documents centralize project management knowledge, convert tacit team insights into versioned and searchable artifacts, and enable consistent, repeatable project execution across all cross-functional initiatives.

## Quick Links to Process Documents

### Core Process Guides

1. **[Project Management Overview](./octoacme-project-management-overview.md)**
   - High-level introduction to OctoAcme's approach, core principles, and key artifacts
   - Overview of roles, lifecycle, and communication cadence
   - *Start here* if you're new to OctoAcme

2. **[Project Initiation Guide](./octoacme-project-initiation.md)**
   - Steps to validate and authorize new work
   - Stakeholder alignment and Project One-pager template
   - Decision gates for moving into planning

3. **[Project Planning](./octoacme-project-planning.md)**
   - Turn approved initiatives into actionable plans and backlogs
   - Backlog item templates and sprint planning approach
   - Risk and dependency management framework

4. **[Execution & Tracking](./octoacme-execution-and-tracking.md)**
   - Manage day-to-day execution and track progress
   - Team rhythm, PR workflows, and quality standards
   - Blocker escalation paths and execution checklist

5. **[Risk Management & Communication](./octoacme-risks-and-communication.md)**
   - Identify, manage, and communicate risks and dependencies
   - Risk Register structure and lifecycle
   - Stakeholder communication templates and escalation paths

6. **[Release & Deployment Guide](./octoacme-release-and-deployment.md)**
   - Standardized release and deployment procedures
   - Pre-release requirements and deployment checklist
   - Rollback and incident playbook

7. **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)**
   - Capture learnings and convert them into actionable improvements
   - Retrospective structure and action item tracking
   - Building a continuous improvement culture

8. **[Roles & Personas](./octoacme-roles-and-personas.md)**
   - Detailed role definitions and responsibilities
   - Personas: Developers, Product Managers, Project Managers, and QA/Testing

---

## OctoAcme Project Management Overview

### Core Principles

OctoAcme operates on five foundational principles:

- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments to reduce risk and enable rapid feedback
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and continuous improvement

### Key Roles

- **Project Manager (PM)**: Coordinates delivery, schedules, risks, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs, approvals, and strategic direction

### Project Lifecycle

OctoAcme projects follow a structured five-phase lifecycle:

1. **Initiation**: Problem statement, stakeholder identification, high-level timeline
2. **Planning**: Scope definition, resource allocation, milestones, and dependency mapping
3. **Execution**: Build, test, review, and iterate with continuous feedback
4. **Release**: Deploy, verify functionality, and announce to stakeholders
5. **Close & Retrospective**: Capture learnings and identify improvements for future projects

### Quality Assurance & Testing Practices

Quality is embedded throughout the OctoAcme project lifecycle:

- **Unit tests** for all new logic
- **Integration tests** where applicable
- **End-to-end smoke tests** for critical flows before release
- **Security scanning** integrated into CI pipeline
- **Manual QA** for feature acceptance when needed
- **Definition of Done** established during planning with clear acceptance criteria
- **Pre-release checklist**: All acceptance criteria met, CI passing, security scans cleared, rollback plan documented

### Workflows & Execution Model

OctoAcme uses GitHub Projects and Pull Requests as core execution tools:

- **Project Board**: Columns include Backlog, Ready, In Progress, In Review, QA, Done
- **Pull Request Standards**: Small PRs (≤400 lines), include issue links and acceptance criteria, pass CI before review, require ≥1 approval
- **Team Rhythm**:
  - Daily standups (15 min) - progress, blockers, dependencies
  - Weekly delivery sync - show progress, updates, flagged risks
  - Sprint/milestone demos and reviews
- **Backlog Management**: Prioritized, estimated items with clear acceptance criteria and owners
- **Capacity Planning**: Sprint planning respects team capacity to prevent overload

### Communication & Risk Management

OctoAcme maintains structured communication and proactive risk management:

- **Risk Register**: Tracked with ID, description, impact, likelihood, owner, mitigation, status
- **Communication Cadence**:
  - Weekly PM + PdM sync
  - Twice-weekly delivery team standups
  - Monthly stakeholder updates
  - Ad-hoc escalations as needed
- **Escalation Path**: Team-level → PM → Product Lead → Sponsor
- **Weekly Status Template**: Progress, next steps, risks/blockers, decisions needed
- **Incident Communication**: Triage summary, actions, timeline, blameless retrospective

### Continuous Improvement

OctoAcme embeds learning into every project phase:

- **Retrospectives**: Held after each sprint, release, or milestone (45–75 min)
- **Structure**: What went well, what could improve, 2–3 prioritized action items
- **Tracking**: Action items added to backlog with clear owners and due dates
- **Measurement**: Impact of improvements tracked and celebrated

---

## How to Use These Docs

- **New to OctoAcme?** Start with [Project Management Overview](./octoacme-project-management-overview.md)
- **Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md)
- **Need planning guidance?** Refer to [Project Planning](./octoacme-project-planning.md)
- **Day-to-day execution questions?** Check [Execution & Tracking](./octoacme-execution-and-tracking.md)
- **Managing risks or communicating with stakeholders?** See [Risk Management & Communication](./octoacme-risks-and-communication.md)
- **Preparing for a release?** Review [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- **After a project concludes?** Follow [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- **Understanding roles on your team?** Review [Roles & Personas](./octoacme-roles-and-personas.md)

## Contributing to These Docs

To request updates or add new content to OctoAcme's process documentation, use the **[Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** issue template.

This ensures all improvements are reviewed, documented, and aligned with the team's project management approach.

---

**Last Updated**: July 2026  
**Maintained By**: OctoAcme Project Management Team
