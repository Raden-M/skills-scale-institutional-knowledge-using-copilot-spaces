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

## Security Lead

### Role Summary
Security Leads ensure that projects are designed, built, and released with appropriate security controls, risk mitigation, and compliance awareness. They partner with engineering, PMs, and stakeholders to reduce security exposure without slowing delivery unnecessarily.

### Responsibilities
- Define security requirements and review criteria for the project
- Facilitate threat modeling and secure design reviews
- Triage vulnerabilities and prioritize remediation based on risk
- Partner with engineers and PMs to ensure secure-by-default decisions
- Review release readiness from a security perspective

### Goals
- Reduce project security risk and prevent preventable incidents
- Align delivery decisions with organizational security standards
- Make security trade-offs explicit and actionable

### Typical Communication
- Security review meetings and design discussions
- Risk and vulnerability triage with engineering leads
- Release readiness checks and escalation for high-risk issues

### Interaction with Existing Roles
- Works with Project Managers to escalate security-related schedule or dependency risks
- Collaborates with Developers on secure implementation and remediation planning
- Supports Product Managers by clarifying trade-offs between feature scope and security risk
- Keeps Stakeholders informed when security findings impact timing, launch readiness, or compliance requirements

---

## QA Lead / Quality Partner

### Role Summary
QA Leads define and govern the quality strategy for a project, ensuring that delivered work meets acceptance criteria, user expectations, and release thresholds.

### Responsibilities
- Define test strategy, quality gates, and acceptance validation approach
- Partner with engineering and product on defect triage and prioritization
- Verify that new work meets business and technical criteria before release
- Coordinate manual QA, regression coverage, and release quality checks
- Identify patterns of quality risk and suggest mitigations

### Goals
- Deliver dependable user experiences and minimize avoidable defects
- Ensure predictable handoff from development to release
- Support product confidence in the quality of each milestone

### Typical Communication
- Review meetings with engineering and product stakeholders
- QA signoff criteria and defect review discussions
- Release readiness updates and quality risk summaries

### Interaction with Existing Roles
- Works closely with Developers to validate functionality and identify gaps in coverage
- Supports Product Managers by confirming that delivered outcomes satisfy acceptance criteria
- Coordinates with Project Managers on milestone readiness and risk-based release decisions
- Keeps Stakeholders informed when quality risks may affect launch timing or user impact

---

## Release Manager / Delivery Coordinator

### Role Summary
Release Managers coordinate the operational aspects of shipping work, including deployment windows, rollback readiness, communication, and release quality checks across teams.

### Responsibilities
- Plan deployment windows and release sequencing
- Coordinate rollback readiness and incident communication paths
- Validate pre-release criteria and production deployment readiness
- Align communications across engineering, support, and stakeholders
- Track release health and post-deployment verification outcomes

### Goals
- Reduce release risk and operational disruption
- Improve predictability of go-live activities
- Ensure stakeholders are informed before and after deployment

### Typical Communication
- Release planning meetings and deployment status updates
- Post-deploy verification summaries
- Support and stakeholder communications during go-live windows

### Interaction with Existing Roles
- Partners with Project Managers to align deployment timing with milestones and capacity
- Coordinates with Technical Leads and Developers on deployment readiness and rollback plans
- Provides Product Managers with release status and customer-impact awareness
- Engages Stakeholders when release timing, changes, or known issues need visibility

---

## Customer Success / Stakeholder Liaison

### Role Summary
Customer Success and Stakeholder Liaisons translate customer and stakeholder feedback into actionable project input, helping teams stay aligned with adoption, usage, and expectation signals.

### Responsibilities
- Gather customer feedback, support trends, and stakeholder concerns
- Translate usage and feedback into backlog or release considerations
- Represent stakeholder perspectives in planning and status discussions
- Communicate project impact, status, and delivery trade-offs to stakeholders
- Help prioritize enhancements that support adoption and retention

### Goals
- Keep product decisions informed by customer realities
- Improve stakeholder trust and alignment
- Connect delivery work to real-world user and business outcomes

### Typical Communication
- Stakeholder updates, customer feedback reviews, and advisory meetings
- Product and roadmap discussions grounded in customer signals
- Release notes and adoption-impact communications

### Interaction with Existing Roles
- Works with Product Managers to incorporate customer insight into prioritization
- Supports Project Managers by surfacing communication needs and stakeholder concerns
- Helps Developers understand the user experience impact of implementation decisions
- Keeps Stakeholders informed about progress, trade-offs, and plan changes

---

## Technical Lead / Engineering Lead

### Role Summary
Technical Leads provide engineering direction, architecture alignment, and cross-team execution guidance so that work remains technically coherent, scalable, and feasible within the agreed delivery plan.

### Responsibilities
- Define technical direction and architecture constraints
- Guide implementation decisions and engineering standards
- Coordinate cross-team dependencies and technical sequencing
- Support planning with feasibility, risks, and design trade-offs
- Ensure alignment between product goals and engineering execution

### Goals
- Deliver technically sound and maintainable solutions
- Reduce delivery friction caused by architecture or dependency conflicts
- Improve execution quality across engineering workstreams

### Typical Communication
- Technical design and architecture reviews
- Dependency and sequencing discussions across teams
- Engineering planning and risk escalation updates

### Interaction with Existing Roles
- Works with Project Managers to manage technical dependencies, staffing, and delivery pace
- Helps Product Managers turn strategy into feasible plans and trade-off decisions
- Guides Developers through design, implementation, and technical quality expectations
- Shares technical constraints and implications with Stakeholders when they affect roadmap or release outcomes

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Together, these roles clarify accountability across delivery, quality, security, stakeholder communication, and technical execution.
