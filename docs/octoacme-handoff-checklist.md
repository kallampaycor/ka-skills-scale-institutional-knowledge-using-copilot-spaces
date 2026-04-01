# OctoAcme — Cross-Functional Handoff Checklist

## Purpose
Reduce friction and information loss at key transition points between roles and phases. Use the appropriate checklist below when handing off work across functions to ensure the receiving team has everything they need to continue without delay.

---

## 1. Design-to-Dev Handoff

Use this checklist when UX design is ready to hand off to Developers for implementation.

**Owner:** UX Designer  
**Recipient:** Developer(s)

- [ ] Final design files and assets are exported and shared in the agreed location (e.g., Figma link, asset folder)
- [ ] All screens and interaction states are documented (default, hover, active, error, loading, empty)
- [ ] Responsive / breakpoint specifications are included
- [ ] Accessibility requirements are called out (WCAG level, contrast ratios, ARIA notes)
- [ ] Design tokens and component references from the design system are noted
- [ ] Edge cases and out-of-scope items are explicitly marked
- [ ] A design walkthrough session has been scheduled or recorded for the dev team
- [ ] Open design questions or dependencies are logged and assigned
- [ ] Acceptance criteria in the backlog item reflect the design intent
- [ ] UX Designer is available for questions during the implementation sprint

---

## 2. Dev-to-QA Handoff

Use this checklist when a feature or fix is ready to move from development to QA for validation.

**Owner:** Developer  
**Recipient:** QA Automation Specialist

- [ ] All acceptance criteria are met and listed in the PR or linked issue
- [ ] Pull request is merged (or identified branch is stable and deployed to test environment)
- [ ] Test environment is running the correct build version
- [ ] Known limitations or out-of-scope items are documented in the PR
- [ ] New or changed automated tests are included and passing in CI
- [ ] API changes, data migrations, or environment config changes are documented
- [ ] Test data and setup instructions are provided if needed
- [ ] Specific test scenarios or edge cases the developer is uncertain about are flagged for QA focus
- [ ] The developer is available during QA validation for quick clarifications
- [ ] Bug tracking process is confirmed (project tracker, severity definitions)

---

## 3. Pre-Release Readiness Checklist

Use this checklist before any release is promoted to production to confirm all teams are aligned and ready.

**Owner:** Project Manager  
**Contributors:** Developer, DevOps Engineer, QA Automation Specialist, Product Manager (PdM)

### Quality & Code
- [ ] All planned features and fixes are merged and in the release build
- [ ] CI pipeline is passing (tests, linting, security scans)
- [ ] QA sign-off has been received for all in-scope acceptance criteria
- [ ] No open P0/critical defects remain unresolved

### Documentation & Communication
- [ ] Release notes are drafted and reviewed
- [ ] Stakeholder announcement is prepared
- [ ] Any customer-facing documentation is updated
- [ ] Support team is briefed on new or changed behavior

### Infrastructure & Operations
- [ ] Deployment window is scheduled and communicated
- [ ] Infrastructure changes or migrations are tested in staging
- [ ] Rollback plan is documented and tested where applicable
- [ ] Monitoring and alerting thresholds are reviewed and adjusted if needed
- [ ] On-call coverage is confirmed for the deployment window

### Final Sign-offs
- [ ] Project Manager: schedule and scope confirmed
- [ ] Product Manager (PdM): release scope approved
- [ ] DevOps Engineer: deployment plan reviewed and confirmed
- [ ] QA Automation Specialist: quality gate passed

---

## Related Resources
- [Roles & Personas](./octoacme-roles-and-personas.md)
- [RACI Responsibility Matrix](./octoacme-raci-matrix.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
