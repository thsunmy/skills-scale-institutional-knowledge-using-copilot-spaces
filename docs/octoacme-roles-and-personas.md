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

## Delivery Engineer / Release Lead

### Role Summary
Delivery Engineers and Release Leads coordinate the technical steps required to validate, package, and ship changes safely. They help turn planned work into reliable releases and ensure deployment readiness is visible across the team.

### Responsibilities
- Own build, deploy, and release readiness checks
- Coordinate with engineering and operations on release timing and rollback plans
- Validate environment readiness, dependency status, and deployment gates
- Communicate release status to project managers, stakeholders, and engineering leads
- Support post-release verification and issue triage

### Key Interactions
- Works closely with Developers to confirm the release candidate is complete and validated
- Coordinates with Project Managers on milestones, risks, and communications
- Partners with Security and Compliance Representative and QA Lead to confirm readiness before deployment

### Goals
- Deliver predictable, observable releases
- Reduce deployment risk and confusion during handoffs
- Keep stakeholders informed with clear release status and escalation paths

---

## Product Operations (ProdOps)

### Role Summary
Product Operations keeps processes, runbooks, and delivery checklists usable and current. They help teams maintain operational readiness and reduce friction between planning, delivery, and ongoing support.

### Responsibilities
- Maintain process documentation, checklists, and runbooks
- Coordinate operational readiness reviews and transition activities
- Track workstream readiness, dependencies, and handoff quality
- Support post-launch monitoring and operational follow-up
- Help teams align process execution with defined roles and responsibilities

### Key Interactions
- Partners with Project Managers to ensure documentation and execution stay aligned
- Works with Delivery Engineer / Release Lead on readiness gates and release follow-up
- Supports Product Managers and Stakeholder Liaison in clarifying business outcomes and operational expectations

### Goals
- Strengthen process consistency and accountability across teams
- Improve handoffs and reduce operational delays
- Increase confidence in launch readiness and follow-through

---

## Stakeholder Liaison / Business Representative

### Role Summary
The Stakeholder Liaison represents business needs, priorities, and approval points. They ensure cross-functional decisions reflect stakeholder expectations and that trade-offs are communicated clearly.

### Responsibilities
- Represent business goals, constraints, and priorities
- Help define acceptance criteria and success measures for work
- Escalate unresolved decisions, dependencies, or policy concerns
- Review scope, risk, and readiness from a business perspective
- Confirm stakeholder alignment before launch or major milestone completion

### Key Interactions
- Works with Product Managers to validate scope and priority decisions
- Collaborates with Project Managers on stakeholder communication and milestone readiness
- Provides input to QA Lead and UX Representative to confirm acceptance conditions are meaningful and complete

### Goals
- Align delivery with business value and stakeholder expectations
- Improve decision quality and reduce rework from unclear priorities
- Ensure accountability for business-facing outcomes

---

## QA Lead / Test Owner

### Role Summary
QA Leads define the testing strategy, coordinate validation activities, and ensure release quality matches the intended user and business outcomes.

### Responsibilities
- Define test strategy, test plans, and validation checkpoints
- Own regression, acceptance, and release testing coordination
- Identify quality risks and support issue triage for defects or gaps
- Confirm that functional and non-functional requirements are sufficiently validated
- Coordinate with engineering and project leads on sign-off criteria

### Key Interactions
- Reviews acceptance criteria with Product Managers and Stakeholder Liaison
- Works with Developers to validate fixes, risk areas, and test coverage
- Coordinates with Delivery Engineer / Release Lead on release readiness and release verification

### Goals
- Improve release confidence and reduce late-stage defects
- Ensure quality criteria are explicit and measurable
- Create stronger accountability for validation and sign-off

---

## Security and Compliance Representative

### Role Summary
Security and Compliance Representatives assess project risk, policy alignment, and security requirements across the lifecycle. They protect the organization from avoidable compliance and operational exposure.

### Responsibilities
- Review designs, dependencies, and release artifacts for security and compliance impact
- Identify required controls, policy checkpoints, and risk mitigations
- Support review of data handling, access controls, and release safeguards
- Own or contribute to risk sign-off for sensitive or regulated work
- Partner with project leads on remediation and escalation paths

### Key Interactions
- Works with Developers and Delivery Engineers to review technical risks and deployment concerns
- Coordinates with Project Managers on risk registers and escalation steps
- Contributes to stakeholder and release approvals for high-risk changes

### Goals
- Reduce security and compliance risk across the delivery lifecycle
- Clarify accountability for policy adherence and risk management
- Improve governance without slowing project momentum unnecessarily

---

## Data Owner / Analytics Lead

### Role Summary
Data Owners and Analytics Leads ensure that data, reporting, and downstream metrics remain accurate and trustworthy as projects change or launch. They help teams prevent data quality issues that can distort decisions or user experience.

### Responsibilities
- Validate schemas, migrations, data quality checks, and reporting assumptions
- Define monitoring or analytics requirements tied to project outcomes
- Work with engineering and stakeholders on data dependencies and readiness
- Identify potential impact to reporting, dashboards, and operational measures
- Confirm that data-related acceptance criteria are met before release

### Key Interactions
- Partners with Developers and Product Managers on requirements, metrics, and data dependencies
- Coordinates with Delivery Engineer / Release Lead when release validation includes data checks
- Supports Stakeholder Liaison and Product Operations with business outcome reporting

### Goals
- Protect the trustworthiness of project and business data
- Improve visibility into outcomes after launch
- Reduce downstream issues caused by poor data quality or incomplete validation

---

## UX Representative / Design Partner

### Role Summary
UX Representatives ensure user-facing experiences meet usability, accessibility, and design goals. They help connect customer experience expectations to technical and process decisions.

### Responsibilities
- Review user journeys, flows, and UI requirements
- Validate design consistency, accessibility, and usability quality
- Participate in acceptance reviews for user-facing work
- Provide design feedback and recommendations for implementation trade-offs
- Help align product decisions with customer expectations and usability standards

### Key Interactions
- Works with Product Managers and Stakeholder Liaison to ensure user value is prioritized
- Collaborates with Developers and QA Lead on implementation quality and usability verification
- Provides feedback to Project Managers on milestone readiness when UX decisions affect scope or release quality

### Goals
- Improve customer satisfaction and usability
- Reduce rework caused by unclear design intent or missed requirements
- Ensure quality remains visible beyond technical completion

---

## How these personas fit into the OctoAcme project model

These personas complement the existing Developer, Product Manager, and Project Manager roles by clarifying accountability across delivery, risk, quality, and stakeholder alignment. Each role adds a specific viewpoint that helps reduce ambiguity during planning, execution, and release.

- Developers and Delivery Engineers work together to build and release changes safely.
- Product Managers and Stakeholder Liaisons align business value with delivery priorities.
- Project Managers coordinate cross-functional execution, while Product Operations keeps process artifacts and readiness checkpoints consistent.
- QA Leads, Security and Compliance Representatives, and Data Owners validate quality, control, and readiness at the appropriate checkpoints.
- UX Representatives ensure user experience remains central to delivery decisions.

This expanded set of personas helps teams communicate more clearly, assign ownership more effectively, and improve project outcomes by making responsibilities and handoffs explicit.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- These roles help illustrate how handoffs, approvals, and accountability operate across the full project lifecycle.


