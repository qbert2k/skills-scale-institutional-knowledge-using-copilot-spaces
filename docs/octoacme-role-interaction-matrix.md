# OctoAcme Role Interaction Matrix

This document maps common project lifecycle activities to roles using a lightweight RACI-style matrix.

**Key:** R = Responsible, A = Accountable, C = Consulted, I = Informed

| Activity | Project Manager | Product Manager | Scrum Master | Developer | UX Designer / Researcher | DevOps Engineer | Business Analyst |
|---|---|---|---|---|---|---|---|
| **Initiation** |  |  |  |  |  |  |  |
| Draft project one-pager | R | A | I | I | C | I | C |
| Stakeholder identification & alignment | A | R | I | I | I | I | C |
| Initial risk list | R | C | I | C | I | C | C |
| **Planning** |  |  |  |  |  |  |  |
| Backlog creation & grooming | C | A | R | C | C | C | R |
| Requirements & acceptance criteria | C | A | C | C | C | I | R |
| Sprint / iteration planning | C | C | R | R | C | C | C |
| Release timeline & milestones | R | A | C | C | I | C | C |
| **Execution** |  |  |  |  |  |  |  |
| Feature development | I | I | I | R | C | C | I |
| UX design & prototyping | I | C | I | C | R | I | C |
| Infrastructure & CI/CD setup | I | I | I | C | I | R | I |
| Code review & quality gates | I | I | I | R | I | A | I |
| Daily standup facilitation | I | I | R | C | I | I | I |
| Impediment resolution | A | C | R | C | I | C | I |
| **Release & Deployment** |  |  |  |  |  |  |  |
| Release readiness checklist | A | C | C | C | C | R | I |
| Production deployment | I | I | I | C | I | R | I |
| Release notes | C | A | I | C | I | C | C |
| Rollback decision | A | C | C | C | I | R | I |
| **Risk & Communication** |  |  |  |  |  |  |  |
| Risk register ownership | R | C | C | C | I | C | C |
| Stakeholder status updates | R | A | I | I | I | I | I |
| Escalation management | R | A | C | I | I | C | I |
| **Retrospective** |  |  |  |  |  |  |  |
| Retrospective facilitation | C | I | R | C | C | C | I |
| Action item tracking | R | C | C | C | I | C | I |
| Process improvement proposals | C | C | R | C | C | C | C |

---

## Notes

- This matrix is a guide, not a rigid rulebook. Teams should adapt assignments to their context.
- For small teams, one person may cover multiple roles (e.g., Project Manager + Scrum Master).
- Revisit the matrix at project kickoff to confirm ownership for the specific project.

## Related Documents
- [Roles & Personas](./octoacme-roles-and-personas.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Release & Deployment](./octoacme-release-and-deployment.md)
- [Risks & Communication](./octoacme-risks-and-communication.md)
