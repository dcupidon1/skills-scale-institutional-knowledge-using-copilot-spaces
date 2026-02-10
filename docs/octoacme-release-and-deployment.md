# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged (QA Lead validates)
- Passing CI and security scans (DevOps Engineer confirms)
- Release notes drafted (Release Manager with Product Manager input)
- Rollback / mitigation plan documented (Release Manager + DevOps Engineer)
- Smoke tests prepared (QA Lead)
- Support team briefed (Support/Customer Success prepared)
- Customer communications ready if needed (Product Manager + Support/Customer Success)
- Infrastructure ready for release (DevOps Engineer)

**See `template-release-readiness-checklist.md` for comprehensive pre-release validation.**

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) - *Release Manager*
- [ ] Backup or snapshot (if applicable) - *DevOps Engineer*
- [ ] Deploy to staging and run smoke tests - *DevOps Engineer + QA Lead*
- [ ] QA signoff obtained (see `template-qa-signoff-checklist.md`) - *QA Lead*
- [ ] Go/no-go meeting held with stakeholders - *Release Manager facilitates*
- [ ] Deploy to production (automated pipeline preferred) - *DevOps Engineer*
- [ ] Run post-deploy verifications - *QA Lead + DevOps Engineer*
- [ ] Monitor system health and performance - *DevOps Engineer*
- [ ] Announce release to stakeholders and support - *Release Manager + Product Manager*
- [ ] Support team monitoring for issues - *Support/Customer Success*

**Cross-functional Release Team**:
- *Release Manager*: Coordinates entire process, facilitates decisions
- *QA Lead*: Provides quality signoff and post-deploy validation
- *DevOps Engineer*: Executes deployment and monitors infrastructure
- *Product Manager*: Final approval on release content
- *Support/Customer Success*: Prepared for customer inquiries
- *Developers*: On-call for critical issues

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - **DevOps Engineer**: Trigger incident response and notify on-call team
  - **Release Manager**: Coordinate rollback decision with stakeholders
  - **DevOps Engineer**: Execute rollback to last known-good release if necessary
  - **QA Lead**: Verify system stability post-rollback
  - **Developers + DevOps Engineer**: Triage root cause
  - **Project Manager**: Capture action items and coordinate follow-up
  - **Support/Customer Success**: Monitor customer impact and communicate status

**Incident Response Roles**:
- *Incident Commander*: Release Manager or designated on-call engineer
- *Technical Lead*: Senior Developer or DevOps Engineer
- *Communication Lead*: Project Manager or Product Manager
- *Customer Communication*: Support/Customer Success Manager

## Release Notes Template
- **Release name / number**:
- **Date**:
- **Release Manager**:
- **Summary**: (Product Manager drafts)
- **Notable changes**: (Developers + Product Manager)
- **Migration steps (if any)**: (DevOps Engineer + Developers)
- **Known issues**: (QA Lead)
- **Breaking changes**: (Developers + Product Manager, if applicable)
- **Performance improvements**: (DevOps Engineer)
- **Security fixes**: (Developers + DevOps Engineer)
- **Documentation updates**: (Support/Customer Success)

**Distribution**:
- Internal stakeholders: Release Manager
- Customer-facing: Product Manager + Support/Customer Success
- Technical community: Developers (if open source)
