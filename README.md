# OKX Foundation Risk Disclosure

This repository centralizes public communication when OKX Foundation smart contracts encounter security or risk incidents that require pausing and resuming operations. It provides a unified, transparent log of every disclosed contract issue so that contract users, partners, and auditors can quickly understand the incident context, mitigations, and next steps.

## Background

- **Problem scenario**: When a foundation contract is found to contain logical flaws, configuration mistakes, or on-chain exploit risk, the team must quickly determine whether to pause the contract, how to validate fixes, and when to resume.
- **Disclosure goal**: Clarify the root cause, blast radius, mitigation steps, and recovery criteria to minimize information gaps.

## Required disclosure content

Each disclosure should cover at least:
1. Incident summary (timestamp, trigger, severity).
2. Affected contract repository and deployment address.
3. Risk description and validation steps.
4. Actions taken (pause, upgrade, rollback, etc.).
5. Expected recovery timeline and prerequisites.
6. Follow-up owners and tracking plan.

## Workflow

1. Open a new disclosure issue via `.github/ISSUE_TEMPLATE.md`, capturing all details.
2. Draft the mitigation and disclosure plan, then submit a PR referencing the issue and contract repo using `.github/PULL_REQUEST_TEMPLATE.md`.
3. Once the risk is mitigated and information is disclosed, close the issue and mirror the outcome in this README or other public channels.

## Repository layout

- `README.md`: repository purpose and disclosure workflow.
- `.github/ISSUE_TEMPLATE.md`: public disclosure issue template.
- `.github/PULL_REQUEST_TEMPLATE.md`: disclosure or fix PR template.

Add any extra materials (timeline, FAQ, legal statement, etc.) in new folders and reference them here when needed.

