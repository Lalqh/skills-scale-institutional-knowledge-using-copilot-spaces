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

## Business Analyst

### Role Summary
Business Analysts translate business needs into clear, testable requirements and ensure shared understanding across delivery teams.

### Responsibilities
- Elicit and document business, process, and data requirements
- Refine user stories with clear acceptance criteria and edge cases
- Maintain traceability from requirements to delivered outcomes
- Support backlog grooming with impact and dependency analysis

### Goals
- Reduce requirement ambiguity and rework
- Improve planning predictability through clear scope definition
- Ensure delivered outcomes map to business intent

### Typical Communication
- Partners with **PM** on scope clarity, dependency tracking, and change impact
- Works with **Product Managers** to convert product goals into implementable requirements
- Collaborates with **Developers** to resolve ambiguities before and during implementation
- Aligns with **QA/Testing** to ensure test scenarios map directly to acceptance criteria
- Confirms assumptions and validation points with **Stakeholders** before sign-off

---

## Technical Lead

### Role Summary
Technical Leads provide technical direction for delivery, balancing architecture quality with timeline and scope commitments.

### Responsibilities
- Define implementation approach and technical standards
- Break down complex work and guide estimation accuracy
- Review design and code decisions for maintainability and risk
- Escalate technical risks early with mitigation options

### Goals
- Keep delivery aligned with architecture and quality standards
- Reduce technical risk and avoid late-stage redesign
- Enable consistent engineering decisions across teams

### Typical Communication
- Works with **PM** to align delivery plans with technical sequencing and constraints
- Partners with **Product Managers** on scope trade-offs and feasibility
- Guides **Developers** on architecture, coding patterns, and implementation decisions
- Collaborates with **QA/Testing** on test strategy for integration, performance, and regressions
- Explains technical risks and options to **Stakeholders** for informed decisions

---

## Scrum Master / Delivery Facilitator

### Role Summary
Scrum Masters (or Delivery Facilitators) improve delivery flow, remove blockers, and reinforce team operating cadence.

### Responsibilities
- Facilitate standups, planning, reviews, and retrospectives
- Track and remove impediments affecting team throughput
- Coach the team on process discipline and continuous improvement
- Surface risks in cadence, handoffs, and team dependencies

### Goals
- Improve delivery flow and sprint reliability
- Reduce blockers and process-related delays
- Build a consistent, inspect-and-adapt team cadence

### Typical Communication
- Supports **PM** by maintaining execution rhythm and early blocker visibility
- Coordinates with **Product Managers** to keep backlog readiness aligned with sprint goals
- Helps **Developers** stay focused on sprint commitments and dependency resolution
- Works with **QA/Testing** to prevent end-of-sprint test bottlenecks
- Communicates delivery health and impediment trends to **Stakeholders** through PM channels

---

## Release Manager

### Role Summary
Release Managers coordinate release readiness and deployment governance to reduce production risk and improve accountability.

### Responsibilities
- Define release criteria, schedules, and go/no-go checkpoints
- Coordinate deployment, rollback, and communication plans
- Verify readiness across quality, operational, and dependency gates
- Maintain release logs and post-release follow-up actions

### Goals
- Deliver predictable, low-risk releases
- Improve release transparency and accountability
- Shorten recovery time through stronger rollback readiness

### Typical Communication
- Partners with **PM** on release timelines, dependencies, and risk escalation
- Aligns with **Product Managers** on scope inclusion and release priorities
- Coordinates with **Developers** on deployment runbooks, feature flags, and rollback readiness
- Works with **QA/Testing** on final validation, defect triage, and sign-off evidence
- Shares release status and contingency plans with **Stakeholders** before and after launch

---

## UX / Product Designer

### Role Summary
UX / Product Designers define user experience expectations and interaction patterns so teams deliver usable, coherent solutions that align with product goals.

### Responsibilities
- Create user flows, wireframes, and interaction guidance for planned features
- Validate design assumptions with lightweight user feedback when available
- Document usability requirements and accessibility considerations
- Collaborate on acceptance criteria related to user behavior and interface quality

### Goals
- Improve usability and task completion outcomes
- Reduce rework caused by unclear interaction expectations
- Keep product experience consistent across features

### Typical Communication
- Partners with **PM** on design milestones, dependencies, and delivery sequencing
- Works with **Product Managers** to align user needs with roadmap priorities
- Collaborates with **Developers** to ensure implementation fidelity and feasible UI trade-offs
- Aligns with **QA/Testing** on usability checks and acceptance criteria for UX behavior
- Shares design rationale and expected user impact with **Stakeholders**

---

## Support / Operations Representative

### Role Summary
Support / Operations Representatives provide operational and customer-facing context that helps teams plan for supportability, monitoring, and post-release stability.

### Responsibilities
- Contribute support insights from incidents, tickets, and recurring user pain points
- Define operational readiness inputs such as runbooks, alerts, and handoff needs
- Validate support workflows for new or changed functionality
- Provide feedback after release on adoption issues and service quality

### Goals
- Reduce production incidents and support escalations
- Improve service reliability and maintainability
- Speed up issue triage and resolution after releases

### Typical Communication
- Works with **PM** on readiness checkpoints and operational risk visibility
- Coordinates with **Product Managers** on customer-impact priorities and feedback loops
- Collaborates with **Developers** on observability, diagnostics, and support tooling needs
- Aligns with **QA/Testing** on production-like validation scenarios and failure handling
- Communicates incident trends and support impact to **Stakeholders**

---

## Security / Compliance Reviewer

### Role Summary
Security / Compliance Reviewers ensure solutions meet security and policy requirements throughout planning, implementation, and release preparation.

### Responsibilities
- Review requirements and designs for security and compliance implications
- Define required controls, evidence, and review checkpoints
- Assess risks in authentication, authorization, data handling, and third-party usage
- Confirm remediation plans and exception handling before release approval

### Goals
- Reduce security and compliance risk in delivered features
- Catch control gaps early to avoid late-stage blockers
- Maintain auditability and policy alignment across releases

### Typical Communication
- Partners with **PM** on security milestones, risk registers, and approval gates
- Works with **Product Managers** to align policy constraints with feature scope decisions
- Collaborates with **Developers** on secure implementation patterns and remediation priorities
- Coordinates with **QA/Testing** on security validation scope and evidence collection
- Reports risk posture and required actions to **Stakeholders** for governance decisions

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
