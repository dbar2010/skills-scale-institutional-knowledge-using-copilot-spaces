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

## Engineering Managers / Tech Lead Managers

### Role Summary
Engineering Managers / Tech Lead Managers support engineering teams and oversee technical delivery, team capacity, and development.

### Responsibilities
- Plan team capacity and coordinate staffing across teams
- Monitor technical delivery and help resolve execution blockers
- Coach and develop engineers and technical leads
- Escalate delivery risks and coordinate cross-team support

### Goals
- Build a healthy, effective engineering team
- Make delivery commitments achievable and transparent
- Address technical and staffing risks early

### Typical Communication
- Capacity and delivery discussions with Project Managers
- Scope feasibility and trade-off reviews with Product Managers
- Coaching, feedback, and blocker resolution with Developers
- Delivery updates with Technical Leads and partner teams

### How they interact with existing roles
- **Developers:** Support execution, growth, and blocker resolution without taking over implementation ownership.
- **Product Managers:** Assess scope feasibility and explain engineering capacity and trade-offs.
- **Project Managers:** Align staffing and delivery outlook, surface risks, and coordinate escalations.

### Key Hand-offs
- Share capacity constraints and delivery risks during planning.
- Escalate cross-team staffing needs and unresolved blockers to delivery partners.
- Provide delivery status and team improvement actions to Project Managers.

### Decision Rights / Boundaries
- Decide engineering team assignments, coaching approach, and staffing recommendations within their authority.
- Advise on delivery feasibility; scope and product priority remain with Product Managers.
- Do not replace Project Managers as owners of project plans or Developers as owners of implementation.

---

## Technical Leads / Architects

### Role Summary
Technical Leads / Architects guide technical direction and help teams deliver solutions that meet architectural and non-functional needs.

### Responsibilities
- Define technical direction, architecture guardrails, and integration approaches
- Identify scalability, reliability, and maintainability requirements
- Review designs and surface technical dependencies and risks
- Guide Developers through implementation decisions

### Goals
- Keep solutions coherent, secure, and maintainable
- Make technical decisions clear and timely
- Balance near-term delivery with long-term system health

### Typical Communication
- Design reviews and technical discussions with Developers
- Solution-constraint discussions with Product Managers
- Dependency and risk updates with Project Managers
- Architecture decisions and guidance shared in design documents

### How they interact with existing roles
- **Developers:** Collaborate on designs, implementation choices, and technical reviews.
- **Product Managers:** Explain solution constraints and options that affect scope or outcomes.
- **Project Managers:** Make dependencies, estimates, and technical risks visible for planning.

### Key Hand-offs
- Provide architecture decisions, integration guidance, and non-functional requirements before implementation.
- Share technical dependencies and risks with Project Managers and Engineering Managers.
- Hand over design context and operational considerations to Developers and DevOps / SRE.

### Decision Rights / Boundaries
- Own technical direction and architecture guidance within agreed engineering standards.
- Advise on product trade-offs; Product Managers retain product scope and priority decisions.
- Do not own project schedules or unilaterally approve security or compliance exceptions.

---

## DevOps / SRE

### Role Summary
DevOps / SRE enable reliable delivery and operation through automation, observability, and operational readiness practices.

### Responsibilities
- Maintain CI/CD reliability and release automation
- Define observability, reliability, and incident-readiness practices
- Prepare operational runbooks and support deployment readiness
- Identify operational risks and reliability impacts

### Goals
- Make releases repeatable and safe
- Improve service reliability and time to recover
- Ensure teams can observe and operate what they deliver

### Typical Communication
- Deployment-readiness discussions with Developers and Technical Leads
- Release-window coordination with Project Managers
- Reliability-impact discussions with Product Managers
- Runbooks, dashboards, and incident follow-ups

### How they interact with existing roles
- **Developers:** Collaborate on build, deployment, observability, and operational readiness.
- **Product Managers:** Explain reliability risks and customer impact to inform product trade-offs.
- **Project Managers:** Coordinate release windows, readiness milestones, and operational dependencies.

### Key Hand-offs
- Provide deployment guidance, monitoring expectations, and runbooks before release.
- Hand over release status and operational risks to Project Managers and customer-facing partners.
- Share incidents and reliability follow-ups with Developers and Product Managers.

### Decision Rights / Boundaries
- Own operational practices and can raise a readiness concern or recommend delaying an unsafe deployment.
- Coordinate release execution; product scope and project priority remain with Product Managers and Project Managers.
- Do not accept security or compliance risks on behalf of their designated reviewers.

---

## Security / Compliance Reviewers

### Role Summary
Security / Compliance Reviewers assess security and compliance risks and define review criteria for sensitive changes and releases.

### Responsibilities
- Assess security risks and provide threat-modeling input
- Check applicable compliance requirements and evidence
- Advise on secure implementation and risk mitigations
- Define review and escalation criteria for sensitive releases

### Goals
- Reduce security and compliance risk before release
- Make required controls and evidence clear to the team
- Enable informed, timely risk decisions

### Typical Communication
- Security design and implementation reviews with Developers and Technical Leads
- Risk and release-impact updates with Product Managers and Project Managers
- Written findings, remediation guidance, and approval criteria

### How they interact with existing roles
- **Developers:** Explain secure implementation requirements and review mitigations.
- **Product Managers:** Clarify risk implications and the effect of controls on product scope.
- **Project Managers:** Identify review milestones, evidence needs, and escalation paths.

### Key Hand-offs
- Provide review findings, required mitigations, and approval criteria before release decisions.
- Return review evidence and unresolved risks to the designated release decision-makers.
- Escalate security incidents through the established incident process.

### Decision Rights / Boundaries
- Own security and compliance assessments and any formal sign-off assigned to the role.
- Can withhold that sign-off when required criteria are unmet; communicate exceptions through the authorized risk process.
- Do not set product priorities or independently change delivery plans.

---

## UX Researchers / Designers

### Role Summary
UX Researchers / Designers help teams understand user needs and create accessible, usable experiences.

### Responsibilities
- Validate user journeys and problem assumptions through research
- Create design specifications and interaction patterns
- Plan and conduct usability testing
- Identify accessibility considerations and design dependencies

### Goals
- Make product experiences useful, clear, and accessible
- Ground design decisions in user evidence
- Reduce usability risk before and after implementation

### Typical Communication
- Problem framing and success-metric discussions with Product Managers
- Design reviews and implementation discussions with Developers
- Milestone and dependency planning with Project Managers
- Research findings, prototypes, and design specifications

### How they interact with existing roles
- **Developers:** Clarify design behavior, accessibility needs, and implementation details.
- **Product Managers:** Shape problem framing, validate assumptions, and align on success measures.
- **Project Managers:** Identify design and research dependencies and agree on milestones.

### Key Hand-offs
- Provide research findings and design specifications before implementation.
- Share usability-test results and accessibility needs with Product Managers and Developers.
- Hand over validated design changes and remaining experience risks for release planning.

### Decision Rights / Boundaries
- Own research methods and design recommendations within agreed product goals and standards.
- Advise on usability and accessibility; Product Managers own product priority and Developers own implementation choices.
- Do not approve project scope or schedule changes.

---

## Customer Support / Success Liaisons

### Role Summary
Customer Support / Success Liaisons bring customer feedback into delivery and help prepare teams to support releases.

### Responsibilities
- Gather and share customer feedback and recurring pain points
- Prepare release communications and support materials
- Track known issues and customer impact
- Report post-release customer outcomes and support trends

### Goals
- Keep customer needs visible throughout delivery
- Help customers and support teams understand changes and known issues
- Close the loop between customer feedback and product decisions

### Typical Communication
- Feedback and impact discussions with Product Managers
- Stakeholder and release updates with Project Managers
- High-impact issue triage with Developers
- Release notes, support guidance, and customer-impact reports

### How they interact with existing roles
- **Developers:** Share reproducible, high-impact issues and customer context to support triage.
- **Product Managers:** Surface customer pain points and feedback to inform prioritization.
- **Project Managers:** Coordinate stakeholder updates, release communications, and support readiness.

### Key Hand-offs
- Provide customer themes and impact evidence during initiation and planning.
- Hand over release notes, known issues, and support guidance before release.
- Return post-release feedback and impact trends to Product Managers and the delivery team.

### Decision Rights / Boundaries
- Own customer-support readiness and the accuracy of support guidance within their remit.
- Recommend customer communication and escalation based on impact.
- Do not commit to product changes, delivery dates, or technical fixes on behalf of Product Managers, Project Managers, or Developers.

---

## Role Interaction Across the Lifecycle

In the matrix, **A** means accountable for the role's domain-specific deliverable in that phase, **C** means actively collaborates, and **I** means kept informed. Accountability is scoped to each role's area; it does not grant authority over another role's decisions.

| Role | Initiation | Planning | Execution | Release | Retrospective |
| --- | --- | --- | --- | --- | --- |
| Developers | I | C | A (implementation) | C | C |
| Product Managers | A (problem and outcomes) | A (product scope) | C | C | C |
| Project Managers | C | A (delivery plan) | C | C | A (facilitation and actions) |
| Engineering Managers / Tech Lead Managers | C | C | A (team capacity and delivery oversight) | C | C |
| Technical Leads / Architects | C | C | A (technical direction) | C | C |
| DevOps / SRE | I | C | C | A (operational readiness) | C |
| Security / Compliance Reviewers | C | C | C | A (required security/compliance review) | C |
| UX Researchers / Designers | C | C | C | C | C |
| Customer Support / Success Liaisons | C | C | I | C | C |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
