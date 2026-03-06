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

## Designer

### Role Summary
Designers define the user experience and visual direction of a product. They create and manage UI/UX assets, ensuring that features are usable, accessible, and aligned with the product vision.

### Responsibilities
- Work with Product Managers to design wireframes, user flows, and visual assets
- Collaborate with Developers to validate technical feasibility of designs
- Review implemented features for fidelity against design specifications
- Maintain a design system or shared asset library
- Participate in usability reviews and user research sessions

### Goals
- Deliver clear, consistent, and accessible user experiences
- Reduce back-and-forth between design and development through early alignment
- Ensure design intent is preserved through implementation

### Typical Communication
- Design review sessions and handoff meetings with Developers
- Annotations in design tools (e.g., Figma) shared with the team
- Sprint planning participation to clarify acceptance criteria for UI tasks

### Key Interactions
- **Product Managers**: Receive feature requirements; align on user goals and flows
- **Developers**: Collaborate on feasibility and provide design assets for implementation
- **QA/Test Engineers**: Review implemented UI against design specs before sign-off

---

## QA/Test Engineer

### Role Summary
QA/Test Engineers own validation of feature deliverables to ensure they meet acceptance criteria and quality standards. They serve as the last line of defense before release.

### Responsibilities
- Create and maintain test plans covering functional, regression, and exploratory testing
- Automate tests where practical (unit, integration, end-to-end)
- Perform manual QA for features that require it
- Sign off on release readiness in coordination with the Project Manager
- Track and report defects with clear reproduction steps

### Goals
- Prevent regressions and catch quality issues before they reach production
- Reduce manual testing burden through automation over time
- Provide clear, data-driven release readiness decisions

### Typical Communication
- Test plans shared before sprint or release testing windows
- Bug reports and defect tickets filed in the project tracker
- Release sign-off notes or QA summary reports

### Key Interactions
- **Developers**: Collaborate to clarify acceptance criteria and triage defects
- **Product Managers**: Validate feature behavior against user stories and acceptance criteria
- **Designers**: Review implemented UI against design specs
- **Project Managers**: Provide release readiness assessments

---

## Data Analyst

### Role Summary
Data Analysts identify success metrics, implement analytics instrumentation, and share actionable insights that inform product and project decisions.

### Responsibilities
- Advise teams on measurement setup and instrumentation for features
- Design reports and dashboards to track key product metrics
- Analyze post-release usage data and surface actionable insights
- Support hypothesis testing and A/B experiment analysis
- Present findings in reviews or planning sessions to guide prioritization

### Goals
- Enable data-driven decision-making across teams
- Ensure success metrics are measurable from day one of a release
- Provide clear visibility into feature adoption and business impact

### Typical Communication
- Analytics requirements and instrumentation specs shared with Developers before implementation
- Post-release reports and dashboards distributed to Product Managers and stakeholders
- Participation in sprint reviews to present data findings

### Key Interactions
- **Product Managers**: Collaborate on defining success metrics and reviewing results
- **Developers**: Provide instrumentation requirements and verify data collection
- **Project Managers**: Supply metrics for milestone reports and status updates

---

## Security/Compliance Stakeholder

### Role Summary
Security/Compliance Stakeholders ensure that project processes and deliverables comply with applicable security standards and regulatory requirements. They provide guidance, conduct reviews, and coordinate incident response.

### Responsibilities
- Review project plans and technical designs for security risks and compliance gaps
- Conduct security audits and threat modeling sessions as needed
- Coordinate or support incident response for security-related issues
- Advise teams on secure coding practices, data handling, and regulatory obligations
- Sign off on security requirements before major releases

### Goals
- Minimize security and compliance risk in deliverables
- Ensure teams follow established security policies and best practices
- Enable proactive identification and remediation of vulnerabilities

### Typical Communication
- Security review checklists and audit reports shared with Project Managers and Developers
- Participation in release go/no-go decisions when security criteria are in scope
- Incident communication and post-incident reviews for security events

### Key Interactions
- **Developers**: Review code and architecture for security issues; advise on mitigations
- **Product Managers**: Align on compliance requirements that affect feature design
- **Project Managers**: Flag security blockers and sign off on release readiness

---

## Support/Customer Success

### Role Summary
Support/Customer Success representatives serve as the voice of the customer. They coordinate support readiness, manage incoming feedback, and ensure customers can successfully use released features.

### Responsibilities
- Prepare support documentation and FAQs ahead of each release
- Triage incoming customer issues and escalate bugs to Developers and Product Managers
- Relay aggregated customer feedback to help inform the roadmap
- Participate in release readiness reviews to confirm support teams are prepared
- Track top customer pain points and advocate for improvements

### Goals
- Ensure customers can successfully adopt new features with minimal friction
- Reduce time-to-resolution for customer-reported issues
- Close the feedback loop between customers and the product team

### Typical Communication
- Support readiness updates shared ahead of releases
- Bug reports and customer feedback tickets filed in the project tracker
- Participation in sprint reviews to share customer insights

### Key Interactions
- **Product Managers**: Share customer feedback and pain points to inform prioritization
- **Developers**: Escalate bugs and provide reproduction steps for customer issues
- **Project Managers**: Confirm support readiness as part of the release checklist

---

## Executive Sponsor

### Role Summary
The Executive Sponsor provides high-level strategic direction, champions the project's value to the organization, and removes escalated blockers that are beyond the team's authority to resolve.

### Responsibilities
- Set the initial project vision and ensure alignment with organizational priorities
- Review progress at major milestones and decision gates
- Facilitate access to resources, budget, or cross-functional support when needed
- Support escalation resolution for issues that cannot be resolved at the team level
- Communicate project status and value to senior leadership

### Goals
- Ensure the project delivers measurable business value
- Maintain organizational alignment and sponsorship throughout delivery
- Remove strategic or organizational blockers efficiently

### Typical Communication
- Milestone reviews and executive briefings (typically monthly or at key decision gates)
- Escalation calls when critical issues require leadership involvement
- High-level status summaries from Project and Product Managers

### Key Interactions
- **Product Managers**: Align on product vision and strategic priorities
- **Project Managers**: Receive escalated risks and provide decisions on blockers
- **Stakeholders**: Communicate project value and organizational impact

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

