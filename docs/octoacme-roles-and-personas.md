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
- **With Technical Lead / Architect**: Receive technical direction and mentorship; collaborate on design reviews and architectural decisions
- **With QA Lead / Quality Engineer**: Define testable acceptance criteria; work on test automation and bug fixes
- **With Product Manager**: Clarify requirements and validate understanding; discuss trade-offs and feasibility
- **With Project Manager**: Provide estimates and progress updates; escalate blockers and dependencies
- **With UX/UI Designer**: Implement designs; provide technical feasibility feedback
- **With Business Analyst**: Clarify requirements and edge cases during implementation

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
- **With Project Manager**: Align on delivery timeline; review risks and dependencies weekly
- **With Developers**: Define acceptance criteria; validate solutions against requirements
- **With Technical Lead / Architect**: Discuss feasibility and technical trade-offs; align on roadmap priorities
- **With QA Lead / Quality Engineer**: Define quality standards and acceptance criteria; review test coverage
- **With UX/UI Designer**: Align on user research findings and design direction
- **With Business Analyst**: Validate requirements and success metrics
- **With Support Lead / Operations**: Coordinate on feature readiness and support preparation

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
- **With Product Manager**: Align on priorities and timeline weekly; review and escalate risks
- **With Developers**: Facilitate sprint planning and standups; track progress and blockers
- **With Technical Lead / Architect**: Track technical risks and dependencies
- **With QA Lead / Quality Engineer**: Monitor testing progress and quality gates
- **With Business Analyst**: Ensure requirements are clear and documented; coordinate stakeholder feedback
- **With Support Lead / Operations**: Schedule handoff meetings; plan deployment and rollback procedures
- **With all roles**: Facilitate escalation and remove blockers

---

## Technical Lead / Architect

### Role Summary
Technical Leads guide the technical vision and architectural direction of projects. They mentor developers, make key technical decisions, and ensure code quality and maintainability. They serve as the bridge between business requirements and technical implementation.

### Responsibilities
- Define and maintain the technical architecture and design patterns
- Review pull requests and provide technical mentorship to developers
- Identify and mitigate technical risks
- Make trade-off decisions between performance, scalability, and maintainability
- Establish and enforce code quality standards
- Participate in design reviews and technical planning sessions
- Support the team in resolving complex technical challenges

### Goals
- Ensure systems are well-architected, maintainable, and scalable
- Reduce technical debt and prevent architectural anti-patterns
- Foster a culture of technical excellence and continuous learning
- Enable fast, confident delivery without sacrificing quality

### Typical Communication
- Technical design reviews and architecture discussions
- Code review comments and mentoring sessions
- Weekly technical syncs and planning sessions
- Documentation of architectural decisions and rationale

### Interactions with Other Roles
- **With Developers**: Provide technical mentorship; lead design reviews; clarify architectural decisions
- **With Product Manager**: Assess feasibility of features; discuss technical trade-offs and impacts
- **With Project Manager**: Escalate technical risks; coordinate complex technical dependencies
- **With QA Lead / Quality Engineer**: Define testability requirements; discuss technical test strategy
- **With UX/UI Designer**: Provide technical constraints and feasibility feedback on designs

---

## QA Lead / Quality Engineer

### Role Summary
QA Leads own the end-to-end quality assurance strategy for projects. They design comprehensive test plans, lead manual and automated testing efforts, and ensure features meet acceptance criteria before release. They champion quality and are the gatekeeper for release readiness.

### Responsibilities
- Design and maintain end-to-end test strategies and test plans
- Create and maintain automated test suites (unit, integration, end-to-end)
- Lead manual testing efforts and coordinate QA resources
- Validate acceptance criteria and sign-off on feature readiness
- Coordinate security and performance testing
- Identify, document, and track bugs and quality issues
- Provide quality metrics and dashboards to the team
- Plan smoke tests and post-deployment verification

### Goals
- Ensure features meet quality standards before release
- Reduce post-release defects and support tickets
- Enable confident, risk-aware deployments
- Provide visibility into product quality

### Typical Communication
- QA test plans and coverage reports
- Bug reports and quality dashboards
- Weekly quality reviews and acceptance sign-offs
- Release readiness checklists

### Interactions with Other Roles
- **With Developers**: Define testable acceptance criteria; collaborate on test automation; debug failures
- **With Product Manager**: Clarify acceptance criteria; validate against product goals and user scenarios
- **With Project Manager**: Track testing progress and quality gates; report on release readiness
- **With Technical Lead / Architect**: Discuss testability of architectural decisions; plan test infrastructure
- **With Support Lead / Operations**: Prepare post-deployment verification and support handoff materials

---

## UX/UI Designer

### Role Summary
UX/UI Designers translate product requirements and user stories into user-centric designs. They conduct user research, create wireframes and mockups, and advocate for usability and accessibility standards throughout the development process.

### Responsibilities
- Conduct user research and validate user needs
- Create wireframes, prototypes, and high-fidelity designs
- Define user flows and interaction patterns
- Advocate for accessibility and usability best practices
- Collaborate with developers on design feasibility and implementation
- Test designs with users and iterate based on feedback
- Document design decisions and maintain design systems

### Goals
- Create intuitive, accessible, and delightful user experiences
- Reduce user friction and support burden
- Align design with product strategy and business goals
- Enable developers to implement designs consistently

### Typical Communication
- Design mockups, wireframes, and prototypes
- Design specifications and interaction documentation
- User research findings and usability test results
- Design reviews and feedback sessions

### Interactions with Other Roles
- **With Product Manager**: Validate design decisions against user research and product goals
- **With Developers**: Discuss technical feasibility; collaborate on responsive design and implementation details
- **With Technical Lead / Architect**: Understand technical constraints and opportunities
- **With Project Manager**: Plan design reviews and feedback cycles
- **With QA Lead / Quality Engineer**: Validate UI against design specs; coordinate usability testing

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between stakeholders and the delivery team. They gather and document detailed requirements, clarify ambiguities and edge cases, and ensure solutions align with business needs. They ensure that what is being built meets true business requirements.

### Responsibilities
- Gather and document detailed business requirements from stakeholders
- Clarify ambiguities, edge cases, and assumptions
- Translate business needs into acceptance criteria and user stories
- Serve as a liaison between stakeholders and the delivery team
- Validate proposed solutions against business requirements
- Maintain requirements documentation and traceability
- Identify business risks and dependencies
- Support stakeholder communication and feedback loops

### Goals
- Ensure clarity and shared understanding of requirements
- Reduce rework and scope creep caused by requirement gaps
- Deliver solutions that truly meet business needs
- Accelerate decision-making by providing clear information to stakeholders

### Typical Communication
- Requirements documents and user stories
- Stakeholder interviews and discovery sessions
- Requirement clarification and change requests
- Acceptance sign-offs and validation reports

### Interactions with Other Roles
- **With Product Manager**: Refine requirements into product backlog items; align on priorities
- **With Developers**: Clarify requirements and edge cases during implementation; answer questions
- **With Project Manager**: Communicate requirement changes and their impact; escalate requirement ambiguities
- **With QA Lead / Quality Engineer**: Define testable acceptance criteria; validate against business scenarios
- **With Support Lead / Operations**: Capture operational requirements and constraints

---

## Support Lead / Operations

### Role Summary
Support Leads ensure features are operationally ready before release and coordinate support readiness. They represent the operations and support perspective, prepare handoff materials, coordinate incident response, and ensure timely follow-up on post-release issues and customer feedback.

### Responsibilities
- Represent operations and support perspective in project planning
- Prepare operational runbooks, documentation, and support materials
- Coordinate support team training and readiness before release
- Plan and execute post-deployment verification
- Manage incident response procedures and escalation paths
- Monitor post-release issues and coordinate follow-up
- Collect customer feedback and support metrics
- Identify operational risks and constraints early

### Goals
- Ensure smooth feature launches and customer adoption
- Minimize support burden and post-release issues
- Provide visibility into customer impact and satisfaction
- Enable rapid incident response and resolution

### Typical Communication
- Operational runbooks and support documentation
- Support readiness checklists and training schedules
- Incident summaries and post-deployment reports
- Customer feedback and support metrics

### Interactions with Other Roles
- **With Product Manager**: Understand feature scope and customer impact; provide support perspective on requirements
- **With Project Manager**: Coordinate deployment timing and support staffing; plan release communication
- **With Developers**: Clarify operational concerns and constraints; coordinate on monitoring and instrumentation
- **With QA Lead / Quality Engineer**: Participate in acceptance testing; plan post-deployment verification
- **With Business Analyst**: Capture operational requirements and constraints

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the **Interactions with Other Roles** sections to understand cross-functional collaboration patterns throughout the project lifecycle.
