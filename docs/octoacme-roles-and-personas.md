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

## UX/UI Designers

### Role Summary
UX/UI Designers create intuitive, accessible, and visually consistent user experiences. They bridge the gap between user needs and technical implementation, collaborating closely with Product Managers and Developers.

### Responsibilities
- Conduct user research and usability testing
- Design wireframes, prototypes, and high-fidelity mockups
- Define and maintain design systems and style guides
- Collaborate with developers to ensure accurate implementation of designs
- Advocate for accessibility and inclusive design practices

### Goals
- Improve user satisfaction and task completion rates
- Reduce onboarding friction and support costs
- Ensure visual and interaction consistency across the product

### Typical Communication
- Design reviews and critique sessions
- Handoff documentation (Figma, Zeplin, or similar)
- Regular syncs with Product Managers and front-end Developers

### Interaction with Existing Roles
- **Developers**: Provide design specs, assets, and clarifications; review implemented features for fidelity
- **Product Managers**: Translate user research insights into design requirements
- **Project Managers**: Report design milestones and flag scope changes affecting UX

---

## QA Engineers

### Role Summary
QA Engineers ensure the quality, reliability, and performance of software releases. They design and execute test strategies that catch defects early and prevent regressions.

### Responsibilities
- Develop and maintain test plans, test cases, and automated test suites
- Execute functional, regression, integration, and performance tests
- Identify, document, and track defects to resolution
- Collaborate with Developers to reproduce and resolve issues
- Define and monitor quality metrics (defect rate, test coverage, etc.)

### Goals
- Reduce defect escape rate to production
- Increase test automation coverage
- Enable fast, confident releases through robust regression suites

### Typical Communication
- Bug reports and defect triage meetings
- Test result summaries and quality dashboards
- Sprint ceremonies to surface quality risks early

### Interaction with Existing Roles
- **Developers**: Collaborate on test-driven development and defect resolution
- **Product Managers**: Validate that acceptance criteria are testable and met
- **Project Managers**: Communicate quality risks that could impact release timelines

---

## DevOps / Site Reliability Engineers (SRE)

### Role Summary
DevOps/SRE Engineers own the build, deployment, and operational reliability of systems. They embed reliability and automation practices throughout the software delivery lifecycle.

### Responsibilities
- Design and maintain CI/CD pipelines and deployment automation
- Monitor system health, performance, and availability
- Define and track SLOs, SLAs, and error budgets
- Manage infrastructure as code and cloud environments
- Lead incident response, post-mortems, and reliability improvements

### Goals
- Achieve high availability and fast mean time to recovery (MTTR)
- Automate toil and reduce manual intervention
- Enable safe, frequent deployments with minimal downtime

### Typical Communication
- On-call rotation and incident channels
- Runbooks, post-mortem reports, and reliability dashboards
- Sprint ceremonies to surface infrastructure risks and capacity needs

### Interaction with Existing Roles
- **Developers**: Support local development environments and pipeline troubleshooting
- **QA Engineers**: Maintain test environments and deployment gates
- **Project Managers**: Communicate infrastructure changes and outage risks

---

## Technical Leads / Architects

### Role Summary
Technical Leads and Architects set the technical direction for projects and ensure that solutions are scalable, maintainable, and aligned with organizational standards.

### Responsibilities
- Define technical architecture, patterns, and best practices
- Lead design reviews and architectural decision records (ADRs)
- Mentor developers and guide technical skill growth
- Identify and mitigate technical debt and architectural risk
- Evaluate and recommend tools, frameworks, and third-party services

### Goals
- Build systems that are easy to change, scale, and operate
- Reduce technical debt while delivering business value
- Align technical decisions with long-term product strategy

### Typical Communication
- Architecture design documents and ADRs
- Technical deep-dives and whiteboard sessions
- Code review guidance and engineering standards documentation

### Interaction with Existing Roles
- **Developers**: Provide technical guidance, mentorship, and code review feedback
- **DevOps/SRE**: Align on infrastructure design and deployment architecture
- **Product Managers**: Translate product requirements into scalable technical solutions

---

## Business Analysts

### Role Summary
Business Analysts bridge the gap between business stakeholders and the development team. They elicit, document, and validate requirements to ensure solutions deliver intended business outcomes.

### Responsibilities
- Gather and document business requirements from stakeholders
- Create user stories, process flows, and acceptance criteria
- Analyze current-state processes and identify improvement opportunities
- Validate delivered solutions against business requirements
- Support change management and stakeholder communication

### Goals
- Ensure delivered solutions address real business problems
- Reduce rework due to misunderstood or incomplete requirements
- Improve stakeholder alignment and requirement traceability

### Typical Communication
- Requirements workshops and stakeholder interviews
- Business requirements documents (BRDs) and process maps
- Sprint reviews and acceptance sign-off sessions

### Interaction with Existing Roles
- **Product Managers**: Translate business goals into prioritized product requirements
- **Developers**: Clarify requirements and validate technical interpretations
- **Project Managers**: Provide requirements status updates and flag scope changes

---

## Scrum Masters / Agile Coaches

### Role Summary
Scrum Masters and Agile Coaches facilitate agile ceremonies, remove impediments, and coach teams on continuous improvement. They protect the team's focus and foster a culture of collaboration.

### Responsibilities
- Facilitate sprint ceremonies (planning, standups, reviews, retrospectives)
- Remove blockers and escalate impediments to leadership
- Coach the team on agile principles and practices
- Track team velocity, capacity, and health metrics
- Support organizational agile transformation and maturity

### Goals
- Improve team velocity, predictability, and morale
- Foster a continuous improvement mindset
- Reduce waste and friction in the delivery process

### Typical Communication
- Sprint ceremonies and team retrospectives
- Impediment logs and escalation summaries
- Agile health dashboards and coaching reports

### Interaction with Existing Roles
- **Developers**: Shield from distractions and facilitate self-organization
- **Project Managers**: Coordinate on timelines, dependencies, and stakeholder updates
- **Product Managers**: Facilitate backlog refinement and sprint goal alignment

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- New personas (UX/UI Designer, QA Engineer, DevOps/SRE, Technical Lead, Business Analyst, Scrum Master) extend the original set to provide a more comprehensive view of modern software delivery teams.

