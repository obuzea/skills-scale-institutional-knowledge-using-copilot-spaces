# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Roles may be combined on smaller teams, but ownership and decision-making accountability should remain explicit.

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

## UX/Product Designers

### Role Summary
UX/Product Designers research user needs and design usable, accessible product experiences that address agreed product goals.

### Responsibilities
- Conduct or synthesize user research and translate findings into workflows, prototypes, and interface designs
- Define interaction patterns and accessibility considerations
- Validate design concepts with users and incorporate feedback
- Provide design specifications and clarify intended behavior during implementation

### Collaboration and Accountability
- Partner with the Product Manager to shape discovery, user needs, and acceptance criteria; the Product Manager remains accountable for product priorities and outcomes
- Work with Developers and the Technical Lead to assess feasibility and resolve implementation questions
- Collaborate with QA/Testing to include usability, accessibility, and design fidelity in validation
- Share research and design decisions with the Project Manager so dependencies and milestones are reflected in the plan

---

## Technical Leads / Architects

### Role Summary
Technical Leads or Architects guide the technical approach and help ensure solutions are secure, reliable, maintainable, and aligned with system architecture.

### Responsibilities
- Lead technical design and document significant architecture decisions
- Identify technical risks, constraints, and integration dependencies
- Support engineering estimates and resolve complex technical questions
- Promote engineering quality through design and code reviews

### Collaboration and Accountability
- Work with Developers on implementation, code quality, and technical choices
- Coordinate with the Product Manager on feasibility and scope trade-offs, while product priority remains with the Product Manager
- Partner with the Project Manager to surface dependencies, risks, and schedule impacts
- Engage the Security/Privacy Lead, DevOps/Release Engineer, and QA/Testing early when their expertise affects the design

---

## DevOps / Release Engineers

### Role Summary
DevOps or Release Engineers enable reliable delivery and operation of software through automation, deployment support, and production observability.

### Responsibilities
- Maintain or improve CI/CD pipelines and deployment environments
- Coordinate release readiness, deployment procedures, and rollback plans
- Support monitoring, alerting, and operational observability
- Identify infrastructure and operational risks and recommend mitigations

### Collaboration and Accountability
- Work with Developers and the Technical Lead to make systems deployable and operable
- Coordinate with QA/Testing on environment readiness and release verification
- Partner with the Project Manager on release timing, dependencies, and operational risks
- Support the Product Manager and Customer Support/Operations Representative with impact information and release communications; product acceptance remains with the Product Manager and operational incident ownership follows the team’s on-call process

---

## Data / Analytics Leads

### Role Summary
Data/Analytics Leads help teams define, collect, and interpret evidence about product usage and project outcomes.

### Responsibilities
- Advise on measurable indicators, event definitions, and instrumentation
- Validate data quality and create or maintain relevant dashboards
- Analyze results and communicate limitations and insights
- Help ensure data collection follows applicable privacy and governance practices

### Collaboration and Accountability
- Partner with the Product Manager to connect success metrics to product questions and interpret outcomes
- Work with Developers and the Technical Lead to implement instrumentation and reliable data flows
- Coordinate with the Project Manager to report agreed delivery and outcome signals
- Consult the Security/Privacy Lead when measurement involves sensitive data; prioritization decisions remain with the Product Manager and relevant stakeholders

---

## Security / Privacy Leads

### Role Summary
Security/Privacy Leads advise teams on security, privacy, and compliance risks and on the controls needed to address them.

### Responsibilities
- Identify relevant security and privacy requirements, threats, and risks
- Recommend controls and review plans, designs, and changes proportionate to risk
- Coordinate required security or privacy assessments and track remediation
- Escalate material unresolved risks through established security and project channels

### Collaboration and Accountability
- Work with the Technical Lead and Developers to integrate safeguards into architecture and implementation
- Coordinate with QA/Testing on security-related validation and with DevOps/Release Engineers on deployment and operational controls
- Partner with the Project Manager to record risks, owners, mitigations, and escalation status
- Advise the Product Manager and stakeholders about risk implications; risk acceptance and release decisions follow organizational policy and are not assumed by this advisory role

---

## Customer Support / Operations Representatives

### Role Summary
Customer Support or Operations Representatives bring customer-facing and service-operational perspectives into planning, release readiness, and continuous improvement.

### Responsibilities
- Share customer feedback, common support issues, and operational needs
- Identify support, training, documentation, and service-readiness requirements
- Review customer-facing release information and escalation paths
- Feed incident and service trends into product planning and retrospectives

### Collaboration and Accountability
- Work with the Product Manager to communicate customer needs and validate support impact
- Coordinate with the Project Manager on readiness tasks, dependencies, and stakeholder updates
- Partner with Developers, QA/Testing, and DevOps/Release Engineers on supportability, runbooks, and release verification
- Share operational feedback with the Technical Lead and Security/Privacy Lead when reliability or security concerns arise; technical fixes remain owned by the delivery team

---

## Business Sponsors

### Role Summary
Business Sponsors provide organizational sponsorship, strategic direction, and timely decisions on escalated business trade-offs.

### Responsibilities
- Confirm strategic alignment and champion the initiative with the organization
- Help secure necessary resources and resolve organizational impediments
- Make or obtain decisions on major escalated scope, priority, or investment trade-offs
- Review milestone outcomes and business impact

### Collaboration and Accountability
- Align with the Product Manager on intended outcomes and priority; the Product Manager continues to manage the product vision and backlog
- Work with the Project Manager on sponsorship, resource constraints, escalations, and milestone updates
- Receive recommendations from the delivery team and make decisions within delegated authority; day-to-day execution remains with the team
- Engage stakeholders as needed to resolve cross-organizational decisions

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- On smaller teams, one person may cover multiple personas; explicitly name owners for decisions and deliverables so responsibilities are not lost between roles.
