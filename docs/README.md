# OctoAcme Project Management Documentation

## Overview

This directory contains comprehensive guidance for how OctoAcme manages projects. Our approach emphasizes customer-first delivery, iterative execution, clear ownership, data-informed decisions, and psychological safety.

OctoAcme follows a structured, lifecycle-based approach to project management that applies to all cross-functional projects delivering product features, services, or integrations. The framework is built on five key phases—**Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**—each guided by core principles and supported by lean, essential artifacts such as project charters, risk registers, sprint backlogs, and retrospective notes.

The organizational structure relies on clear role definition and collaboration among **Project Managers** (who coordinate schedules, risks, and communications), **Product Managers** (who define outcomes and prioritize the backlog), **Developers** (who implement features and maintain quality), **QA/Testing teams**, and **Stakeholders**. Communication cadences are formalized through daily standups, weekly syncs, and monthly stakeholder updates to ensure that decisions are made efficiently and all parties have visibility into project status.

Execution is managed through disciplined workflows grounded in quality and risk management. Teams use project boards with defined columns, enforce small PRs with CI/CD validation, and conduct regular demos and reviews. Risk management operates at three escalation levels—team-level triage, PM escalation to Product Leads, and sponsor-level involvement—with a maintained Risk Register. OctoAcme emphasizes continuous improvement through structured retrospectives and blameless incident postmortems, creating a culture where teams deliver reliably while adapting based on evidence and feedback.

## Quick Start

- **New to OctoAcme projects?** Start with [Project Management Overview](./octoacme-project-management-overview.md)
- **Starting a new initiative?** See [Project Initiation Guide](./octoacme-project-initiation.md)
- **Planning delivery?** Read [Project Planning](./octoacme-project-planning.md)
- **Tracking progress?** Refer to [Execution & Tracking](./octoacme-execution-and-tracking.md)
- **Managing risks?** Check [Risk Management & Communication](./octoacme-risks-and-communication.md)
- **Preparing release?** Review [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- **Capturing learnings?** See [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- **Understanding roles?** Read [Roles & Personas](./octoacme-roles-and-personas.md)

## Project Lifecycle

1. **Initiation**: Validate problem statement, align stakeholders, confirm go/no-go
2. **Planning**: Break into shippable increments, estimate, define dependencies
3. **Execution**: Build, test, review, iterate with clear tracking
4. **Release**: Deploy to production with verification and communication
5. **Close & Retrospective**: Capture learnings and continuous improvements

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named PM and Product Lead
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Key Roles

- **Project Manager**: Coordinates delivery, schedules, risks, communications
- **Product Manager**: Defines outcomes, prioritizes backlog, measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs and approvals

## Communication Cadence

- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly PM + Product Manager sync
- Twice-weekly team standups (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## How to Use These Docs

- Keep project charters and documentation updated in your project repository
- Share relevant process docs with team members and stakeholders
- Adapt processes as needed while maintaining alignment with core principles
- Add project-specific artifacts to `.copilot/` for Copilot Spaces context
- Use issue templates in `.github/ISSUE_TEMPLATE/` to request updates to process documentation
