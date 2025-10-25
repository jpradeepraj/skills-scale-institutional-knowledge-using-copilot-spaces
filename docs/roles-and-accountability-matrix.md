# OctoAcme Roles and Accountability Matrix

## Purpose
This RACI matrix clarifies who is Responsible, Accountable, Consulted, and Informed for core project activities. Use this to reduce ambiguity, speed decision-making, and ensure appropriate involvement across roles.

## RACI Key
- **R (Responsible)**: Does the work to complete the activity
- **A (Accountable)**: Ultimately accountable for completion and has decision authority (only one A per activity)
- **C (Consulted)**: Provides input and expertise (two-way communication)
- **I (Informed)**: Kept up-to-date on progress (one-way communication)

---

## Accountability Matrix

| Activity | Product Manager | Project Manager | Developer | QA | UX/UI Designer | DevOps Engineer | Business Analyst | Support/Customer Success | Security Lead |
|----------|----------------|-----------------|-----------|-----|----------------|-----------------|------------------|-------------------------|---------------|
| **Project Initiation** | A | R | I | I | C | I | C | I | I |
| **Backlog Prioritization** | A | C | C | C | C | I | C | I | C |
| **Design Approval** | C | I | C | C | A | I | C | I | C |
| **Development** | I | C | R/A | C | C | C | C | I | C |
| **QA/Testing** | I | C | C | R/A | C | C | C | C | C |
| **Release Coordination** | C | R | C | C | I | A | I | C | C |
| **Incident Response** | I | C | R | R | I | R/A | I | R | R (security) |
| **Post-release Retrospective** | C | R/A | C | C | C | C | C | C | C |

---

## Activity Details

### Project Initiation
Establish project goals, scope, stakeholders, and initial planning.
- **Accountable**: Product Manager defines vision and success criteria
- **Responsible**: Project Manager creates project plan and coordinates kickoff
- **Consulted**: UX/UI Designer and Business Analyst provide early input on user needs and requirements

### Backlog Prioritization
Determine the order and priority of work items based on value, risk, and dependencies.
- **Accountable**: Product Manager owns prioritization decisions
- **Consulted**: All technical roles provide input on effort, risk, and dependencies; Business Analyst provides business context

### Design Approval
Review and approve design artifacts before implementation.
- **Accountable**: UX/UI Designer owns design decisions and sign-off
- **Consulted**: Product Manager validates alignment with vision; Developers and QA provide feasibility feedback; Security Lead reviews for security implications

### Development
Implement features, fixes, and technical work.
- **Responsible & Accountable**: Developers execute and own code quality
- **Consulted**: Project Manager tracks progress; QA, DevOps Engineer, and Business Analyst provide input as needed; Security Lead reviews for security best practices

### QA/Testing
Validate that features meet acceptance criteria and quality standards.
- **Responsible & Accountable**: QA executes testing and signs off on quality
- **Consulted**: Developers support bug triage and fixes; Security Lead may conduct security testing

### Release Coordination
Plan, execute, and validate production deployments.
- **Accountable**: DevOps Engineer owns deployment execution and production stability
- **Responsible**: Project Manager coordinates release planning and communication
- **Consulted**: Product Manager, Developers, QA, and Security Lead validate readiness; Support/Customer Success prepares for customer impact

### Incident Response
Respond to and resolve production incidents and outages.
- **Accountable**: DevOps Engineer coordinates overall response (or Security Lead for security incidents)
- **Responsible**: Developers, QA, DevOps Engineers, and Support/Customer Success triage and resolve; Security Lead leads security incident response
- **Consulted**: Project Manager tracks communication; Product Manager provides input on impact and prioritization

### Post-release Retrospective
Review what went well, what didn't, and identify improvements.
- **Responsible & Accountable**: Project Manager facilitates and captures action items
- **Consulted**: All roles participate and provide feedback

---

## Using This Matrix

1. **Before starting an activity**, confirm who is accountable and responsible
2. **Identify conflicts early** if multiple people believe they are accountable
3. **Avoid decision paralysis** by ensuring each activity has exactly one accountable person
4. **Adjust as needed** for your project context while maintaining clarity on decision authority

For escalation paths and communication guidelines, see [Communication and Escalation Guidelines](templates/communication-and-escalation-guidelines.md).
