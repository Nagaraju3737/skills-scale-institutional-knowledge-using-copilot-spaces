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
UX Designers are responsible for end-user experience design, prototyping, and usability validation. They translate user needs and product requirements into intuitive, accessible interfaces. UX Designers collaborate closely with Product Managers and Developers to ensure delivered features meet user expectations.

### Responsibilities
- Conduct user research and usability testing to inform design decisions
- Create wireframes, prototypes, and high-fidelity mockups
- Define and maintain design standards, patterns, and component libraries
- Review implemented features against design specifications
- Advocate for accessibility and inclusive design practices

### Goals
- Reduce user friction and improve product usability
- Ensure consistent, accessible user experience across all features
- Validate designs with real users before and after implementation

### Typical Communication
- Design reviews with Product Managers during planning and backlog refinement
- Handoff sessions with Developers before and during implementation
- Usability test readouts shared with Product Managers and stakeholders
- Participation in sprint reviews to evaluate implemented UI

### Integration into the Project Lifecycle
- **Initiation**: Contributes user research insights to the problem statement
- **Planning**: Produces wireframes and prototypes for backlog items
- **Execution**: Partners with Developers on design implementation; reviews PRs for UI accuracy
- **Release**: Validates final UI against design specs; contributes to acceptance criteria
- **Retrospective**: Shares user feedback and usability findings for continuous improvement

---

## DevOps Engineer

### Role Summary
DevOps Engineers manage CI/CD pipelines, deployment automation, and operational monitoring. They bridge the gap between development and operations to ensure reliable, repeatable delivery. DevOps Engineers work closely with Developers and Project Managers to maintain platform stability and accelerate release cycles.

### Responsibilities
- Design, implement, and maintain CI/CD pipelines and deployment automation
- Manage infrastructure-as-code and cloud environment configurations
- Monitor system health, availability, and performance
- Define and enforce environment promotion and release gates
- Collaborate on incident response, root cause analysis, and remediation

### Goals
- Enable fast, reliable, and repeatable deployments
- Reduce mean time to recovery (MTTR) for production incidents
- Maintain high system availability and operational observability

### Typical Communication
- Deployment readiness checks with Project Managers ahead of releases
- Infrastructure reviews and pipeline updates with Developers
- Incident notifications and post-mortems with the broader delivery team
- Participation in release planning and go/no-go discussions

### Integration into the Project Lifecycle
- **Initiation**: Advises on infrastructure requirements and platform constraints
- **Planning**: Identifies DevOps tasks (pipeline updates, environment provisioning) for the project plan
- **Execution**: Maintains CI/CD pipelines; supports Developers with environment issues
- **Release**: Executes and monitors deployments; owns rollback procedures
- **Retrospective**: Reviews deployment metrics and proposes automation improvements

---

## Security Lead

### Role Summary
Security Leads conduct threat modeling, review code and configurations for security risks, and establish security policies and best practices. They ensure that security is a first-class concern throughout the project lifecycle. Security Leads coordinate with Developers and Project Managers to integrate security into delivery workflows.

### Responsibilities
- Perform threat modeling and security risk assessments for new features
- Review code, infrastructure configurations, and third-party dependencies for vulnerabilities
- Define and maintain security standards, policies, and guidelines
- Integrate security scanning and testing into CI/CD pipelines
- Track and drive remediation of identified security findings

### Goals
- Proactively identify and mitigate security risks before they reach production
- Embed security practices into the development workflow (shift-left security)
- Ensure compliance with applicable security policies and regulations

### Typical Communication
- Security reviews with Developers during design and implementation phases
- Risk briefings with Project Managers when high-severity issues are identified
- Security policy updates communicated to the full delivery team
- Participation in release go/no-go reviews to confirm security sign-off

### Integration into the Project Lifecycle
- **Initiation**: Identifies security requirements and regulatory constraints early
- **Planning**: Contributes security-related acceptance criteria and tasks to the backlog
- **Execution**: Reviews PRs for security issues; validates security controls are implemented correctly
- **Release**: Provides security sign-off as part of the pre-release checklist
- **Retrospective**: Reviews security findings and proposes process improvements

---

## Data Analyst

### Role Summary
Data Analysts track metrics, provide data-driven insights, and help teams make informed decisions. They translate raw data into actionable intelligence that guides product strategy and project outcomes. Data Analysts interact closely with Product Managers and stakeholders to ensure KPIs are defined, measured, and interpreted correctly.

### Responsibilities
- Define, instrument, and monitor key performance indicators (KPIs) and success metrics
- Analyze product usage data and surface insights to inform prioritization
- Build and maintain dashboards and reports for stakeholders and the delivery team
- Partner with Product Managers to validate hypotheses through data
- Identify data quality issues and work with Developers to address instrumentation gaps

### Goals
- Enable data-informed decision-making across all project phases
- Ensure that success metrics are measurable, tracked, and acted upon
- Surface early signals of issues or opportunities from product data

### Typical Communication
- Regular metric reviews with Product Managers and stakeholders
- Data requirements shared with Developers for instrumentation work
- Dashboard updates and insight reports distributed to the broader team
- Participation in retrospectives to present impact measurements

### Integration into the Project Lifecycle
- **Initiation**: Helps define measurable success criteria for the project
- **Planning**: Specifies data instrumentation requirements as backlog items
- **Execution**: Validates that instrumentation is implemented correctly; monitors early data signals
- **Release**: Confirms tracking and dashboards are live before or at release
- **Retrospective**: Presents outcome data and impact measurements to inform future decisions

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

