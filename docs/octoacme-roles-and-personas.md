# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

Use it to:
- clarify ownership and reduce ambiguity across cross-functional work
- speed up onboarding by making responsibilities explicit
- make handoffs and escalations predictable (especially during release/incident scenarios)

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers (PdM)

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers (PM)

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA / Test Engineer

### Role Summary
QA/Test Engineers validate that delivered functionality meets acceptance criteria and quality expectations. They help define test approaches early to reduce defects and rework.

### Responsibilities
- Define and execute test plans (manual and automated where applicable)
- Validate acceptance criteria with PdM and PM
- Identify quality risks and advise on release readiness
- Help reproduce, triage, and verify bug fixes

### Goals
- Reduce escaped defects
- Improve confidence in releases
- Enable fast feedback loops through clear acceptance criteria and test strategy

### Typical Communication
- Test plans and QA status updates
- Bug reports and reproduction steps
- Release readiness and sign-off notes (as agreed)

### Interactions with existing roles
- Works with PdM to clarify acceptance criteria and edge cases
- Works with Developers to make features testable and to verify fixes
- Works with PM to align test scope with timelines and risk tolerance

---

## Engineering Manager (EM)

### Role Summary
Engineering Managers ensure the team is staffed, supported, and able to deliver sustainably. They partner with PM/PdM on scope, sequencing, and risk trade-offs.

### Responsibilities
- Ensure staffing, capacity planning, and sustainable delivery
- Provide technical leadership support (often via Tech Lead) and escalation path
- Coach engineers; support hiring and onboarding
- Partner with PM/PdM on prioritization trade-offs and delivery risk

### Goals
- High-performing, healthy engineering team
- Predictable delivery and reduced burn-out
- Strong engineering practices and quality culture

### Typical Communication
- Capacity and staffing discussions
- Escalations on delivery risk or resourcing constraints
- Alignment on engineering standards and quality gates

### Interactions with existing roles
- Works with PM on capacity, milestones, and risk management
- Works with PdM to balance scope vs. feasibility and timelines
- Supports Developers by removing organizational blockers

---

## Tech Lead (TL) / Architect

### Role Summary
Tech Leads provide technical direction, ensure architectural coherence, and reduce long-term risk. They guide design decisions and drive implementation standards.

### Responsibilities
- Lead technical design, architecture, and key trade-off decisions
- Ensure non-functional requirements (security, performance, reliability) are addressed
- Define and maintain technical standards and guardrails
- Mentor developers and coordinate complex cross-team integrations

### Goals
- Maintainable, scalable, reliable systems
- Reduced technical risk and rework
- Clear technical direction and decision-making

### Typical Communication
- Architecture/design docs and reviews
- Technical spikes and proof-of-concept outcomes
- Cross-team technical syncs

### Interactions with existing roles
- Partners with PdM to translate outcomes into feasible technical scope
- Partners with PM to surface technical risks, sequencing constraints, and dependencies
- Guides Developers through design reviews and implementation approach

---

## Scrum Master / Delivery Lead (Agile Coach)

### Role Summary
The Scrum Master/Delivery Lead facilitates delivery ceremonies, helps remove blockers, and improves team flow. This role complements (not replaces) PM responsibilities; the exact split varies by team.

### Responsibilities
- Facilitate team rhythm (standups, planning, review, retro)
- Identify and remove impediments; improve throughput
- Coach the team on delivery best practices and continuous improvement
- Help ensure work is “ready” before starting (clear AC, dependencies, owners)

### Goals
- Reduced cycle time and fewer blocked items
- Healthy iteration cadence and predictable delivery
- Continuous improvement that sticks (action items tracked to completion)

### Typical Communication
- Facilitated ceremonies and follow-ups
- Blocker tracking and escalation support
- Improvement experiments and results

### Interactions with existing roles
- Works with PM to manage delivery risks and coordination
- Works with PdM to ensure backlog readiness and clear acceptance criteria
- Works with Developers/QA to keep work flowing and reduce context switching

---

## UX / Product Designer

### Role Summary
Designers ensure solutions are usable, accessible, and aligned with customer needs. They collaborate with PdM and engineering from discovery through validation.

### Responsibilities
- Conduct/participate in user research and synthesis
- Create flows, wireframes, prototypes, and design specs
- Define UX acceptance criteria (accessibility, usability)
- Validate designs through testing and iterate based on feedback

### Goals
- Improve usability, conversion, and user satisfaction
- Reduce rework by clarifying interaction details early
- Ensure accessibility and consistency with design system

### Typical Communication
- Design reviews and prototypes
- UX acceptance criteria in backlog items
- Collaboration with QA on UX verification

### Interactions with existing roles
- Partners with PdM to define problem, users, and success metrics
- Partners with Developers/TL to ensure feasibility and implementation details
- Partners with QA to validate UX acceptance and accessibility checks

---

## Business Analyst (BA)

### Role Summary
Business Analysts translate business needs into detailed requirements and help ensure solutions meet business rules and operational constraints.

### Responsibilities
- Elicit and document business requirements and workflows
- Define business rules, edge cases, and data mapping
- Support acceptance criteria definition and test scenario creation
- Validate outcomes with stakeholders and operations where applicable

### Goals
- Reduce ambiguity and rework due to unclear requirements
- Ensure operational fit and correct business behavior
- Increase alignment across stakeholders and delivery team

### Typical Communication
- Requirements docs and process flows
- Stakeholder workshops and requirement reviews
- Clarifications and Q&A during execution

### Interactions with existing roles
- Works with PdM to refine scope and acceptance criteria
- Works with Developers/QA to ensure business rules are implemented/tested correctly
- Works with PM to identify stakeholder dependencies and review timelines

---

## Technical Writer / Documentation Owner

### Role Summary
Technical Writers keep user and internal documentation accurate, usable, and aligned with releases. They reduce support burden by ensuring docs ship with product changes.

### Responsibilities
- Create/maintain end-user docs, internal runbooks, and release notes inputs
- Define documentation acceptance criteria for features
- Validate docs accuracy with engineering and product
- Ensure docs updates are included in the Definition of Done when required

### Goals
- Reduce user confusion and support tickets
- Ensure documentation stays in sync with product
- Improve onboarding and operational readiness

### Typical Communication
- Docs PRs and review comments
- Release readiness checks and doc status updates
- Collaboration with Support/CS on frequently asked questions

### Interactions with existing roles
- Works with PdM to understand target users and messaging
- Works with Developers/QA to validate behavior and screenshots/steps
- Works with PM to ensure docs are planned and tracked like deliverables

---

## Support / Customer Success / On-call

### Role Summary
Support/CS represents customer reality and production signals. They handle incidents, feed recurring pain points into the backlog, and help ensure releases are operable.

### Responsibilities
- Triage customer issues and manage incident communications (as agreed)
- Provide feedback on top user pain points and product gaps
- Validate operational readiness (runbooks, alerts, known issues)
- Coordinate escalations with engineering during incidents

### Goals
- Fast time-to-triage and resolution
- Fewer repeat incidents and improved customer experience
- Clear expectations and communication during outages

### Typical Communication
- Incident channels and post-incident summaries
- Release announcements and known issues
- Support ticket trends and feedback reports

### Interactions with existing roles
- Works with Developers/QA to reproduce issues and verify fixes
- Works with PdM to prioritize fixes/improvements based on impact
- Works with PM to manage stakeholder communications during incidents/releases

---

## Security / Privacy Representative

### Role Summary
Security/Privacy ensures solutions meet security and compliance expectations, and that security incidents follow a predictable runbook.

### Responsibilities
- Perform/advise on threat modeling and security reviews
- Ensure secure defaults, secrets handling, and vulnerability management
- Define security acceptance criteria (as needed)
- Coordinate security incident response and post-incident actions

### Goals
- Reduce security risk and prevent incidents
- Improve response quality when incidents occur
- Ensure compliance and appropriate data handling

### Typical Communication
- Security review notes and sign-offs (as needed)
- Vulnerability reports and remediation tracking
- Incident response coordination

### Interactions with existing roles
- Works with TL/Developers to address security design and implementation
- Works with PM to align security reviews with project timelines
- Works with Support/On-call during security incidents and communications

---

## Data / Analytics Partner

### Role Summary
Data/Analytics helps define measurable outcomes, instrumentation, and reporting so product decisions are evidence-based.

### Responsibilities
- Help define success metrics and measurement strategy
- Define instrumentation requirements (events, dashboards, funnels)
- Validate tracking is correct and trustworthy
- Provide analysis and insights post-release

### Goals
- Reliable measurement for decision-making
- Faster learning cycles after releases
- Reduced ambiguity around “did it work?”

### Typical Communication
- Metric definitions and dashboard links
- Instrumentation reviews
- Post-release analysis summaries

### Interactions with existing roles
- Works with PdM to define outcomes and metrics
- Works with Developers/TL to implement instrumentation
- Works with PM to include measurement tasks in scope and milestones

---

## Interaction matrix (high-level)
Use this as a quick “who partners with whom” reference across the lifecycle.

### Initiation
- PM + PdM: align scope, stakeholders, timeline, success metrics
- PdM + Design + Data: validate problem and define measurable outcomes
- PM + EM/TL: confirm capacity and feasibility risks
- Security (as needed): early risk assessment for sensitive areas

### Planning
- PdM + BA: refine requirements, edge cases, acceptance criteria
- PM + TL/EM: sequence milestones, dependencies, and staffing
- QA + Developers: define test approach; clarify acceptance criteria
- Tech Writer: identify docs deliverables; add to plan/DoD
- Support/CS: surface operational needs and common failure modes

### Execution
- Developers + TL: design reviews and implementation guidance
- PM + Scrum Master: unblock work; keep cadence; manage delivery risks
- QA + Developers: continuous testing, bug triage, verification
- PdM + Design: validate incrementally; adjust scope if needed

### Release
- PM + Support/On-call: comms plan and release readiness
- Developers + QA: smoke tests and verification
- Security (as needed): final checks or incident readiness
- Tech Writer: ensure docs/release notes are ready

### Retrospective
- Scrum Master/PM: run retro and track action items
- EM/TL: address systemic engineering/process improvements
- PdM: evaluate outcome vs metrics; feed learnings into roadmap

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.