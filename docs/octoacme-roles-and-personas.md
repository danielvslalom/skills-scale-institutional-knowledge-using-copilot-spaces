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
UX Designers advocate for user-centric design and ensure that products are intuitive, accessible, and aligned with user needs. They bridge the gap between user research insights and engineering implementation.

### Responsibilities
- Conduct user research and usability testing to uncover needs and pain points
- Create wireframes, prototypes, and design specifications
- Define and maintain design systems and style guides
- Review implemented features against design specs and provide feedback
- Collaborate with Product Managers to validate assumptions and acceptance criteria

### Goals
- Deliver cohesive, accessible user experiences that meet user needs
- Reduce usability issues discovered late in development
- Maintain design consistency across products and features

### Typical Communication
- Design review sessions with Developers and Product Managers
- Usability test reports shared with Product and QA
- Prototype walk-throughs at sprint reviews
- Async feedback via design tools or PR comments on UI changes

### Role Interactions
- **With Developers:** Partners closely to ensure design feasibility; reviews implementations and provides acceptance sign-off on UI changes.
- **With Product Managers:** Collaborates to translate user needs into feature requirements; validates designs against product goals.
- **With Project Managers:** Flags design dependencies and timelines; participates in kickoff and planning to surface design effort estimates.
- **With QA/Testing:** Supports usability testing; clarifies design intent to inform test cases.

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business stakeholders and delivery teams. They elicit, document, and manage requirements, ensuring that technical work is grounded in clear business needs and measurable outcomes.

### Responsibilities
- Elicit and document functional and non-functional requirements from stakeholders
- Create and maintain business requirements documents (BRDs) and functional specs
- Manage scope: identify, assess, and communicate scope changes
- Translate business needs into actionable user stories and acceptance criteria
- Support test case definition and UAT planning

### Goals
- Ensure requirements are clear, complete, and agreed upon before development starts
- Reduce rework caused by ambiguous or missing requirements
- Align technical deliverables with stated business objectives

### Typical Communication
- Requirements workshops and stakeholder interviews
- Functional spec reviews with Product Managers, Developers, and QA
- Scope change assessments shared with the Project Manager
- Backlog refinement sessions to clarify acceptance criteria

### Role Interactions
- **With Product Managers:** Collaborates to translate product vision into detailed requirements; aligns on scope and priority.
- **With Developers:** Clarifies ambiguous requirements during development; reviews implementations against acceptance criteria.
- **With Project Managers:** Supports scope management; flags risks associated with requirement changes.
- **With QA/Testing:** Co-defines acceptance criteria and UAT scenarios to ensure test coverage aligns with business expectations.

---

## DevOps Engineer

### Role Summary
DevOps Engineers design, build, and maintain the pipelines, infrastructure, and tooling that enable reliable, repeatable delivery. They champion automation, observability, and operational excellence across the development lifecycle.

### Responsibilities
- Design and maintain CI/CD pipelines for build, test, and deployment automation
- Manage infrastructure as code (IaC) and environment provisioning
- Define and enforce deployment standards, branching strategies, and release gates
- Monitor system health and respond to production incidents
- Drive improvements in build speed, deployment frequency, and reliability

### Goals
- Minimize manual steps in the release process and reduce deployment risk
- Ensure environments are consistent, reproducible, and auditable
- Provide fast feedback loops to Developers through automated testing and monitoring

### Typical Communication
- Release readiness reviews with Project Managers and QA
- Incident post-mortems and runbook updates
- Pipeline and infrastructure change notifications to the delivery team
- Coordination with Developers on build/test failures and environment issues

### Role Interactions
- **With Developers:** Collaborates on build and test automation; helps troubleshoot CI failures and reviews infrastructure-as-code changes.
- **With Project Managers:** Provides deployment readiness status; flags infrastructure blockers or environment risks affecting the timeline.
- **With QA/Testing:** Ensures test environments mirror production; coordinates automated test execution in CI pipelines.
- **With Change Manager:** Coordinates change advisory board (CAB) submissions; provides technical impact assessments for releases.

---

## Change Manager

### Role Summary
Change Managers plan and oversee organizational and process change introduced by a project. They ensure that people, processes, and communication are ready for new capabilities, minimizing disruption and maximizing adoption.

### Responsibilities
- Develop and maintain change management plans, impact assessments, and stakeholder analyses
- Lead communication and training planning for go-live and post-launch adoption
- Coordinate cross-functional change readiness reviews
- Gather adoption feedback post-launch and update rollout playbooks accordingly
- Maintain a change log and ensure approvals are tracked

### Goals
- Achieve smooth transitions with minimal disruption to operations
- Drive adoption and long-term retention of new processes or capabilities
- Ensure stakeholders are informed, prepared, and supportive

### Typical Communication
- Change advisory board (CAB) or readiness meetings before each release
- Training plans and communication drafts reviewed with stakeholders
- Go/no-go checklists shared with Project Manager and Product Lead
- Post-launch adoption surveys and feedback summaries

### Role Interactions
- **With Project Managers:** Aligns change management milestones with project timelines; co-owns the go/no-go decision.
- **With Product Managers:** Translates product changes into stakeholder impact narratives; collaborates on communication plans.
- **With Developers / DevOps Engineers:** Reviews deployment plans to understand technical change scope; incorporates rollback procedures into change plans.
- **With Stakeholders:** Primary liaison for managing expectations, gathering feedback, and driving change adoption.

---

## Scrum Master (if Agile)

### Role Summary
The Scrum Master serves the delivery team by facilitating Agile ceremonies, removing impediments, and coaching team members on Agile principles and practices. They protect the team's focus and foster a culture of continuous improvement.

### Responsibilities
- Facilitate Agile ceremonies: sprint planning, daily standups, sprint reviews, and retrospectives
- Identify and remove blockers that impede the team's progress
- Coach team members and stakeholders on Agile values and practices
- Track and communicate sprint progress, velocity, and health metrics
- Shield the team from unplanned interruptions and scope creep

### Goals
- Sustain a predictable, high-performing delivery cadence
- Continuously improve team processes and collaboration
- Foster psychological safety and transparent communication

### Typical Communication
- Daily standup facilitation (timebox: 15 minutes)
- Sprint review and retrospective facilitation
- Impediment log updates shared with Project Manager
- Agile metrics dashboards (velocity, burndown) distributed to stakeholders

### Role Interactions
- **With Developers:** Acts as a servant leader; removes technical and process blockers; coaches on Agile best practices.
- **With Product Managers:** Ensures backlog is refined and ready for sprint planning; facilitates healthy prioritization conversations.
- **With Project Managers:** Aligns sprint progress with project milestones; escalates risks and impediments that affect delivery commitments.
- **With QA/Testing:** Ensures testing activities are included in sprint capacity planning and that Definition of Done incorporates quality gates.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- For a visual overview of how these roles interact and share responsibilities, see the [OctoAcme RACI Template](./octoacme-raci-template.md).

