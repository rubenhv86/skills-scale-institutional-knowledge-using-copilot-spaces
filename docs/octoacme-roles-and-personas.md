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

### Interactions with Other Roles
- **QA/Testing Lead**: Collaborate on test planning, accept QA feedback on defects and test coverage
- **Technical Lead/Architect**: Receive design guidance, architectural decisions, and code quality feedback
- **Scrum Master**: Report blockers and progress in daily standups, receive facilitation support
- **Product Manager**: Receive requirements and acceptance criteria, provide implementation feedback
- **Project Manager**: Report estimates and timeline updates, participate in planning meetings

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

### Interactions with Other Roles
- **Stakeholder/Sponsor**: Present business cases, obtain approval for priorities and resource allocation
- **Design/UX Lead**: Define user experience requirements, validate design solutions
- **Customer/Product Owner**: Gather customer feedback, validate product-market fit
- **Project Manager**: Provide prioritization guidance, review release plans
- **Developers**: Define acceptance criteria, clarify requirements during implementation

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

### Interactions with Other Roles
- **Scrum Master/Agile Coach**: Coordinate sprint planning and delivery cadence, escalate team impediments
- **Stakeholder/Sponsor**: Provide status updates, escalate risks and decisions needing approval
- **DevOps/Release Engineer**: Coordinate release planning and deployment schedules
- **Technical Lead/Architect**: Track technical dependencies and risks, review complexity estimates
- **Product Manager**: Align on priorities and release sequencing

---

## QA/Testing Lead

### Role Summary
QA and Testing Leaders ensure product quality through comprehensive test planning, execution, and quality assurance across all phases of development. They work closely with developers and release engineers to validate solutions meet acceptance criteria and quality standards.

### Responsibilities
- Create and maintain test plans aligned with acceptance criteria
- Execute unit, integration, and end-to-end testing
- Identify, document, and triage defects and quality issues
- Perform security and performance testing in collaboration with Security Lead
- Validate releases before production deployment
- Mentor team on quality best practices and testing standards
- Track test coverage and quality metrics

### Goals
- Deliver high-quality, defect-free releases
- Reduce post-release issues and customer impact
- Establish and maintain quality standards across projects
- Enable fast, reliable feedback loops for developers

### Typical Communication
- Sprint planning and review meetings
- Daily standups and QA status reports
- Test case documentation and defect reports
- Pre-release quality sign-offs with DevOps/Release Engineer
- Quality metrics dashboards

### Interactions with Other Roles
- **Developers**: Collaborate on test planning, provide defect feedback, mentor on testing practices
- **Technical Lead/Architect**: Review test strategies for complex systems, identify critical test paths
- **DevOps/Release Engineer**: Coordinate pre-release smoke tests, validate deployment quality
- **Security Lead**: Coordinate security and compliance testing within test plans
- **Product Manager**: Validate acceptance criteria are testable, demo features for acceptance

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters facilitate agile ceremonies, remove impediments, and coach teams on agile principles to enable continuous delivery and team effectiveness. They focus on team health, velocity, and continuous improvement.

### Responsibilities
- Facilitate daily standups, sprint planning, sprint review, and retrospectives
- Identify and escalate blockers and impediments
- Coach team on agile practices and frameworks
- Maintain team velocity metrics and health indicators
- Protect team from external interruptions and scope creep
- Track and communicate sprint progress
- Support retrospective action item follow-up

### Goals
- Maximize team productivity and psychological safety
- Enable consistent, predictable delivery
- Foster continuous improvement culture
- Reduce cycle time and enable faster feedback

### Typical Communication
- Agile ceremonies facilitation
- Impediment escalations to Project Manager
- Sprint metrics and health dashboards
- Retrospective action item tracking and reviews
- Team coaching and one-on-ones

### Interactions with Other Roles
- **Project Manager**: Escalate team-level impediments and blockers, align on sprint planning
- **Developers**: Facilitate daily communication, remove impediments, coach on agile practices
- **QA/Testing Lead**: Integrate quality into sprint planning, track test coverage metrics
- **Product Manager**: Facilitate backlog refinement and prioritization in sprint planning
- **Technical Lead/Architect**: Address technical impediments, facilitate design discussions

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and project sponsors provide business context, funding, and strategic alignment. They validate business outcomes and make go/no-go decisions for projects and major milestones.

### Responsibilities
- Approve project charter and business case
- Define business success metrics and acceptance criteria
- Provide strategic direction and priority alignment
- Review and approve major deliverables and milestones
- Communicate outcomes to leadership and broader organization
- Support escalations and resource decisions
- Participate in go/no-go decision gates

### Goals
- Ensure project delivers measurable business value
- Maintain alignment with organizational strategy and priorities
- Enable timely decision-making and resource allocation
- Minimize business risk and maximize ROI

### Typical Communication
- Project kickoff and initiation reviews
- Monthly stakeholder updates and demos
- Risk and escalation notifications
- Go/no-go decision gates at key milestones
- Budget and resource approval meetings

### Interactions with Other Roles
- **Project Manager**: Receive status updates, provide approvals and escalation decisions
- **Product Manager**: Review business cases, prioritization rationale, and success metrics
- **Technical Lead/Architect**: Review technical feasibility and risk assessments
- **Scrum Master**: Escalated impediments affecting timelines and commitments
- **DevOps/Release Engineer**: Approve production deployment windows and rollback decisions

---

## Technical Lead / Architect

### Role Summary
Technical Leaders provide architectural guidance, make complex technical decisions, and ensure solutions are scalable, maintainable, and aligned with technical standards. They serve as technical mentors and owners of system design and quality.

### Responsibilities
- Define system architecture, design patterns, and technical standards
- Review technical proposals, designs, and implementation approaches
- Guide technical decisions on trade-offs, technology choices, and dependencies
- Identify technical risks and propose mitigations
- Establish and enforce code quality, testing, and documentation standards
- Mentor developers on technical best practices and design principles
- Conduct architecture reviews and design critiques

### Goals
- Deliver scalable, maintainable, secure technical solutions
- Reduce technical debt and rework
- Enable consistent, high-quality architecture across projects
- Build team technical capability and knowledge

### Typical Communication
- Technical design reviews and architecture discussions
- Code review feedback and standards documentation
- Technical risk identification and mitigation planning
- Knowledge transfer and mentoring sessions
- Architecture decision records (ADRs) and design documentation

### Interactions with Other Roles
- **Developers**: Provide design guidance, code review feedback, mentor on technical practices
- **QA/Testing Lead**: Review test strategies for complex systems, identify testability concerns
- **Project Manager**: Assess technical complexity and effort estimates, escalate technical risks
- **Security Lead**: Collaborate on security architecture and threat modeling
- **DevOps/Release Engineer**: Review deployment requirements and infrastructure implications

---

## DevOps / Release Engineer

### Role Summary
DevOps and Release Engineers own the deployment pipeline, infrastructure, and release processes to enable safe, frequent, and reliable deployments. They ensure systems are observable, scalable, and resilient.

### Responsibilities
- Manage CI/CD pipeline and automation infrastructure
- Plan and execute production deployments with minimal downtime
- Monitor system health, performance, and incident metrics
- Manage infrastructure and environment configuration as code
- Implement disaster recovery, backup, and rollback procedures
- Support incident response and post-mortems
- Establish and maintain operational runbooks and documentation

### Goals
- Enable safe, frequent, and reliable deployments
- Minimize downtime and deployment-related incidents
- Maintain system performance and observability
- Reduce manual effort through automation

### Typical Communication
- Release planning and deployment coordination with Project Manager
- Deployment runbooks and incident playbooks
- System health and performance dashboards
- Post-incident retrospectives and action items
- Infrastructure and deployment documentation

### Interactions with Other Roles
- **Project Manager**: Coordinate release schedules and deployment windows, escalate deployment issues
- **QA/Testing Lead**: Execute pre-release smoke tests, validate deployment quality
- **Developers**: Advise on deployment requirements and infrastructure implications
- **Technical Lead/Architect**: Review infrastructure and deployment architecture
- **Stakeholder/Sponsor**: Escalate critical deployment decisions and rollback decisions

---

## Customer / Product Owner

### Role Summary
Customer representatives and product owners provide the voice of the customer, validate solutions, and ensure delivered products meet real customer needs and use cases. They bridge the gap between the business/customers and the delivery team.

### Responsibilities
- Represent customer needs, pain points, and use cases
- Validate solution usability and value delivery
- Provide feedback on prototypes, beta features, and releases
- Support customer success and adoption
- Identify emerging customer needs and pain points
- Participate in user research, testing, and feedback sessions
- Champion customer perspective in product decisions

### Goals
- Ensure product delivers measurable customer value and solves real problems
- Enable high customer satisfaction and product adoption
- Drive product-market fit and competitive advantage
- Build strong customer relationships and trust

### Typical Communication
- Requirements and acceptance criteria definition with Product Manager
- User research sessions and customer feedback interviews
- Product demos and beta testing feedback
- Customer success and adoption planning
- Voice of customer reporting to Product Manager and stakeholders

### Interactions with Other Roles
- **Product Manager**: Provide customer feedback and validation, guide prioritization decisions
- **Design/UX Lead**: Participate in user research and usability testing
- **Developers**: Clarify use cases and acceptance criteria during implementation
- **QA/Testing Lead**: Validate releases meet customer expectations
- **Project Manager**: Communicate customer-impacting risks and timeline implications

---

## Design / UX Lead

### Role Summary
Design and UX Leaders ensure products are intuitive, accessible, and deliver excellent user experiences through research, design, and usability validation. They advocate for user needs and drive consistency across product experiences.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Establish design systems and consistency standards
- Review interfaces for usability, accessibility, and consistency
- Advocate for user needs in product and technical decisions
- Mentor team on design principles and best practices
- Ensure compliance with accessibility standards (WCAG)

### Goals
- Deliver intuitive, accessible, delightful user experiences
- Reduce user friction and support costs
- Establish consistent, scalable design standards
- Continuously improve usability through feedback and metrics

### Typical Communication
- Design critiques and usability testing sessions
- Design system documentation and component specifications
- User research findings and insights
- Accessibility audits and recommendations
- Design collaboration with developers and product teams

### Interactions with Other Roles
- **Product Manager**: Define user experience requirements, validate design aligns with product goals
- **Customer/Product Owner**: Conduct user research and usability testing
- **Developers**: Collaborate on implementation, clarify design specifications, provide feasibility feedback
- **Technical Lead/Architect**: Address technical feasibility of design solutions
- **QA/Testing Lead**: Validate UI matches design specifications, test accessibility features

---

## Security Lead

### Role Summary
Security Leaders ensure products are secure, compliant, and resilient to threats through security architecture, policy, and incident management. They establish security practices and guide secure development across the organization.

### Responsibilities
- Define security requirements, standards, and frameworks
- Conduct security architecture reviews and threat modeling
- Manage vulnerability scanning, assessment, and remediation
- Lead security incident response and forensic investigations
- Ensure regulatory compliance (SOC2, GDPR, HIPAA, etc.)
- Educate team on security best practices and secure coding
- Manage security dependencies and third-party risk

### Goals
- Deliver secure, compliant, resilient products
- Minimize security incidents and data breaches
- Maintain customer trust and regulatory standing
- Embed security into development culture and practices

### Typical Communication
- Security requirement documentation and threat models
- Vulnerability reports and remediation tracking
- Security incident response and escalations
- Compliance audit and review participation
- Security training and awareness communications

### Interactions with Other Roles
- **Technical Lead/Architect**: Collaborate on security architecture and secure design patterns
- **Developers**: Provide security guidance, code review feedback, and secure coding training
- **QA/Testing Lead**: Coordinate security and compliance testing within test plans
- **DevOps/Release Engineer**: Ensure secure deployment practices and infrastructure hardening
- **Project Manager**: Escalate security risks and compliance requirements to stakeholders
- **Stakeholder/Sponsor**: Report on security posture and compliance status

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference persona interactions to understand cross-functional dependencies and communication patterns in project workflows.
