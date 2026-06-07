# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management process library. This collection of documents provides guidance for running projects with clarity, consistency, and measurable outcomes.

## Overview

OctoAcme uses a lightweight, **customer-centric approach to project management** that emphasizes:

- **Iterative delivery**: ship small, testable increments
- **Clear ownership**: each project has a named Project Manager and Product Lead
- **Data-informed decisions**: measure impact and iterate based on evidence
- **Psychological safety**: encourage feedback, learning, and transparency
- **Stakeholder alignment**: regular communication and decision gates throughout the lifecycle

### Project Lifecycle

All OctoAcme projects follow a consistent five-phase lifecycle:

1. **Initiation** — Validate business need, align stakeholders, confirm go/no-go
2. **Planning** — Break work into shippable increments, identify risks and dependencies
3. **Execution** — Build, test, review, and iterate with clear quality standards
4. **Release** — Deploy to production with safety checks and rollback plans
5. **Retrospective** — Capture learnings and feed improvements back into future projects

### Core Principles & Approach

OctoAcme defines clear roles and responsibilities across three primary personas: **Project Managers** (who coordinate delivery, manage risks, and facilitate communication), **Product Managers** (who define what should be built and prioritize based on customer value), and **Developers** (who implement features, write tests, and collaborate on design decisions). This separation of concerns prevents role confusion and enables teams to operate with psychological safety and clear accountability.

During execution, OctoAcme uses GitHub Projects to visualize workflow through columns (Backlog, Ready, In Progress, In Review, QA, Done) and maintains quality through unit tests, integration tests, end-to-end smoke tests, security scanning in CI, and manual QA when needed. Pull requests follow a discipline of small increments (≤400 lines when possible), inclusion of issue links and acceptance criteria, and require at least one approval before merging. Risk management is continuous, using a lightweight Risk Register reviewed weekly with clear escalation paths: team-level triage in standups → PM escalation to Product Lead and dependent teams → sponsor-level escalation for business-impacting issues.

Release and deployment is standardized to reduce risk through pre-release requirements (acceptance criteria met, CI/security passing, smoke tests prepared, rollback plans documented), and clear incident playbooks for rapid response. After each sprint, release, or significant milestone, teams conduct retrospectives to capture learnings and define 2–3 prioritized action items with clear owners and timelines. This commitment to continuous improvement, combined with measurement of impact and celebration of wins, creates a culture where learnings feed directly back into future projects and organizational practices.

### Communication Cadence

- **Daily standups** (15 min) — Progress, blockers, dependencies
- **Weekly PM + PdM sync** — Alignment and decision-making
- **Twice-weekly delivery team standups** — Focused execution updates (or as agreed)
- **Weekly stakeholder status updates** — Progress, risks, and asks
- **Sprint/milestone demos** — Show progress and gather feedback
- **Monthly executive updates** — High-level status and forward-looking insights

---

## Process Documentation Index

### Getting Started

- **[Project Management Overview](octoacme-project-management-overview.md)** — Start here for a high-level introduction to OctoAcme's approach, roles, and key artifacts

### Phase-Specific Guides

- **[Project Initiation Guide](octoacme-project-initiation.md)** — Validate business need, align stakeholders, and make the go/no-go decision
  - *Use this when*: A new project idea or feature proposal is ready to be explored
  - *Key deliverable*: Project One-pager with problem, goal, success metrics, and resource needs

- **[Project Planning](octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan and backlog
  - *Use this when*: You've received initiation approval and are ready to detail the work
  - *Key deliverable*: Prioritized backlog, release plan, Definition of Done, and risk register

- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Manage day-to-day execution and track progress toward milestones
  - *Use this when*: Your team is actively delivering work
  - *Key practices*: Small PRs, automated tests and security scanning, daily standups, risk escalation

- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardize releases to reduce risk and improve observability
  - *Use this when*: Features are ready to ship to production
  - *Key deliverables*: Release notes, deployment checklist, smoke tests, rollback plan

- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements
  - *Use this when*: A sprint, release, or significant milestone is complete
  - *Key practice*: Run 45–75 minute retrospectives; prioritize 2–3 action items per cycle

### Cross-Cutting Concerns

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks and dependencies
  - *Key practices*: Maintain a Risk Register, escalation paths, stakeholder communication templates

- **[Roles and Personas](octoacme-roles-and-personas.md)** — Detailed role descriptions and responsibilities
  - *Use this when*: Clarifying who owns what, or onboarding new team members into their role

---

## How to Use These Docs

### For New Team Members
1. Start with **[Project Management Overview](octoacme-project-management-overview.md)** to understand the big picture
2. Read **[Roles and Personas](octoacme-roles-and-personas.md)** to find your role and responsibilities
3. Bookmark the **Process Documentation Index** above for quick reference

### For Starting a New Project
Follow this sequence:
1. **[Project Initiation Guide](octoacme-project-initiation.md)** — Validate and authorize the work
2. **[Project Planning](octoacme-project-planning.md)** — Plan the execution
3. **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Deliver and measure progress
4. **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Ship the product
5. **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Learn and improve

### For Ongoing Project Management
Refer to **[Risk Management & Communication](octoacme-risks-and-communication.md)** throughout your project for guidance on escalating blockers, communicating status, and maintaining stakeholder alignment.

---

## Key Artifacts

Projects should maintain these key artifacts in their repository:

- **Project Charter / One-pager** — Problem, goal, success metrics, stakeholders, timeline, risks
- **Roadmap and Release Plan** — Milestones, dependencies, delivery dates
- **Sprint/Iteration Backlog** — Prioritized work items with acceptance criteria and estimates
- **Definition of Done** — Quality standards and checklist for complete work
- **Risk Register** — Active risks, mitigation plans, and status
- **Retrospective Notes** — Learnings, action items, and follow-ups
- **Release Notes** — Changes, migrations, known issues

---

## Continuous Improvement

These process documents are living artifacts. If you identify gaps, improvements, or new guidance that should be captured, please:

1. Open an issue using the **["Add Content to Project Management Process Docs"](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** template
2. Propose the update with rationale and suggested content
3. Collaborate with stakeholders to refine and merge improvements

---

## Questions?

If you have questions about OctoAcme's project management approach:
- Check the relevant phase guide or cross-cutting document above
- Reach out to your Project Manager or Product Manager
- Open an issue to propose clarifications or updates to these docs
