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
UX Designers ensure that products meet usability and user experience goals from ideation through delivery. They translate user needs and business requirements into intuitive workflows, prototypes, and visual designs.

### Responsibilities
- Conduct user research, usability testing, and synthesis of findings
- Create wireframes, prototypes, and high-fidelity design assets
- Collaborate with Product Managers to refine requirements from a user-centered perspective
- Participate in sprint planning and reviews to validate that implementations match design intent
- Maintain a design system or style guide shared with the development team
- Provide design annotations and acceptance notes to guide development

### Goals
- Deliver experiences that are intuitive, accessible, and consistent
- Reduce rework caused by ambiguous or misunderstood requirements
- Ensure user feedback informs each iteration

### Typical Communication
- Design reviews and prototype walkthroughs with PdM and Developers
- Usability test readouts shared with the full team
- Design handoff notes and annotated specs in project repository or design tool

### Interaction with Other Roles
| Role | Interaction |
|---|---|
| Product Manager (PdM) | Align on user needs, validate problem statements, review acceptance criteria |
| Developers | Provide design specs, answer implementation questions, review UI before release |
| Project Manager (PM) | Flag design dependency timelines; participate in sprint demos |
| QA / Testers | Share design annotations and acceptance notes to inform test scenarios |
| Technical Writer | Coordinate on in-product copy, help text, and onboarding content |

---

## Scrum Master / Agile Coach

### Role Summary
The Scrum Master or Agile Coach facilitates Agile ceremonies, removes blockers, and continually improves team practices. They serve the team rather than direct it, ensuring the team remains productive, focused, and aligned.

### Responsibilities
- Facilitate daily standups, sprint planning, sprint reviews, and retrospectives
- Track and remove blockers; escalate where the team cannot self-resolve
- Coach team members on Agile values and iterative delivery practices
- Shield the team from unplanned interruptions during a sprint
- Track sprint health, velocity trends, and capacity utilisation
- Support the Project Manager in maintaining the project board and burn-down data

### Goals
- Maximise team throughput while protecting team capacity and wellbeing
- Foster a culture of continuous improvement and psychological safety
- Keep ceremonies efficient and purposeful

### Typical Communication
- Daily standups and retrospective facilitation
- Sprint metrics shared with PM and PdM after each sprint
- One-on-one coaching conversations with team members as needed

### Interaction with Other Roles
| Role | Interaction |
|---|---|
| Project Manager (PM) | Co-own ceremony scheduling; share velocity and impediment data for status reports |
| Product Manager (PdM) | Ensure backlog is refined and prioritised ahead of each sprint |
| Developers | Remove blockers; coach on Agile practices; shield from scope creep |
| QA / Testers | Include QA in Definition of Done discussions; flag testing bottlenecks |
| UX Designer | Ensure design work feeds the sprint backlog with adequate lead time |

---

## Technical Writer

### Role Summary
Technical Writers maintain high-quality documentation that enables the team, users, and stakeholders to understand and use the product effectively. They own the documentation lifecycle from planning through post-release updates.

### Responsibilities
- Write and maintain process docs, onboarding guides, API references, and release notes
- Collaborate with Developers and PdM to clarify complex topics and capture tacit knowledge
- Review and proofread documentation for accuracy, consistency, and accessibility
- Maintain a documentation update checklist aligned with the release process
- Track documentation debt and propose improvements in retrospectives

### Goals
- Ensure no feature ships without corresponding documentation
- Reduce support burden by providing clear self-service content
- Maintain a single source of truth for product and process knowledge

### Typical Communication
- Documentation review cycles embedded in sprint and release workflows
- Async comments on PRs and docs for accuracy feedback
- Documentation status updates in weekly PM/PdM sync

### Interaction with Other Roles
| Role | Interaction |
|---|---|
| Product Manager (PdM) | Align on what documentation is needed per feature; review product copy |
| Project Manager (PM) | Include documentation tasks in the project plan and Definition of Done |
| Developers | Pair to document complex logic; review technical accuracy of written content |
| QA / Testers | Validate that documented steps match actual product behaviour |
| UX Designer | Coordinate on in-product help text, tooltips, and onboarding flows |

---

## QA Engineer / Tester

### Role Summary
QA Engineers ensure that software meets defined quality standards and acceptance criteria before it reaches users. They design test strategies, execute tests, and advocate for quality throughout the development lifecycle.

### Responsibilities
- Design and maintain test plans, test cases, and automated test suites
- Execute manual and automated tests across unit, integration, and end-to-end levels
- Report and track defects to resolution
- Validate acceptance criteria and contribute to the Definition of Done
- Participate in sprint planning to estimate testing effort and surface risks early
- Conduct regression testing before each release

### Goals
- Prevent defects from reaching production
- Enable confident, frequent releases through automated test coverage
- Provide clear, actionable bug reports that reduce resolution time

### Typical Communication
- Test result summaries after each sprint and before each release
- Defect reports linked to user stories or PRs
- Quality metrics (test coverage, defect escape rate) shared in weekly syncs

### Interaction with Other Roles
| Role | Interaction |
|---|---|
| Developers | Collaborate on acceptance criteria; review PRs for testability; pair on test automation |
| Product Manager (PdM) | Validate that delivered features meet stated success metrics |
| Project Manager (PM) | Report quality status and testing blockers during weekly syncs |
| UX Designer | Test UI implementations against design specs and accessibility standards |
| Scrum Master | Flag testing bottlenecks that affect sprint velocity |
| Technical Writer | Confirm that documented procedures match actual product behaviour |

---

## Engineering Manager / Tech Lead

### Role Summary
The Engineering Manager or Tech Lead provides technical direction, mentors engineers, and bridges delivery execution with broader organizational goals. They are accountable for code quality, architecture decisions, and team capability growth.

### Responsibilities
- Set and uphold technical standards (architecture, code review, security, observability)
- Remove technical blockers and make or facilitate high-impact engineering decisions
- Mentor and grow developers through feedback and career development discussions
- Collaborate with PdM on feasibility, complexity, and trade-off analysis
- Represent engineering in cross-functional planning and roadmap discussions
- Oversee onboarding of new engineers to team practices and codebase

### Goals
- Maintain a healthy, scalable codebase that supports product velocity
- Grow team technical capability and reduce bus-factor risk
- Align engineering effort with business priorities

### Typical Communication
- Architecture decision records (ADRs) for significant technical choices
- Code review participation and PR comments
- 1:1s with engineers and attendance at planning and retrospective ceremonies

### Interaction with Other Roles
| Role | Interaction |
|---|---|
| Project Manager (PM) | Provide effort estimates; flag technical risks; confirm milestone feasibility |
| Product Manager (PdM) | Evaluate technical trade-offs; influence feasibility of roadmap items |
| Developers | Provide technical guidance; conduct code and architecture reviews |
| Scrum Master | Collaborate on removing engineering blockers during sprints |
| QA Engineer | Define testability requirements and support automated test strategy |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the [RACI-lite template](./octoacme-raci-template.md) to assign roles for specific project activities.
- Use the [Handoff Checklist](./octoacme-handoff-checklist.md) to manage transitions between phases and teams.

