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

## Scrum Master

### Role Summary
The Scrum Master facilitates Agile ceremonies, coaches the team on continuous improvement, and removes impediments to delivery. They protect the team's focus and help improve process efficiency sprint over sprint.

### Responsibilities
- Facilitate sprint planning, daily standups, sprint reviews, and retrospectives
- Remove blockers and escalate impediments to the Project Manager when needed
- Coach the team on Agile principles and practices
- Track team velocity and help forecast delivery
- Shield the team from unplanned interruptions during a sprint

### Goals
- Maintain a sustainable, predictable delivery cadence
- Continuously improve team processes and collaboration
- Reduce impediment resolution time

### Typical Communication
- Daily standups and sprint ceremonies
- Impediment log and retrospective action items
- Coordination with Project Manager on blockers and risks

### How This Role Interacts With Others
- **Developers**: Runs ceremonies, clears blockers, coaches on Agile practices.
- **Product Managers**: Ensures backlog is groomed and stories are sprint-ready.
- **Project Managers**: Surfaces team-level risks and impediments; aligns on delivery forecasts.

---

## UX Designer / UX Researcher

### Role Summary
UX Designers and Researchers define the user experience strategy, conduct user research, and collaborate with product and engineering to ensure solutions are usable, accessible, and aligned to user needs.

### Responsibilities
- Conduct user interviews, usability tests, and research synthesis
- Create wireframes, prototypes, and design specifications
- Define and maintain UX standards and accessibility guidelines
- Review implemented features against design intent
- Collaborate on acceptance criteria to include usability requirements

### Goals
- Ensure delivered features are intuitive and meet user needs
- Reduce rework caused by usability issues found late in development
- Maintain a consistent product experience across features

### Typical Communication
- Design review sessions with Developers and Product Managers
- Research findings and usability test reports
- Design system and component documentation

### How This Role Interacts With Others
- **Developers**: Provides design specs and reviews implementations; aligns on feasibility trade-offs.
- **Product Managers**: Informs prioritization with research insights; collaborates on feature definition.
- **Project Managers**: Flags design scope changes or research timelines that may affect the schedule.

---

## DevOps Engineer / Platform Engineer

### Role Summary
DevOps / Platform Engineers maintain the infrastructure, CI/CD pipelines, and tooling that enable reliable, repeatable software delivery. They focus on automation, observability, and reducing friction in the release process.

### Responsibilities
- Build and maintain CI/CD pipelines and deployment automation
- Manage infrastructure provisioning, configuration, and reliability
- Define and enforce security, compliance, and observability standards
- Support developers with tooling, environments, and on-call runbooks
- Lead release readiness checks and coordinate production deployments

### Goals
- Maximize deployment frequency while maintaining system stability
- Reduce mean time to recovery (MTTR) for incidents
- Automate quality and compliance gates throughout the pipeline

### Typical Communication
- Release readiness checklists and deployment runbooks
- Incident postmortems and reliability metrics
- Infrastructure change proposals and architecture reviews

### How This Role Interacts With Others
- **Developers**: Provides tooling and environment support; reviews PRs for deployment and security concerns.
- **Product Managers**: Aligns on release windows and infrastructure implications of new features.
- **Project Managers**: Communicates deployment schedules, infrastructure risks, and release blockers.

---

## Business Analyst

### Role Summary
Business Analysts bridge business and technical teams by clarifying requirements, modeling processes, and capturing precise acceptance criteria. They ensure that solutions address real business needs and that stakeholders and engineers share a common understanding.

### Responsibilities
- Elicit, document, and validate business and functional requirements
- Create process models, user stories, and acceptance criteria
- Facilitate requirements workshops and stakeholder interviews
- Identify gaps, inconsistencies, and out-of-scope requests early
- Support UAT planning and sign-off coordination

### Goals
- Reduce ambiguity in requirements before development begins
- Minimize rework caused by misunderstood or incomplete requirements
- Ensure delivered solutions meet documented business objectives

### Typical Communication
- Requirements documents, user stories, and acceptance criteria
- Process diagrams and workflow models
- Workshop facilitation notes and decision logs

### How This Role Interacts With Others
- **Developers**: Clarifies requirements and acceptance criteria; supports technical questions about business rules.
- **Product Managers**: Translates high-level product goals into detailed requirements; validates priorities against business needs.
- **Project Managers**: Flags scope changes, requirement risks, and UAT timelines.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

## Role Interaction Matrix
For a lightweight RACI-like overview of how these roles collaborate across common project activities, see [octoacme-role-interaction-matrix.md](./octoacme-role-interaction-matrix.md).

