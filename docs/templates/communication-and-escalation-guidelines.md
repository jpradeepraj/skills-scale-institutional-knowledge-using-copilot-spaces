# Communication and Escalation Guidelines

## Purpose
Define communication cadence, stakeholder updates, and clear escalation paths for blockers and incidents. These guidelines ensure timely information flow and rapid resolution of critical issues.

---

## Team Communication Cadence

### Daily
- **Daily Standup** (15 min)
  - **Who**: All delivery team members (Developers, QA, UX/UI Designer, DevOps Engineer)
  - **Format**: What I did yesterday, what I'm doing today, blockers/asks
  - **Owner**: Project Manager facilitates

### Weekly
- **Weekly Status Sync** (30 min)
  - **Who**: Product Manager, Project Manager, Tech Lead, and key stakeholders
  - **Format**: Progress update, risks/blockers, decisions needed
  - **Owner**: Project Manager prepares and shares status report (see [Risk Management & Communication](../octoacme-risks-and-communication.md) for template)

- **Backlog Refinement** (1 hour)
  - **Who**: Product Manager, Developers, QA, Business Analyst
  - **Format**: Review upcoming stories, clarify acceptance criteria, estimate effort
  - **Owner**: Product Manager leads

### Sprint Ceremonies (Bi-weekly or as defined)
- **Sprint Planning**: Define sprint goals and commit to work
- **Sprint Review/Demo**: Showcase completed work to stakeholders
- **Sprint Retrospective**: Reflect on process and identify improvements (see [Retrospective and Continuous Improvement](../octoacme-retrospective-and-continuous-improvement.md))

### Ad-hoc
- **Design Reviews**: As needed when new designs are ready
- **Technical Design Reviews**: For significant architectural changes
- **Stakeholder Briefings**: Scheduled by Product Manager as needed for major milestones

---

## Stakeholder Communication

### Identify Stakeholder Groups
- **Internal Engineering**: Tech leads, adjacent teams, platform teams
- **Business Stakeholders**: Sales, Marketing, Operations, Executive sponsors
- **Support/Customer Success**: Customer-facing teams needing release information
- **Security and Compliance**: For changes impacting security or regulatory requirements

### Communication Channels
- **Project Updates**: Use a single source of truth (project README, wiki page, or release doc)
- **Release Announcements**: Coordinated by Project Manager and communicated via email/Slack to all stakeholders (see [Release and Deployment Guide](../octoacme-release-and-deployment.md))
- **Incident Updates**: Real-time updates via dedicated incident channel (see Incident Response below)

### Weekly Status Template
```
**Progress this week:**
- [Completed item 1]
- [Completed item 2]

**Next steps:**
- [Planned work for next week]

**Risks & blockers:**
- [Risk/blocker with severity and mitigation plan]

**Ask / decisions needed:**
- [Decision or help needed from stakeholders]
```

---

## Escalation Paths

### General Blocker Escalation
Use this path for non-critical blockers (dependencies, resource constraints, prioritization conflicts):

1. **Team-level**: Raise in daily standup; team attempts to resolve
2. **Project Manager**: If unresolved within 1-2 days, Project Manager coordinates resolution
3. **Product Manager / Tech Lead**: If cross-team or prioritization conflict, escalate to Product Manager or Tech Lead
4. **Product Lead / Engineering Manager**: For strategic decisions or resource allocation
5. **Executive Sponsor**: For budget, scope, or high-impact organizational decisions

**Timeline**: Escalate within 48 hours if blocker impacts sprint goals or critical path.

### Critical Incident Escalation (Production Outage or Major Degradation)
For production incidents affecting customers:

1. **On-call Engineer/DevOps**: Immediately begins triage and starts incident response
2. **Incident Commander**: Coordinates response, communicates status, and decides on rollback/mitigation (typically DevOps Engineer or Tech Lead)
3. **Product Manager / Project Manager**: Informed immediately; coordinates stakeholder communication
4. **Support/Customer Success**: Informed to handle customer inquiries and provide updates
5. **Executive Leadership**: Notified for high-severity, customer-impacting incidents

**Communication**: 
- Create dedicated incident channel (e.g., `#incident-YYYYMMDD-description`)
- Post regular updates (every 30-60 min) on status, actions taken, and ETA
- Follow up with blameless post-mortem (see [Risk Management & Communication](../octoacme-risks-and-communication.md))

**Rollback**: See [Release and Deployment Guide](../octoacme-release-and-deployment.md) for rollback procedures.

### Security Incident Escalation
For suspected security breaches, vulnerabilities, or compliance issues:

1. **Security Lead**: Immediately notified and takes ownership
2. **Security On-call / Incident Response Team**: Activated for investigation and containment
3. **DevOps Engineer**: Coordinates infrastructure and access controls as directed by Security Lead
4. **Product Manager / Engineering Manager**: Informed of impact and timeline
5. **Legal / Compliance**: Notified for regulatory or data breach incidents

**Timeline**: Security incidents are escalated immediately (within 15 minutes of discovery).

**Communication**:
- Use secure communication channels (avoid public Slack channels for sensitive details)
- Security Lead coordinates all external communication
- Follow security incident runbook and notify affected stakeholders per compliance requirements

---

## Blocker Severity Guidelines

Use these guidelines to determine escalation urgency:

| Severity | Description | Escalation Timeline |
|----------|-------------|---------------------|
| **Low** | Minor inconvenience; workaround available | Raise in standup; resolve within 1 week |
| **Medium** | Impacts progress but not sprint goals | Escalate to Project Manager within 2 days |
| **High** | Blocks sprint goal or critical path | Escalate immediately; resolve within 24 hours |
| **Critical** | Production outage or security incident | Escalate immediately; activate incident response |

---

## Best Practices

### Do's
- **Communicate early**: Raise issues as soon as they are identified
- **Be specific**: Provide context, impact, and what you need to unblock
- **Follow up**: Confirm blockers are resolved and close the loop
- **Document decisions**: Capture key decisions in project notes or decision log

### Don'ts
- **Don't wait**: Delays compound; escalate blockers promptly
- **Don't bypass**: Follow escalation paths to ensure proper context and coordination
- **Don't surprise stakeholders**: Provide advance notice of risks that could impact deadlines

---

## Additional Resources

- [Risk Management & Communication](../octoacme-risks-and-communication.md)
- [Release and Deployment Guide](../octoacme-release-and-deployment.md)
- [Roles and Accountability Matrix](../roles-and-accountability-matrix.md)
- [Retrospective and Continuous Improvement](../octoacme-retrospective-and-continuous-improvement.md)
