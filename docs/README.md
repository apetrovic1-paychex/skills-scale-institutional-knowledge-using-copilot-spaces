# OctoAcme Project Management Docs

## Overview

This README provides a central entry point to the OctoAcme project management documentation set. OctoAcme uses a lightweight, structured project management approach that emphasizes clear ownership, iterative delivery, documented planning, regular execution tracking, proactive risk management, disciplined release practices, and continuous improvement.

## Project Management Process Summary

OctoAcme follows a structured, lifecycle-based approach to project management grounded in five core principles: customer-first prioritization, iterative delivery, clear ownership, data-informed decisions, and psychological safety. The project lifecycle spans five distinct phases—initiation, planning, execution, release, and closure with retrospective—each with defined deliverables and decision gates. Projects are led by a Project Manager (PM) who coordinates delivery and risk management, and a Product Manager (PdM) who defines outcomes and measures success. During **Initiation**, teams validate business need by creating a lightweight One-pager that captures the problem statement, success metrics, stakeholders, timeline, and initial risks. A decision gate ensures stakeholder alignment before proceeding to Planning, where the team breaks work into prioritized backlog items, estimates scope, defines acceptance criteria and a Definition of Done, and identifies cross-team dependencies and risks.

**Execution and Tracking** is driven by a consistent team rhythm: daily standups (15 minutes), weekly delivery syncs, and sprint/milestone-based demos. Work flows through a project board with columns (Backlog, Ready, In Progress, In Review, QA, Done), and Pull Requests are kept small (≤400 lines where possible) with automated testing, linting, and at least one approval required before merge. Quality is enforced through unit tests, integration tests, end-to-end smoke tests, security scanning, and manual QA for feature acceptance. **Risk and Communication** are managed through a Risk Register that tracks impact, probability, owner, and mitigation for each identified risk, reviewed weekly during syncs. Stakeholders receive regular updates via a standardized Weekly Status template covering progress, next steps, risks, and decisions needed. Escalation follows a clear path: team triage → PM → Product Lead → Sponsor, with ad-hoc incident communication for critical issues.

Finally, **Release and Deployment** follows a pre-release checklist ensuring all acceptance criteria are met, CI passes, security scans complete, smoke tests are prepared, and a rollback plan is documented. Releases are announced to stakeholders and support, and a post-incident blameless retrospective is conducted if issues arise. After each sprint, release, or milestone, **Retrospectives** capture what went well, what could improve, and generate 2–3 prioritized action items with clear owners and due dates. This structured, transparent approach reduces single-person dependency risk, enables consistent execution, and creates a living feedback loop where validated improvements are fed back into the documentation.

## Documentation Links

- [OctoAcme — Project Management Overview](./octoacme-project-management-overview.md)
- [OctoAcme — Project Initiation Guide](./octoacme-project-initiation.md)
- [OctoAcme — Project Planning](./octoacme-project-planning.md)
- [OctoAcme — Execution & Tracking](./octoacme-execution-and-tracking.md)
- [OctoAcme — Risk Management & Communication](./octoacme-risks-and-communication.md)
- [OctoAcme — Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [OctoAcme — Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [OctoAcme Personas](./octoacme-roles-and-personas.md)

## How to Use These Docs

- **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) to understand core roles, principles, and the project lifecycle.
- **Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md) to validate the business need and align stakeholders.
- **Planning a project?** Use the [Project Planning](./octoacme-project-planning.md) guide to scope work, estimate, and identify dependencies.
- **Executing and tracking?** Refer to [Execution & Tracking](./octoacme-execution-and-tracking.md) for team rhythms, PR workflows, and quality standards.
- **Managing risks and stakeholders?** Consult [Risk Management & Communication](./octoacme-risks-and-communication.md) for escalation paths and status reporting.
- **Preparing a release?** Follow the [Release & Deployment Guide](./octoacme-release-and-deployment.md) for pre-release checklists and rollback procedures.
- **Conducting a retrospective?** See [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) to capture learnings and generate action items.
- **Understanding roles?** Review [OctoAcme Personas](./octoacme-roles-and-personas.md) for detailed role descriptions and responsibilities.
