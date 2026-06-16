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

## New / Expanded Personas (proposed additions)

Each persona below includes: Role summary, Responsibilities, Interactions, When to involve, and Contact guideline.

### Delivery Lead
- Role summary: Oversees day-to-day delivery execution for a project or program. Focused on operational delivery and releases rather than coordination-only activities.
- Responsibilities:
  - Track milestone progress and release readiness
  - Manage releases and cutovers (schedule, runbooks)
  - Coordinate cross-team dependencies and handoffs
  - Maintain deployment/runbook artifacts and escalation paths
- Interactions:
  - Works with Project Manager (PM) to align schedule and risk
  - Partners with PdM on scope/prioritization trade-offs during release windows
  - Coordinates with Developers, QA, and SRE/Platform to validate readiness
- When to involve: Release planning, cutover rehearsals, cross-team dependency resolution
- Contact: @delivery-leads or delivery-lead@team.example.com

### Engineering Manager (EM)
- Role summary: Line manager and technical leader for engineering teams.
- Responsibilities:
  - People development and career growth coaching
  - Capacity planning and allocation across priorities
  - Technical risk mitigation and architecture guidance
  - Approve technical trade-offs that impact team capacity
- Interactions:
  - Works with PM and PdM on resourcing and trade-offs
  - Partners with Developers on technical design and delivery
  - Coordinates with SRE/Platform on operational initiatives
- When to involve: Capacity changes, hiring decisions, significant architecture impact
- Contact: engineering-managers@org.example.com

### UX Researcher / Designer
- Role summary: Drives user research, interaction design, and usability validation.
- Responsibilities:
  - Define and run user research and usability sessions
  - Produce wireframes, prototypes, and design specs
  - Ensure accessibility and consistency with design system
  - Validate solutions with real users and supply acceptance inputs
- Interactions:
  - Collaborates with PdM to shape requirements and acceptance criteria
  - Hands off designs to Developers and QA for implementation and testing
- When to involve: Discovery, design reviews, pre-release usability checks
- Contact: ux-team@org.example.com

### Data Analyst / Data Product Manager
- Role summary: Owns analytics instrumentation, dashboards, and success metrics.
- Responsibilities:
  - Define telemetry/event schemas and measurement plan
  - Build dashboards and run analyses to validate success metrics
  - Support experiments and measurement after releases
- Interactions:
  - Works with PdM on success metrics and analysis needs
  - Partners with Developers to implement telemetry
  - Coordinates with Project Manager to ensure metrics availability for milestones
- When to involve: Success-metric definition, experiment design, post-release validation
- Contact: data-team@org.example.com

### SRE / Platform Engineer
- Role summary: Ensures reliability, performance, and secure operation of services.
- Responsibilities:
  - Define SLOs and alerting thresholds
  - Maintain CI/CD pipelines, observability, and runbooks
  - Lead incident response and post-incident reviews
- Interactions:
  - Partners with Developers on deployment and rollback strategies
  - Advises PM/PdM on operational risk and release readiness
  - Works with Delivery Lead on cutovers and environment readiness
- When to involve: Release readiness, production incidents, capacity planning
- Contact: oncall-sre@org.example.com

### QA Lead / Test Owner
- Role summary: Coordinates testing strategy and acceptance criteria for releases.
- Responsibilities:
  - Define test plans and acceptance criteria
  - Maintain automation suites and coordinate exploratory testing
  - Sign off on QA readiness for production releases
- Interactions:
  - Works with Developers on testability and acceptance criteria
  - Collaborates with PM on release gates and schedules
  - Coordinates with SRE on environment and test data needs
- When to involve: Sprint planning for test effort, pre-release verification
- Contact: qa-leads@org.example.com

### Business Analyst (BA)
- Role summary: Bridges business stakeholders and the delivery team to clarify requirements.
- Responsibilities:
  - Elicit and document detailed requirements and process flows
  - Maintain traceability between requirements and delivered work
  - Support acceptance testing with business scenarios
- Interactions:
  - Works with PdM to refine backlog items
  - Partners with Developers to clarify expected behaviour and edge cases
  - Communicates with Stakeholders to validate outcomes
- When to involve: Complex business-rule clarifications, regulatory requirements, process mapping
- Contact: business-analysts@org.example.com

### Customer Success / Support Liaison
- Role summary: Represents customer-facing teams and brings customer context to prioritization and acceptance.
- Responsibilities:
  - Surface customer feedback and support trends to the team
  - Help define acceptance for customer-impacting features
  - Coordinate communication and rollouts with support/CS teams post-release
- Interactions:
  - Works with PdM on prioritization for customer-impacting work
  - Coordinates with Project Manager for external communications
  - Helps QA reproduce and prioritize customer-reported issues
- When to involve: Features with customer impact, incident communications, release announcements
- Contact: cs-liaison@org.example.com

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
