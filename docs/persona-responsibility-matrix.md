# Persona Responsibility Matrix

This matrix maps common responsibility areas to the primary owner persona(s). Use this as a quick reference to clarify ownership and handoffs.

| Responsibility area | Primary owner(s) | Notes |
|---|---:|---|
| Feature discovery & success metrics | Product Manager, Data Analyst | PM defines the problem & metrics; Data Analyst instruments and validates. |
| Technical architecture & design | Tech Lead | Tech Lead owns architecture decisions; Tech Lead + Developers implement. |
| Implementation (code) | Developers | Developers implement per acceptance criteria and DoD. |
| Team capacity & staffing | Engineering Manager | Eng Manager handles hiring, allocation, and career development. |
| CI/CD pipelines & deployments | DevOps / Platform Engineer | Owns pipeline health and deployment automation. |
| Release orchestration & scheduling | DevOps / Project Manager | DevOps runs deploys; PM schedules windows and communicates stakeholders. |
| Test strategy & QA gating | QA Lead | QA Lead defines gating criteria and test strategy. |
| User research & design | UX Researcher / Product Designer | Designs and research lead product usability decisions. |
| Instrumentation & analytics | Data Analyst | Implements telemetry and dashboards. |
| Security & compliance | Security & Compliance Lead | Runs reviews, tracks remediation, and escalates as needed. |
| Incident response & mitigation | DevOps / Security / Project Manager | Depends on incident type; triage ownership defined in incident playbook. |

Guidance:
- If ownership is shared, indicate a clear primary owner and a supporting owner.
- Use this file as a canonical short-form reference inside project READMEs and in release/incident playbooks.
