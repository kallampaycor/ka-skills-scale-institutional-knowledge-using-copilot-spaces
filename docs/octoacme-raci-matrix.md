# OctoAcme — RACI Responsibility Matrix

## Purpose
Provide a concise reference for who is **Responsible**, **Accountable**, **Consulted**, or **Informed** for each major activity across the OctoAcme project lifecycle. Use this matrix to set expectations, resolve ambiguity, and support onboarding.

## Key

| Letter | Meaning |
|--------|---------|
| **R** | Responsible — does the work |
| **A** | Accountable — owns the outcome and has final sign-off |
| **C** | Consulted — provides input before/during the activity |
| **I** | Informed — kept up to date on decisions and outcomes |

## Roles

| Abbreviation | Role |
|---|---|
| PM | Project Manager |
| PdM | Product Manager |
| Dev | Developer |
| UX | UX Designer |
| DevOps | DevOps Engineer |
| QA | QA Automation Specialist |
| BA | Business Analyst |

---

## Responsibility Matrix

| Lifecycle Activity | PM | PdM | Dev | UX | DevOps | QA | BA |
|---|---|---|---|---|---|---|---|
| **Initiation** | | | | | | | |
| Define business problem & success criteria | C | A | I | C | I | I | R |
| Stakeholder identification & engagement | A | C | I | I | I | I | R |
| Project one-pager / charter sign-off | R | C | I | I | I | I | C |
| Initial risk identification | A | C | C | C | C | C | R |
| **Planning** | | | | | | | |
| Backlog creation & prioritization | C | A | C | C | I | C | R |
| Sprint / milestone planning | A | C | R | C | C | C | C |
| Acceptance criteria definition | C | A | C | R | I | C | R |
| Design & UX prototyping | I | C | C | A | I | I | C |
| Test strategy & plan | C | I | C | I | C | A | C |
| Infrastructure & environment planning | C | I | C | I | A | C | I |
| **Execution & Tracking** | | | | | | | |
| Feature implementation | I | C | A | C | C | C | C |
| Design-to-dev handoff | I | C | R | A | I | I | C |
| Code review & quality gates | I | I | A | I | C | R | I |
| Automated test execution & coverage | I | I | C | I | C | A | I |
| Daily standup facilitation | A | I | R | R | R | R | R |
| Risk register updates | A | C | C | C | C | C | C |
| Blocker escalation | A | C | C | I | C | C | C |
| **Risk & Communication** | | | | | | | |
| Weekly stakeholder status update | A | C | I | I | I | I | C |
| Incident communication | C | I | C | I | A | C | I |
| Risk mitigation planning | A | C | C | C | C | C | R |
| **Release & Deployment** | | | | | | | |
| Release readiness sign-off | A | C | C | I | R | R | C |
| Deployment execution | I | I | C | I | A | C | I |
| Dev-to-QA handoff | C | I | R | I | C | A | I |
| Post-deploy verification | C | I | C | I | R | R | I |
| Release announcement | A | C | I | I | I | I | I |
| **Retrospective & Continuous Improvement** | | | | | | | |
| Retro facilitation | A | C | R | R | R | R | R |
| Action item tracking | A | C | R | R | R | R | R |
| Process improvement proposals | C | C | C | C | C | C | A |

---

## Notes
- When a cell is blank, the role has no formal obligation for that activity but may participate situationally.
- This matrix is a guide, not a strict governance document. Teams should adapt it to their project context.
- For detailed handoff steps between roles, see the [Cross-Functional Handoff Checklist](./octoacme-handoff-checklist.md).
- For role definitions, see [Roles & Personas](./octoacme-roles-and-personas.md).
