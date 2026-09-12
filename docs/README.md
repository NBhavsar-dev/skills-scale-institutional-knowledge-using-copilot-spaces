# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management Docs. This is your central hub for understanding how OctoAcme plans, executes, and delivers projects.

## Our Approach

OctoAcme projects follow a structured lifecycle based on these core principles:

- **Customer-first**: Prioritize customer value and usability in every decision
- **Iterative delivery**: Deliver small, testable increments to reduce risk and gather feedback early
- **Clear ownership**: Every project has named leadership (Project Manager and Product Lead)
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and continuous improvement

## Project Lifecycle

OctoAcme follows a structured five-phase project lifecycle to ensure consistent, predictable delivery:

1. **Initiation**: Validate business need, align stakeholders, and define success criteria
   - *Read: [Project Initiation Guide](octoacme-project-initiation.md)*

2. **Planning**: Break work into prioritized backlog items with acceptance criteria, identify dependencies, and create a release plan
   - *Read: [Project Planning](octoacme-project-planning.md)*

3. **Execution**: Build, test, and review work iteratively on a regular cadence with daily standups and weekly syncs
   - *Read: [Execution & Tracking](octoacme-execution-and-tracking.md)*

4. **Release**: Deploy to production with confidence, requiring pre-flight checks, passing tests, security scans, and a documented rollback plan
   - *Read: [Release & Deployment Guide](octoacme-release-and-deployment.md)*

5. **Close & Retrospective**: Capture learnings and convert them into tracked action items for continuous improvement
   - *Read: [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)*

## Process Overview

### Roles, Responsibilities & Communication

OctoAcme defines four core personas, each with clear ownership and accountability:

- **Project Manager (PM)**: Coordinates delivery, manages schedules, risks, and stakeholder communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, and measures success
- **Developers**: Implement features, collaborate on design and testability, and help identify technical risks
- **QA/Testing**: Validates acceptance criteria and quality standards

Clear ownership is foundational—each project has a named PM and Product Lead. Communication follows a consistent cadence: daily standups (15 min) focus on progress and blockers, weekly delivery syncs show progress and flagged risks, and monthly stakeholder updates provide visibility. Weekly PM-to-Product Lead alignment ensures dependencies and risks stay in sync.

*For detailed role responsibilities, see [OctoAcme Personas](octoacme-roles-and-personas.md)*

### Quality Assurance & Risk Management

Quality is embedded throughout execution:

- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

A **Risk Register** (ID, Description, Impact, Likelihood, Owner, Mitigation, Status) is maintained and reviewed at weekly syncs. Risks are escalated hierarchically—from team triage in standups, to PM escalation to Product Lead, to sponsor-level escalation for business-impacting issues. Blockers are surfaced immediately, and incident response includes triage, root-cause analysis, and blameless retrospectives.

### Workflows & Artifacts

Key workflows include:

- **Project Board**: GitHub Projects with columns spanning Backlog → Ready → In Progress → In Review → QA → Done
- **Pull Requests**: Small PRs (≤400 lines when possible) with issue links, acceptance criteria, and automated CI/CD checks
- **Backlog Items**: Prioritized with acceptance criteria, estimates, owners, and related links
- **Definition of Done**: Ensures consistent quality standards across all deliverables
- **Risk Register**: Tracks and escalates risks throughout the project lifecycle

## Documentation Index

- [OctoAcme Project Management Overview](octoacme-project-management-overview.md) – Principles, roles, artifacts, and communication cadence
- [Project Initiation Guide](octoacme-project-initiation.md) – Validate ideas and authorize work
- [Project Planning](octoacme-project-planning.md) – Create actionable plans and prioritized backlog
- [Execution & Tracking](octoacme-execution-and-tracking.md) – Day-to-day delivery, workflows, and quality standards
- [Risk Management & Communication](octoacme-risks-and-communication.md) – Identify, manage, and escalate risks; communicate status
- [Release & Deployment Guide](octoacme-release-and-deployment.md) – Standardized release procedures and rollback playbook
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) – Run retros and capture learnings
- [OctoAcme Personas](octoacme-roles-and-personas.md) – Role definitions and responsibilities

## Quick Start: Which Doc Should I Read?

- **Starting a new project?** → Read [Project Initiation Guide](octoacme-project-initiation.md)
- **In planning phase?** → Read [Project Planning](octoacme-project-planning.md)
- **Delivering work?** → Read [Execution & Tracking](octoacme-execution-and-tracking.md)
- **Preparing for release?** → Read [Release & Deployment Guide](octoacme-release-and-deployment.md)
- **Running retrospective?** → Read [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- **Understanding roles?** → Read [OctoAcme Personas](octoacme-roles-and-personas.md)
- **Managing risks?** → Read [Risk Management & Communication](octoacme-risks-and-communication.md)

## Key Artifacts & Templates

Throughout the project lifecycle, teams use standardized templates to ensure consistency and quality:

- **Project One-pager**: Used in Initiation to define business case, success metrics, and stakeholders
- **Backlog Item Template**: Used in Planning to structure work with acceptance criteria and estimates
- **Definition of Done**: Used across Execution to ensure quality and consistency
- **Risk Register**: Used throughout to track, assess, and escalate risks
- **Release Notes Template**: Used in Release phase to communicate changes
- **Action Item Template**: Used in Retrospectives to capture and track improvements

## Communication Cadence

- **Daily**: Team standups (15 min focus on progress, blockers, and dependencies)
- **Twice-weekly**: Delivery team syncs (or as agreed by team)
- **Weekly**: PM + PdM sync, Risk review, Status updates
- **Monthly**: Stakeholder updates and business reviews
- **Ad-hoc**: Escalations, incident response, and unplanned communications

## Getting Started

1. **New team member?** Start with this README, then read [OctoAcme Project Management Overview](octoacme-project-management-overview.md) for context on roles and principles.
2. **Joining a project in Initiation?** Read [Project Initiation Guide](octoacme-project-initiation.md) and familiarize yourself with the Project One-pager.
3. **Already executing?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) for daily workflows and quality standards.
4. **Questions about a specific phase?** Use the Quick Start guide above to find the right doc.

---

**Last Updated**: September 2026  
**Maintained By**: OctoAcme Project Management Team
