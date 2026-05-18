# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation hub! This README provides a comprehensive overview of our project management processes and serves as the central entry point for all related documentation.

## Project Management Processes Summary

OctoAcme uses an iterative, customer-first project management approach structured around a five-phase lifecycle designed to deliver customer value while maintaining clear ownership, transparency, and quality. Here's how we run projects:

### Key Workflows & Lifecycle

**Initiation → Planning → Execution → Release → Close & Retrospective**

The **Initiation** phase validates business need through a lightweight Project One-pager, stakeholder alignment, and a go/no-go decision gate. **Planning** transforms approved initiatives into actionable backlogs with prioritized items, acceptance criteria, T-shirt sizing or story points, and a Definition of Done. 

**Execution** follows an agile cadence using GitHub Projects with columns (Backlog, Ready, In Progress, In Review, QA, Done), daily 15-minute standups focused on progress and blockers, and small pull requests (≤400 lines) with automated CI testing before peer review. The **Release** phase includes pre-deployment checklists, staging verification, smoke tests, and documented rollback plans. **Retrospectives** capture learnings and convert them into tracked action items with clear owners and due dates, closing the loop on continuous improvement.

### Personas & Core Roles

OctoAcme defines three primary personas with distinct responsibilities:

- **Developers** design, build, test, and deliver software; they implement features meeting acceptance criteria, write and maintain tests, participate in code reviews, and help identify technical risks.

- **Product Managers** define what should be built by establishing problem statements, prioritizing backlogs, validating solutions through user research, and measuring outcomes against success metrics.

- **Project Managers** coordinate delivery by creating and maintaining timelines, managing risks and dependencies, facilitating meetings (kickoff, planning, retrospectives), and ensuring consistent documentation and status reporting.

Each role has clear ownership and communication touchpoints, preventing ambiguity and enabling smooth cross-functional collaboration.

### Communication Strategies

OctoAcme maintains a disciplined communication cadence with multiple layers:

- **Regular syncs**: Weekly PM-PdM alignment, twice-weekly delivery standups, monthly stakeholder updates
- **Daily standups** (15 min): Focus on progress, blockers, and dependencies
- **Weekly delivery syncs**: Review progress and flag risks
- **Status reporting**: Standardized templates covering progress, next steps, risks/blockers, and decisions needed
- **Risk escalation**: Three-level path (Level 1: team triage → Level 2: PM escalates to Product Lead → Level 3: sponsor-level)
- **Incident communication**: Dedicated protocols with triage summaries, actions, timelines, and blameless retrospectives

This multi-channel approach ensures transparency, alignment, and rapid issue resolution.

### Quality Assurance Practices

Quality is embedded throughout execution, not siloed at the end:

- **Testing strategy**: Unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows
- **CI/CD rigor**: All PRs must pass automated tests and linting before review
- **PR standards**: Small PRs (≤400 lines), clear issue links and acceptance criteria, at least one peer approval
- **Pre-release requirements**: All acceptance criteria met, CI/security scans pass, release notes drafted, rollback plans documented
- **Post-deployment verification**: Smoke tests in staging, automated production deployment, post-deploy checks
- **Metrics tracking**: Velocity, burndown, success metrics, dashboards for errors/latency/usage

## Process Documentation Index

- [Project Management Overview](./octoacme-project-management-overview.md) - Introduction to OctoAcme's approach, roles, and key artifacts
- [Project Initiation Guide](./octoacme-project-initiation.md) - Steps for validating and authorizing new work
- [Project Planning](./octoacme-project-planning.md) - Breaking initiatives into actionable plans and backlogs
- [Execution & Tracking](./octoacme-execution-and-tracking.md) - Day-to-day execution, standups, and progress tracking
- [Risk Management & Communication](./octoacme-risks-and-communication.md) - Risk management and stakeholder communication strategies
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) - Standardized release processes and rollback procedures
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) - Capturing learnings and driving improvements
- [Roles and Personas](./octoacme-roles-and-personas.md) - Detailed role definitions and responsibilities

## How to Use These Docs

1. **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) to understand our approach, roles, and key artifacts.
2. **Starting a project?** Follow the sequence: Initiation → Planning → Execution & Tracking → Release & Deployment → Retrospective & Continuous Improvement.
3. **Need specific guidance?** Use the index above to jump to the relevant process document.
4. **Looking for templates or checklists?** Each process document includes practical tools and templates.

## How to Contribute

We believe in continuous improvement and welcome feedback on our process documentation. To propose updates or improvements:

1. Use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.
2. Describe what content you want to add or update and why.
3. Reference the relevant process document(s).
4. Include suggested content if available.

Your contributions help us scale institutional knowledge and ensure everyone has equal access to our processes and best practices.

## Using These Docs in Copilot Spaces

To leverage these docs as context in Copilot Spaces:
- Add files to `.copilot/` for Copilot Spaces context
- Use the issue template to request updates to process documentation
- Keep docs current and versioned in the repository

---

**Last Updated:** 2026-05-18  
**Maintained by:** OctoAcme Project Management Team  
**Powered by:** Copilot Spaces
