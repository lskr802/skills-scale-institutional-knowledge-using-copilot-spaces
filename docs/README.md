# OctoAcme Program Process Docs

This `docs/` folder is the source of truth for OctoAcme’s project management processes. OctoAcme runs work through a lightweight lifecycle that emphasizes clear ownership, iterative delivery, and measurable outcomes: **Initiation → Planning → Execution & Tracking → Release & Deployment → Retrospective & Continuous Improvement**. Projects start with a simple one-pager/charter to confirm the business need, success metrics, stakeholders, an initial timeline, and key risks before moving into detailed planning.

Roles are intentionally explicit to keep decisions and delivery unblocked. A **Project Manager (PM)** coordinates delivery (planning, schedules, risks, and communications) while a **Product Manager / Product Lead (PdM)** owns outcomes (problem definition, prioritization, and success measurement). **Developers** design and implement shippable increments with testability in mind; **QA/Testing** validates quality and acceptance criteria; and **Stakeholders** provide inputs and approvals at key decision points.

Communication follows a predictable cadence and is backed by transparent artifacts. Teams maintain a project board (e.g., GitHub Projects) and use recurring touchpoints (daily standups, weekly delivery syncs, demos/reviews) plus periodic stakeholder updates. Risks and dependencies are tracked via a simple risk register and escalated through a defined path (**team → PM → Product Lead → sponsor**) to keep delivery moving and decision-making timely.

Quality assurance is embedded throughout execution and release. OctoAcme favors small pull requests, clear acceptance criteria, CI checks (tests/lint/security scans), and at least one approval before merge (per team policy). Testing includes unit, integration (where applicable), and end-to-end smoke tests for critical flows, complemented by manual QA when needed. Releases use a consistent checklist (release notes, rollback/mitigation planning, staged verification) and incidents trigger structured communication and a blameless retrospective to drive continuous improvement.

## Key Process Documents

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)
