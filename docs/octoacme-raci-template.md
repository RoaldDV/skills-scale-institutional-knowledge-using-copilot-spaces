# OctoAcme — RACI-Lite Template

## Purpose
Provide a lightweight Responsible/Accountable/Consulted/Informed (RACI) table that teams can copy and customise for each project or major initiative. A completed RACI matrix prevents role confusion, surfaces missing ownership, and accelerates decision-making.

## How to use
1. Copy the blank table below into your project's planning doc or README.
2. For each activity row, assign at least one **R** (Responsible) and exactly one **A** (Accountable).
3. Add **C** (Consulted) for roles whose input is needed before work is done.
4. Add **I** (Informed) for roles who need status updates but are not doing the work.
5. Review the completed table in your kickoff meeting and update as roles evolve.

## RACI Key
| Letter | Meaning |
|---|---|
| **R** | **Responsible** — does the work |
| **A** | **Accountable** — owns the outcome; ultimately answerable |
| **C** | **Consulted** — provides input before decisions are finalised |
| **I** | **Informed** — kept up-to-date on decisions/progress |

> Each activity must have exactly one **A**. Multiple **R**s are allowed but keep them focused.

---

## Blank RACI Table

| Activity / Deliverable | PM | PdM | Dev | QA | UX | Scrum Master | Tech Writer | Eng Manager |
|---|---|---|---|---|---|---|---|---|
| Project charter / one-pager | | | | | | | | |
| Backlog creation and prioritisation | | | | | | | | |
| Sprint planning | | | | | | | | |
| Technical design / architecture | | | | | | | | |
| UI/UX design and prototyping | | | | | | | | |
| Feature development | | | | | | | | |
| Test plan and test case authoring | | | | | | | | |
| Code review | | | | | | | | |
| Acceptance testing / UAT | | | | | | | | |
| Risk register maintenance | | | | | | | | |
| Stakeholder status updates | | | | | | | | |
| Release notes | | | | | | | | |
| Deployment execution | | | | | | | | |
| Post-release verification | | | | | | | | |
| Retrospective facilitation | | | | | | | | |
| Documentation update | | | | | | | | |
| Incident response coordination | | | | | | | | |

---

## Example: Filled RACI for a Typical Feature Release

| Activity / Deliverable | PM | PdM | Dev | QA | UX | Scrum Master | Tech Writer | Eng Manager |
|---|---|---|---|---|---|---|---|---|
| Project charter / one-pager | A/R | C | I | I | I | I | I | C |
| Backlog creation and prioritisation | C | A/R | C | C | C | C | I | C |
| Sprint planning | R | C | R | R | C | A/R | I | C |
| Technical design / architecture | I | C | R | C | I | I | I | A/R |
| UI/UX design and prototyping | I | C | C | I | A/R | I | I | I |
| Feature development | I | I | A/R | C | C | I | I | C |
| Test plan and test case authoring | I | C | C | A/R | C | I | I | I |
| Code review | I | I | R | I | I | I | I | A/R |
| Acceptance testing / UAT | I | A | R | R | C | I | I | I |
| Risk register maintenance | A/R | C | C | C | I | C | I | C |
| Stakeholder status updates | A/R | C | I | I | I | I | I | I |
| Release notes | C | C | C | I | I | I | A/R | I |
| Deployment execution | C | I | A/R | R | I | I | I | C |
| Post-release verification | C | I | R | A/R | I | I | I | I |
| Retrospective facilitation | C | C | R | R | R | A/R | I | C |
| Documentation update | C | C | C | C | C | I | A/R | I |
| Incident response coordination | A/R | C | R | R | I | I | I | C |

---

## Tips
- If a cell is empty, explicitly confirm that role has no involvement rather than leaving it ambiguous.
- Avoid assigning **A** to a committee — accountability must rest with one individual.
- Revisit the RACI at each sprint retrospective if team composition changes.
- Cross-reference with the [Handoff Checklist](./octoacme-handoff-checklist.md) to ensure smooth phase transitions.
