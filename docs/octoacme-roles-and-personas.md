# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Delivery Roles

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

#### Interaction with Other Roles
- **Product Manager**: Receives acceptance criteria and success metrics; provides implementation feedback
- **Project Manager**: Estimates effort; flags risks and blockers; participates in planning
- **UX Designer**: Collaborates on design review and usability implementation
- **QA/Testing**: Coordinates on test coverage and acceptance validation

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

#### Interaction with Other Roles
- **Project Manager**: Aligns on scope, timeline, and dependencies; escalates risks
- **Developers**: Defines requirements; reviews technical proposals
- **Data Analyst**: Consults on metrics to define success and measure impact
- **UX Designer**: Collaborates on user flows, wireframes, and usability goals
- **Customer Support**: Incorporates customer feedback and support impact assessment

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

#### Interaction with Other Roles
- **Product Manager**: Aligns on priorities and dependencies; collaborates on trade-offs
- **Developers**: Tracks progress; manages blockers and resource availability
- **Release Manager**: Coordinates deployment timelines and cross-team change management
- **Stakeholders**: Provides regular status updates and escalations

---

## Cross-Functional Support Roles

### UX Designer

#### Role Summary
UX Designers create intuitive, usable experiences that delight customers. They design user flows, wireframes, and prototypes, ensuring that implemented features meet usability goals and accessibility standards.

#### Responsibilities
- Design user flows, wireframes, and interactive prototypes
- Conduct user research and usability testing
- Collaborate with Product Manager on user requirements and use cases
- Partner with Developers to ensure design implementation meets specifications
- Participate in design reviews and provide feedback on features
- Advocate for accessibility and inclusive design principles

#### Goals
- Deliver interfaces that are intuitive and enjoyable for users
- Reduce support burden through clear, usable design
- Ensure accessibility compliance and user satisfaction

#### Typical Communication
- Design kickoff meetings with Product and Development teams
- Design review sessions and critique sessions
- Wireframe and prototype documentation in design tools
- Usability test findings and recommendations

#### Interaction with Other Roles
- **Product Manager**: Aligns on customer needs, user personas, and feature prioritization
- **Developers**: Provides design specifications and collaborates on implementation feasibility
- **Data Analyst**: Reviews user metrics and A/B test results to inform design iterations
- **Customer Support**: Incorporates feedback on usability pain points reported by customers

---

### Data Analyst

#### Role Summary
Data Analysts provide data-driven insights to inform product and business decisions. They define success metrics, track usage and performance, and help teams measure the impact of features and initiatives.

#### Responsibilities
- Define success metrics aligned with project objectives
- Track and monitor key performance indicators (KPIs) and business metrics
- Conduct analysis of user behavior, feature adoption, and performance trends
- Support A/B testing and experimentation design and analysis
- Provide dashboards and reports for stakeholder visibility
- Identify data gaps and recommend improvements to tracking

#### Goals
- Enable evidence-based decision-making across the organization
- Ensure projects deliver measurable business impact
- Improve visibility into product health and user satisfaction

#### Typical Communication
- Metrics and success criteria recommendations during planning
- Weekly or bi-weekly analytics reviews and dashboards
- A/B test results and analysis reports
- Data-driven recommendations for feature refinement or pivots

#### Interaction with Other Roles
- **Product Manager**: Defines success metrics; provides insights to inform prioritization and iterate on features
- **Project Manager**: Tracks project KPIs and communicates impact to stakeholders
- **Developers**: Advises on instrumentation and data collection best practices
- **Customer Support**: Analyzes support ticket trends and user feedback to identify gaps

---

### Customer Support

#### Role Summary
Customer Support represents the voice of the customer, surfacing user pain points, feedback, and common issues to inform product decisions and planning. They ensure smooth customer experiences and help users succeed with the product.

#### Responsibilities
- Provide responsive, knowledgeable support to customers
- Triage and escalate issues to appropriate teams (developers, product, security)
- Surface common customer pain points and feedback to the Product team
- Contribute input on feature impact and support readiness during planning
- Maintain support documentation and knowledge base
- Participate in incident response and escalation handling

#### Goals
- Maximize customer satisfaction and retention
- Reduce support volume through better product design and documentation
- Ensure customer voice is heard in product decisions

#### Typical Communication
- Support ticket tracking and escalation
- Weekly feedback summaries and pain point reports to Product
- Input on feature impact and support readiness during planning
- Incident response and customer communication during outages

#### Interaction with Other Roles
- **Product Manager**: Provides customer feedback to inform prioritization; advises on feature usability concerns
- **Project Manager**: Communicates feature readiness and support impact; escalates customer-critical issues
- **Developers**: Reports technical bugs and works with teams on resolution
- **Release Manager**: Coordinates customer communication and support readiness for new releases

---

### Release Manager

#### Role Summary
Release Managers orchestrate the deployment and release process, ensuring smooth, coordinated rollouts across teams. They manage release planning, deployment procedures, communication, and rollback when needed.

#### Responsibilities
- Coordinate release planning and timeline across teams
- Create and maintain deployment procedures and runbooks
- Manage version numbering, release notes, and communications
- Coordinate pre-release testing and staging validation
- Execute deployments and monitor for issues
- Manage rollback procedures and incident response during deployments
- Ensure cross-team alignment on deployment windows and communication

#### Goals
- Minimize deployment risk and service disruptions
- Ensure coordinated, transparent communication across stakeholders
- Maintain consistent, auditable deployment practices

#### Typical Communication
- Release planning meetings and deployment schedules
- Release notes and stakeholder announcements
- Pre-deployment and post-deployment checklists
- Incident communications and rollback decisions

#### Interaction with Other Roles
- **Project Manager**: Aligns on release timeline and interdependencies
- **Developers**: Reviews deployment readiness, test coverage, and known issues
- **Security Engineer**: Coordinates security validation before production deployment
- **Product Manager**: Communicates feature availability to stakeholders
- **Customer Support**: Coordinates customer-facing communications and support readiness

---

### Security Engineer

#### Role Summary
Security Engineers ensure that products are built, deployed, and operated securely. They advise on secure development practices, review features for security risks, and help teams respond to security incidents.

#### Responsibilities
- Advise on secure development and deployment practices
- Review features and architecture for security risks and compliance requirements
- Support security testing and vulnerability assessments
- Manage security incident response and escalation
- Maintain security runbooks and incident playbooks
- Provide security training and guidance to teams
- Coordinate with external security assessments and audits

#### Goals
- Protect customer data and product integrity
- Reduce security risk and compliance violations
- Enable teams to build security in by default

#### Typical Communication
- Security reviews for features and deployments
- Security incident alerts and incident response coordination
- Security training and best practices guidance
- Compliance and audit reporting

#### Interaction with Other Roles
- **Developers**: Reviews code and architecture for security best practices; advises on remediation
- **Project Manager**: Flags security risks and compliance requirements; escalates security incidents
- **Release Manager**: Validates security readiness before production deployment
- **Product Manager**: Advises on security/privacy implications of features

---

### Scrum Master / Agile Coach

#### Role Summary
Scrum Masters (or Agile Coaches) facilitate agile ceremonies, help teams apply agile principles, and remove impediments to delivery. They serve the team and foster a culture of continuous improvement.

#### Responsibilities
- Facilitate agile ceremonies (standups, planning, retrospectives, reviews)
- Help the team apply agile practices and iterative delivery
- Identify and help remove process impediments and blockers
- Coach teams on collaboration and communication best practices
- Track team velocity and process metrics
- Foster a culture of continuous improvement and psychological safety
- Facilitate retrospectives and action item tracking

#### Goals
- Enable high-performing, self-organizing teams
- Reduce cycle time and improve delivery consistency
- Foster psychological safety and continuous learning

#### Typical Communication
- Daily standup facilitation
- Sprint planning and retrospective meetings
- Coaching conversations with team members
- Metrics and process improvement recommendations

#### Interaction with Other Roles
- **Project Manager**: Collaborates on planning, risk management, and escalation
- **Developers**: Coaches on agile practices; removes process blockers
- **Product Manager**: Facilitates backlog refinement and prioritization discussions
- **All roles**: Fosters team collaboration and psychological safety

---

## How these personas are used in the exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Understand interaction patterns between roles to identify communication and handoff opportunities.
- When designing processes or workflows, ensure all relevant personas are considered and their responsibilities are clear.
