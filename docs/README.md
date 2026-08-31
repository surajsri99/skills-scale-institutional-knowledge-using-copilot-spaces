# OctoAcme Project Management Documentation

## Overview
OctoAcme runs projects with a lightweight, iterative process that moves from formal initiation through planning, execution, release, and retrospective. Work starts with a Project One‑pager and stakeholder alignment, then is broken into shippable increments with prioritized backlogs, clear acceptance criteria, and a Definition of Done. Key artifacts (project charter/one‑pager, roadmap, sprint backlog, risk register, release notes) are stored in this docs/ directory as the single source of truth.

Our workflows emphasize small, well‑scoped work and automated checks. Teams use a project board (Backlog → Ready → In Progress → In Review → QA → Done) and a Pull Request workflow that encourages small PRs, links to issues with acceptance criteria, and requires passing CI and security scans before review. Releases are categorized (patch/minor/major) with pre‑release checks, staged deployments, smoke tests, and a documented rollback plan.

Roles and responsibilities are explicit: Product Managers define outcomes and prioritize work; Project Managers coordinate delivery, risks, and stakeholder communication; Developers implement and test; QA validates acceptance criteria through automated and manual tests. Daily standups, weekly delivery syncs, and sprint demos keep progress and risks visible. Retrospectives capture improvements and action items, which are tracked back into the backlog.

Quality assurance combines unit, integration, and end‑to‑end smoke tests, security scanning in CI, and manual QA for feature acceptance when needed. The process includes escalation paths for blockers, a risk register for tracking mitigations, and a continuous improvement loop so practices evolve based on measured outcomes and team learnings.

## Quick Start
New to OctoAcme? Start with the Project Management Overview to get the high‑level approach, then follow the lifecycle documents for your current phase.

- Project Management Overview: ./octoacme-project-management-overview.md
- Roles & Personas: ./octoacme-roles-and-personas.md
- Project Initiation: ./octoacme-project-initiation.md
- Project Planning: ./octoacme-project-planning.md
- Execution & Tracking: ./octoacme-execution-and-tracking.md
- Release & Deployment: ./octoacme-release-and-deployment.md
- Retrospective & Continuous Improvement: ./octoacme-retrospective-and-continuous-improvement.md
- Risks & Communication: ./octoacme-risks-and-communication.md

## How to Contribute / Update Docs
To propose additions or edits to these process docs, open an issue using the "Add Content to Project Management Process Docs" template in .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml. For small updates, create a branch, add the change in docs/, and open a pull request referencing the related issue.

## Acceptance Criteria (for this README)
- This README provides an accurate index and summary of all files in docs/
- The README includes a brief overview of OctoAcme's core project management processes
- Links to each existing document are present and correct
