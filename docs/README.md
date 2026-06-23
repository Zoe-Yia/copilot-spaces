# OctoAcme Project Management Docs README

This README provides a brief summary of OctoAcme's project management processes and links to the full process documents in the docs/ folder.

## OctoAcme Project Management Processes Overview

OctoAcme follows a structured five-phase project lifecycle designed to deliver customer value iteratively while maintaining clear ownership, risk management, and stakeholder alignment.

### Lifecycle & Core Workflows

OctoAcme's project lifecycle consists of **Initiation**, **Planning**, **Execution**, **Release**, and **Retrospective** phases. During initiation, teams validate business need and create a lightweight Project One-pager that captures the problem statement, goals, success metrics, stakeholders, and initial risks. This serves as the decision gate before moving into detailed planning. In the planning phase, work is broken into prioritized, estimated backlog items with clear acceptance criteria and a Definition of Done. Teams identify dependencies, create release timelines, and prepare a risk register. Execution follows an iterative delivery model with daily standups, weekly delivery syncs, and demos at sprint/milestone intervals. Work flows through a project board (GitHub Projects) with columns: Backlog → Ready → In Progress → In Review → QA → Done. A formal release phase includes pre-deployment checks (CI/security scans, smoke tests, rollback plans), and post-release verification. Finally, retrospectives capture learnings and convert them into actionable improvements with tracked owners and due dates.

### Roles & Responsibilities

OctoAcme defines three core personas with distinct ownership: **Product Managers** define what to build by owning the vision, prioritizing the backlog, and measuring outcomes through success metrics. **Project Managers** coordinate delivery by creating plans, managing risks and dependencies, facilitating meetings, and maintaining transparent status reporting across stakeholders. **Developers** design and build solutions by implementing features to acceptance criteria, writing tests, participating in code reviews, and identifying technical risks. This clear role separation ensures accountability: Product owns the "what" and "why," Project owns the schedule and coordination, and Developers own the "how" and quality. Weekly syncs between PM and PdM keep priorities aligned, while twice-weekly standups keep the delivery team synchronized on progress and blockers.

### Risk Management & Communication

OctoAcme uses a structured Risk Register (ID, Description, Impact/Likelihood, Owner, Mitigation, Status) that is reviewed and updated weekly during syncs. Risks are identified during planning and monitoring throughout execution, with a clear escalation path: team-level triage → PM escalation → Product Lead → Sponsor for business-impacting issues. Communication follows a multi-channel approach: weekly status updates summarizing progress, next steps, and blockers; regular stakeholder briefings at monthly intervals; and ad-hoc escalations as needed. A single source of truth (project README or release doc) prevents information fragmentation. Incident communication is particularly formal, with triage summaries, planned actions, and blameless retrospectives scheduled post-incident.

### Quality & Delivery Standards

Quality is built into the execution rhythm through multiple checkpoints: unit and integration tests are required for new logic, end-to-end smoke tests validate critical flows before release, and security scanning runs in CI. Pull requests follow a standardized workflow—limited to ≤400 lines when possible, include issue links and acceptance criteria, require automated test and lint checks before review, and need at least one approval before merging. Acceptance criteria and Definition of Done are documented upfront and reviewed in demos. Pre-release requirements are non-negotiable: all acceptance criteria must be met, CI and security scans must pass, release notes must be drafted, and a rollback/mitigation plan must be documented. Post-deployment, teams verify the release and announce it to stakeholders and support. This layered approach—clear criteria, automated checks, manual validation, and staged deployment—minimizes production risk and ensures consistent, repeatable delivery.

## Summary of Project Management Processes

- **Initiation** — Validate the idea, create a one-pager, identify stakeholders, and decide whether to move into planning.
- **Planning** — Turn approved initiatives into a prioritized backlog, estimate scope, identify dependencies and risks, and create a release plan.
- **Execution & Tracking** — Use project boards and PR workflows to deliver increments, run CI/tests, and track progress via regular team rhythms and metrics.
- **Risk Management & Communication** — Maintain a risk register, communicate status to stakeholders, and escalate according to defined paths.
- **Release & Deployment** — Follow pre-release checks, deployment checklist, rollback playbook, and post-deploy verification.
- **Retrospective & Continuous Improvement** — Run retrospectives, capture action items, and track improvements.
- **Roles & Personas** — Define responsibilities for PM, PdM, developers, QA, and stakeholders.

## Links to Process Documents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

## How to Use This README

- Link to specific docs from PRs, project boards, and planning artifacts.
- Keep the README updated whenever process docs are added or renamed.
- Use the overview sections above to onboard new team members and reinforce key principles.
