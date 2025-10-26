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

## UX Designer

### Role Summary
UX Designers create intuitive, accessible user experiences. They conduct research, design wireframes and prototypes, and validate designs with users and stakeholders.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Collaborate with Product and Engineering on design feasibility
- Ensure accessibility and consistency across the product
- Handoff design assets and specifications to developers

### Goals
- Create user-centered, accessible designs
- Reduce friction and improve user satisfaction
- Ensure design consistency and brand alignment

### Typical Communication & Interactions
- Design reviews with Product and Engineering
- User testing sessions and findings reports
- Handoff meetings with developers (specs, assets, interaction notes)

### Sample Handoff Artifacts
- Figma/Sketch files with component specifications
- Design system documentation
- Interaction flow diagrams
- Accessibility checklist

---

## QA Engineer

### Role Summary
QA Engineers ensure quality through testing, validation, and defect tracking. They collaborate with developers to define testability and acceptance criteria, and validate releases before deployment.

### Responsibilities
- Create and execute test plans (manual and automated)
- Validate features against acceptance criteria
- Report and track defects
- Ensure regression coverage
- Participate in release go/no-go decisions

### Goals
- Minimize defects reaching production
- Ensure features meet acceptance criteria
- Improve test coverage and automation

### Typical Communication & Interactions
- Daily standups with development team
- Bug triage and severity discussions
- Release readiness reviews
- Test plan reviews with Product and Engineering

### Sample Handoff Artifacts
- Test plans and test cases
- Defect reports with reproduction steps
- Test coverage reports
- Release sign-off documentation

---

## DevOps Engineer

### Role Summary
DevOps Engineers design and maintain infrastructure, CI/CD pipelines, and deployment processes. They enable reliable, scalable, and secure software delivery.

### Responsibilities
- Build and maintain CI/CD pipelines
- Manage infrastructure and cloud resources
- Implement monitoring, alerting, and observability
- Ensure security and compliance in deployments
- Support incident response and troubleshooting

### Goals
- Enable fast, safe, automated deployments
- Maintain high availability and performance
- Reduce mean time to recovery (MTTR)

### Typical Communication & Interactions
- Infrastructure design reviews
- Deployment planning and runbooks
- Incident retrospectives
- Security and compliance discussions

### Sample Handoff Artifacts
- Deployment runbooks
- Infrastructure as Code (IaC) templates
- Monitoring dashboards and alert configurations
- Incident reports and postmortems

---

## Data Analyst

### Role Summary
Data Analysts collect, analyze, and interpret data to inform product and business decisions. They create reports, dashboards, and insights that help teams measure success.

### Responsibilities
- Define metrics and KPIs with Product and stakeholders
- Build and maintain dashboards and reports
- Analyze user behavior and feature usage
- Provide data-driven insights and recommendations
- Validate A/B test results and experiments

### Goals
- Enable data-driven decision-making
- Measure product impact and user outcomes
- Identify opportunities for improvement

### Typical Communication & Interactions
- Weekly metrics reviews with Product and leadership
- Ad-hoc analysis requests from stakeholders
- Experiment design and results presentations
- Data pipeline and reporting tool discussions

### Sample Handoff Artifacts
- Dashboard links and metric definitions
- Analysis reports and insights summaries
- SQL queries and data models
- A/B test results and recommendations

---

## Support Lead

### Role Summary
Support Leads manage customer inquiries, escalations, and feedback. They bridge the gap between customers and product/engineering teams, ensuring issues are resolved and insights are shared.

### Responsibilities
- Triage and prioritize customer issues
- Escalate bugs and feature requests to Engineering and Product
- Document common issues and create knowledge base articles
- Track support metrics (response time, resolution time, satisfaction)
- Provide customer feedback to inform product roadmap

### Goals
- Deliver fast, helpful customer support
- Reduce repeat issues through documentation and fixes
- Improve customer satisfaction and retention

### Typical Communication & Interactions
- Daily ticket reviews and escalations
- Weekly sync with Product and Engineering on trends
- Customer feedback sessions
- Knowledge base and documentation updates

### Sample Handoff Artifacts
- Bug reports with customer impact details
- Feature request summaries with user stories
- Support metrics and trend reports
- Knowledge base articles and FAQs

---

## Roles & Handoffs

### Understanding Handoffs
Handoffs occur when work transitions between roles or teams. Clear handoffs reduce miscommunication, rework, and delays. Each handoff should include:
- **What**: Deliverable or artifact being handed off
- **Why**: Context and goals for the recipient
- **How**: Instructions, dependencies, and acceptance criteria

### Artifact Ownership
| Artifact | Owner | Contributors | Approvers |
|----------|-------|--------------|-----------|
| Product Roadmap | Product Manager | Project Manager, Stakeholders | Leadership |
| Design Specs | UX Designer | Product Manager, Developers | Product Manager |
| Code & Tests | Developers | QA Engineer | Tech Lead, Code Reviewers |
| Test Plans | QA Engineer | Developers, Product Manager | QA Lead |
| Release Runbook | DevOps Engineer | Developers, QA Engineer | Engineering Manager |
| Support Documentation | Support Lead | Product Manager, QA Engineer | Product Manager |

### RACI Example for Feature Delivery
| Activity | PM | PdM | Dev | QA | UX | DevOps | Support |
|----------|----|----|-----|----|----|--------|---------|
| Define Requirements | I | R/A | C | C | C | I | I |
| Create Design | I | C | C | I | R/A | I | I |
| Implement Feature | I | I | R/A | C | I | I | I |
| Test Feature | I | I | C | R/A | I | I | I |
| Deploy to Production | C | I | C | C | I | R/A | I |
| Create Documentation | C | C | C | I | I | I | R/A |

**RACI Legend:**
- R = Responsible (does the work)
- A = Accountable (final approver)
- C = Consulted (provides input)
- I = Informed (kept updated)

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

