# OctoAcme — Handoff Checklist

## Purpose
Prevent work from getting lost or misunderstood when transitioning between project phases or between functional teams. Use this checklist at each major handoff point to ensure the receiving role has everything they need to proceed without delays.

---

## When to Use
- When moving from **Initiation → Planning**
- When moving from **Planning → Development**
- When moving from **Development → QA**
- When moving from **QA → Release/Deployment**
- When moving from **Release → Retrospective / Steady State**
- Any time work is handed between individuals or teams mid-sprint

---

## 1. Initiation → Planning Handoff
**Sender:** Product Manager (PdM) + Project Manager (PM)
**Receiver:** Full delivery team (Dev, QA, UX, Tech Writer)

### Checklist
- [ ] Project One-pager reviewed and approved by sponsor
- [ ] Success metrics and acceptance criteria documented
- [ ] Stakeholder list shared with delivery team
- [ ] High-level timeline and key milestones agreed
- [ ] Initial risk list reviewed and shared
- [ ] Resource needs confirmed (roles, availability)
- [ ] Project board / repo set up with initial structure
- [ ] Kickoff meeting scheduled and agenda shared

---

## 2. Planning → Development Handoff
**Sender:** Product Manager (PdM) + UX Designer
**Receiver:** Development team + QA

### Checklist
- [ ] Backlog items prioritised and estimated
- [ ] Acceptance criteria written and reviewed by PdM and QA
- [ ] Design assets (wireframes, prototypes, specs) linked to tickets
- [ ] Definition of Ready confirmed for sprint 1 items
- [ ] Definition of Done agreed and documented
- [ ] Test plan / QA approach drafted
- [ ] Branching and PR conventions shared with Dev team
- [ ] CI/CD pipeline set up and verified
- [ ] Dependencies identified and unblocked (or risk flagged)
- [ ] Technical design reviewed by Eng Manager / Tech Lead

---

## 3. Development → QA Handoff
**Sender:** Developer
**Receiver:** QA Engineer / Tester

### Checklist (per feature / PR)
- [ ] PR description includes issue link and acceptance criteria
- [ ] Unit and integration tests written and passing in CI
- [ ] Feature deployed to staging or test environment
- [ ] Known limitations or deferred items noted in PR/ticket
- [ ] Design assets reviewed against implementation by UX Designer (if UI)
- [ ] Release notes draft updated by Technical Writer (if applicable)
- [ ] Ticket status updated to "In Review" or "QA" on project board
- [ ] QA informed of any environment dependencies or test data needs
- [ ] Security scanning passed in CI

---

## 4. QA → Release / Deployment Handoff
**Sender:** QA Engineer + PM
**Receiver:** Developer (deployment lead) + PM + PdM

### Checklist
- [ ] All acceptance criteria verified and signed off by QA
- [ ] No critical or high-priority defects open (or exceptions documented with PdM approval)
- [ ] Regression test suite passed
- [ ] Release notes finalised by Technical Writer and reviewed by PdM
- [ ] Deployment checklist completed (see [Release & Deployment Guide](./octoacme-release-and-deployment.md))
- [ ] Rollback / mitigation plan documented and reviewed
- [ ] Deployment window communicated to stakeholders
- [ ] Support / Customer Success team briefed on new features and known issues
- [ ] Smoke test plan prepared for post-deploy verification

---

## 5. Release → Retrospective / Steady State Handoff
**Sender:** PM + PdM
**Receiver:** Full team + stakeholders

### Checklist
- [ ] Release announced to stakeholders and support team
- [ ] Post-deploy verification completed and results shared
- [ ] Success metrics baseline recorded for tracking
- [ ] Any open defects or known issues logged in the backlog
- [ ] Documentation updated (process docs, user guides, release notes live)
- [ ] Retrospective scheduled within one week of release
- [ ] Action items from retrospective captured with owners and due dates
- [ ] Risk register updated to reflect post-release status
- [ ] Project board archived or transitioned to maintenance mode

---

## Mid-Sprint Role-to-Role Handoff Notes

### UX Designer → Developer
- Share design files with version labels and change highlights
- Annotate designs with interaction notes, edge cases, and responsive behaviour
- Be available for async questions during implementation
- Schedule a design review before the item moves to QA

### Developer → Technical Writer
- Provide a feature summary: what changed, why, and how to use it
- Review draft documentation for technical accuracy before it's published
- Flag any API changes, configuration options, or migration steps

### PM → Scrum Master (sprint kick-off)
- Share sprint goal and any constraints (team availability, external dependencies)
- Confirm ceremony schedule and attendees
- Highlight any high-risk items or stakeholder sensitivities for the sprint

### PM → Stakeholders (milestone updates)
- Use the weekly status template from [Risk Management & Communication](./octoacme-risks-and-communication.md)
- Summarise progress, risks, and decisions needed clearly and concisely
- Confirm next expected communication date
