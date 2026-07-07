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

### Key Interactions
- **With QA/Testing Lead**: Collaborate on test automation, review test results
- **With Technical Lead**: Receive architectural guidance and design reviews
- **With Project Managers**: Coordinate on sprint planning and blockers
- **With DevOps**: Align on deployment requirements and infrastructure needs

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

### Key Interactions
- **With Project Managers**: Align on sprint priorities and release planning
- **With QA/Testing Lead**: Define acceptance criteria and validate feature acceptance
- **With Sponsors/Stakeholders**: Present progress and gather requirements
- **With Technical Lead**: Assess feasibility and scope of proposed features

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

### Key Interactions
- **With Product Managers**: Coordinate on backlog prioritization and release planning
- **With Scrum Master/Agile Coach**: Facilitate ceremonies and track team velocity
- **With Sponsors/Stakeholders**: Provide status updates and manage expectations
- **With QA/Testing Lead**: Track quality metrics and release readiness
- **With DevOps**: Coordinate deployment scheduling and release planning

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads define testing strategy, establish quality standards, and ensure that delivered features meet acceptance criteria and quality gates before release.

### Responsibilities
- Define testing strategy and acceptance criteria validation approach
- Create and maintain test plans and test cases
- Establish quality gates and exit criteria for features
- Coordinate manual and automated testing efforts
- Identify quality risks and propose testing mitigations
- Report on test coverage and quality metrics
- Participate in acceptance criteria definition during planning

### Goals
- Ensure every release meets quality standards
- Reduce post-release defects through comprehensive testing
- Enable fast, confident deployments
- Maintain visibility into quality trends and metrics

### Key Interactions
- **With Developers**: Review acceptance criteria, provide test results, collaborate on test automation
- **With Product Managers**: Validate that features meet user acceptance criteria
- **With Project Managers**: Report quality status and flag quality risks
- **With Security/Compliance Officer**: Define security test cases and compliance validation
- **With DevOps**: Support staging environment setup and pre-release testing

### Typical Communication
- Sprint planning for test scope estimation
- Daily QA standup updates
- Quality metrics in weekly status reports
- Pre-release quality sign-off
- Test result summaries and defect reports

---

## Technical Lead/Architect

### Role Summary
Technical Leads provide architectural guidance, review technical decisions, and ensure solutions are scalable, maintainable, and aligned with technical strategy.

### Responsibilities
- Define technical approach and architecture for major initiatives
- Review technical designs and code for architectural alignment
- Identify and mitigate technical risks and dependencies
- Mentor developers on technical best practices
- Assess feasibility and estimate technical effort
- Ensure code quality standards and design patterns
- Participate in design reviews and architecture discussions

### Goals
- Deliver scalable, maintainable solutions
- Reduce technical debt and rework
- Build team technical capabilities
- Align solutions with organizational technical strategy

### Key Interactions
- **With Developers**: Review designs and PRs, provide technical guidance
- **With Project Managers**: Highlight technical risks and dependencies
- **With Product Managers**: Assess feasibility of proposed features
- **With Security/Compliance Officer**: Ensure secure architecture and threat modeling
- **With DevOps**: Review infrastructure and deployment requirements

### Typical Communication
- Design reviews and architecture discussions
- Code review feedback
- Technical risk escalations
- Mentoring and knowledge sharing sessions

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters facilitate agile ceremonies, remove team blockers, coach the team on agile practices, and help maintain team velocity and health.

### Responsibilities
- Facilitate daily standups, planning, reviews, and retrospectives
- Remove impediments and blockers affecting the team
- Coach team on agile principles and continuous improvement
- Track sprint metrics and team velocity
- Protect team from external interruptions and scope creep
- Support retrospective action item tracking
- Foster psychological safety and open communication

### Goals
- Maximize team productivity and velocity
- Foster psychological safety and continuous improvement
- Reduce ceremony overhead and meeting fatigue
- Build agile maturity across the team

### Key Interactions
- **With Developers**: Remove blockers, facilitate ceremonies, coach on agile practices
- **With Project Managers**: Coordinate sprint planning and status reporting
- **With Product Managers**: Manage backlog refinement and prioritization ceremonies
- **With all team members**: Support continuous improvement and team health

### Typical Communication
- Daily standup facilitation
- Sprint planning and retrospective leadership
- One-on-ones with team members
- Escalations to PM for blockers requiring management intervention

---

## Sponsor/Stakeholder

### Role Summary
Sponsors and key stakeholders provide business context, approve major milestones, secure resources, and ensure organizational alignment with project objectives.

### Responsibilities
- Define business objectives and success criteria
- Approve project charter and major milestones
- Secure budget and resource allocation
- Provide executive visibility and stakeholder communication
- Escalate or remove organizational blockers
- Review and approve release decisions
- Represent business and organizational interests

### Goals
- Achieve business objectives and ROI
- Maintain stakeholder confidence and alignment
- Enable team success by removing organizational barriers
- Ensure project alignment with organizational strategy

### Key Interactions
- **With Project Managers**: Receive status updates, approve milestones, provide guidance
- **With Product Managers**: Align on business priorities and success metrics
- **With Team**: Participate in kickoff and release reviews
- **With other Sponsors/Stakeholders**: Coordinate across organizational interests

### Typical Communication
- Monthly status briefings
- Milestone approval meetings
- Executive dashboards and metrics
- Escalation path for critical decisions

---

## Security/Compliance Officer

### Role Summary
Security and Compliance Officers ensure that projects meet security standards, regulatory requirements, and organizational policies. They identify and mitigate security risks.

### Responsibilities
- Review security requirements and threat models
- Conduct security reviews of designs and code
- Ensure compliance with regulatory and organizational policies
- Identify and track security risks and vulnerabilities
- Define security acceptance criteria and testing
- Provide security incident response guidance
- Stay current on security standards and emerging threats

### Goals
- Prevent security breaches and data exposure
- Maintain regulatory compliance
- Build security into every release
- Reduce security-related incidents and rework

### Key Interactions
- **With Developers**: Review security design, provide guidance on secure coding
- **With Technical Leads**: Review architecture for security considerations
- **With Project Managers**: Flag security risks and compliance issues
- **With QA/Testing Lead**: Define security test cases and penetration testing approach
- **With DevOps**: Ensure secure deployment and infrastructure practices

### Typical Communication
- Security design reviews
- Risk assessment and mitigation planning
- Security training and awareness
- Pre-release security sign-off

---

## DevOps/Infrastructure Engineer

### Role Summary
DevOps and Infrastructure Engineers manage deployment pipelines, infrastructure, and release operations. They enable reliable, automated deployments and maintain system observability.

### Responsibilities
- Design and maintain CI/CD pipelines and deployment automation
- Manage infrastructure provisioning and scaling
- Ensure deployment reliability and rollback capabilities
- Monitor system health, performance, and observability
- Coordinate production deployments and incident response
- Optimize infrastructure costs and performance
- Support troubleshooting and post-incident analysis

### Goals
- Enable fast, reliable deployments with minimal risk
- Maintain high system availability and performance
- Reduce manual effort through automation
- Enable rapid incident response and recovery

### Key Interactions
- **With Developers**: Support local development environments, review deployment requirements
- **With Release Management/Project Managers**: Coordinate deployment windows and runbooks
- **With QA**: Support staging environment setup and pre-release testing
- **With On-call Teams**: Manage incident response and rollbacks
- **With Security/Compliance Officer**: Ensure secure and compliant infrastructure practices

### Typical Communication
- Deployment planning and coordination
- Infrastructure reviews and capacity planning
- Incident response and postmortems
- Monitoring and observability dashboards

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference these personas when defining escalation paths, communication templates, and decision-making frameworks in other project management documents.
