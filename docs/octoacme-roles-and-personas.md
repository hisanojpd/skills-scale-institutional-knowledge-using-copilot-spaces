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

## Additional Personas

Project roles may be combined on small projects. When combined, the named role should retain clear accountability and follow the existing Project Manager, Product Manager, Developer, and stakeholder escalation paths.

## Delivery Lead / Scrum Master

### Role Summary
The Delivery Lead enables predictable team delivery, healthy team practices, and continuous improvement.

### Responsibilities
- Facilitate ceremonies, including standups, planning, and retrospectives
- Identify and remove team-level impediments
- Promote sustainable flow and WIP limits
- Coordinate team-level dependencies and delivery risks

### Goals
- Improve predictability and team focus
- Reduce avoidable delays and recurring process friction
- Strengthen a culture of learning and continuous improvement

### Typical Communication
- Daily standups and retrospectives
- Sprint planning and delivery syncs
- Impediment and flow reports

### Interactions with existing roles
The Delivery Lead works with Developers to address capacity and workflow constraints and with QA to surface quality readiness issues. The Project Manager retains accountability for project-level schedules, cross-project dependencies, risk reporting, and stakeholder communication.

## Technical / Engineering Lead

### Role Summary
The Technical / Engineering Lead provides technical direction and guides delivery decisions across architecture, integrations, maintainability, and engineering practices.

### Responsibilities
- Set and communicate technical direction and design principles
- Evaluate architecture and integration trade-offs
- Coordinate technical spikes and cross-team implementation decisions
- Support developers in estimating and managing technical risk
- Identify delivery, operational, and maintainability concerns

### Goals
- Deliver scalable, secure, and maintainable solutions
- Reduce avoidable technical debt and rework
- Improve engineering consistency and technical alignment

### Typical Communication
- Technical design reviews and architecture discussions
- Delivery planning and code review forums
- Engineering risk and dependency updates

### Interactions with existing roles
The Engineering Lead advises Developers on implementation approaches and partners with QA on testability and quality requirements. It works with the Product Manager on feasibility and trade-offs and with the Project Manager on technical dependencies and schedules. The Product Manager remains accountable for outcome and priority decisions.

## UX / Design Lead

### Role Summary
The UX / Design Lead represents customer and usability needs throughout discovery and delivery.

### Responsibilities
- Research user needs and validate design concepts
- Translate requirements into user flows, prototypes, and design specifications
- Define interaction, accessibility, and usability acceptance considerations
- Collaborate on design reviews and usability feedback

### Goals
- Improve usability, accessibility, and customer value
- Reduce rework caused by unclear or unvalidated experiences
- Ensure design decisions are testable and measurable

### Typical Communication
- Discovery sessions and design critiques
- Backlog and acceptance-criteria reviews
- Usability testing summaries

### Interactions with existing roles
The UX Lead partners with the Product Manager on user needs and prioritized outcomes and with Developers on implementation details. It collaborates with QA to translate usability and accessibility requirements into test coverage. The Product Manager remains accountable for product priorities; the UX Lead owns the quality and consistency of the proposed experience.

## QA / Test Lead

### Role Summary
The QA / Test Lead owns the test strategy and quality signals that determine delivery readiness.

### Responsibilities
- Define and maintain the test strategy and quality gates
- Identify test coverage gaps and release risks
- Coordinate manual and automated testing activities
- Validate acceptance criteria and feature readiness
- Report quality trends and defects

### Goals
- Prevent defects from reaching production
- Make quality status visible and evidence-based
- Improve test effectiveness and automation

### Typical Communication
- Test planning and defect triage
- Acceptance reviews and release-readiness checks
- Quality dashboards and status reports

### Interactions with existing roles
The QA Lead works with Developers on testability and defect resolution, with the Product Manager on acceptance criteria, and with the Project Manager on release risks and readiness decisions. The Engineering Lead helps resolve systemic technical quality issues. The Product Manager owns acceptance of product outcomes, while QA provides independent readiness evidence.

## Business Analyst / Requirements Lead

### Role Summary
The Business Analyst clarifies requirements and maintains traceability between stakeholder needs, project outcomes, and delivered work.

### Responsibilities
- Elicit and analyze stakeholder needs
- Document requirements and assumptions
- Maintain traceability to success metrics and backlog items
- Identify gaps, ambiguities, and conflicting requirements
- Support backlog refinement and validation

### Goals
- Reduce misunderstanding and rework
- Improve requirement completeness and traceability
- Align stakeholders on measurable outcomes

### Typical Communication
- Requirements workshops and backlog refinement
- Stakeholder interviews and decision logs
- Traceability updates and acceptance reviews

### Interactions with existing roles
The Business Analyst translates stakeholder input for the Product Manager and delivery team and partners with Developers and QA to clarify implementation and validation needs. The Project Manager coordinates stakeholders and decisions, while the Product Manager remains accountable for product prioritization and outcome trade-offs.

## Release / DevOps Lead

### Role Summary
The Release / DevOps Lead coordinates environment, deployment, observability, and rollback readiness.

### Responsibilities
- Plan and coordinate deployment activities
- Maintain release automation and environment readiness
- Define observability and operational verification requirements
- Document rollback and mitigation procedures
- Support incident recovery and post-release verification

### Goals
- Reduce release risk and deployment time
- Improve deployment repeatability and recovery
- Maintain operational visibility

### Typical Communication
- Release planning and readiness reviews
- Deployment coordination and post-deploy verification
- Operational dashboards and incident updates

### Interactions with existing roles
The Release Lead works with Developers on deployable builds and operational instrumentation, with QA on smoke testing, and with the Project Manager and Executive Sponsor on release timing and risk. It coordinates operational readiness with Customer Support. The Project Manager owns project-level release coordination, but the Release Lead owns technical release execution and readiness evidence.

## Security and Compliance Lead

### Role Summary
The Security and Compliance Lead ensures project decisions address security, privacy, and applicable compliance requirements.

### Responsibilities
- Review security and compliance risks and control requirements
- Advise on threat modeling, data handling, and audit needs
- Coordinate security reviews and evidence collection
- Escalate unresolved security or compliance issues
- Support incident and vulnerability processes

### Goals
- Prevent avoidable security and compliance exposure
- Produce evidence needed for audits and assurance
- Integrate risk controls into delivery practices

### Typical Communication
- Security and privacy reviews
- Risk register updates and control assessments
- Incident and escalation reports

### Interactions with existing roles
The Security Lead advises the Engineering Lead and Developers on secure implementation and partners with QA on security testing. It provides risk guidance to the Product Manager and Project Manager, who retain accountability for informed prioritization and project escalation decisions. Critical incidents follow the repository's security incident process and notify the designated security on-call.

## Data / Analytics Lead

### Role Summary
The Data / Analytics Lead defines and evaluates the evidence used to measure project outcomes and operational performance.

### Responsibilities
- Translate success criteria into metrics and instrumentation
- Validate data quality and measurement methods
- Analyze usage, adoption, quality, and operational signals
- Communicate findings and recommended follow-up actions
- Support experiments and outcome reviews

### Goals
- Improve the reliability of product and delivery decisions
- Demonstrate whether project outcomes are achieved
- Turn data into actionable improvements

### Typical Communication
- Metric-definition and instrumentation reviews
- Dashboard reviews and experiment analysis
- Outcome and retrospective reports

### Interactions with existing roles
The Analytics Lead partners with the Product Manager to define success measures and with Developers to instrument features. It provides evidence to stakeholders and the Project Manager for delivery and outcome reviews. The Product Manager owns prioritization based on findings, while the Analytics Lead owns metric quality and analysis integrity.

## Customer Support / Operations Lead

### Role Summary
The Customer Support / Operations Lead represents operational readiness and real customer experience.

### Responsibilities
- Prepare support teams for new features and known issues
- Collect and prioritize recurring customer feedback
- Develop support content and escalation guidance
- Monitor operational impact after releases
- Escalate incidents and service-impacting trends

### Goals
- Reduce customer disruption and support burden
- Improve readiness for releases and incidents
- Convert customer feedback into actionable improvements

### Typical Communication
- Release-readiness and support briefings
- Incident updates and customer-impact reports
- Feedback reviews with Product and Engineering

### Interactions with existing roles
The Support Lead partners with the Product Manager on customer feedback and with Engineering and QA on known issues and operational defects. It works with the Release Lead on support readiness and with the Project Manager on customer-impact risks. The Product Manager owns backlog decisions; Engineering owns technical remediation; the Support Lead owns operational readiness and customer communication.

## Executive Sponsor / Decision Maker

### Role Summary
The Executive Sponsor provides organizational authority, removes major barriers, and makes or enables high-impact project decisions.

### Responsibilities
- Sponsor the project and reinforce its strategic importance
- Approve major scope, investment, or priority changes
- Remove organizational barriers and resolve cross-organization conflicts
- Review outcome and risk information at governance milestones
- Support escalations that exceed delivery-team authority

### Goals
- Ensure the project remains aligned with strategic priorities
- Resolve decisions that cannot be made below executive level
- Protect outcomes and minimize organizational risk

### Typical Communication
- Executive status reviews and steering forums
- Milestone and investment decisions
- Sponsor-level escalation updates

### Interactions with existing roles
The Sponsor receives project risks and outcome summaries from the Project Manager and Product Manager and resolves trade-offs that exceed their delegated authority. It supports, rather than replaces, the delivery team's day-to-day accountability. The Product Manager owns product priorities, the Project Manager owns delivery coordination and reporting, and the Sponsor owns executive decisions and major investment or priority approvals.

## Accountability and Role Boundaries

When roles overlap:
- The Product Manager decides what outcome to prioritize.
- The Project Manager coordinates how work is planned and reported.
- The Engineering Lead directs technical approach; Developers implement it.
- QA provides quality evidence; the Product Manager accepts outcomes and the Project Manager confirms readiness across delivery commitments.
- The Sponsor approves major scope, investment, or priority decisions and resolves organization-level escalation.
- The Delivery Lead improves team flow but does not replace Project Manager accountability for project-level delivery.
- Roles may be combined, but one named person should remain accountable for each project decision and deliverable.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

