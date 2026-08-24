# OctoAcme Project Management Docs

This folder contains OctoAcme's project management process documentation. This README is the entry point for orienting new team members and quickly finding the right document.

## Project Management Processes Summary

OctoAcme uses a customer-first, iterative project management lifecycle with clear ownership and data-informed decisions. Projects move through **initiation, planning, execution, release, and retrospective/close**. Initiation starts with a lightweight one-pager covering the problem, SMART objective, success metrics, stakeholders, timeline, risks, dependencies, and proposed team, followed by stakeholder and Product Lead alignment. Planning turns that one-pager into a prioritized backlog with estimates, acceptance criteria, a Definition of Done, identified dependencies, milestones, and a release plan.

Key roles have clearly defined responsibilities: **Project Managers** coordinate schedules, risks, dependencies, resources, meetings, documentation, and stakeholder communication; **Product Managers** own product vision, outcomes, backlog prioritization, and acceptance criteria; **developers** design, implement, test, and document solutions while contributing to estimates and technical risk management; **QA** validates acceptance criteria and quality; and **stakeholders** provide input, approvals, and business context. This ownership model supports accountability while encouraging collaboration and psychological safety.

During execution, teams track work on a project board (Backlog, Ready, In Progress, In Review, QA, Done) and deliver small, testable increments through focused pull requests linked to issues and acceptance criteria. Communication follows a regular rhythm of standups, weekly delivery/PM syncs, stakeholder updates, sprint or milestone demos, and ad-hoc escalations. Risks and dependencies are tracked in a register, reviewed regularly, and escalated from the team to the PM, Product Lead, and sponsor based on business impact.

Quality assurance is integrated throughout delivery: new logic requires unit tests, with integration and end-to-end smoke tests added for critical flows; CI runs automated tests, linting, and security scans before review, and pull requests generally require at least one approval before merging. Before release, acceptance criteria must be complete, CI and security checks must pass, and release notes and rollback plans must be prepared, followed by staging smoke tests. After deployment, teams verify production behavior, communicate the release, and hold retrospectives to capture lessons and track a small number of actionable improvements.

## Process Documentation

- [Project Management Overview](octoacme-project-management-overview.md) — Principles, roles, artifacts, lifecycle, and communication cadence.
- [Project Initiation Guide](octoacme-project-initiation.md) — Business need, stakeholders, success criteria, timeline, and the initiation decision gate.
- [Project Planning](octoacme-project-planning.md) — Kickoff, backlog creation, estimation, Definition of Done, dependencies, risks, and release planning.
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Team rhythm, board workflow, pull requests, quality practices, metrics, and blocker escalation.
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Risk register, risk lifecycle, stakeholder updates, incident communication, and escalation paths.
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Release types, pre-release requirements, deployment checks, rollback, and release notes.
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Retrospective structure, action-item tracking, and continuous improvement practices.
- [Roles & Personas](octoacme-roles-and-personas.md) — Responsibilities, goals, and communication patterns for developers, Product Managers, and Project Managers.

> **Note:** This README should be updated whenever process documents are added, removed, or renamed so it remains an accurate index.
