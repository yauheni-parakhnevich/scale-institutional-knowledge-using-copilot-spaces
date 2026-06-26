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
QA/Testing Leads own quality assurance strategy and execution. They validate that features meet acceptance criteria, identify defects, and ensure release readiness.

### Responsibilities
- Design and execute test plans for features and releases
- Validate acceptance criteria before PR approval
- Identify and triage defects; prioritize regressions
- Coordinate end-to-end and smoke testing before release
- Provide quality metrics and coverage reports
- Collaborate with developers on testability and CI configuration

### Goals
- Ensure predictable, high-quality releases
- Reduce post-release defects and customer impact
- Enable fast, confident deployment cycles

### Key Interactions
- **Developers**: feedback on test coverage, reproducibility, and acceptance criteria clarity
- **Product Managers/PdM**: alignment on Definition of Done and QA acceptance gates
- **Project Manager**: coordination of testing timelines and release readiness
- **Technical Lead**: testability requirements and observability standards

### Typical Communication
- Automated test reports in CI/CD
- QA sign-off in Definition of Done checklist
- Weekly quality metrics in project status updates
- Test plan documentation and defect triage reports

---

## Sponsor/Stakeholder

### Role Summary
Sponsors and key Stakeholders provide business context, prioritization guidance, and approvals. They ensure projects align with organizational goals and remove business blockers.

### Responsibilities
- Approve project charter, scope, and major milestones
- Provide business context and success metrics
- Escalate business-level blockers and constraints
- Participate in gate reviews (initiation, planning, release)
- Communicate project outcomes to their teams and leadership
- Validate alignment with organizational strategy

### Goals
- Ensure project delivers measurable business value
- Remove organizational barriers to execution
- Align project strategy with organizational priorities
- Build stakeholder confidence through transparency

### Key Interactions
- **Project Manager**: regular status updates and escalation channel
- **Product Manager**: input on prioritization and business requirements
- **Executive team**: reporting on project outcomes and impact
- **Development team**: approval and support for major decisions

### Typical Communication
- Monthly stakeholder updates
- Gate review presentations
- Ad-hoc escalation for business-blocking issues
- Executive steering committee meetings

---

## Technical Lead/Architect

### Role Summary
Technical Leads define architecture, design patterns, and technical strategy for projects. They ensure solutions are scalable, maintainable, and align with platform standards.

### Responsibilities
- Create technical design documents and architecture decisions
- Review code for alignment with standards and best practices
- Identify technical risks and propose mitigation strategies
- Mentor developers on technical approach and patterns
- Collaborate on platform integrations and dependencies
- Establish and enforce coding standards and quality gates

### Goals
- Deliver technically sound, maintainable solutions
- Reduce technical debt and future refactoring costs
- Enable knowledge sharing and consistency across teams
- Improve system scalability and performance

### Key Interactions
- **Developers**: mentoring, design review, and technical guidance
- **Project Manager**: identification and escalation of technical risks
- **QA Lead**: testability and observability requirements
- **Security Officer**: security architecture and threat mitigation design
- **Product Manager**: feasibility assessment and trade-off analysis

### Typical Communication
- Architecture review meetings
- Technical design documents in PR descriptions
- Code review comments and technical retrospectives
- Design decision records (ADRs)

---

## Security/Compliance Officer

### Role Summary
Security and Compliance Officers ensure projects meet security standards, regulatory requirements, and data protection policies. They conduct threat assessments and approve security-critical releases.

### Responsibilities
- Conduct threat modeling and security reviews
- Define security acceptance criteria and controls
- Review security scanning results and approve mitigations
- Coordinate security incident response
- Ensure compliance with regulatory and organizational standards
- Provide security training and guidance to development teams

### Goals
- Prevent security vulnerabilities and breaches
- Ensure regulatory and compliance adherence
- Build customer trust through transparent security practices
- Minimize security incident impact and response time

### Key Interactions
- **Developers**: security training and secure coding standards
- **QA Lead**: security testing requirements and automation
- **Project Manager**: risk escalation and compliance timelines
- **Technical Lead**: secure architecture design and threat mitigation
- **Release Lead**: pre-release security sign-off and vulnerability assessment

### Typical Communication
- Security checklist in Definition of Done
- Automated security scanning results in CI
- Security incident runbooks and post-mortems
- Compliance audit reports and remediation plans

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters / Agile Coaches facilitate team ceremonies, remove process blockers, and coach teams on agile practices. They foster psychological safety and continuous improvement.

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Identify and help resolve team workflow bottlenecks
- Coach team members on agile ceremonies and practices
- Track team velocity and capacity
- Foster continuous improvement culture
- Remove impediments that prevent team progress

### Goals
- Maximize team throughput and predictability
- Improve team health and psychological safety
- Enable data-driven process improvements
- Strengthen team cohesion and collaboration

### Key Interactions
- **Developers**: support with sprint flow and ceremony facilitation
- **Project Manager**: coordination of backlog grooming and planning
- **Product Manager**: collaboration on sprint selection and prioritization
- **All team members**: coaching and impediment removal

### Typical Communication
- Velocity trends and capacity planning
- Retrospective action items and follow-up
- Sprint planning facilitation and adjustments
- Team health metrics and improvement initiatives

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Cross-functional interactions highlight collaboration points and communication dependencies.
- New team members can reference this document to understand their role's responsibilities and how they contribute to project success.
