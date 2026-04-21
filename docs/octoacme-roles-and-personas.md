# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

Related template: [OctoAcme Cross-functional Handoff Checklist](./octoacme-cross-functional-handoff-checklist.md)

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

## UX/UI Designer

### Role Summary
UX/UI Designers shape usable, accessible product experiences and validate design direction before and during implementation.

### Responsibilities
- Translate requirements into user flows, wireframes, and interface designs
- Define interaction details and accessibility considerations
- Partner with Developers to clarify design intent and implementation trade-offs
- Support QA by clarifying expected behavior and edge-case interactions
- Incorporate feedback from demos, stakeholder reviews, and support signals

### Goals
- Improve usability and task completion for end users
- Reduce rework caused by unclear interface expectations
- Ensure design quality remains consistent through delivery

### Typical Communication
- Design reviews with Developers and Product Managers
- Planning input with Project Managers on scope and sequencing
- Sprint demos and stakeholder walkthroughs

---

## Business Analyst

### Role Summary
Business Analysts connect business needs to delivery-ready requirements and help keep scope, acceptance criteria, and decisions traceable.

### Responsibilities
- Clarify business rules, constraints, and process impacts with stakeholders
- Decompose high-level needs into backlog-ready requirements
- Co-author acceptance criteria with Product Managers and QA
- Identify requirement gaps, dependencies, and handoff risks early
- Maintain traceability between objectives, requirements, and delivered outcomes

### Goals
- Improve requirement clarity before implementation starts
- Reduce churn from late requirement changes
- Keep delivery aligned with measurable business outcomes

### Typical Communication
- Requirement workshops with Product Managers and stakeholders
- Planning sessions with Project Managers and Developers
- Acceptance and scope clarification with QA during validation

---

## Technical Writer

### Role Summary
Technical Writers ensure user-facing and internal documentation is accurate, current, and ready for release.

### Responsibilities
- Plan and maintain product, API, and operational documentation updates
- Convert implementation details into clear task-based guidance
- Partner with Developers and QA to validate document accuracy
- Prepare release-facing documentation assets and known-issues notes
- Incorporate feedback from Support Lead and stakeholder audiences

### Goals
- Reduce support friction caused by missing or outdated documentation
- Improve onboarding and feature adoption
- Ensure documentation readiness is part of release readiness

### Typical Communication
- Documentation readiness check-ins during execution and release
- PR and release-note coordination with Developers
- Review cycles with Product Managers and Support Lead

---

## Support Lead

### Role Summary
Support Leads represent customer-facing operational needs and ensure support readiness across planning, release, and post-release follow-through.

### Responsibilities
- Surface recurring customer issues and edge cases into planning
- Validate support-impacting scenarios in acceptance and release prep
- Coordinate launch-readiness artifacts (FAQs, internal runbooks, escalation paths)
- Track post-release themes and route actionable insights to Product and delivery teams
- Support incident communication with Project Managers during escalations

### Goals
- Reduce time-to-resolution for customer-impacting issues
- Improve release readiness for support teams
- Strengthen feedback loops between customers and product delivery

### Typical Communication
- Weekly syncs with Project Managers and Product Managers
- Readiness and incident updates with Stakeholders
- Bug trend and edge-case handoffs to Developers and QA

---

## Site Reliability Engineer (SRE)

### Role Summary
Site Reliability Engineers help ensure production readiness, reliability, and operational observability for delivered changes.

### Responsibilities
- Define and review reliability requirements for critical flows
- Ensure monitoring, alerting, and runbook readiness before release
- Partner with Developers on resilience, performance, and operability concerns
- Support QA with production-like validation scenarios where relevant
- Participate in incident response, mitigation, and follow-up improvements

### Goals
- Maintain service reliability and availability targets
- Detect and mitigate release risks early
- Improve mean time to detect and recover from incidents

### Typical Communication
- Release readiness reviews with Project Managers and Developers
- Risk and dependency communication with Product Managers and Stakeholders
- Incident channel coordination with Support Lead and on-call responders

---

## Interaction Map for Cross-functional Collaboration

This map clarifies how the added personas collaborate with existing roles through planning, execution, validation, and release.

| Persona | Project Managers (planning, status, risk) | Product Managers (requirements, prioritization, success metrics) | Developers (implementation, reviews, testability) | QA/Testing (acceptance validation) | Stakeholders (updates/approvals) |
| --- | --- | --- | --- | --- | --- |
| UX/UI Designer | Aligns design scope to milestones; flags UX risks and dependencies | Refines requirements into user experience decisions and validation approaches | Reviews implementation against design intent; clarifies interaction behavior | Confirms expected UX behaviors and edge cases for validation | Participates in demos and design approvals where needed |
| Business Analyst | Supports planning with requirement readiness and dependency mapping; tracks requirement risks | Clarifies business rules, acceptance criteria, and outcome traceability | Translates requirements into delivery-ready details and testable scenarios | Partners on acceptance validation against business rules | Facilitates requirement sign-off and decision traceability |
| Technical Writer | Plans documentation delivery with execution/release timelines; flags doc readiness risks | Aligns documentation scope with feature priorities and audience outcomes | Pulls implementation details from PRs/reviews for accurate documentation | Verifies docs match validated system behavior | Supports release communications and approval-ready documentation |
| Support Lead | Shares support readiness status and support-risk signals during execution/release | Contributes customer pain points and support trends into prioritization | Routes field issues and reproducible cases to engineering | Shares customer edge cases for acceptance and regression focus | Communicates release impact and readiness to support stakeholders |
| Site Reliability Engineer (SRE) | Reviews operational readiness, deployment risk, and rollback preparedness | Aligns reliability trade-offs with product priorities and success criteria | Advises on observability, resilience, and safe rollout patterns | Helps define production-like validation for reliability-sensitive paths | Provides reliability/risk updates for go-live decisions |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
