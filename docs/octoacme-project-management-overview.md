# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles

### Foundational Roles (all projects)
- **Project Manager (PM)**: coordinates delivery, schedules, risk, communications.
- **Product Manager (PdM)**: defines outcomes, prioritizes backlog, and measures success.
- **Developers**: implement features, collaborate on design and testability.
- **QA/Testing**: validate quality and acceptance criteria.
- **Stakeholders**: provide inputs and approvals.

### Specialized Roles (engage as needed)
- **UX Designer**: responsible for end-user experience design, prototyping, and usability validation. Engage when features have significant user-interface or user-experience impact.
- **DevOps Engineer**: manages CI/CD pipelines, deployment automation, and operational monitoring. Engage at project kickoff for infrastructure planning and throughout execution and release.
- **Security Lead**: conducts threat modeling, reviews code and configurations for security risks, and establishes security policies. Engage during planning to set security requirements and during execution for reviews and sign-off.
- **Data Analyst**: tracks metrics, provides data-driven insights, and helps teams make informed decisions. Engage during initiation to define success metrics and during execution to validate instrumentation.

See [Roles and Personas](./octoacme-roles-and-personas.md) for full role definitions and [Cross-Functional Collaboration](./octoacme-cross-functional-collaboration.md) for interaction patterns and RACI guidance. Use the [Role Engagement Checklist](./role-engagement-checklist.md) to determine when to involve specialized roles.

## Key Artifacts
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Lifecycle (high-level)
1. Initiation: problem statement, stakeholders, high-level timeline.
2. Planning: scope, resources, milestones, dependencies.
3. Execution: build, test, review, iterate.
4. Release: deploy, verify, announce.
5. Close & Retrospective: capture learnings and next steps.

## Communication Cadence
- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
