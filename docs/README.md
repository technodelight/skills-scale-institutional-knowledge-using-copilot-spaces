# OctoAcme Project Management Docs

Welcome! This README provides an overview of the project management processes used by OctoAcme, with direct links to detailed documentation.

## Project Management Process Summary

OctoAcme uses an iterative, customer-first approach to project management that emphasizes clear ownership, data-driven decisions, and psychological safety. All projects follow a consistent lifecycle:

### Core Principles
- **Customer-first:** Prioritize customer value and usability in all decisions
- **Iterative delivery:** Deliver small, testable increments rather than monolithic releases
- **Clear ownership:** Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions:** Measure impact and iterate based on evidence
- **Psychological safety:** Encourage feedback, learning, and continuous improvement

### Project Lifecycle

1. **Initiation:** Define the problem statement, identify stakeholders, establish success metrics, and confirm business need. This phase produces a lightweight Project One-pager and goes through a decision gate before moving to planning.

2. **Planning:** Break down approved work into shippable increments, estimate scope, identify dependencies and risks, define acceptance criteria, and create a prioritized backlog and release plan.

3. **Execution & Tracking:** Execute daily standups, maintain an agile project board (Backlog → Ready → In Progress → In Review → QA → Done), run automated CI/CD, conduct code reviews, and track progress toward milestones with weekly delivery syncs.

4. **Release & Deployment:** Follow standardized pre-release requirements, deploy to staging with smoke tests, deploy to production via automated pipeline, and prepare rollback plans for critical issues.

5. **Retrospective & Continuous Improvement:** After each sprint or milestone, capture learnings, identify 2–3 actionable improvements, assign owners and due dates, and track impact over time.

### Key Roles
- **Project Manager (PM):** Coordinates delivery, schedules, risks, and communications
- **Product Manager (PdM):** Defines outcomes, prioritizes backlog, and measures success
- **Developers:** Implement features, collaborate on design, and ensure code quality
- **QA/Testing:** Validates quality and acceptance criteria
- **Stakeholders:** Provide inputs, approvals, and business context

### Communication Cadence
- **Daily standups** (15 min) – focus on progress, blockers, dependencies
- **Weekly PM + PdM sync** – alignment and decision-making
- **Weekly delivery sync** – show progress, updates, and flagged risks
- **Twice-weekly standups** (or as agreed) – for delivery team
- **Monthly stakeholder updates** – status and milestones
- **Ad-hoc escalations** – as needed for blockers or risks

---

## Process Documents

Detailed guidance for each phase and aspect of project management:

### Overview & Foundations
- **[Project Management Overview](./octoacme-project-management-overview.md)** – Introduction to OctoAcme's approach, roles, artifacts, and lifecycle

### Project Phases
- **[Project Initiation Guide](./octoacme-project-initiation.md)** – How to validate ideas, align stakeholders, and create a Project One-pager
- **[Project Planning](./octoacme-project-planning.md)** – Breaking down work, estimating, identifying risks, and creating a release plan
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** – Day-to-day execution, project boards, PR workflow, quality standards, and metrics
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** – Release types, pre-release requirements, deployment checklists, and rollback procedures
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** – Running retrospectives, capturing learnings, and tracking action items

### Cross-Cutting Topics
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** – Risk registers, escalation paths, stakeholder communication templates, and incident playbooks
- **[Roles & Personas](./octoacme-roles-and-personas.md)** – Detailed descriptions of Developer, Product Manager, and Project Manager roles and responsibilities

---

## How to Use These Docs

1. **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) for a high-level introduction.
2. **Starting a new project?** Follow the [Initiation Guide](./octoacme-project-initiation.md) → [Planning](./octoacme-project-planning.md) path.
3. **In execution mode?** Reference [Execution & Tracking](./octoacme-execution-and-tracking.md) and [Risk Management & Communication](./octoacme-risks-and-communication.md).
4. **Preparing for release?** Use [Release & Deployment](./octoacme-release-and-deployment.md).
5. **Wrapping up?** Conduct a [Retrospective](./octoacme-retrospective-and-continuous-improvement.md) to capture learnings.

---

## Contributing to These Docs

To propose updates, clarifications, or new content to the project management process docs:

1. Open a new issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template
2. Provide a summary of the update, rationale, and suggested content
3. Work with your team and PM to validate the proposal
4. Submit a pull request with the changes linked to the issue

Our goal is to keep these docs accurate, clear, and useful for the entire team. Your feedback and contributions are welcome!
