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
QA and Testing Leads own the quality assurance strategy, test automation, and validation processes. They work with developers and product managers to define acceptance criteria and ensure features meet quality standards before release.

### Responsibilities
- Develop and maintain test strategies and plans for projects
- Build and maintain test automation frameworks and suites
- Collaborate with developers on acceptance criteria and edge cases
- Conduct functional, integration, and regression testing
- Identify and document defects with clear reproduction steps
- Validate readiness for release through smoke and acceptance testing
- Report quality metrics and trends to the PM and team

### Goals
- Deliver zero-defect releases and maintain customer trust
- Reduce time spent on manual testing through automation
- Identify quality issues early in the development cycle

### Typical Communication
- Sprint planning and backlog refinement discussions
- QA sign-off gates before merging PRs and releases
- Weekly quality metrics reports
- Bug triage and defect review sessions

### Interaction with Other Roles
- **Developers**: Collaborate on test cases, acceptance criteria refinement, and edge case identification
- **Product Managers**: Validate feature acceptance and ensure quality aligns with customer expectations
- **Project Managers**: Provide quality metrics and readiness assessments for release planning
- **Tech Leads**: Partner on test automation strategy and technical quality standards

---

## Tech Lead / Architect

### Role Summary
Tech Leads and Architects provide technical direction, review architectural decisions, and mentor developers. They ensure technical solutions are scalable, maintainable, and aligned with long-term product vision.

### Responsibilities
- Design technical solutions and review design decisions
- Mentor developers and support code review processes
- Identify technical risks and propose mitigations
- Evaluate and recommend technology choices and frameworks
- Collaborate with Product and Project leads on feasibility and effort
- Champion code quality, testing, and documentation standards
- Support capacity planning and technical debt management

### Goals
- Deliver scalable, maintainable technical solutions
- Reduce technical debt and minimize future rework
- Build a strong, skilled engineering team

### Typical Communication
- Technical design reviews and RFC (Request for Comment) sessions
- Code review and architecture guidance
- Planning and capacity estimation sessions
- Risk identification and mitigation planning

### Interaction with Other Roles
- **Developers**: Provide architectural guidance, mentorship, and code review feedback
- **Product Managers**: Collaborate on feasibility assessments and technical trade-offs
- **Project Managers**: Support effort estimation and identify technical dependencies
- **QA/Testing Leads**: Define testability requirements and technical quality standards

---

## Security/Compliance Officer

### Role Summary
Security and Compliance Officers review security requirements, conduct security assessments, and ensure projects meet compliance and data protection standards.

### Responsibilities
- Review project requirements for security and compliance implications
- Conduct security assessments and threat modeling
- Define security acceptance criteria and testing requirements
- Review code changes for security vulnerabilities
- Maintain and update security scanning in CI/CD pipelines
- Advise on data privacy, encryption, and access control
- Support incident response and post-incident reviews

### Goals
- Prevent security breaches and data loss
- Ensure compliance with regulations and organizational policy
- Embed security practices into the development lifecycle

### Typical Communication
- Security review gates in planning and development
- Weekly or milestone-based security scanning reports
- Risk register updates for security-related items
- Post-incident security retrospectives

### Interaction with Other Roles
- **Developers**: Conduct security reviews, provide vulnerability feedback, and advise on secure coding practices
- **Product Managers**: Identify security requirements and compliance implications early in planning
- **Project Managers**: Flag security risks and escalate compliance concerns
- **Tech Leads**: Review architecture decisions for security impact and recommend secure frameworks

---

## Design/UX Lead

### Role Summary
Design and UX Leads define user experience, create design systems, and ensure all features meet usability and accessibility standards. They bridge customer needs with engineering implementation.

### Responsibilities
- Define user experience and interaction patterns
- Create and maintain design systems and style guides
- Conduct user research and usability testing
- Review feature designs for usability and accessibility
- Collaborate with developers on design implementation and edge cases
- Support user acceptance testing and feedback incorporation
- Advocate for user-centered design in prioritization and planning

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user confusion and support burden
- Maintain consistency across products and features

### Typical Communication
- Design reviews and design system governance
- Backlog refinement and acceptance criteria definition
- User testing and feedback sessions
- Planning and roadmap alignment on user experience impact

### Interaction with Other Roles
- **Developers**: Collaborate on design implementation, component creation, and accessibility compliance
- **Product Managers**: Partner on user research, validate product concepts, and align on user needs
- **Project Managers**: Provide design dependencies and timeline estimates for UX-heavy features
- **QA/Testing Leads**: Define usability test scenarios and accessibility acceptance criteria

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate agile ceremonies, remove team blockers, and help the team adopt agile best practices. They serve as process experts and enablers of continuous improvement.

### Responsibilities
- Facilitate sprint planning, daily standups, retrospectives, and reviews
- Remove blockers and impediments that slow team progress
- Coach team members on agile principles and practices
- Monitor and improve team velocity and sprint predictability
- Foster psychological safety and encourage open communication
- Support escalation of risks and dependencies to appropriate stakeholders
- Track and share team metrics and health signals

### Goals
- Enable the team to deliver consistently and predictably
- Build a high-performing, self-organizing team
- Promote continuous improvement and learning mindset

### Typical Communication
- Daily standups and sprint ceremonies
- One-on-ones with team members to identify blockers
- Retrospective facilitation and action item tracking
- Escalation to Project Managers and Product Leads as needed

### Interaction with Other Roles
- **All Roles**: Act as process facilitator, blocker remover, and team health advocate
- **Project Managers**: Work together to manage dependencies and escalations
- **Developers**: Coach on agile practices and help remove impediments
- **Product Managers**: Support with sprint planning and backlog refinement processes

---

## Stakeholder / Business Sponsor

### Role Summary
Stakeholders and Business Sponsors provide business context, strategic direction, and approvals for project decisions. They represent customer needs and business priorities to the delivery team.

### Responsibilities
- Define business objectives and success metrics
- Provide business context and strategic alignment
- Approve scope changes and trade-off decisions
- Escalate blockers that require executive attention
- Communicate project status to broader organization
- Support team access to customer and market insights
- Validate that delivered solutions meet business needs

### Goals
- Ensure project delivers measurable business value
- Maintain alignment between team delivery and strategic priorities
- Minimize scope creep and unplanned changes
- Enable timely decision-making and escalations

### Typical Communication
- Monthly stakeholder updates and status briefings
- Scope approval and change management gates
- Executive escalations for business-critical decisions
- Launch announcements and success celebrations

### Interaction with Other Roles
- **Project Managers**: Collaborate on status reporting and escalation paths
- **Product Managers**: Partner on business requirements and success metrics definition
- **Developers & Tech Leads**: Provide business rationale for technical decisions
- **All Roles**: Offer strategic context for priorities and decisions

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Understand how personas interact across the project lifecycle (initiation, planning, execution, release, retrospective).
- Reference persona responsibilities when defining roles for specific projects or teams.
