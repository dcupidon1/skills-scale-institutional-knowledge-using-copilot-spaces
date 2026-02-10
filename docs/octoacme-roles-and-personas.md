# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

### Inter-role Interactions
- **With Product Managers**: Clarify requirements, discuss technical feasibility, estimate effort
- **With UX Designer**: Review design feasibility, collaborate on implementation approach
- **With QA Lead**: Coordinate on test coverage, pair on test automation, fix bugs
- **With DevOps Engineer**: Optimize CI/CD, troubleshoot deployment issues, improve observability
- **With Project Managers**: Provide progress updates, flag technical risks and blockers

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

### Inter-role Interactions
- **With Developers**: Define requirements, review technical proposals, prioritize backlog
- **With UX Designer**: Align on user needs, review design solutions, validate prototypes
- **With Business Analyst**: Validate business requirements, clarify market needs
- **With QA Lead**: Define quality standards, review acceptance criteria
- **With Support/Customer Success**: Gather customer feedback, prioritize issues and feature requests

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

### Inter-role Interactions
- **With All Team Members**: Coordinate schedules, track progress, facilitate communication
- **With Product Managers**: Align on priorities, manage scope changes, escalate risks
- **With Release Manager**: Coordinate release schedules, manage dependencies
- **With DevOps Engineer**: Track infrastructure readiness, manage technical constraints
- **With Business Analyst**: Monitor requirements status, manage scope baseline

---

## UX Designer

### Role Summary
UX Designers research user needs, design interfaces, and ensure products are intuitive and accessible. They work closely with Product Managers to translate user requirements into design solutions and collaborate with Developers to ensure designs are implemented correctly.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and prototypes
- Design user flows and information architecture
- Maintain design systems and UI component libraries
- Collaborate with developers on implementation feasibility
- Validate implementations against design specifications

### Goals
- Create intuitive, accessible user experiences
- Reduce user friction and support costs
- Maintain consistent design language across products
- Validate designs through user feedback and data

### Typical Communication
- Design critiques and review sessions
- User research findings and personas
- Figma/design tool annotations and handoff specs
- Collaboration with Product and Engineering on feasibility

### Inter-role Interactions
- **With Product Managers**: Align on user needs, prioritize design work, validate solutions
- **With Developers**: Review implementation feasibility, provide design specs, validate UI
- **With QA Lead**: Define acceptance criteria for UI/UX, review test scenarios
- **With Business Analysts**: Understand business requirements, user workflows

---

## QA Lead

### Role Summary
QA Leads ensure software quality through comprehensive testing strategies, test planning, and quality metrics. They coordinate testing efforts, define acceptance criteria, and act as gatekeepers for release readiness.

### Responsibilities
- Develop test strategies and test plans
- Define and maintain quality standards and metrics
- Coordinate manual and automated testing efforts
- Review acceptance criteria and definition of done
- Sign off on release readiness
- Identify and track quality risks and technical debt
- Mentor team members on testing best practices

### Goals
- Prevent defects from reaching production
- Maintain high test coverage and quality metrics
- Reduce regression incidents and customer-reported bugs
- Enable continuous delivery through automated testing

### Typical Communication
- Test plans and test case reviews
- QA signoff reports and release readiness assessments
- Bug triage meetings and quality metrics dashboards
- Coordination with developers on test automation

### Inter-role Interactions
- **With Developers**: Review test coverage, coordinate bug fixes, pair on test automation
- **With Product Managers**: Validate acceptance criteria, prioritize quality vs. speed trade-offs
- **With Release Manager**: Provide release readiness assessment, coordinate deployment testing
- **With Project Managers**: Report on quality metrics, flag quality risks

---

## Release Manager

### Role Summary
Release Managers orchestrate the release process from code freeze to production deployment. They coordinate cross-team activities, manage release schedules, and ensure smooth deployments with minimal disruption.

### Responsibilities
- Plan and coordinate release schedules
- Manage release branches and version control
- Coordinate deployment activities across environments
- Ensure release documentation is complete
- Monitor deployment health and coordinate rollbacks if needed
- Maintain release calendars and communicate release status
- Facilitate go/no-go decision meetings

### Goals
- Deliver reliable, on-time releases
- Minimize deployment risks and production incidents
- Maintain clear release documentation and audit trails
- Improve release cycle time and deployment frequency

### Typical Communication
- Release planning meetings and go/no-go decisions
- Release notes and deployment runbooks
- Stakeholder notifications and status updates
- Post-deployment reports and retrospectives

### Inter-role Interactions
- **With QA Lead**: Review test results, coordinate release signoff
- **With DevOps Engineer**: Plan deployments, coordinate infrastructure changes
- **With Product Managers**: Align on release content and timing
- **With Project Managers**: Coordinate cross-project dependencies, manage release risks
- **With Support/Customer Success**: Communicate release timing, prepare for customer impact

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain the infrastructure, CI/CD pipelines, and deployment automation that enable rapid, reliable software delivery. They bridge development and operations, focusing on automation, monitoring, and reliability.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage infrastructure as code and cloud resources
- Implement monitoring, logging, and alerting systems
- Automate deployment and operational tasks
- Ensure system security, scalability, and reliability
- Support incident response and troubleshooting
- Optimize build and deployment performance

### Goals
- Enable fast, safe deployments with high automation
- Maintain high system availability and performance
- Reduce operational toil through automation
- Provide visibility into system health and performance

### Typical Communication
- Infrastructure design reviews and technical documentation
- Incident response and post-mortems
- Performance and reliability metrics
- Automation and tooling guidance for teams

### Inter-role Interactions
- **With Developers**: Provide CI/CD guidance, optimize build pipelines, support debugging
- **With Release Manager**: Coordinate deployments, manage infrastructure for releases
- **With QA Lead**: Provide test environments, integrate test automation in pipelines
- **With Project Managers**: Report on infrastructure readiness, flag technical constraints

---

## Business Analyst

### Role Summary
Business Analysts bridge business stakeholders and technical teams, translating business requirements into actionable specifications. They analyze processes, gather requirements, and ensure solutions meet business objectives.

### Responsibilities
- Gather and document business requirements
- Analyze current processes and identify improvement opportunities
- Create functional specifications and user stories
- Facilitate requirements workshops and stakeholder meetings
- Validate solutions against business needs
- Support user acceptance testing (UAT)
- Maintain requirements traceability

### Goals
- Ensure solutions deliver measurable business value
- Bridge communication between business and technical teams
- Reduce rework through clear, validated requirements
- Improve process efficiency and effectiveness

### Typical Communication
- Business requirements documents (BRDs)
- Process flow diagrams and use case documentation
- Stakeholder interview notes and requirement workshops
- UAT plans and business validation reports

### Inter-role Interactions
- **With Product Managers**: Collaborate on product vision, validate market requirements
- **With Developers**: Clarify requirements, answer business logic questions
- **With UX Designer**: Provide business context for design decisions
- **With QA Lead**: Define business acceptance criteria, support UAT
- **With Project Managers**: Provide requirement status, identify scope changes

---

## Support/Customer Success

### Role Summary
Support and Customer Success professionals are the voice of the customer, ensuring users get value from products and providing critical feedback to improve the product. They handle customer inquiries, track issues, and advocate for customer needs.

### Responsibilities
- Respond to customer inquiries and support tickets
- Troubleshoot and resolve customer issues
- Document common issues and solutions in knowledge base
- Escalate product bugs and feature requests
- Provide customer feedback to product and engineering teams
- Track customer satisfaction and support metrics
- Create user documentation and training materials
- Conduct customer onboarding and training

### Goals
- Maximize customer satisfaction and retention
- Reduce time-to-resolution for customer issues
- Provide actionable product feedback to teams
- Enable customer self-service through documentation

### Typical Communication
- Support ticket responses and escalations
- Customer feedback reports and satisfaction surveys
- Knowledge base articles and user guides
- Product feedback sessions with Product and Engineering

### Inter-role Interactions
- **With Product Managers**: Share customer feedback, prioritize feature requests
- **With Developers**: Report bugs, validate fixes, provide reproduction steps
- **With Release Manager**: Prepare for customer impact of releases, update documentation
- **With QA Lead**: Provide real-world usage scenarios, validate fixes
- **With UX Designer**: Share usability feedback, participate in user research

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The inter-role interactions show how these personas collaborate throughout the project lifecycle.

