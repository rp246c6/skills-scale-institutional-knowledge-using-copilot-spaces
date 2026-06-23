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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Operational and Cross-functional Personas

This section documents additional operational and cross-functional personas that support delivery, releases, and ongoing operations. These roles close gaps in ownership and clarify handoffs between product, engineering, and operations.

### Delivery Lead
- Role Summary: Owns end-to-end delivery for a project or major feature, coordinates cross-functional teams, drives milestone progress, and monitors schedule and risks.
- Responsibilities:
  - Manage plan execution and daily/weekly progress tracking
  - Coordinate cross-team dependencies and unblock teams
  - Maintain milestone schedules and highlight risks
  - Ensure project artifacts (plans, decision logs, test status) are available
- Goals:
  - Ensure on-time delivery of committed scope
  - Reduce delays caused by unclear ownership or blocked dependencies
- Interactions:
  - Works with Product Manager for scope and priority decisions
  - Coordinates with Technical Architect for design approvals
  - Aligns with Release Coordinator for deployment windows

### Product Operations (ProdOps)
- Role Summary: Maintains project tooling, runbooks, and operational processes that support project execution and launches.
- Responsibilities:
  - Configure and maintain project tooling (boards, dashboards, CI status)
  - Maintain onboarding/offboarding docs and runbooks for project processes
  - Track and present delivery metrics and health indicators
  - Drive process improvements for repeatable workflows
- Goals:
  - Reduce onboarding friction and tooling-related delays
  - Improve observability of project health
- Interactions:
  - Supports Delivery Lead, Project Manager, and Feature Owners with tooling and dashboards

### QA Owner / Test Lead
- Role Summary: Owns testing strategy and execution readiness for releases and major milestones.
- Responsibilities:
  - Define test strategy and acceptance criteria per feature
  - Own test plans, automation coverage, and test environments
  - Coordinate defect triage and release testing windows
  - Certify release readiness from a quality perspective
- Goals:
  - Maintain high confidence in releases, reduce production defects
  - Ensure timely identification and triage of issues during release
- Interactions:
  - Works with Developers, Feature Owners, and Release Coordinator

### Technical Architect
- Role Summary: Provides architectural guidance and ensures technical direction supports non-functional requirements and scale.
- Responsibilities:
  - Review critical designs and ensure alignment to architecture principles
  - Identify and mitigate architectural risks
  - Define non-functional requirements and observability needs
- Goals:
  - Prevent architectural drift and ensure long-term maintainability
- Interactions:
  - Advises Delivery Lead and Engineers; escalates major architecture risks to stakeholders

### Change Manager
- Role Summary: Coordinates change approvals and communication for changes that impact operations or customers.
- Responsibilities:
  - Manage change approval workflows and policy compliance
  - Coordinate communications and rollout plans for operational changes
  - Ensure rollback/mitigation plans are defined and tested when required
- Goals:
  - Reduce customer impact and ensure compliant change execution
- Interactions:
  - Works with Release Coordinator and Stakeholder Liaison for approvals and communications

### Release Coordinator
- Role Summary: Plans and executes releases, maintains release checklists, and coordinates deployments and rollbacks.
- Responsibilities:
  - Maintain release calendar and coordinate deployment windows
  - Own pre-release readiness checks and rollback plans
  - Coordinate cross-functional release communications
- Goals:
  - Ensure smooth, repeatable release processes with minimal incidents
- Interactions:
  - Coordinates with QA Owner, Change Manager, Delivery Lead, and Ops

### Stakeholder Liaison
- Role Summary: Primary contact for external stakeholders and business owners; collects feedback and communicates status.
- Responsibilities:
  - Maintain stakeholder contact list and communication cadence
  - Translate technical status into business impact and next steps
  - Collect and prioritize stakeholder feedback for the Product Manager
- Goals:
  - Ensure stakeholder expectations are managed and met
- Interactions:
  - Aligns with Product Manager and Delivery Lead for stakeholder updates

### Handoffs & Escalation (summary)
- For every major milestone, define the owner of the handoff, the artifacts required (design docs, test signoff, runbooks), and the escalation path (primary contact, secondary contact, and closure expectations).
- Suggested practice: Each handoff must include a short "handoff note" (one paragraph) stating the scope handed off, outstanding risks, known issues, and the contact for escalations.
