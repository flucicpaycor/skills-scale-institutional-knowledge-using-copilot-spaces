# OctoAcme Project Management Docs

This README is the entry point for OctoAcme's project management process documentation. Use it to quickly onboard new teammates and to find the right process guide during day-to-day project work.

## OctoAcme project management approach

OctoAcme uses a lightweight, iterative project management approach designed to keep teams aligned from idea through delivery. Work begins with project initiation, where teams clarify the business need, define measurable outcomes, identify stakeholders, and decide whether an effort should move into planning. From there, planning turns the initiative into an actionable backlog with acceptance criteria, scope estimates, dependencies, milestones, and a documented definition of done. This creates a structured but flexible foundation that supports incremental delivery rather than large, high-risk launches.

The process depends on clearly defined roles and shared ownership across the team. Project Managers coordinate timelines, risks, communications, and delivery activities, while Product Managers define outcomes, prioritize work, and measure success against customer and business value. Developers are responsible for implementation, testing, and surfacing technical risks, and QA or testing contributors validate that work meets acceptance criteria and quality expectations. Stakeholders support the process by providing input, alignment, and approvals at key points, helping ensure that priorities remain connected to broader business goals.

Communication and visibility are built into every phase of the workflow. OctoAcme emphasizes regular team rhythms such as standups, weekly syncs, sprint reviews, demos, and stakeholder updates to keep progress, blockers, and dependencies visible. Risks are managed through a simple risk register and reviewed continuously, with defined escalation paths from team-level triage through project and product leadership up to sponsors when business impact increases. The documentation also encourages teams to maintain a single source of truth for status, decisions, and release information so that both delivery teams and stakeholders can quickly find current information.

Quality assurance is treated as an ongoing delivery practice rather than a final checkpoint. The execution and release guidance calls for unit tests on new logic, integration testing where needed, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance when appropriate. Pull requests are expected to stay reasonably small, include links to issues and acceptance criteria, and pass automated checks before review and merge. After releases, teams are expected to reflect through retrospectives, capture action items, and feed improvements back into the backlog or documentation, reinforcing a culture of continuous improvement and repeatable execution.

## When and how to use these docs

- **Starting a new project:** begin with the overview and initiation guides.
- **Preparing delivery:** use planning, then execution/tracking guidance.
- **Managing uncertainty:** use the risk and communication guide during planning and execution.
- **Shipping a release:** follow the release and deployment checklist.
- **Closing loops:** run retrospectives and track improvement actions.
- **Clarifying responsibilities:** reference the roles and personas guide.

## Process documents

- [OctoAcme Project Management Overview](./octoacme-project-management-overview.md)  
  High-level principles, roles, key artifacts, lifecycle, and communication cadence.
- [OctoAcme — Project Initiation Guide](./octoacme-project-initiation.md)  
  Defines the one-pager, stakeholder alignment, and go/no-go decision gate.
- [OctoAcme — Project Planning](./octoacme-project-planning.md)  
  Covers backlog creation, estimation, definition of done, milestones, and dependencies.
- [OctoAcme — Execution & Tracking](./octoacme-execution-and-tracking.md)  
  Day-to-day delivery rhythm, PR workflow expectations, quality practices, and escalation.
- [OctoAcme — Risk Management & Communication](./octoacme-risks-and-communication.md)  
  Risk register practices, communication templates, and escalation paths.
- [OctoAcme — Release & Deployment Guide](./octoacme-release-and-deployment.md)  
  Release types, pre-release checks, deployment checklist, and rollback playbook.
- [OctoAcme — Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)  
  Retrospective structure, action-item tracking, and improvement culture.
- [OctoAcme Personas](./octoacme-roles-and-personas.md)  
  Role summaries, responsibilities, goals, and communication patterns for core personas.

## Quick onboarding path (new team members)

1. Read the [Overview](./octoacme-project-management-overview.md) for shared vocabulary and lifecycle context.
2. Review [Personas](./octoacme-roles-and-personas.md) to understand role expectations.
3. Walk through [Initiation](./octoacme-project-initiation.md) and [Planning](./octoacme-project-planning.md) before active project setup.
4. Keep [Execution & Tracking](./octoacme-execution-and-tracking.md), [Risks & Communication](./octoacme-risks-and-communication.md), and [Release & Deployment](./octoacme-release-and-deployment.md) open during delivery.
5. End each sprint/release with [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md).
