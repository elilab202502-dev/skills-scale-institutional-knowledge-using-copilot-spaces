# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management Docs. This folder contains comprehensive guidance for managing projects across all phases of the project lifecycle.

## Our Approach

OctoAcme follows a customer-first, iterative delivery model with clear ownership and data-informed decisions. Our project management approach emphasizes psychological safety, transparency, and continuous improvement.

## Project Management Processes Overview

OctoAcme’s project management approach is a lightweight, iterative lifecycle centered on clear outcomes and shared ownership. Projects begin with a focused initiation step (a Project One-pager) to confirm the problem, success metrics, stakeholders, and a go/no‑go decision. Planning converts that approved initiative into a prioritized, estimable backlog and a release/milestone map; teams use a Definition of Done, backlog item templates, and a planning checklist to ensure work is ready for execution. The documented lifecycle follows a clear flow: Initiation → Planning → Execution → Release → Close & Retrospective.

Day‑to‑day work is organized around a simple project board and a disciplined pull request workflow. Boards use columns like Backlog, Ready, In Progress, In Review, QA, and Done to signal state. PR guidance emphasizes small, reviewable changes (<= 400 lines when possible), linking issues and acceptance criteria in PR descriptions, running CI/lint before review, and requiring approvals per team policy. Regular rhythms—daily standups, a weekly delivery sync, and sprint/milestone demos—are used to surface progress, blockers, and dependencies so triage and escalation can happen quickly.

Quality assurance and release practices are explicit and automated where possible. QA expectations include unit and integration tests, end‑to‑end smoke tests for critical flows, security scanning in CI, and manual QA for acceptance as needed. Releases are classified (patch, minor, major) with pre‑release requirements such as passing CI/security scans, release notes, rollback/mitigation plans, and smoke tests; a documented rollback and incident playbook guides incident response and post‑incident learning. Metrics (velocity, burndown, product success measures) and dashboards are recommended for monitoring health and impact.

Risk management and continuous improvement are built into the process. Teams maintain a simple risk register (ID, impact/likelihood, owner, mitigation, status), follow escalation paths from team → PM → Product Lead → Sponsor, and use weekly syncs to review risks and dependencies. Retrospectives after sprints, releases, or incidents capture what went well, what could improve, and a small set of prioritized action items tracked back into the backlog.

## Documentation Index

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)

## Quick Reference: Which Doc Should I Read?

- I'm new and want to understand how we run projects → Project Management Overview
- We're starting a new project or feature → Project Initiation
- I need to create a project plan → Project Planning
- I'm executing and need to track progress → Execution & Tracking
- We're preparing to release → Release & Deployment
- I need to manage or communicate a risk → Risk Management & Communication
- We're running a retrospective → Retrospective & Continuous Improvement
- I want to understand key roles → Roles and Personas
