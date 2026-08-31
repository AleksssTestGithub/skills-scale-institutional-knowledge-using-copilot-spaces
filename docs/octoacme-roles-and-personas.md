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

## Release Manager

### Role Summary
Release Managers coordinate release readiness, deployment timing, and communication across engineering, product, and support teams. They help ensure that the right work reaches production with clear ownership and minimal customer disruption.

### Responsibilities
- Define and track release scope, milestones, and readiness criteria
- Coordinate cross-team deployment planning and release communication
- Verify quality gates, rollback plans, and operational readiness
- Align release timing with stakeholder expectations and business priorities
- Monitor launch health and support resolution of issues after deployment

### Goals
- Deliver updates with predictable quality and low operational risk
- Maintain clear release communication across internal and external stakeholders
- Reduce release conflicts, defects, and customer-facing disruption

### Typical Communication
- Release readiness reviews and deployment checklists
- Launch updates and post-release status reports
- Coordination with engineering, product, and support teams before and after release

### Interactions
- Works closely with Project Managers to sequence milestones and dependencies
- Collaborates with Developers and Technical Leads to confirm release readiness and rollback plans
- Aligns with Product Managers on business impact, launch goals, and customer messaging
- Coordinates with Support/Operations representatives to prepare monitoring and incident response

---

## Scrum Master / Delivery Lead

### Role Summary
Scrum Masters or Delivery Leads help the team operate effectively, remove obstacles, and keep delivery focused on agreed priorities. They support sustainable execution while protecting the team from unnecessary churn and blockers.

### Responsibilities
- Facilitate agile ceremonies and delivery routines
- Remove or escalate blockers that impact team delivery
- Help maintain a healthy backlog, sprint plan, and flow of work
- Coach the team on process discipline, prioritization, and continuous improvement
- Coordinate with project leadership to surface risks and delivery issues early

### Goals
- Improve team predictability and delivery flow
- Reduce friction in planning, execution, and retrospectives
- Support a healthy, collaborative working rhythm across teams

### Typical Communication
- Daily standups, sprint planning, and retrospective meetings
- Team health updates and dependency tracking
- Escalation summaries to project and product leadership

### Interactions
- Works with Project Managers to monitor progress, risks, and schedule impacts
- Partners with Product Managers to refine priorities and keep work aligned to customer value
- Supports Developers by reducing blockers and facilitating smoother collaboration
- Coordinates with Technical Leads to identify dependency risks and sequencing issues

---

## Technical Lead

### Role Summary
Technical Leads provide engineering direction, technical decision-making, and architectural guidance for a project or initiative. They balance product needs with system quality, maintainability, and delivery constraints.

### Responsibilities
- Define technical direction, architecture, and implementation standards
- Guide design decisions, trade-offs, and technical risk management
- Review implementation quality and ensure maintainability across features
- Support developers in resolving complex technical issues and cross-team dependencies
- Align engineering choices with release, security, and operational constraints

### Goals
- Deliver technically sound, scalable, and maintainable solutions
- Reduce avoidable rework and architectural debt
- Improve the quality and consistency of engineering execution

### Typical Communication
- Design reviews and architecture discussions
- Technical risk and dependency updates
- Guidance for implementation decisions and engineering standards

### Interactions
- Works with Product Managers and Project Managers to translate priorities into feasible technical plans
- Provides technical direction to Developers and helps validate implementation choices
- Coordinates with Security/Compliance Reviewers on controls, vulnerabilities, and approvals
- Supports Release Managers by confirming deployment readiness and technical rollback considerations

---

## Security / Compliance Reviewer

### Role Summary
Security and Compliance Reviewers help ensure products and delivery processes meet relevant security, privacy, and governance requirements. They act as a safeguard for risk reduction and policy alignment across the project lifecycle.

### Responsibilities
- Review architecture, workflows, and implementations for security and compliance risks
- Identify vulnerabilities, access concerns, and control gaps
- Validate compliance with legal, regulatory, and organizational policies
- Support remediation planning and approval checkpoints
- Provide guidance on secure development and deployment practices

### Goals
- Reduce security and compliance risk before production exposure
- Build trust in the process and release quality
- Ensure teams operate within required standards and controls

### Typical Communication
- Security review checkpoints, remediation plans, and audit documentation
- Risk assessments and policy clarifications
- Sign-off or escalation for release-ready decisions

### Interactions
- Reviews technical design and implementation decisions with Technical Leads and Developers
- Works with Project Managers and Release Managers to ensure milestones include required controls
- Coordinates with Product Managers to balance regulatory obligations with user value
- Provides clear decision points that Support/Operations teams can rely on for secure incident response

---

## Support / Operations Representative

### Role Summary
Support and Operations Representatives represent the realities of running the product in production. They ensure that customer impact, service health, and operational readiness are considered in planning, release, and incident response.

### Responsibilities
- Define operational requirements, monitoring needs, and support readiness criteria
- Participate in release reviews to assess deployment risk and customer impact
- Help triage incidents, monitor service health, and share operational learnings
- Provide feedback from production experience to improve reliability and usability
- Coordinate with engineering on incident response and follow-up actions

### Goals
- Maintain service reliability, customer trust, and operational continuity
- Turn production feedback into actionable improvements
- Ensure teams are prepared for launch and post-release support

### Typical Communication
- Incident updates and operational readiness reviews
- Post-release monitoring notes and support escalations
- Feedback sessions with product and engineering teams

### Interactions
- Works with Release Managers to validate release health and support plans
- Collaborates with Developers and Technical Leads to address operational issues and improve observability
- Provides product and project teams with customer-impact insight that informs prioritization
- Supports Security/Compliance Reviewers by helping assess operational risk and response readiness

---

## Data / Analytics Stakeholder

### Role Summary
Data and Analytics stakeholders help teams interpret outcomes, measure value, and make decisions based on evidence. They connect product and project delivery to measurable business and user outcomes.

### Responsibilities
- Define metrics, dashboards, and reporting needs for product and project performance
- Help interpret experiment results, customer trends, and operational data
- Validate whether outcomes meet success criteria and business goals
- Support data-informed decision-making across planning and release cycles
- Surface gaps in instrumentation, observability, and analytics coverage

### Goals
- Improve decision quality with clear, measurable evidence
- Connect delivery outcomes to business value and user impact
- Ensure metrics are available and actionable across the lifecycle

### Typical Communication
- KPI reviews, dashboard updates, and performance briefings
- Experiment results and retrospective analysis
- Metric definitions and requirements for product and release tracking

### Interactions
- Works with Product Managers to validate that success metrics align with customer needs
- Collaborates with Project Managers and Scrum Masters to track progress against measurable outcomes
- Provides Developers and Technical Leads with data requirements and instrumentation guidance
- Supports Release Managers and Support/Operations by clarifying launch impact and post-release trends

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

