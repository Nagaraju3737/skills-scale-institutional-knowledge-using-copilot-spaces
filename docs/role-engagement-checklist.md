# Role Engagement Checklist

Use this checklist at the start of each project or major initiative to ensure the right roles are engaged at the right time. Work through each section with the relevant leads to confirm coverage and avoid gaps.

---

## Instructions

- Complete this checklist during the **Initiation** and **Planning** phases.
- Revisit at each phase transition to confirm ongoing engagement.
- If a role is not engaged, document the reason in the "Notes" column.
- Store this completed checklist in the project repository alongside the Project Charter.

---

## Section 1 — Core Roles (Required for All Projects)

| Role | Engaged? | Named Individual | Notes |
|------|----------|-----------------|-------|
| Project Manager | ☐ Yes ☐ No | | |
| Product Manager | ☐ Yes ☐ No | | |
| Developer(s) | ☐ Yes ☐ No | | |
| QA/Testing | ☐ Yes ☐ No | | |
| Key Stakeholders identified | ☐ Yes ☐ No | | |

---

## Section 2 — UX Designer Engagement

Engage a UX Designer when any of the following apply:

- ☐ The project includes new or significantly changed user-facing interfaces
- ☐ User research or usability testing is needed to validate the approach
- ☐ Accessibility requirements apply (e.g., WCAG compliance)
- ☐ A design system or component library needs to be updated or created
- ☐ User workflows are complex or span multiple screens/surfaces

**Decision:** ☐ UX Designer required ☐ Not required (reason: _________________________)

| Milestone | UX Designer Involvement | Planned Date | Completed? |
|-----------|------------------------|-------------|------------|
| User research / discovery | Conduct or review research; share findings with team | | ☐ |
| Wireframes and prototypes | Produce designs for high-priority backlog items | | ☐ |
| Design review sign-off | Product Manager approves designs before development starts | | ☐ |
| Implementation review | Review implemented UI against specs; raise discrepancies | | ☐ |
| Pre-release validation | Final sign-off that UI matches approved designs | | ☐ |

---

## Section 3 — DevOps Engineer Engagement

Engage a DevOps Engineer when any of the following apply:

- ☐ New infrastructure, environments, or cloud resources are required
- ☐ CI/CD pipeline changes or new deployment automation is needed
- ☐ The project has non-trivial release, rollback, or environment promotion requirements
- ☐ Operational monitoring, alerting, or SLA/SLO definitions need to be established
- ☐ Container orchestration, secrets management, or IaC changes are involved

**Decision:** ☐ DevOps Engineer required ☐ Not required (reason: _________________________)

| Milestone | DevOps Involvement | Planned Date | Completed? |
|-----------|-------------------|-------------|------------|
| Initiation | Identify infrastructure requirements and platform constraints | | ☐ |
| Planning | Define pipeline tasks, environment provisioning plan, and release approach | | ☐ |
| Execution | Maintain CI/CD; support Developers with environment issues | | ☐ |
| Deployment readiness review | Confirm runbook, rollback plan, and smoke tests | | ☐ |
| Release execution | Execute deployment; monitor post-release; own rollback if needed | | ☐ |

---

## Section 4 — Security Lead Engagement

Engage a Security Lead when any of the following apply:

- ☐ The project handles sensitive, personal, or regulated data
- ☐ New authentication, authorization, or access control mechanisms are introduced
- ☐ External integrations, APIs, or third-party dependencies are added
- ☐ Infrastructure changes could expose new attack surfaces
- ☐ Compliance requirements (e.g., SOC 2, ISO 27001, GDPR) apply to the project
- ☐ The project is customer-facing or internet-accessible

**Decision:** ☐ Security Lead required ☐ Not required (reason: _________________________)

| Milestone | Security Lead Involvement | Planned Date | Completed? |
|-----------|--------------------------|-------------|------------|
| Initiation | Identify security requirements and compliance constraints | | ☐ |
| Planning | Add security acceptance criteria; complete threat model | | ☐ |
| Execution | Review PRs and configurations for security issues | | ☐ |
| Pre-release sign-off | Confirm all critical security findings are resolved | | ☐ |
| Retrospective | Review security findings; propose process improvements | | ☐ |

---

## Section 5 — Data Analyst Engagement

Engage a Data Analyst when any of the following apply:

- ☐ Success metrics or KPIs need to be defined or instrumented
- ☐ The project requires usage tracking, funnel analysis, or A/B testing
- ☐ Existing dashboards or reports need to be updated or created
- ☐ Data-driven prioritization or hypothesis validation is part of the scope
- ☐ Stakeholders require regular data reporting on project outcomes

**Decision:** ☐ Data Analyst required ☐ Not required (reason: _________________________)

| Milestone | Data Analyst Involvement | Planned Date | Completed? |
|-----------|-------------------------|-------------|------------|
| Initiation | Define measurable success criteria and identify data sources | | ☐ |
| Planning | Specify instrumentation requirements as backlog items | | ☐ |
| Execution | Validate instrumentation implementation; monitor early signals | | ☐ |
| Release | Confirm tracking and dashboards are live | | ☐ |
| Retrospective | Present impact measurements and KPI results | | ☐ |

---

## Section 6 — Phase Transition Checklist

Use this checklist to confirm all roles are properly handed off at each project phase transition.

### Initiation → Planning
- ☐ Project charter approved by Sponsor/Stakeholders
- ☐ All required roles identified and named individuals confirmed
- ☐ UX Designer (if required) has completed initial discovery
- ☐ Security Lead (if required) has documented security requirements
- ☐ DevOps Engineer (if required) has identified infrastructure needs
- ☐ Data Analyst (if required) has defined success metrics

### Planning → Execution
- ☐ Backlog is groomed with acceptance criteria for all sprint-1 stories
- ☐ UX Designer (if required) has delivered approved wireframes for sprint-1 features
- ☐ Security threat model (if required) is complete and reviewed
- ☐ DevOps pipeline and environment plan is confirmed
- ☐ Data instrumentation requirements are captured in the backlog
- ☐ QA test plan is created

### Execution → Release
- ☐ All acceptance criteria met and validated by QA
- ☐ UX Designer sign-off on implemented UI (if applicable)
- ☐ Security Lead pre-release sign-off (if applicable)
- ☐ DevOps deployment runbook reviewed and rollback plan confirmed
- ☐ Data Analyst confirms tracking is live (if applicable)
- ☐ Stakeholder communication plan confirmed

### Release → Retrospective
- ☐ Deployment confirmed stable (post-release monitoring period complete)
- ☐ Any post-release incidents documented and resolved
- ☐ All roles invited to retrospective and have prepared contributions

---

## Section 7 — Project Sign-Off

| Role | Sign-Off Required? | Name | Date |
|------|-------------------|------|------|
| Project Manager | ☐ Yes | | |
| Product Manager | ☐ Yes | | |
| UX Designer | ☐ If engaged | | |
| DevOps Engineer | ☐ If engaged | | |
| Security Lead | ☐ If engaged | | |
| Data Analyst | ☐ If engaged | | |

---

*Reference [Roles and Personas](./octoacme-roles-and-personas.md) for full role definitions and [Cross-Functional Collaboration](./octoacme-cross-functional-collaboration.md) for interaction patterns and escalation paths.*
