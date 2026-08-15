# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management documentation hub. These guides provide a standardized framework for managing projects across our organization, centralizing the processes, roles, and artifacts teams rely on to deliver work predictably and with quality.

OctoAcme follows a lightweight, iterative lifecycle: Initiation (validate the business need and align stakeholders), Planning (create a prioritized, estimable backlog and define Done), Execution (build in small increments with CI, reviews, and tracking), Release (pre-release checks, smoke tests, and rollback plans), and Retrospective (capture learnings and convert them into action). Key artifacts — the project one‑pager, roadmap, backlog, risk register, and release notes — act as the single sources of truth for decisions and progress.

Workflows emphasize small, reviewable increments and clear handoffs: a project board with Backlog → Ready → In Progress → In Review → QA → Done, guidance for small PRs that include issue links and acceptance criteria, and automated CI checks before requesting review. Planning uses a structured backlog item template and timeboxed sprint planning; risks and cross-team dependencies are tracked explicitly and escalated through defined channels. Releases require passing CI and security scans, documented rollback plans, and post-deploy verification.

Personas and responsibilities are defined to ensure ownership and alignment: Project Manager (delivery coordination, schedules, risk and communication), Product Manager (outcomes, prioritization, success metrics), Developers (implementation, tests, reviews), and QA (validation and acceptance). Communication cadence includes daily standups for blockers, weekly PM–PdM syncs and delivery updates, regular demos at the end of sprints, and monthly stakeholder updates. Quality practices include unit and integration tests, end-to-end smoke tests for critical flows, security scanning in CI, dashboards for monitoring velocity and product signals, and retrospectives that turn findings into tracked action items.

## Quick Start
New to OctoAcme? Start with the [Project Management Overview](octoacme-project-management-overview.md) for a concise introduction to our approach, core roles, and key artifacts.

## Project Lifecycle
1. Initiation — Validate business need, create one‑pager, confirm stakeholders  
2. Planning — Kickoff, prioritize backlog, estimate, define DoD  
3. Execution — Implement small increments, CI, reviews, tracking  
4. Release — Pre‑release checks, deploy with rollback plan, verify  
5. Retrospective — Capture learnings and create action items

## Documentation Index
- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

## How to use these docs
- Start at the Overview to understand principles and roles, then open the phase-specific guide that matches your current activity (Initiation → Planning → Execution → Release → Retrospective).
- Keep project-specific artifacts (one-pager, roadmap, risk register) in the project repo and link them from the project README so this hub remains the canonical process reference.
- To propose changes to these docs, use the "Add Content to Project Management Process Docs" issue template in .github/ISSUE_TEMPLATE/ and link the issue in your PR.

## Core Principles
- Customer-first: prioritize customer value and usability  
- Iterative delivery: ship small, testable increments  
- Clear ownership: each project has a named PM and Product Lead  
- Data-informed decisions: measure impact and iterate  
- Psychological safety: encourage feedback and learning
