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

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads own quality assurance strategy, test planning, and validation of acceptance criteria across the project lifecycle. They ensure that all deliverables meet quality standards before release.

### Responsibilities
- Develop and maintain test plans and test cases aligned with acceptance criteria
- Coordinate manual and automated testing activities
- Execute smoke tests, regression tests, and end-to-end testing
- Collaborate with developers on test coverage and CI/CD integration
- Identify and triage quality issues with severity levels
- Validate readiness for release and production deployment
- Track and report quality metrics

### Goals
- Ensure all acceptance criteria are met before release
- Maintain high quality and minimize post-release defects
- Reduce manual testing effort through automation
- Enable fast, confident deployments

### Typical Communication
- Sprint planning and backlog refinement sessions
- Definition of Done validation discussions
- Daily standups (status of test execution)
- Release readiness sign-offs
- Quality metrics and test coverage reports

### Interaction with Other Personas
- **With Developers**: Collaborates on test requirements, test coverage targets, and automation strategies
- **With Product Managers**: Validates acceptance criteria and confirms feature completeness
- **With Project Managers**: Provides quality status and release readiness assessments
- **With Technical Lead**: Reviews test plans for technical completeness

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors represent business interests, strategic priorities, and approval authority for project direction and major milestones. They ensure alignment with organizational goals and enable decision-making.

### Responsibilities
- Provide business context and success metrics definition
- Approve project charter and major scope changes
- Validate alignment with organizational strategy
- Participate in Go/No-Go decisions and gate reviews
- Support escalation and removal of organizational blockers
- Communicate project status to executive leadership
- Champion project value and secure organizational support

### Goals
- Ensure project delivers measurable business value
- Maintain strategic alignment and priority
- Reduce risk through active governance
- Enable rapid decision-making

### Typical Communication
- Project initiation and planning kickoff
- Monthly or milestone-based status updates
- Decision gates and go/no-go reviews
- Escalation channels for strategic blockers
- Executive-level progress reporting

### Interaction with Other Personas
- **With Project Managers**: Receives status updates and escalations; approves major changes
- **With Product Managers**: Provides strategic direction and business priorities
- **With Development Team**: Participates in milestone reviews and release ceremonies

---

## Technical Lead/Architect

### Role Summary
Technical Leads and Architects provide technical strategy, design guidance, and ensure architectural soundness of solutions. They mentor the team and reduce technical risk.

### Responsibilities
- Define technical approach and architecture for major features
- Guide technical design decisions and trade-offs
- Identify technical dependencies and integration points
- Conduct code and design reviews for complex components
- Mentor developers on technical best practices
- Assess technical feasibility and scalability risks
- Document architectural decisions and rationale

### Goals
- Ensure solutions are technically sound and maintainable
- Reduce technical debt and architectural risk
- Share knowledge across the team
- Enable long-term system health and scalability

### Typical Communication
- Technical design reviews before implementation
- Architecture decision records (ADRs) and documentation
- Code and design review feedback
- Sprint planning for technical complexity assessment
- Technical risk identification and mitigation

### Interaction with Other Personas
- **With Developers**: Provides architecture guidance and code review feedback
- **With Project Managers**: Assesses feasibility and provides estimates for technical complexity
- **With QA/Testing Lead**: Reviews test plans for technical adequacy
- **With DevOps Engineer**: Collaborates on infrastructure and deployment requirements

---

## Security/Compliance Officer

### Role Summary
Security and Compliance Officers ensure security requirements, compliance standards, and privacy controls are integrated throughout the project lifecycle. They protect the organization and customers from security and regulatory risks.

### Responsibilities
- Define security requirements and acceptance criteria
- Review architecture and implementation for security risks
- Conduct security testing and scanning validation
- Ensure compliance with regulatory and policy requirements
- Identify and track security-related risks
- Participate in incident response and post-incident reviews
- Maintain security documentation and compliance records

### Goals
- Deliver secure, compliant solutions
- Prevent security incidents and data breaches
- Maintain customer trust and regulatory standing
- Integrate security early rather than as an afterthought

### Typical Communication
- Security requirements definition during planning
- Security review of architecture and PRs
- CI/CD security scanning and vulnerability management
- Incident triage and response coordination
- Compliance reporting and audit coordination

### Interaction with Other Personas
- **With Developers**: Reviews code and provides security guidance
- **With Technical Lead**: Reviews architecture for security risks
- **With Project Managers**: Escalates security blockers and tracks security-related risks
- **With DevOps Engineer**: Ensures infrastructure meets security standards

---

## DevOps/Infrastructure Engineer

### Role Summary
DevOps and Infrastructure Engineers own infrastructure, deployment pipelines, observability, and operational readiness for production systems. They enable reliable, scalable operations.

### Responsibilities
- Design and maintain CI/CD pipelines and deployment infrastructure
- Ensure infrastructure scalability and reliability
- Implement monitoring, logging, and alerting
- Support deployment and rollback procedures
- Optimize performance and reduce operational overhead
- Collaborate on infrastructure-as-code and infrastructure requirements
- Support incident response and operational troubleshooting

### Goals
- Enable fast, safe deployments
- Maintain system reliability and performance
- Reduce time-to-resolution for operational issues
- Automate and scale infrastructure efficiently

### Typical Communication
- Infrastructure planning during project planning phase
- CI/CD pipeline reviews and improvements
- Deployment coordination and post-deploy verification
- Incident response and root cause analysis
- Performance metrics and operational dashboards

### Interaction with Other Personas
- **With Developers**: Supports CI/CD pipeline and provides deployment guidance
- **With Technical Lead**: Collaborates on infrastructure and scalability requirements
- **With Project Managers**: Coordinates deployment schedules and operational readiness
- **With Security Officer**: Ensures infrastructure meets security and compliance standards

---

## How These Personas Work Together

### Cross-Persona Dependencies and Communication Flow

**Project Initiation**: Stakeholder + Product Manager + Project Manager define scope and priorities

**Planning Phase**: Technical Lead assesses feasibility; Security Officer defines requirements; QA Lead develops test strategy; DevOps Engineer plans infrastructure

**Execution Phase**: Developers implement; Technical Lead provides guidance; QA Lead validates; DevOps Engineer maintains pipelines

**Release Phase**: QA Lead signs off on quality; DevOps Engineer coordinates deployment; Security Officer validates compliance; Project Manager communicates status to Stakeholder

**Post-Release**: DevOps Engineer monitors operations; Team participates in retrospective to capture learnings

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference specific personas when documenting responsibilities, communication, and decision-making in project processes.
