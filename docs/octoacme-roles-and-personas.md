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

## QA (Quality Assurance)

### Role Summary
QA Engineers validate that features meet acceptance criteria and quality standards. They design test strategies, write automated tests, and perform manual validation to ensure reliability and usability.

### Responsibilities
- Create test plans and test cases aligned to acceptance criteria
- Execute manual and automated testing (functional, regression, performance)
- Report and track bugs and quality issues
- Collaborate with Developers to improve testability and coverage
- Validate releases in staging before production deployment

### Goals
- Ensure high product quality and minimize defects in production
- Improve test coverage and automation
- Reduce cycle time for validation and feedback

### Typical Communication
- Daily standups and sprint ceremonies
- Bug reports and test case documentation
- Sign-off on release readiness

### Interactions with Other Roles
- **Product Managers**: Clarify acceptance criteria and edge cases
- **Project Managers**: Report testing progress and risks blocking release
- **Developers**: Collaborate on bug triage, test design, and automation
- **DevOps Engineers**: Coordinate test environment setup and deployment validation

### Accountability
- **Primary (R)**: QA/Testing activities, test automation, bug tracking
- **Accountable (A)**: Release sign-off from quality perspective
- **Consulted (C)**: Design approval, backlog prioritization
- **Informed (I)**: Project initiation, retrospectives

---

## UX/UI Designer

### Role Summary
UX/UI Designers create user-centered designs that balance usability, aesthetics, and business goals. They conduct research, prototype interfaces, and collaborate with Product and Engineering to deliver intuitive experiences.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Define design systems and UI component standards
- Collaborate with Developers on implementation fidelity
- Validate designs through user feedback and analytics

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Maintain design consistency across the product
- Reduce user friction and improve satisfaction metrics

### Typical Communication
- Design reviews and critique sessions
- Prototypes and design specs (Figma, Sketch, etc.)
- User research findings and usability reports

### Interactions with Other Roles
- **Product Managers**: Align designs with product vision and user needs
- **Project Managers**: Communicate design timeline and dependencies
- **Developers**: Provide design specs and collaborate on feasibility
- **QA**: Validate visual and interaction fidelity during testing

### Accountability
- **Primary (R)**: Design approval, UX research
- **Accountable (A)**: Design sign-off and design system governance
- **Consulted (C)**: Backlog prioritization, project initiation
- **Informed (I)**: Development, QA/Testing, release coordination

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain infrastructure, CI/CD pipelines, and observability systems. They enable fast, reliable, and secure deployments while ensuring operational excellence.

### Responsibilities
- Build and maintain CI/CD pipelines and automation
- Manage infrastructure (cloud, containers, orchestration)
- Implement monitoring, logging, and alerting systems
- Ensure security and compliance in deployment processes
- Support incident response and production troubleshooting

### Goals
- Minimize deployment friction and lead time to production
- Maximize system reliability and uptime
- Automate repetitive operational tasks

### Typical Communication
- Deployment notifications and pipeline status
- Infrastructure changes and capacity planning
- Incident response and post-mortem reports

### Interactions with Other Roles
- **Developers**: Collaborate on build, test, and deployment automation
- **Project Managers**: Report infrastructure dependencies and risks
- **QA**: Provide test environments and coordinate deployment validation
- **Security Lead**: Implement security controls and compliance requirements

### Accountability
- **Primary (R)**: Release coordination, infrastructure management
- **Accountable (A)**: Deployment pipeline and production environment health
- **Consulted (C)**: Development, QA/Testing
- **Informed (I)**: Backlog prioritization, design approval, retrospectives

---

## Business Analyst

### Role Summary
Business Analysts bridge business stakeholders and technical teams by gathering requirements, analyzing workflows, and defining functional specifications. They ensure solutions align with business objectives and operational needs.

### Responsibilities
- Elicit and document business requirements and use cases
- Analyze current state processes and identify improvement opportunities
- Translate business needs into functional specifications for development
- Facilitate requirement reviews and acceptance sign-off
- Support testing by validating business rules and workflows

### Goals
- Ensure solutions deliver measurable business value
- Reduce ambiguity in requirements and minimize rework
- Improve stakeholder alignment and communication

### Typical Communication
- Requirements documents and user stories
- Process diagrams and workflow documentation
- Stakeholder workshops and alignment meetings

### Interactions with Other Roles
- **Product Managers**: Collaborate on feature definition and prioritization
- **Project Managers**: Support planning and scope management
- **Developers**: Clarify requirements and provide domain expertise
- **QA**: Define acceptance criteria and support validation

### Accountability
- **Primary (R)**: Requirements gathering, acceptance criteria definition
- **Accountable (A)**: Business requirements sign-off
- **Consulted (C)**: Backlog prioritization, design approval, development
- **Informed (I)**: Release coordination, retrospectives

---

## Support/Customer Success

### Role Summary
Support and Customer Success teams serve as the voice of the customer, helping users adopt the product, resolving issues, and feeding insights back to Product and Engineering. They ensure customer satisfaction and retention.

### Responsibilities
- Respond to customer inquiries and troubleshoot issues
- Document common issues and maintain knowledge base articles
- Escalate bugs and product gaps to Engineering and Product
- Collect customer feedback and feature requests
- Monitor support metrics and identify trends

### Goals
- Maximize customer satisfaction and reduce time to resolution
- Minimize support volume through improved product quality and documentation
- Drive product improvements based on customer insights

### Typical Communication
- Support tickets and escalations
- Customer feedback summaries and trend reports
- Knowledge base articles and FAQs

### Interactions with Other Roles
- **Product Managers**: Share customer feedback and prioritize support issues
- **Developers**: Escalate bugs and collaborate on troubleshooting
- **QA**: Validate fixes and provide real-world test scenarios
- **Project Managers**: Communicate readiness for customer-facing releases

### Accountability
- **Primary (R)**: Customer issue resolution, feedback collection
- **Accountable (A)**: Support escalation and knowledge base maintenance
- **Consulted (C)**: Release coordination, retrospectives
- **Informed (I)**: Backlog prioritization, development, QA/Testing

---

## Security Lead

### Role Summary
Security Leads ensure the product and infrastructure meet security and compliance standards. They identify vulnerabilities, define security requirements, and guide secure development practices.

### Responsibilities
- Define security requirements and threat models
- Conduct security reviews and vulnerability assessments
- Oversee security testing (SAST, DAST, penetration testing)
- Respond to security incidents and coordinate remediation
- Maintain compliance with security policies and regulations

### Goals
- Minimize security vulnerabilities and attack surface
- Ensure compliance with security standards and regulations
- Foster a security-aware culture across the organization

### Typical Communication
- Security review findings and recommendations
- Incident response coordination and post-mortem reports
- Security training and awareness communications

### Interactions with Other Roles
- **Developers**: Review code for security issues and guide secure coding practices
- **DevOps Engineers**: Implement security controls in infrastructure and pipelines
- **Product Managers**: Balance security requirements with feature delivery
- **Project Managers**: Identify security dependencies and risks

### Accountability
- **Primary (R)**: Security review, threat modeling, incident response (security)
- **Accountable (A)**: Security sign-off and compliance
- **Consulted (C)**: Design approval, development, release coordination
- **Informed (I)**: Backlog prioritization, QA/Testing, retrospectives

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

