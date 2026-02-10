# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles
- **Project Manager (PM)**: coordinates delivery, schedules, risk, communications.
- **Product Manager (PdM)**: defines outcomes, prioritizes backlog, and measures success.
- **Developers**: implement features, collaborate on design and testability.
- **UX Designer**: research user needs, design interfaces, ensure usability and accessibility.
- **QA Lead**: ensure quality through testing strategies, test planning, and release signoff.
- **Release Manager**: orchestrate release process, coordinate deployments, manage release schedules.
- **DevOps Engineer**: build and maintain infrastructure, CI/CD pipelines, and deployment automation.
- **Business Analyst**: translate business requirements into specifications, bridge stakeholders and technical teams.
- **Support/Customer Success**: voice of customer, handle inquiries, provide product feedback.
- **Stakeholders**: provide inputs and approvals.

*See `octoacme-roles-and-personas.md` for detailed role descriptions and inter-role interactions.*

## Key Artifacts
- **Project Charter / One-pager**: problem statement, goals, stakeholders, timeline
- **Roadmap and Release Plan**: prioritized features and release schedule
- **Sprint/Iteration Backlog**: current work items and acceptance criteria
- **Acceptance Criteria & Definition of Done**: quality gates and completion criteria
- **Risk Register**: identified risks, mitigation strategies, and status
- **Retrospective notes and action items**: continuous improvement tracking
- **Release Readiness Checklist**: comprehensive pre-release validation (see `template-release-readiness-checklist.md`)
- **QA Signoff Checklist**: quality validation before deployment (see `template-qa-signoff-checklist.md`)
- **Onboarding Checklist**: new team member integration guide (see `template-onboarding-checklist.md`)
- **Retrospective Template**: structured reflection and improvement process (see `template-retrospective.md`)

## Lifecycle (high-level)
1. **Initiation**: problem statement, stakeholders, high-level timeline.
   - *Key roles*: Project Manager, Product Manager, Business Analyst, Stakeholders
   
2. **Planning**: scope, resources, milestones, dependencies.
   - *Key roles*: Project Manager, Product Manager, Developers, UX Designer, QA Lead, DevOps Engineer
   - *Cross-functional collaboration*: Business Analyst defines requirements, UX Designer creates wireframes, DevOps Engineer assesses infrastructure needs
   
3. **Execution**: build, test, review, iterate.
   - *Key roles*: Developers, UX Designer, QA Lead, DevOps Engineer, Product Manager
   - *Cross-functional collaboration*: Daily standups include all execution roles, UX Designer validates implementation, QA Lead runs continuous testing
   
4. **Release**: deploy, verify, announce.
   - *Key roles*: Release Manager, QA Lead, DevOps Engineer, Support/Customer Success
   - *Cross-functional collaboration*: QA Lead provides signoff, DevOps Engineer executes deployment, Release Manager coordinates, Support prepared for customer impact
   
5. **Close & Retrospective**: capture learnings and next steps.
   - *Key roles*: All team members, Project Manager (facilitator)
   - *Cross-functional collaboration*: All roles contribute feedback, action items assigned across functions

## Communication Cadence
- **Daily standups**: delivery team (Developers, QA Lead, UX Designer, DevOps Engineer) - 15 min
- **Weekly PM + PdM sync**: Project Manager and Product Manager alignment
- **Weekly delivery sync**: cross-functional team progress review (includes all active roles)
- **Bi-weekly design reviews**: UX Designer, Product Manager, Developers
- **Sprint planning**: all execution team members
- **Sprint retrospectives**: all team members (use `template-retrospective.md`)
- **Monthly stakeholder updates**: Project Manager, Product Manager to business stakeholders
- **Release planning meetings**: Release Manager, QA Lead, DevOps Engineer, Product Manager
- **Ad-hoc escalations**: as needed based on role (see `octoacme-roles-and-personas.md` for inter-role interactions)

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
