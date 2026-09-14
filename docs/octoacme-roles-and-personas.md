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
QA/Testing Leads ensure product quality by developing test strategies, validating acceptance criteria, and managing test automation. They collaborate with developers and product managers to define and execute quality standards.

### Responsibilities
- Create test plans aligned with acceptance criteria and Definition of Done
- Execute manual testing and validate acceptance criteria
- Design and maintain automated test suites (unit, integration, end-to-end)
- Identify and document defects with clear reproduction steps
- Perform security and performance testing
- Coordinate user acceptance testing (UAT) with stakeholders

### Goals
- Deliver high-quality features that meet acceptance criteria
- Reduce defects in production through early testing
- Maintain test coverage and reliability of automated tests

### Typical Communication
- Test planning sessions during sprint planning
- Defect reports and test status updates
- Acceptance criteria discussions with Product Managers
- CI/CD integration and feedback on automation

### How these personas interact with other roles
- Work closely with Developers to define testability requirements and validate implementation quality
- Collaborate with Product Managers on acceptance criteria and release readiness
- Partner with DevOps / Release Engineers on deployment validation, smoke tests, and test automation in CI/CD

---

## Technical Lead / Architect

### Role Summary
Technical Leads provide technical direction, review designs, and ensure solutions meet quality and scalability standards. They guide developers on best practices and identify technical risks early.

### Responsibilities
- Review and approve technical designs and architecture decisions
- Guide developers on code quality, performance, and maintainability
- Identify technical risks and propose mitigation strategies
- Mentor junior developers and conduct technical reviews
- Ensure alignment with platform standards and tech debt management
- Lead technical spike investigations when needed

### Goals
- Deliver technically sound, scalable, and maintainable solutions
- Prevent technical debt accumulation
- Support team growth through mentorship
- Enable fast, reliable delivery

### Typical Communication
- Technical design reviews and architecture discussions
- Code review feedback
- Technical risk assessments in planning and standups
- Mentoring sessions with developers

### How these personas interact with other roles
- Mentor Developers and help the team make sound implementation decisions
- Advise Project Managers on technical feasibility, risks, and timeline impact
- Collaborate with Product Managers on solution approaches that balance business value and engineering constraints

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders / Sponsors are executives or business stakeholders who validate business needs, approve scope and budget, and ensure projects align with organizational strategy.

### Responsibilities
- Define business requirements and success metrics
- Provide strategic context and business priorities
- Approve project scope, timeline, and resource allocation
- Serve as escalation point for business-impacting decisions
- Communicate project status to senior leadership
- Provide feedback and sign-off on key deliverables

### Goals
- Ensure projects deliver measurable business value
- Maintain alignment with organizational strategy
- Manage stakeholder expectations and risk
- Enable fast decision-making on trade-offs

### Typical Communication
- Monthly stakeholder briefings
- Decision approvals on scope and changes
- Milestone reviews and release announcements
- Escalation conversations for business-critical issues

### How these personas interact with other roles
- Work with Project Managers for escalations, status communications, and major delivery decisions
- Engage Product Managers on prioritization, business outcomes, and success metrics
- Approve scope, timeline, and resource decisions that affect delivery plans

---

## Scrum Master / Team Lead

### Role Summary
Scrum Masters / Team Leads facilitate ceremonies, remove blockers, coach the team on processes, and ensure adherence to team agreements. They enable smooth execution and continuous improvement.

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Remove impediments and blockers for the team
- Coach team on Agile practices and process adherence
- Track and communicate progress and velocity
- Support team collaboration and psychological safety
- Drive continuous improvement and process adjustments

### Goals
- Enable team productivity and delivery consistency
- Foster continuous learning and improvement culture
- Maintain team morale and psychological safety
- Reduce impediments and cycle time

### Typical Communication
- Daily standups and ceremony facilitation
- Impediment tracking and escalation
- Team retrospectives and process updates
- Velocity and progress reporting

### How these personas interact with other roles
- Partner with Project Managers on schedule visibility and delivery coordination
- Support Developers through impediment removal and healthy team practices
- Work with Product Managers on backlog refinement, sprint planning, and expectation setting

---

## DevOps / Release Engineer

### Role Summary
DevOps / Release Engineers manage build, test, and deployment infrastructure. They enable rapid, safe, and reliable releases through automation and observability.

### Responsibilities
- Build and maintain CI/CD pipelines
- Manage staging and production environments
- Execute production deployments and rollbacks
- Monitor post-deployment health and performance
- Manage infrastructure scaling and reliability
- Document deployment procedures and runbooks

### Goals
- Enable fast, reliable, and frequent deployments
- Minimize deployment risk and reduce time-to-recovery
- Maintain high system availability and performance
- Reduce manual effort through automation

### Typical Communication
- Deployment planning and coordination
- Release notes and deployment procedures
- Post-deployment verification and monitoring
- Infrastructure and performance discussions

### How these personas interact with other roles
- Collaborate with Developers on deployment readiness, observability, and environment requirements
- Work with QA/Testing Leads on smoke test validation and release verification
- Report release status to Project Managers and support incident response when deployments need attention

---

## Security Engineer

### Role Summary
Security Engineers perform security reviews, ensure compliance, conduct threat modeling, and manage security incidents. They embed security throughout the development lifecycle.

### Responsibilities
- Perform security code reviews and vulnerability assessments
- Conduct threat modeling and security design reviews
- Ensure compliance with security policies and standards
- Manage security incidents and post-incident reviews
- Provide security guidance and training to the team
- Maintain security documentation and risk register

### Goals
- Prevent security vulnerabilities and data breaches
- Ensure regulatory compliance and security best practices
- Build security awareness across the team
- Enable secure-by-default development

### Typical Communication
- Security design reviews and threat modeling sessions
- Vulnerability reports and remediation tracking
- Security incident coordination and post-mortems
- Training and guidance to developers

### How these personas interact with other roles
- Partner with Developers on secure coding practices and vulnerability remediation
- Collaborate with Technical Leads / Architects on architecture security and technical controls
- Work with Project Managers on security-related timeline impacts and advise Stakeholders / Sponsors on compliance risk

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
