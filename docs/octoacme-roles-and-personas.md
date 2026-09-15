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
QA/Testing Leads define quality standards, create and oversee test strategies, and validate that delivered work meets acceptance criteria before release.

### Responsibilities
- Define Definition of Done (DoD) for testing and quality gates
- Create and maintain test plans and test cases
- Execute manual and automated testing
- Validate acceptance criteria with product and development teams
- Identify quality risks and propose mitigation
- Coordinate smoke tests and post-deployment verification
- Report quality metrics and test coverage

### Goals
- Ensure features meet quality standards before release
- Reduce production defects and improve reliability
- Provide early feedback on testability and acceptance criteria

### Typical Communication
- Sprint planning and backlog refinement sessions
- Test plan reviews with Product and Development
- Daily updates on test status and blockers
- Quality reports in weekly syncs

### Interaction with Other Roles
- Works closely with Developers on testability and acceptance criteria clarification
- Collaborates with Product Manager to validate feature acceptance
- Coordinates with Release Manager on smoke tests and deployment verification
- Provides quality metrics and risk assessment to Project Manager

---

## Security Lead

### Role Summary
Security Leads embed security requirements and practices into projects, conduct security reviews, and lead incident response.

### Responsibilities
- Define security requirements and acceptance criteria
- Conduct threat modeling and security assessments
- Review code and architecture for security concerns
- Oversee security scanning in CI/CD
- Lead security incident response and post-incident reviews
- Provide guidance on compliance and data protection

### Goals
- Prevent security vulnerabilities and data breaches
- Ensure compliance with organizational and regulatory standards
- Build security into the development process

### Typical Communication
- Security requirements in backlog planning
- Security reviews before release
- Incident response and escalation
- Post-deployment security verification

### Interaction with Other Roles
- Partners with Developers and Technical Leads on architecture and code review
- Escalates security incidents to Project Manager and Sponsor per incident playbook
- Provides security validation gates for Release Manager
- Advises Product Manager on security-related feature implications

---

## Technical Lead/Architect

### Role Summary
Technical Leads provide technical direction, lead design reviews, and ensure technical feasibility. They guide architectural decisions and mitigate technical risks across the project.

### Responsibilities
- Define technical architecture and design standards
- Lead technical design reviews and code reviews
- Identify and mitigate technical risks and dependencies
- Mentor developers and advocate for technical excellence
- Coordinate with external systems and teams on integration points
- Provide technical input to planning and estimation

### Goals
- Ensure scalable, maintainable technical solutions
- Reduce technical debt and rework
- Enable team velocity through good design and practices

### Typical Communication
- Technical design docs and architecture reviews
- Code review and technical discussions
- Planning sessions with estimation and feasibility input
- Risk discussions with Project Manager and Product Lead

### Interaction with Other Roles
- Collaborates with Developers on implementation approaches
- Partners with QA/Testing Lead on testability requirements
- Works with Product Lead on technical feasibility and trade-offs
- Escalates architectural risks to Project Manager

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors are business owners and decision authorities who provide strategic direction, resource approval, and executive oversight of the project.

### Responsibilities
- Define business objectives and success criteria
- Approve project scope, budget, and timeline
- Make escalation decisions and resolve priority conflicts
- Remove organizational blockers
- Receive regular status updates and provide strategic feedback
- Authorize release decisions

### Goals
- Ensure project delivers business value
- Manage organizational risk and resource allocation
- Maintain alignment with strategic priorities

### Typical Communication
- Monthly stakeholder updates and executive briefings
- Escalation and decision requests from Project Manager
- Approval checkpoints during key gates (initiation, planning, release)
- Post-release retrospective insights

### Interaction with Other Roles
- Receives escalations from Project Manager on risks and decisions
- Reviews success metrics and outcomes with Product Manager
- Approves release decisions in coordination with Release Manager
- Provides strategic context for Product Lead

---

## Product Lead

### Role Summary
Product Leads are senior product strategy authorities who set product direction, resolve Product Manager conflicts, and serve as the escalation point for product decisions. They differ from Product Managers in their focus on strategic vision versus execution.

### Responsibilities
- Define product strategy and long-term vision
- Escalation point for Product Manager decisions and conflicts
- Align product roadmap with business and customer strategy
- Mentor Product Managers
- Participate in release and major milestone decisions
- Coordinate between Product Managers and Sponsors

### Goals
- Ensure product strategy aligns with business and customer needs
- Enable consistent product decision-making across initiatives
- Build sustainable, coherent product experiences

### Typical Communication
- Weekly or bi-weekly syncs with Product Manager
- Strategic planning meetings and roadmap reviews
- Escalation decisions on feature conflicts or trade-offs
- Stakeholder and Sponsor briefings on product direction

### Interaction with Other Roles
- Escalation point for Product Manager decisions
- Reviews Product Manager success metrics and impact
- Coordinates with Project Manager on planning trade-offs
- Advises Technical Lead on strategic technical directions
- Recommends to Sponsor on major release decisions

---

## Release Manager

### Role Summary
Release Managers plan, coordinate, and execute releases to production. They ensure releases are safe, well-communicated, and traceable.

### Responsibilities
- Plan release schedules and deployment windows
- Coordinate pre-release readiness (code, tests, documentation)
- Execute or oversee deployment to production
- Run post-deployment verification and smoke tests
- Coordinate rollback and incident response if needed
- Document release notes and communicate releases
- Track release metrics and status

### Goals
- Ensure smooth, risk-reduced deployments
- Maintain production stability and uptime
- Provide clear visibility on release status and changes

### Typical Communication
- Release coordination meetings with engineering and QA
- Pre-deployment checklists and sign-offs
- Release notes and announcements to stakeholders and support
- Post-deployment verification and incident communications

### Interaction with Other Roles
- Works with QA/Testing Lead on smoke tests and deployment verification
- Coordinates with Developers on release readiness and hotfixes
- Reviews Security Lead requirements before deployment
- Reports release status to Project Manager and Stakeholder
- Escalates deployment issues to Technical Lead or Project Manager

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate agile ceremonies, remove blockers, and coach the team on agile practices and continuous improvement. This role is optional and may be combined with Project Manager responsibilities in smaller teams.

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Identify and help remove blockers and impediments
- Coach team on agile principles and practices
- Maintain sprint board and backlog hygiene
- Facilitate conflict resolution and team discussions
- Track team velocity and cycle time metrics
- Advocate for team health and psychological safety

### Goals
- Enable high-performing, self-organizing teams
- Reduce cycle time and improve delivery consistency
- Foster continuous improvement culture

### Typical Communication
- Daily standups and sprint ceremonies
- One-on-ones with team members
- Retrospective facilitation and action item tracking
- Blocker escalations to Project Manager

### Interaction with Other Roles
- Supports Project Manager with ceremony facilitation and team coordination
- Works with all team members to identify and resolve blockers
- Escalates organizational impediments to Project Manager
- Contributes to team health and retrospective outcomes

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Cross-functional teams will include multiple personas working together; refer to the "Interaction with Other Roles" section to understand communication patterns and dependencies.
