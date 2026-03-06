# OctoAcme RACI Template

Use this template to map responsibilities across roles at the start of each project. Completing a RACI at initiation reduces ambiguity, prevents duplication of effort, and helps new team members understand where to direct questions.

**RACI Key:**
- **R** — Responsible: does the work
- **A** — Accountable: approves/signs off (one per row)
- **C** — Consulted: provides input before the work is done
- **I** — Informed: receives updates after the work is done

---

## How to use this template

1. Copy this file into your project folder (e.g., `docs/` or a project wiki).
2. Replace example activities with your project's actual activities.
3. Add or remove role columns as needed for your team.
4. Agree on and document the RACI in your kickoff meeting.
5. Review the RACI at each phase transition or when team composition changes.

---

## RACI Matrix

| Activity / Deliverable | Project Manager | Product Manager | Developer | UX Designer | Business Analyst | DevOps Engineer | Change Manager | Scrum Master | QA / Testing | Stakeholders |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Initiation** | | | | | | | | | | |
| Define problem statement & goals | A | R | I | I | C | I | C | I | I | C |
| Identify stakeholders | R | C | I | I | C | I | C | I | I | A |
| Create project one-pager / charter | R | C | I | I | C | I | C | I | I | A |
| **Planning** | | | | | | | | | | |
| Define scope and backlog | C | A/R | C | C | R | C | C | C | C | I |
| Assign roles and responsibilities (RACI) | R | C | C | C | C | C | C | C | C | I |
| Create release plan & milestones | R | C | I | I | C | C | C | I | C | I |
| Define Definition of Done | C | C | R | C | C | C | I | A/R | R | I |
| Design wireframes & prototypes | I | C | C | A/R | C | I | I | I | I | C |
| Document functional requirements | C | C | I | C | A/R | I | C | I | C | C |
| Infrastructure & pipeline setup | I | I | C | I | I | A/R | I | I | C | I |
| **Execution** | | | | | | | | | | |
| Develop features | I | C | A/R | C | C | C | I | I | C | I |
| Review & approve designs (UX) | I | C | C | A | I | I | I | I | I | I |
| Manage CI/CD & deployments | C | I | C | I | I | A/R | C | I | C | I |
| Facilitate Agile ceremonies | C | C | I | I | I | I | I | A/R | I | I |
| Track risks and dependencies | A/R | C | C | I | C | C | C | C | I | I |
| Manage scope changes | A | R | C | C | R | C | C | C | C | I |
| **Testing & Quality** | | | | | | | | | | |
| Write test cases / UAT scenarios | I | C | C | C | C | I | I | I | A/R | I |
| Execute testing & report defects | I | I | C | C | I | C | I | I | A/R | I |
| Approve quality gate for release | C | C | I | I | I | C | C | I | A/R | I |
| **Release & Deployment** | | | | | | | | | | |
| Create release readiness checklist | R | C | C | I | C | C | C | I | C | I |
| Change advisory board (CAB) approval | C | I | I | I | I | C | A/R | I | I | C |
| Execute deployment | C | I | C | I | I | A/R | C | I | C | I |
| Go-live communication & training | C | C | I | I | C | I | A/R | I | I | R |
| **Close & Retrospective** | | | | | | | | | | |
| Facilitate retrospective | R | C | I | I | I | I | I | A/R | I | I |
| Document lessons learned | A/R | C | C | C | C | C | C | C | C | I |
| Archive project artifacts | R | I | I | I | I | I | I | I | I | I |
| Measure outcomes vs. success metrics | C | A/R | I | C | C | I | C | I | I | C |

> **Note:** A/R in the same cell means the same person is both doing the work and accountable for it. In larger teams, consider splitting these.

---

## Role Interaction & Handoff Checklist

Use this checklist alongside the RACI to verify that key handoffs between roles are completed cleanly at each project phase.

### Initiation → Planning
- [ ] Problem statement signed off by Product Manager and stakeholders
- [ ] Proposed team / roles defined and RACI drafted
- [ ] Business Analyst assigned and requirements kick-off scheduled
- [ ] UX Designer engaged and user research scope agreed
- [ ] DevOps Engineer briefed on infrastructure needs

### Planning → Execution
- [ ] Backlog refined with clear acceptance criteria (Business Analyst + Product Manager)
- [ ] Designs reviewed and approved by UX Designer before development starts
- [ ] CI/CD pipeline ready and validated by DevOps Engineer
- [ ] Definition of Done agreed by Developers, QA, and Scrum Master
- [ ] Change Manager briefed on anticipated change impact

### Execution → Testing & Quality
- [ ] Features delivered against acceptance criteria (Developer → QA)
- [ ] UX Designer reviewed implemented UI against design specs
- [ ] Business Analyst confirmed functional requirements are met
- [ ] Defects triaged and prioritized with Product Manager and Project Manager

### Testing → Release & Deployment
- [ ] All test cases passing; test summary report produced by QA
- [ ] Release readiness checklist completed (Project Manager + DevOps Engineer)
- [ ] CAB approval obtained (Change Manager)
- [ ] Go-live communication and training materials ready (Change Manager)
- [ ] Rollback plan documented and approved by DevOps Engineer

### Release → Close & Retrospective
- [ ] Deployment verified in production (DevOps Engineer)
- [ ] Go-live announcement sent to stakeholders (Change Manager / Project Manager)
- [ ] Post-launch support period defined and covered
- [ ] Retrospective facilitated and action items logged (Scrum Master / Project Manager)
- [ ] Lessons learned documented and archived

---

## Meeting / Cadence Template

Use these lightweight agenda templates to run consistent meetings across project phases.

### Project Kickoff
**Purpose:** Align team and stakeholders on goals, scope, roles, and timeline.
**Duration:** 60–90 minutes
**Required attendees:** Project Manager, Product Manager, Business Analyst, Developers, UX Designer, QA, DevOps Engineer, Change Manager, Scrum Master (if Agile), Stakeholders

**Agenda:**
1. Welcome & introductions (5 min)
2. Problem statement and project goals (10 min) — *Product Manager*
3. Scope overview and out-of-scope items (10 min) — *Business Analyst / Product Manager*
4. Roles and RACI walkthrough (10 min) — *Project Manager*
5. High-level timeline and milestones (10 min) — *Project Manager*
6. Risks and open questions (10 min) — *All*
7. Next steps and action items (5 min) — *Project Manager*

**Expected outputs:** Kickoff notes, agreed RACI, open questions log, action items with owners and due dates.

---

### Weekly Status Sync
**Purpose:** Surface progress, risks, and blockers; keep stakeholders informed.
**Duration:** 30–45 minutes
**Required attendees:** Project Manager, Product Manager, Team Leads / representatives

**Agenda:**
1. Progress since last sync (10 min) — *Team Leads*
2. Risks and blockers (10 min) — *All*
3. Upcoming milestones / decisions needed (5 min) — *Project Manager*
4. Action items review (5 min) — *Project Manager*

**Expected outputs:** Updated status report, refreshed risk register, action items log.

---

### Sprint Retrospective
**Purpose:** Reflect on the sprint to identify improvements and celebrate wins.
**Duration:** 45–60 minutes
**Required attendees:** Delivery team (Developers, QA, UX Designer, DevOps Engineer, Business Analyst), Scrum Master, Product Manager

**Agenda:**
1. What went well? (10 min) — *All*
2. What could be improved? (10 min) — *All*
3. Experiment / action for next sprint (10 min) — *All*
4. Shout-outs and recognition (5 min) — *All*

**Expected outputs:** Retro action items with owners, updated team working agreements if needed.
