# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

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

## Product Managers

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

## Project Managers

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

## UX Designer

### Role Summary
UX Designers shape the user experience by translating product goals and user research into intuitive interfaces and interaction patterns. They are involved from requirements gathering through delivery and usability validation.

### Responsibilities
- Create wireframes, prototypes, and user flows to support feature development
- Collaborate with Product Managers (PdM) to clarify and validate requirements
- Conduct usability tests and incorporate feedback into design iterations
- Maintain design systems and accessibility standards
- Support developers during implementation with design intent and asset handoff

### Goals
- Ensure high usability, accessibility, and user satisfaction
- Reduce rework by aligning design direction before development begins
- Represent the user's perspective in product and planning decisions

### Typical Communication
- Design reviews and critique sessions
- Stakeholder and user research demos
- Async comments and annotations in design tools (e.g., Figma)
- Participation in sprint planning and backlog refinement

### Interaction with Existing Roles
- **Product Managers (PdM):** Collaborates closely to translate requirements into design concepts; validates designs against success metrics.
- **Developers:** Provides design specifications and assets; participates in design-to-dev handoff to clarify intent.
- **Project Managers (PM):** Aligns on milestones for design reviews and prototypes; flags design dependencies or blockers.

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain the infrastructure, CI/CD pipelines, and monitoring systems that enable the team to ship reliably and safely. They bridge the gap between development and production operations.

### Responsibilities
- Design, implement, and maintain CI/CD pipelines and deployment automation
- Manage infrastructure provisioning and configuration (IaC)
- Monitor system health, performance, and on-call response
- Enforce security and compliance controls in the delivery pipeline
- Coordinate with the team on release scheduling and deployment windows

### Goals
- Enable fast, safe, and repeatable releases
- Minimize unplanned downtime and mean time to recovery
- Improve observability across services and environments

### Typical Communication
- Deployment status updates and release readiness checks
- Incident reports and post-mortems
- Infrastructure change notifications
- Participation in release planning and retrospectives

### Interaction with Existing Roles
- **Developers:** Partners on build tooling, environment parity, and debugging deployment issues.
- **Project Managers (PM):** Coordinates on release windows, deployment dependencies, and risk mitigations.
- **Product Managers (PdM):** Provides infrastructure and operational constraints to inform release timing and feature flags.

---

## QA Automation Specialist

### Role Summary
QA Automation Specialists design and maintain automated test suites that validate functionality, performance, and regressions across the product lifecycle. They partner with developers to embed quality into the delivery process.

### Responsibilities
- Write, review, and maintain automated tests (unit, integration, end-to-end)
- Integrate testing frameworks and tools into CI/CD workflows
- Triage and track defects found via automated and manual testing
- Define and uphold test coverage standards and quality gates
- Support exploratory testing and contribute to test plans for new features

### Goals
- Improve software reliability and reduce the cost of defects
- Reduce manual test effort through automation coverage
- Provide fast feedback loops to developers and stakeholders

### Typical Communication
- Test plans and coverage reports
- Bug reports and defect triage in the project tracker
- Sprint review feedback on quality signals
- Participation in definition-of-done reviews and release readiness checks

### Interaction with Existing Roles
- **Developers:** Partners on test strategy; reviews code changes for testability; co-owns the CI pipeline quality gates.
- **Project Managers (PM):** Provides quality signal updates; flags when test coverage gaps or defect trends create schedule risk.
- **Product Managers (PdM):** Validates acceptance criteria through automated test scenarios; flags gaps between specs and behavior.

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business objectives and technical solutions. They gather, document, and validate requirements and ensure the delivery team is building the right thing.

### Responsibilities
- Elicit, analyze, and document business and functional requirements
- Map current and future-state processes to identify improvement opportunities
- Facilitate communication between stakeholders and the delivery team
- Manage backlog content and acceptance criteria in partnership with PdM
- Validate delivered functionality against business requirements

### Goals
- Align technical solutions with business needs and maximize value delivered
- Reduce misunderstandings and rework through clear, complete requirements
- Maintain traceability between business objectives and delivered features

### Typical Communication
- Requirements documents, user stories, and process maps
- Backlog refinement sessions and stakeholder workshops
- Acceptance sign-off and change request documentation
- Regular alignment meetings with PM and PdM

### Interaction with Existing Roles
- **Product Managers (PdM):** Co-owns backlog refinement; provides business context to prioritization decisions.
- **Developers:** Clarifies requirements during implementation; validates that solutions meet stated acceptance criteria.
- **Project Managers (PM):** Flags requirements gaps or scope changes that affect timeline or risk.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [RACI Responsibility Matrix](./octoacme-raci-matrix.md) for an overview of who owns or contributes to each lifecycle phase.
- See [Cross-Functional Handoff Checklist](./octoacme-handoff-checklist.md) for templates covering design-to-dev, dev-to-QA, and pre-release transitions.

