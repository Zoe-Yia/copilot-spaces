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

## QA / Testing

### Role Summary
QA and Test Engineers verify that features meet acceptance criteria, quality standards, and that product behavior matches expectations.

### Responsibilities
- Define testing strategy and acceptance criteria
- Create and maintain automated and manual tests
- Validate releases through smoke, regression, and exploratory testing
- Report defects and verify fixes

### Typical Communication
- Work with Developers and Product Managers on acceptance criteria
- Coordinate test environments with DevOps
- Report testing status to PMs and PdMs

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional / Cross-cutting Personas (new additions)

These personas help close ownership gaps for cross-cutting concerns (release orchestration, security, metrics, design validation, etc.). Add each as a subsection below. Each section includes Role Summary, Responsibilities, Goals, and Typical Communication.

### Tech Lead

- Role Summary: Drives technical design and architecture for the project; balances delivery and long-term maintainability.
- Responsibilities:
  - Define and communicate architecture and key technical decisions.
  - Propose trade-offs and technical approaches.
  - Mentor developers and guide code quality.
  - Identify technical risks and mitigation plans.
- Goals:
  - Ensure scalable, maintainable systems.
  - Reduce technical debt and delivery risk.
- Typical Communication:
  - Works with Developers on implementation details and code reviews.
  - Collaborates with Product Managers on feasibility and effort.
  - Updates Project Managers on technical risks and estimates.

### Engineering Manager

- Role Summary: Oversees team health, capacity planning, and organizational blockers; supports career development.
- Responsibilities:
  - Manage capacity, hiring, and performance processes.
  - Resolve organizational blockers and escalate when needed.
  - Support resource allocation and team formation.
- Goals:
  - Maintain sustainable team velocity and morale.
  - Ensure the team has the right skills and capacity.
- Typical Communication:
  - Coordinates with Project Managers for staffing and timeline decisions.
  - Works with Tech Leads on technical escalations.
  - Aligns with Product Managers on prioritization impacts.

### UX Researcher / Product Designer

- Role Summary: Validates user needs and creates usable designs; ensures product decisions are informed by research.
- Responsibilities:
  - Conduct user research, usability testing, and synthesis.
  - Produce design artifacts (wireframes, prototypes, specs).
  - Validate product assumptions with users and stakeholders.
- Goals:
  - Improve usability and user satisfaction.
  - Reduce rework by validating designs early.
- Typical Communication:
  - Partners with Product Managers on discovery and success metrics.
  - Handoffs designs and specs to Developers and Tech Leads.
  - Participates in sprint reviews and demos.

### DevOps / Platform Engineer (including Release Manager duties)

- Role Summary: Owns CI/CD, environments, release orchestration, and deployment safety.
- Responsibilities:
  - Maintain build and deployment pipelines (CI/CD).
  - Manage staging and production environments and run deployments.
  - Define rollback and incident runbooks.
  - Ensure observability and monitoring are in place for releases.
- Goals:
  - Reduce deployment risk and recovery time.
  - Keep environments stable and reproducible.
- Typical Communication:
  - Works with Developers/Tech Leads to ensure deployment readiness.
  - Coordinates with QA Lead on smoke/regression test gating.
  - Aligns with Project Managers to schedule release windows.

### QA Lead / Test Engineer

- Role Summary: Owns test strategy and quality gates for releases.
- Responsibilities:
  - Define test strategy (automated + manual) and maintain test health in CI.
  - Drive release acceptance criteria and coordinate manual test runs.
  - Lead QA efforts during release and incident triage.
- Goals:
  - Maintain confidence in releases through robust testing.
  - Improve test automation coverage and reliability.
- Typical Communication:
  - Works with Developers and Tech Leads to improve testability.
  - Partners with Product Managers on acceptance criteria.
  - Coordinates with DevOps for test environments.

### Data Analyst

- Role Summary: Defines success metrics, instruments analytics, and provides actionable insights.
- Responsibilities:
  - Define and implement telemetry and instrumentation.
  - Produce dashboards and analyses to validate outcomes.
  - Run experiments and measure impact against success metrics.
- Goals:
  - Provide data to inform product decisions.
  - Ensure reliable measurement of KPIs and experiments.
- Typical Communication:
  - Works with Product Managers on success metrics and experiment design.
  - Collaborates with Developers on instrumentation.
  - Reports progress and KPIs to Project Managers and stakeholders.

### Security & Compliance Lead

- Role Summary: Ensures that security and compliance requirements are identified, tracked, and mitigated.
- Responsibilities:
  - Run threat models and security reviews.
  - Define and track remediation plans and compliance checks.
  - Coordinate scans, audits, and security on-call escalation.
- Goals:
  - Reduce security risk and ensure compliance obligations are met.
  - Embed secure practices into development lifecycle.
- Typical Communication:
  - Works with Tech Leads and Developers on secure design and fixes.
  - Escalates with Project Managers for business-impacting security issues.
  - Coordinates with central Security teams / on-call.

---

## Implementation notes (summary)
- Each persona should have: Role Summary, Responsibilities, Goals, and Typical Communication.
- Add a Responsibility Matrix (see docs/persona-responsibility-matrix.md) mapping common responsibilities to the owning persona(s).
- Link to related artifacts (release checklist, incident playbook, instrumentation guide) from each persona where relevant.
- Keep tone and formatting consistent with the existing document.
