# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management Documentation. This is your guide to how we run projects at OctoAcme.

## Quick Summary

OctoAcme follows a structured yet flexible approach to project management that emphasizes:
- **Customer-first delivery** of measurable value
- **Iterative execution** with clear milestones
- **Transparent communication** with stakeholders
- **Data-informed decisions** based on success metrics
- **Continuous improvement** through retrospectives and learning

Our project lifecycle flows through five key phases: **Initiation → Planning → Execution → Release → Retrospective**.

## OctoAcme Project Management Process Overview

OctoAcme operates a structured five-phase project lifecycle designed to deliver customer value through iterative, data-informed decision-making. The process begins with **Initiation**, where teams validate business needs and create a lightweight Project One-pager with success metrics, stakeholder alignment, and resource requirements. This leads to **Planning**, where approved initiatives are broken into shippable increments with prioritized backlogs, acceptance criteria, and clear Definition of Done standards. The core **Execution & Tracking** phase manages day-to-day delivery through daily standups, weekly syncs, and a structured project board workflow (Backlog → Ready → In Progress → In Review → QA → Done). Teams follow a rigorous Pull Request workflow with small PRs (≤400 lines), automated CI testing, security scanning, and mandatory peer review before merging. Once features are complete, the **Release & Deployment** phase standardizes production releases with pre-release checklists, smoke tests, rollback plans, and post-deploy verification. Finally, **Retrospectives & Continuous Improvement** capture learnings and convert them into actionable improvements tracked through the project backlog.

OctoAcme defines clear roles and responsibilities across three core personas. **Product Managers** own the product vision, prioritize the backlog, and measure outcomes through success metrics defined during initiation. **Project Managers** coordinate delivery, manage schedules, risks, and cross-team dependencies, serving as the primary liaison for stakeholder communication and escalation. **Developers** implement features, write tests, participate in code reviews, and help identify technical risks. This separation of concerns—PdM defining "what," PM coordinating "how," and developers building "it"—ensures accountability and alignment across the organization.

Communication and risk management are woven throughout OctoAcme's process. The cadence includes twice-weekly team standups, weekly PM-PdM syncs, and monthly stakeholder updates, with ad-hoc escalations for blockers. Risk management follows a formal lifecycle: risks are identified during planning and execution, assessed for impact and likelihood, mitigated through documented action plans, and monitored in a shared Risk Register reviewed at weekly syncs. A three-level escalation path (Team → PM → Product Lead → Sponsor) ensures issues are surfaced and resolved quickly. Stakeholder communication uses templated weekly status updates and incident protocols to maintain transparency.

Quality assurance and continuous improvement are non-negotiable parts of the OctoAcme culture. Before release, teams must pass unit and integration tests, run end-to-end smoke tests on critical flows, complete security scanning in CI, and obtain manual QA sign-off when needed. Velocity and burndown metrics are tracked to monitor delivery health, and success metrics from the One-pager guide post-release validation. After each sprint, release, or milestone, teams conduct structured retrospectives (45–75 minutes) to identify what went well and what could improve, prioritizing 2–3 actionable items with clear owners and due dates. This commitment to measurement, accountability, and learning enables OctoAcme to deliver reliably while building a culture of psychological safety and continuous improvement.

## Project Management Process Documents

### Start Here
- **[OctoAcme Project Management Overview](./octoacme-project-management-overview.md)** — Foundational concepts, core roles, and the project lifecycle
- **[OctoAcme Personas](./octoacme-roles-and-personas.md)** — Definitions of Project Managers, Product Managers, Developers, and their responsibilities

### By Project Phase
- **[Project Initiation](./octoacme-project-initiation.md)** — Validate business need, align stakeholders, create a lightweight plan
- **[Project Planning](./octoacme-project-planning.md)** — Break work into shippable increments, identify dependencies, plan releases
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Day-to-day delivery, team rhythm, quality standards, blocker escalation
- **[Release & Deployment](./octoacme-release-and-deployment.md)** — Pre-release requirements, deployment checklist, rollback procedures
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings, drive actionable improvements

### Cross-Cutting Concerns
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Risk registers, stakeholder communication, escalation paths

## How to Use These Docs

- Keep project documentation updated in your project repository
- Add relevant process docs to `.copilot/` if you want Copilot Spaces to use them as context
- Refer to the appropriate process doc based on your current project phase
- Use the navigation links above to jump to the specific process guidance you need
