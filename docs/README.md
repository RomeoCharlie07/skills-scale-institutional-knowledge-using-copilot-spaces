# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management documentation hub. This README provides a concise, onboarding-friendly overview of our project management processes, helping new team members quickly get up to speed with how we run projects.

## Overview

OctoAcme follows a customer-first, iterative delivery approach to project management. Our methodology emphasizes delivering small, testable increments while maintaining clear ownership through named Project Managers and Product Leads. Every project follows a structured lifecycle—from initiation and planning through execution, release, and retrospective—ensuring consistent quality and stakeholder alignment throughout.

Our teams are cross-functional, bringing together developers, product managers, project managers, and QA specialists who collaborate closely using well-defined workflows and communication cadences. We prioritize psychological safety and data-informed decision-making, measuring impact through defined success metrics and iterating based on evidence. Risk management is embedded at every stage, with risks captured in registers and reviewed weekly.

Quality assurance is woven into our process through comprehensive testing strategies including unit tests, integration tests, end-to-end smoke tests, and security scanning in CI. Our PR workflow enforces small, reviewable changes with required approvals, and all work is tracked through project boards with clear acceptance criteria and a Definition of Done. Regular retrospectives ensure we continuously improve our processes and celebrate learnings.

Communication follows a structured cadence—weekly syncs between PM and Product Lead, twice-weekly standups for delivery teams, and monthly stakeholder updates—ensuring everyone stays aligned while minimizing unnecessary meetings. This documentation set provides detailed guidance for each phase of our project lifecycle, enabling teams to deliver consistently and efficiently.

## Core Personas & Roles

| Role | Key Responsibilities |
|------|---------------------|
| **Project Manager (PM)** | Coordinates delivery, manages schedules, risks, and communications; facilitates meetings and ensures documentation |
| **Product Manager (PdM)** | Defines outcomes and success metrics, prioritizes the backlog, validates solutions through user research |
| **Scrum Master** | Facilitates agile ceremonies, removes impediments, coaches on process improvements |
| **Developers** | Design, build, test, and deliver software; participate in code reviews and help identify technical risks |
| **Business Analyst** | Elicits business needs, documents requirements, ensures alignment between stakeholders and technical teams |
| **UX Designer** | Designs user experiences, wireframes, and prototypes to ensure usability and customer value |
| **Technical Writer** | Creates and maintains documentation for internal and external users |
| **QA Lead** | Oversees test strategy, defines acceptance criteria validation, coordinates testing activities |
| **Stakeholders** | Provide inputs, approvals, and business context |

## Key Workflows

### Project Lifecycle

1. **Initiation** — Validate business need, identify stakeholders, define success criteria, and create a Project One-pager
2. **Planning** — Break work into shippable increments, create prioritized backlog, define Definition of Done, and establish release timeline
3. **Execution** — Daily standups, weekly delivery syncs, PR-based development with CI/CD, and regular demos
4. **Release** — Pre-release verification, staging deployment, production release, and stakeholder announcements
5. **Retrospective** — Capture learnings, create actionable improvements, and follow up on previous action items

### Development Workflow

- Use project boards with columns: Backlog → Ready → In Progress → In Review → QA → Done
- Small PRs (≤400 lines when possible) with issue links and acceptance criteria
- Automated tests and linting in CI before requesting review
- At least one approval required before merging

## Communication Cadence

| Frequency | Activity |
|-----------|----------|
| Daily | 15-minute standups focused on progress, blockers, and dependencies |
| Twice Weekly | Team standups (or as agreed) |
| Weekly | PM + Product Lead sync; risk register review; status updates |
| End of Sprint | Demo/Review sessions |
| Monthly | Stakeholder updates |
| As Needed | Ad-hoc escalations and incident communications |

### Escalation Paths

- **Level 1**: Team-level triage in daily standup
- **Level 2**: PM escalates to Product Lead and dependent teams
- **Level 3**: Sponsor-level escalation for business-impacting issues

## Quality Assurance Practices

### Testing Strategy

- **Unit tests** for all new logic
- **Integration tests** where applicable
- **End-to-end smoke tests** for critical flows before release
- **Security scanning** in CI pipeline
- **Manual QA** for feature acceptance when needed

### Definition of Done

Every work item must meet these criteria before being considered complete:
- All acceptance criteria met
- PRs merged with required approvals
- Passing CI (tests, lint, security scans)
- Documentation updated
- Release notes drafted (for releases)

### Pre-Release Checklist

- [ ] All acceptance criteria met and PRs merged
- [ ] Passing CI and security scans
- [ ] Release notes drafted
- [ ] Rollback/mitigation plan documented
- [ ] Smoke tests prepared

## Key Artifacts

- **Project Charter / One-pager** — Problem, goal, success metrics, timeline, and team
- **Roadmap and Release Plan** — Milestones and delivery timeline
- **Sprint/Iteration Backlog** — Prioritized work items with estimates
- **Definition of Done** — Quality criteria for completed work
- **Risk Register** — Tracked risks with owners and mitigation plans
- **Retrospective Notes** — Learnings and action items

## Detailed Documentation

For in-depth guidance on specific topics, see:

- [Project Management Overview](./octoacme-project-management-overview.md) — Principles, roles, and lifecycle
- [Project Initiation](./octoacme-project-initiation.md) — Starting new projects
- [Project Planning](./octoacme-project-planning.md) — Creating actionable plans and backlogs
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Day-to-day delivery management
- [Release & Deployment](./octoacme-release-and-deployment.md) — Production release standards
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Learning and improvement
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Risk tracking and stakeholder updates
- [Roles & Personas](./octoacme-roles-and-personas.md) — Detailed role descriptions
- [Role Handoff Checklist](./octoacme-role-handoff-checklist.md) — Managing role transitions and knowledge transfer
- [Team Member Onboarding](./octoacme-onboarding-checklist.md) — Onboarding new team members

---

> **Tip:** Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context for your project.
