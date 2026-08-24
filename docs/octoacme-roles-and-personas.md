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

## Engineering Lead / Technical Lead

### Role Summary
Engineering Leads own technical direction for the solution and help the team make sound architecture, implementation, and risk decisions.

### Responsibilities
- Define technical approach, architecture decisions, and engineering standards
- Guide Developers through implementation trade-offs, code reviews, and technical blockers
- Identify technical risks, dependencies, operational constraints, and mitigation options
- Partner with QA/Testing on testability, quality gates, and defect triage

### Goals / Decision Rights
- Decide or recommend technical approaches within agreed product scope
- Escalate feasibility, performance, reliability, or maintainability risks early
- Ensure technical handoffs and operational readiness are clear before release

### Key Interactions
- Works with Developers on implementation details, code quality, and technical debt
- Advises Product Managers on feasibility, scope trade-offs, and sequencing
- Supports Project Managers with estimates, dependency mapping, milestone risks, and escalations
- Engages stakeholders when technical decisions affect commitments, integrations, or support expectations

---

## UX/Product Designer

### Role Summary
UX/Product Designers define user flows, interaction designs, and usability considerations that help the team deliver customer-centered outcomes.

### Responsibilities
- Create workflows, wireframes, prototypes, or design specifications as needed
- Validate designs with users, customers, support teams, or stakeholders
- Clarify usability acceptance criteria and edge cases
- Partner with QA/Testing to confirm usability coverage and customer-facing behavior

### Goals / Decision Rights
- Own design recommendations for user experience within product goals and constraints
- Identify usability risks and handoff requirements before development starts
- Confirm design readiness for implementation and review deviations during execution

### Key Interactions
- Partners with Product Managers on customer outcomes, problem definition, and acceptance criteria
- Collaborates with Developers on feasibility, accessibility, and implementation details
- Coordinates with Project Managers on design milestones, dependencies, and stakeholder reviews
- Brings stakeholder and customer feedback into planning, demos, and retrospectives

---

## Business Analyst or Product Operations Partner

### Role Summary
Business Analysts or Product Operations Partners translate stakeholder needs into clear requirements, workflows, and measurable outcomes.

### Responsibilities
- Document requirements, business rules, workflows, and acceptance criteria
- Maintain traceability from problem statements through delivery and validation
- Clarify scope, dependencies, handoffs, and open decisions
- Support QA/Testing with test scenarios, data needs, and requirement validation

### Goals / Decision Rights
- Recommend requirement interpretations and identify gaps or conflicts
- Ensure decisions, owners, and handoffs are explicit across the lifecycle
- Escalate unclear scope, duplicated effort, or stakeholder misalignment

### Key Interactions
- Works with Product Managers on prioritization, success metrics, and scope boundaries
- Helps Developers and QA/Testing understand requirements and expected outcomes
- Supports Project Managers with planning inputs, risk tracking, and decision logs
- Coordinates with stakeholders to confirm requirements, approvals, and communication needs

---

## Release / DevOps / Site Reliability Engineer

### Role Summary
Release, DevOps, or Site Reliability Engineers own deployment readiness, operational controls, observability, and rollback preparedness.

### Responsibilities
- Maintain deployment automation, environments, release controls, and operational runbooks
- Confirm observability, alerting, smoke tests, and rollback or mitigation plans
- Coordinate release validation with Developers and QA/Testing
- Prepare support and stakeholder communications for operational readiness

### Goals / Decision Rights
- Recommend go/no-go readiness based on deployment, reliability, and operational risk
- Own release execution plans and escalation paths for deployment or production issues
- Ensure release handoffs include monitoring, support, and incident response expectations

### Key Interactions
- Works with Developers on build, deployment, telemetry, and incident remediation
- Advises Product Managers on release constraints, rollout options, and customer-impacting risks
- Coordinates with Project Managers on release milestones, dependencies, and risk status
- Engages QA/Testing, support, and stakeholders during pre-release validation and post-deploy verification

---

## Customer or Support Representative

### Role Summary
Customer or Support Representatives bring customer needs, support trends, adoption concerns, and feedback into planning and validation.

### Responsibilities
- Share customer issues, support themes, and adoption risks with the delivery team
- Help reproduce customer-reported issues and validate customer-facing outcomes
- Prepare support readiness inputs such as known issues, FAQs, or release notes feedback
- Represent customer impact during prioritization, escalation, and retrospectives

### Goals / Decision Rights
- Recommend priority adjustments based on customer impact and support burden
- Confirm whether planned communications and support materials meet customer needs
- Escalate urgent customer-impacting issues through the agreed communication path

### Key Interactions
- Partners with Product Managers on problem definition, success metrics, and outcome validation
- Helps Developers and QA/Testing reproduce issues and verify fixes
- Coordinates with Project Managers on stakeholder communications, readiness, and escalations
- Shares customer and stakeholder feedback during demos, release planning, and retrospectives

---

## Security / Privacy / Compliance Partner

### Role Summary
Security, Privacy, or Compliance Partners identify regulatory, privacy, security, and threat-related requirements and review mitigations where applicable.

### Responsibilities
- Define security, privacy, compliance, and threat requirements for the project
- Review designs, data flows, controls, and remediation plans
- Validate required governance checkpoints, evidence, and release readiness inputs
- Partner with QA/Testing on security test coverage and risk-based validation

### Goals / Decision Rights
- Recommend risk acceptance, mitigation, or escalation paths for security and compliance issues
- Identify release blockers when unresolved risks exceed agreed thresholds
- Ensure required controls, documentation, and handoffs are complete

### Key Interactions
- Works with Developers and Engineering Leads on secure implementation and remediation
- Advises Product Managers on risk-based trade-offs and customer or regulatory obligations
- Coordinates with Project Managers on governance checkpoints, risk registers, and escalations
- Engages stakeholders when security, privacy, or compliance decisions affect scope or launch readiness

---

## Data / Analytics Partner

### Role Summary
Data or Analytics Partners define measurement approaches, instrumentation, dashboards, and post-release analysis for success metrics.

### Responsibilities
- Translate success metrics into instrumentation, reporting, and analysis plans
- Define data quality, telemetry, dashboard, and experiment requirements
- Validate analytics implementation with Developers and QA/Testing
- Share post-release insights to inform decisions and retrospectives

### Goals / Decision Rights
- Recommend measurement approaches and decision points for product outcomes
- Identify analytics gaps that limit release learning or stakeholder reporting
- Confirm whether data is ready to support launch measurement and iteration

### Key Interactions
- Partners with Product Managers on outcomes, hypotheses, and data-informed prioritization
- Works with Developers on telemetry, event definitions, and data pipelines
- Supports Project Managers with reporting milestones, decision points, and stakeholder updates
- Engages QA/Testing and stakeholders to validate data accuracy and interpret results

---

## Lifecycle Engagement Model

Not every OctoAcme project needs every persona. Smaller teams may have one person fulfill multiple personas, but ownership and decision rights must remain explicit in the Project One-pager, backlog items, release plan, risk register, and decision log.

| Lifecycle area | Accountable owner(s) | Engaged roles and handoffs |
| --- | --- | --- |
| Initiation | Product Manager, Project Manager | Stakeholders, Customer/Support, Business Analyst/Product Operations, UX/Product Designer, Engineering Lead, Security/Privacy/Compliance, and Data/Analytics help clarify customer outcomes, success metrics, feasibility, constraints, and initial risks. |
| Planning | Project Manager, Product Manager | Developers, Engineering Lead, UX/Product Designer, Business Analyst/Product Operations, QA/Testing, Release/DevOps/SRE, Security/Privacy/Compliance, Data/Analytics, and stakeholders align scope, acceptance criteria, Definition of Done, milestones, dependencies, and decision rights. |
| Execution | Developers, Engineering Lead | Product Managers clarify scope and trade-offs; Project Managers track progress, blockers, and dependencies; UX/Product Designer, Business Analyst/Product Operations, QA/Testing, Security/Privacy/Compliance, Data/Analytics, and Release/DevOps/SRE support reviews, validation, handoffs, and risk mitigation. |
| Release | Release/DevOps/SRE, Project Manager | Developers, QA/Testing, Product Managers, Security/Privacy/Compliance, Customer/Support, Data/Analytics, and stakeholders confirm release readiness, operational readiness, communications, smoke tests, rollback plans, customer impact, and success measurement. |
| Risk management | Project Manager | Engineering Lead, Product Manager, Security/Privacy/Compliance, Release/DevOps/SRE, Customer/Support, Business Analyst/Product Operations, QA/Testing, Data/Analytics, and stakeholders identify, own, mitigate, monitor, and escalate risks. |
| Communication | Project Manager | Product Managers, Customer/Support, Release/DevOps/SRE, Business Analyst/Product Operations, Data/Analytics, and stakeholders contribute roadmap updates, release notes, support readiness, metrics, decisions needed, and escalation messages. |
| Retrospectives | Project Manager | Developers, Product Managers, QA/Testing, Engineering Lead, UX/Product Designer, Customer/Support, Release/DevOps/SRE, Security/Privacy/Compliance, Data/Analytics, Business Analyst/Product Operations, and stakeholders share learnings, customer outcomes, quality results, incidents, analytics, and improvement actions. |

Use the matrix as a lightweight guide rather than a staffing checklist. For each project, name the accountable owner for key decisions, document who must be consulted before handoffs, and identify escalation paths for quality, security/compliance, operational readiness, customer outcomes, analytics, and release readiness.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
