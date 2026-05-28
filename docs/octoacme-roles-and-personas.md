# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Roles

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

#### Key Interactions
- Works with QA Lead on test coverage and acceptance criteria
- Collaborates with UX Designer on UI/UX implementation
- Partners with DevOps Engineer on deployment and CI/CD
- Reports blockers and risks to Project Manager

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

#### Key Interactions
- Partners with Data Analyst to define and track success metrics
- Collaborates with UX Designer on user experience priorities
- Works with Customer Support Liaison to incorporate user feedback
- Syncs with Project Manager on scope and timeline trade-offs

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

#### Key Interactions
- Coordinates with QA Lead on testing schedules and release readiness
- Works with DevOps Engineer to schedule deployments
- Escalates blockers identified by Developers
- Partners with Business Analyst on requirement clarification

---

## Extended Roles

### UX Designer

#### Role Summary
UX Designers define and enforce user experience standards, ensuring that features are usable, accessible, and aligned with product vision. They bridge the gap between customer needs and technical implementation.

#### Responsibilities
- Create wireframes and design mockups for features
- Define UX acceptance criteria alongside Product Managers
- Review and provide feedback on UI implementation during sprints
- Conduct usability testing and gather user feedback
- Maintain design systems and component libraries
- Ensure accessibility standards (WCAG compliance)

#### Goals
- Deliver intuitive, user-centric solutions
- Reduce support burden through superior UX
- Maintain consistent visual and interaction language
- Improve customer satisfaction and adoption metrics

#### Typical Communication
- Design review sessions with developers
- Collaboration on acceptance criteria refinement
- Feedback on pull requests with UI changes
- Participation in retrospectives and user research activities

#### Key Interactions
- Works closely with Product Manager to refine feature priorities from UX perspective
- Partners with Developers on implementation feasibility and design system compliance
- Collaborates with QA Lead to define UX test cases and acceptance scenarios
- Engages with Customer Support Liaison to understand real-world usability issues

---

### QA Lead

#### Role Summary
QA Leads coordinate quality assurance strategy, define testing approaches, and ensure that features meet acceptance criteria before release. They own the quality gate and act as the voice of end-user validation.

#### Responsibilities
- Define and maintain test strategy and test plans
- Coordinate testing efforts across the team and external QA resources
- Create and review test cases aligned with acceptance criteria
- Identify and track defects through to resolution
- Oversee regression test suites and automation
- Validate release readiness and smoke tests

#### Goals
- Ensure high-quality releases with minimal production defects
- Reduce cycle time through efficient test automation
- Maintain test coverage above agreed thresholds
- Enable faster feedback loops to developers

#### Typical Communication
- Test planning during sprint kickoff
- Daily defect triage and status updates
- Test execution reports and metrics
- Release readiness reviews with PM and DevOps Engineer

#### Key Interactions
- Partners with Developers on test-driven development practices
- Collaborates with UX Designer to validate UX acceptance scenarios
- Works with Product Manager to refine acceptance criteria
- Coordinates with DevOps Engineer on deployment testing

---

### DevOps Engineer

#### Role Summary
DevOps Engineers maintain CI/CD pipelines, deployment automation, and monitoring infrastructure. They enable rapid, reliable releases and provide observability into production systems.

#### Responsibilities
- Build and maintain CI/CD pipelines and automation
- Manage staging and production deployment processes
- Set up monitoring, alerting, and observability tools
- Execute deployments and coordinate rollbacks when needed
- Optimize build and deployment performance
- Document runbooks for incident response and troubleshooting

#### Goals
- Enable fast, safe deployments with minimal manual effort
- Maintain high system availability and performance
- Reduce mean time to recovery (MTTR) for incidents
- Provide visibility into system health and performance

#### Typical Communication
- Deployment scheduling and coordination
- CI/CD pipeline status and improvement discussions
- Incident response and post-mortems
- Infrastructure capacity and performance planning

#### Key Interactions
- Works with Developers to optimize build performance and test automation
- Collaborates with Project Manager on deployment scheduling
- Partners with Security Lead on infrastructure security and compliance
- Supports on-call responsibilities with QA Lead and Customer Support Liaison

---

### Security Lead

#### Role Summary
Security Leads conduct risk analysis, review code for vulnerabilities, and ensure compliance with security best practices and regulations. They are accountable for protecting customer data and system integrity.

#### Responsibilities
- Conduct security risk assessments for new features
- Review code and infrastructure for vulnerabilities
- Maintain security best practices and standards documentation
- Coordinate security compliance activities (audits, certifications)
- Provide incident response support for security-related issues
- Lead security training and awareness initiatives

#### Goals
- Prevent security breaches and data loss
- Maintain compliance with applicable regulations (GDPR, SOC2, etc.)
- Build security awareness across the organization
- Enable secure, compliant feature delivery

#### Typical Communication
- Security reviews during feature planning and code review
- Vulnerability assessment and remediation tracking
- Compliance and audit coordination
- Incident response and post-mortem participation

#### Key Interactions
- Reviews designs and code with Developers for security implications
- Collaborates with Product Manager on security-related requirements
- Works with DevOps Engineer on infrastructure security and monitoring
- Supports Project Manager in risk escalations involving security concerns

---

### Data Analyst

#### Role Summary
Data Analysts define reporting requirements, develop dashboards, and help teams interpret data to support data-driven decision-making. They connect business outcomes to measurable metrics.

#### Responsibilities
- Define key performance indicators (KPIs) and success metrics
- Build dashboards and reporting infrastructure
- Conduct data analysis to support product decisions
- Identify trends, patterns, and anomalies in system data
- Partner with teams to instrument code for observability
- Translate business questions into data queries and insights

#### Goals
- Enable data-driven decision-making at all levels
- Provide real-time visibility into product health and user behavior
- Support iterative improvement through data insights
- Reduce guesswork in prioritization and roadmapping

#### Typical Communication
- Metric definition workshops with Product Manager and PM
- Weekly or milestone-based analytics reviews
- Dashboard presentations to stakeholders
- Ad-hoc analysis to support decisions

#### Key Interactions
- Partners with Product Manager to define success metrics and interpret results
- Works with Developers to instrument code for proper data collection
- Supports DevOps Engineer in building observability infrastructure
- Provides insights to Customer Support Liaison on user behavior patterns

---

### Customer Support Liaison

#### Role Summary
Customer Support Liaisons serve as the voice of the customer, relaying common issues, feature requests, and feedback from end users. They bridge the gap between support operations and product delivery.

#### Responsibilities
- Relay customer feedback and issues to the product team
- Identify patterns in support tickets and customer inquiries
- Validate that solutions address real customer pain points
- Support quality testing and acceptance validation
- Participate in release communications to support teams
- Provide early feedback on usability and feature completeness

#### Goals
- Reduce support ticket volume through better product design
- Improve customer satisfaction and retention
- Ensure customer voice is heard in prioritization decisions
- Accelerate time to resolution for production issues

#### Typical Communication
- Weekly review of customer feedback and common issues
- Participation in feature refinement and acceptance sessions
- Support ticket trend analysis and reporting
- Release notes and customer communication support

#### Key Interactions
- Works closely with Product Manager to incorporate customer feedback
- Collaborates with UX Designer to surface usability issues
- Provides input to QA Lead on real-world usage scenarios
- Supports Project Manager in risk identification from customer perspective

---

### Business Analyst

#### Role Summary
Business Analysts bridge business requirements and technical implementation, ensuring alignment between stakeholders' needs and delivered solutions. They clarify scope and facilitate understanding across teams.

#### Responsibilities
- Translate business requirements into technical specifications
- Clarify ambiguous requirements and scope boundaries
- Facilitate communication between business and technical teams
- Document business rules and workflows
- Validate that delivered solutions meet business objectives
- Support scope management and change control processes

#### Goals
- Reduce rework due to unclear requirements
- Improve alignment between business and technical perspectives
- Enable faster development through clear specifications
- Support better trade-off decisions through clear impact analysis

#### Typical Communication
- Requirements clarification meetings with stakeholders and engineers
- Business requirement documentation and specifications
- Scope review and change impact analysis
- Acceptance validation and sign-off support

#### Key Interactions
- Works with Product Manager to refine requirements and priorities
- Partners with Developers to ensure technical feasibility and impact estimation
- Collaborates with Project Manager on scope management and timeline
- Supports QA Lead in defining comprehensive test scenarios based on business rules

---

## How these personas are used in the exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference "Key Interactions" sections to understand cross-functional dependencies and communication patterns.
- When assigning work, ensure clarity on which persona(s) own responsibility for outcomes.
