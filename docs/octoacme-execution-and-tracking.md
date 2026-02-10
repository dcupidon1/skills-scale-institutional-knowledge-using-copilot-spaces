# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- **Daily standups (15 min)** — focus on progress, blockers, dependencies
  - *Attendees*: Developers, QA Lead, UX Designer, DevOps Engineer, Project Manager
  - *Cross-functional updates*: Each role shares progress, QA Lead flags quality concerns, DevOps Engineer reports infrastructure status
  
- **Weekly delivery sync** — show progress, updates, and flagged risks
  - *Attendees*: Project Manager, Product Manager, all execution roles
  - *Cross-functional collaboration*: Review project board, discuss cross-role dependencies, escalate blockers
  
- **Demo/Review at the end of each sprint or milestone**
  - *Attendees*: All team members, stakeholders
  - *Cross-functional showcase*: Developers demo features, UX Designer shows design decisions, QA Lead presents testing results

## Workflows

### Project Board Management
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- **Cross-functional workflow**:
  - *Business Analyst/Product Manager*: Define and prioritize backlog items
  - *UX Designer*: Add design tasks and link to feature work
  - *Developers*: Move items through development and review
  - *QA Lead*: Validate in QA column, move to Done when tests pass
  - *Project Manager*: Track overall flow, identify bottlenecks

### Pull Request Workflow
- Small PRs (<= 400 lines when possible)
- Include issue link and acceptance criteria in PR description
- Run automated tests and linting in CI before requesting review
- Require at least one approval before merging (or team-defined policy)
- **Cross-functional PR involvement**:
  - *Developers*: Create and review PRs, address feedback
  - *UX Designer*: Review UI/UX implementation against design specs
  - *QA Lead*: Review test coverage, may conduct exploratory testing
  - *DevOps Engineer*: Review infrastructure/deployment changes

### Design Review Workflow
- **UX Designer** creates designs and prototypes
- **Product Manager** validates against user needs and business goals
- **Developers** review for technical feasibility
- **QA Lead** identifies testability concerns
- Design handoff includes specs, assets, and acceptance criteria

### Release Workflow
- **QA Lead** completes QA Signoff Checklist (see `template-qa-signoff-checklist.md`)
- **Release Manager** coordinates Release Readiness Checklist (see `template-release-readiness-checklist.md`)
- **DevOps Engineer** executes deployment following runbook
- **Support/Customer Success** prepared with documentation and training
- **Product Manager** monitors success metrics post-release

## Quality & Testing
- Unit tests for new logic (Developer responsibility)
- Integration tests where applicable (Developer + QA Lead collaboration)
- End-to-end smoke tests for critical flows before release (QA Lead)
- Security scanning in CI (DevOps Engineer configures, Developers address findings)
- Manual QA for feature acceptance when needed (QA Lead)
- Accessibility testing (UX Designer + QA Lead)
- Performance testing for critical features (DevOps Engineer + QA Lead)

**Quality Gates**:
- All tests must pass before merge
- Code review approval required
- Security scans must show no critical/high vulnerabilities
- QA signoff required before release (see `template-qa-signoff-checklist.md`)

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- **Level 1: Team-level triage** in daily standup
  - *Action*: Team collaborates on solution, re-assigns work if needed
  - *Roles involved*: All execution team members
  
- **Level 2: Cross-functional escalation**
  - *Action*: Project Manager escalates to Product Lead and dependent teams
  - *Roles involved*: Project Manager, Product Manager, relevant technical leads
  
- **Level 3: Sponsor-level escalation**
  - *Action*: Business-impacting issues escalated to executive sponsors
  - *Roles involved*: Project Manager, Product Manager, Business Analyst, stakeholders

**Escalation Triggers**:
- Critical blocker preventing sprint goal
- Cross-team dependency not being met
- Resource constraints impacting timeline
- Technical risk requiring architectural decision
- Quality issues requiring scope trade-offs

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint (DevOps Engineer)
- [ ] Design system and components ready (UX Designer)
- [ ] Test environments provisioned (DevOps Engineer + QA Lead)
- [ ] Monitoring and alerting configured (DevOps Engineer)
- [ ] Regular demos scheduled (Project Manager)
- [ ] Risk register updated weekly (Project Manager)
- [ ] Quality gates defined and communicated (QA Lead)
- [ ] Cross-functional communication channels established (Project Manager)
- [ ] Support documentation plan in place (Support/Customer Success)
