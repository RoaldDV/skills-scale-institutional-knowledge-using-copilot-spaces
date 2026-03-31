# OctoAcme — Definition of Ready & Definition of Done

## Purpose
Establish shared, team-agreed criteria that determine when a backlog item is ready to begin development (Definition of Ready) and when it is truly complete (Definition of Done). Using these definitions consistently reduces rework, prevents misunderstandings, and supports confident, frequent releases.

---

## Definition of Ready (DoR)

A backlog item **must meet all of the following criteria** before it can be pulled into a sprint. The Scrum Master and PdM jointly validate readiness during backlog refinement.

### DoR Checklist — per Backlog Item

**Clarity**
- [ ] The user story is written in the format: *"As a [persona], I want [action] so that [outcome]."*
- [ ] Acceptance criteria are written in clear, testable language (e.g., Given/When/Then or bullet list)
- [ ] The item has a meaningful title and unambiguous description with no open questions

**Design & UX**
- [ ] UI/UX design assets are linked to the ticket (wireframes, prototypes, or annotated specs)
- [ ] Edge cases and error states are documented or flagged for follow-up
- [ ] Accessibility requirements are noted (if applicable)

**Technical**
- [ ] Technical dependencies identified and confirmed unblocked (or risk noted)
- [ ] API contracts or data requirements agreed with relevant teams
- [ ] Security or compliance considerations noted (if applicable)

**Estimation & Planning**
- [ ] Item is estimated (story points or T-shirt size)
- [ ] Item is small enough to complete within one sprint; if not, it is split
- [ ] Owner or team assigned to deliver the item

**Documentation**
- [ ] Documentation scope agreed (what needs to be written/updated)
- [ ] Technical Writer is aware of the item if docs are required

---

## Definition of Done (DoD)

A backlog item or feature is **Done** only when **all of the following criteria** are met. The QA Engineer and PM validate completeness before a ticket moves to "Done" on the board.

### DoD Checklist — per Feature / User Story

**Development**
- [ ] Code implemented and passes all acceptance criteria
- [ ] Code reviewed and approved by at least one peer (Eng Manager for significant changes)
- [ ] All automated tests (unit, integration) written and passing in CI
- [ ] No known regressions introduced (regression suite passed)
- [ ] Security scanning passed in CI pipeline
- [ ] Code merged to the target branch following agreed branching conventions

**Quality**
- [ ] QA Engineer has validated acceptance criteria on staging environment
- [ ] Manual exploratory testing completed for UI/UX changes
- [ ] Defects found during testing resolved or explicitly deferred with PdM sign-off
- [ ] Accessibility tested for UI changes (e.g., keyboard navigation, screen reader)

**Design**
- [ ] UX Designer has reviewed the implementation against design specifications
- [ ] In-product copy / help text reviewed and approved

**Documentation**
- [ ] User-facing documentation updated (user guide, help text, release notes)
- [ ] Process or internal docs updated if workflows changed
- [ ] Technical Writer has reviewed and published applicable documentation

**Deployment Readiness**
- [ ] Feature deployed to staging and verified
- [ ] Rollback steps documented if needed
- [ ] Feature flags or configuration options documented
- [ ] Stakeholders notified of the upcoming change

**Project Board**
- [ ] Ticket status updated to "Done"
- [ ] Acceptance criteria marked as verified in the ticket
- [ ] Time tracking / effort logged (if required)

---

## DoD — Release Level

In addition to the per-story DoD, the following criteria must be met before a **release** is marked complete.

- [ ] All planned features for the release meet the per-story DoD
- [ ] End-to-end smoke tests passed on staging
- [ ] Release notes finalised and reviewed by PdM and Technical Writer
- [ ] Deployment executed and post-deploy verification completed
- [ ] Stakeholder announcement sent
- [ ] Success metrics baseline recorded
- [ ] Retrospective scheduled

---

## Maintaining These Definitions

- Review the DoR and DoD at the **first retrospective of a new project** and update them to reflect team context.
- Revisit at least **quarterly** or after any significant process change.
- Any team member can propose changes — bring proposals to the next retrospective.
- Store the agreed DoR/DoD in the project repository so it is version-controlled and discoverable.

---

## Related Documents
- [Project Planning](./octoacme-project-planning.md) — includes sprint planning and backlog item template
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — workflow and quality standards
- [Handoff Checklist](./octoacme-handoff-checklist.md) — phase-by-phase transition checklists
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — process improvement cadence
