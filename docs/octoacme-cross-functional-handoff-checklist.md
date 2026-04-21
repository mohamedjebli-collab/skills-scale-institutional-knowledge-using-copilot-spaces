# OctoAcme — Cross-functional Handoff Checklist

## Purpose
Provide a lightweight handoff checklist that clarifies ownership and accountability across planning, execution, and release.

Use this alongside existing process docs:
- [Project Initiation](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution and Tracking](./octoacme-execution-and-tracking.md)
- [Release and Deployment](./octoacme-release-and-deployment.md)
- [Risks and Communication](./octoacme-risks-and-communication.md)

## Planning Handoff Checklist
- [ ] Project One-pager updated with goals, success metrics, and named role owners (Project Manager, Product Manager, delivery leads)
- [ ] Requirements and business rules clarified (Product Manager + Business Analyst)
- [ ] UX direction, key flows, and accessibility expectations documented (UX/UI Designer + Product Manager)
- [ ] Initial acceptance criteria and QA approach drafted (Product Manager + QA/Testing + Developers)
- [ ] Documentation and support-impact scope captured (Technical Writer + Support Lead)
- [ ] Operational risks and observability needs identified in risk register (Project Manager + SRE + Developers)

## Execution Handoff Checklist
- [ ] Backlog items include clear acceptance criteria and owner
- [ ] PRs link to issue and acceptance criteria per execution workflow
- [ ] Design and requirement clarifications tracked before work is marked ready for QA
- [ ] QA validates acceptance criteria and critical user flows with input from UX/UI Designer and Business Analyst as needed
- [ ] Technical documentation updates are prepared before merge or release cutoff
- [ ] Weekly status updates include delivery progress, risks, blockers, and decisions needed

## Release Handoff Checklist
- [ ] Pre-release requirements from release guide are complete (CI, security scans, release notes, rollback plan, smoke tests)
- [ ] Support readiness confirmed (Support Lead: FAQs, known issues, escalation path)
- [ ] Documentation readiness confirmed (Technical Writer: user/internal updates, release notes consistency)
- [ ] Operational readiness confirmed (SRE + Developers: monitoring, alerting, runbooks, post-deploy checks)
- [ ] Stakeholder communication plan prepared (Project Manager + Product Manager)
- [ ] Post-release verification owners and communication channel confirmed
