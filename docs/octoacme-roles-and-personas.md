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
The QA/Testing Lead defines quality standards, owns the test strategy, and ensures that all acceptance criteria are validated before release. They collaborate with product and engineering to design testable features and maintain quality throughout the delivery lifecycle.

### Responsibilities
- Define test strategy and quality gates for each release
- Create and prioritize test plans aligned with acceptance criteria
- Coordinate manual and automated testing efforts
- Validate acceptance criteria are met before PR merge
- Identify and triage quality issues
- Report test coverage and quality metrics
- Participate in release readiness reviews

### Goals
- Ensure features meet quality standards before production
- Minimize regressions and customer-impacting defects
- Maintain fast feedback loops to unblock development

### Typical Communication
- Acceptance criteria review sessions with Product Managers and Developers
- Test status updates in standups and release syncs
- Bug reports and quality metrics in weekly dashboards

### Interaction with Existing Roles
- **With Developers**: Reviews testability of implementations, provides test feedback during code reviews, and collaborates on definition of testable acceptance criteria
- **With Product Managers**: Validates acceptance criteria clarity and feasibility of testing, escalates quality risks and trade-offs
- **With Project Managers**: Reports quality metrics and release readiness status, participates in risk assessments and release planning

---

## Technical Lead/Architect

### Role Summary
The Technical Lead provides technical direction, ensures sound architectural decisions, and manages technical risk. They partner with product leadership to make trade-off decisions and guide the team through complex technical challenges.

### Responsibilities
- Lead technical design reviews and architecture decisions
- Identify technical risks and propose mitigation strategies
- Guide code quality standards and best practices
- Mentor junior developers and support skill development
- Coordinate with dependent teams on technical integrations
- Ensure scalability, performance, and maintainability

### Goals
- Deliver technically sound, maintainable solutions
- Build team capability and technical depth
- Prevent technical debt from accumulating

### Typical Communication
- Technical design documents and RFCs
- Code review leadership and architecture discussions
- Technical risk escalations to Product Manager and Project Manager

### Interaction with Existing Roles
- **With Developers**: Guides technical decisions, leads design reviews, mentors on code quality and best practices
- **With Product Managers**: Advises on technical feasibility and trade-offs, identifies technical risks that impact scope or timeline
- **With Project Managers**: Escalates technical blockers and risks, provides technical input to dependency management and risk registers

---

## Stakeholder / Business Owner

### Role Summary
The Stakeholder or Business Owner represents business interests, defines success criteria, and champions the project with executive leadership. They approve scope changes, participate in key decisions, and communicate business impact to the organization.

### Responsibilities
- Define business objectives and success metrics
- Approve scope, timeline, and resource decisions
- Communicate project status and impact to leadership
- Make prioritization trade-offs between competing demands
- Sponsor escalations and remove organizational blockers

### Goals
- Maximize business value delivered by the project
- Maintain stakeholder alignment and confidence
- Ensure project priorities reflect organizational strategy

### Typical Communication
- Monthly stakeholder updates and demos
- Steering committee meetings for major decisions
- Executive briefings on risks and impact

### Interaction with Existing Roles
- **With Product Managers**: Aligns business objectives with product strategy, approves prioritization decisions, validates success metrics
- **With Project Managers**: Provides business context for decisions, escalates organizational blockers, sponsors resource needs
- **With Developers and QA**: Participates in key demos and validation activities, provides feedback on business value delivery

---

## Scrum Master / Agile Coach

### Role Summary
The Scrum Master facilitates agile ceremonies, removes impediments, and coaches teams on agile principles to enable continuous delivery and team effectiveness.

### Responsibilities
- Facilitate daily standups, sprint planning, and retrospectives
- Identify and escalate blockers and impediments
- Coach team on agile practices and frameworks
- Maintain team velocity and health metrics
- Protect team from external interruptions
- Track and communicate sprint progress

### Goals
- Maximize team productivity and psychological safety
- Enable consistent, predictable delivery
- Foster continuous improvement culture

### Typical Communication
- Agile ceremonies facilitation
- Impediment escalations to Project Manager
- Sprint metrics and health dashboards
- Retrospective action item tracking

### Interaction with Existing Roles
- **With Project Managers**: Escalates blockers and impediments, reports sprint health and velocity metrics
- **With Developers, Product Managers, and QA**: Facilitates collaboration across roles, coaches on agile principles and team dynamics

---

## DevOps / Release Engineer

### Role Summary
The DevOps and Release Engineer owns the deployment pipeline, infrastructure, and release processes to enable safe, frequent, and reliable deployments.

### Responsibilities
- Manage CI/CD pipeline and automation
- Plan and execute production deployments
- Monitor system health, performance, and incidents
- Manage infrastructure and environment configuration
- Implement disaster recovery and rollback procedures
- Support incident response and post-mortems

### Goals
- Enable safe, frequent, and reliable deployments
- Minimize downtime and deployment-related incidents
- Maintain system performance and observability

### Typical Communication
- Release planning and deployment coordination
- Deployment runbooks and incident playbooks
- System health and performance dashboards
- Post-incident retrospectives and action items

### Interaction with Existing Roles
- **With Developers**: Ensures deployment readiness, provides feedback on infrastructure needs and performance
- **With Project Managers**: Coordinates release schedules, reports deployment risks, participates in release planning
- **With QA/Testing Lead**: Validates smoke tests and deployment verification procedures

---

## Security Officer / Security Champion

### Role Summary
The Security Officer ensures products are secure, compliant, and resilient to threats through security architecture, policy, and incident management.

### Responsibilities
- Define security requirements and standards
- Conduct security architecture reviews
- Manage vulnerability scanning and remediation
- Lead security incident response and forensics
- Ensure regulatory compliance (SOC2, GDPR, etc.)
- Educate team on security best practices

### Goals
- Deliver secure, compliant, resilient products
- Minimize security incidents and data breaches
- Maintain customer trust and regulatory standing

### Typical Communication
- Security requirement documentation
- Vulnerability reports and remediation tracking
- Security incident response and escalations
- Compliance audit and review participation

### Interaction with Existing Roles
- **With Developers**: Conducts security reviews, educates on secure coding practices, reviews security-related PRs
- **With Technical Leads**: Partners on security architecture decisions and threat modeling
- **With Project Managers**: Escalates security risks, participates in risk registers and release readiness reviews

---

## UX/Design Lead

### Role Summary
The UX/Design Lead ensures products are intuitive, accessible, and deliver excellent user experiences through research, design, and usability validation.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Establish design systems and consistency standards
- Review interfaces for usability and accessibility
- Advocate for user needs in product decisions
- Mentor team on design principles and best practices

### Goals
- Deliver intuitive, accessible, delightful user experiences
- Reduce user friction and support costs
- Establish consistent, scalable design standards

### Typical Communication
- Design critiques and usability testing sessions
- Design system documentation and specifications
- User research findings and insights
- Accessibility audits and recommendations

### Interaction with Existing Roles
- **With Product Managers**: Partners on feature prioritization to ensure user-centered design, validates solutions with user research
- **With Developers**: Reviews implementations for design consistency and usability, collaborates on accessibility compliance
- **With Project Managers**: Participates in planning to ensure adequate time for design and research activities

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When new scenarios involve multiple roles, refer to the "Interaction with Existing Roles" section to understand cross-functional collaboration patterns.
