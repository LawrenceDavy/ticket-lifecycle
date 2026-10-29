# osTicket workflow evidence and incident-testing plan

Updated 29 October 2026. AI-assisted from the existing osTicket repositories. This document is a reproducible plan **not a claim of newly completed technical incident investigation**.

## Existing documented evidence
The [post-install configuration repo](https://github.com/LawrenceDavy/post-install-config) describes roles, departments, agents, Level I/II teams, help topics and example SLA periods. The [ticket lifecycle README](README.md) demonstrates sample ticket intake, assignment, internal/public notes, escalation and closure. Screenshots demonstrate the support workflow, **not the diagnosis and repair of a real infrastructure outage**.

## Planned fault A: misrouted ticket - NOT RUN
Business symptom: a synthetic issue lands with the wrong team and is not worked under the intended escalation policy.

1. In an isolated osTicket instance, create a known-good test ticket and record the assigned department/team, help topic and SLA.
2. Note the original test-only help topic and ticket-filter configuration.
3. Deliberately change a help topic or routing rule to direct a *new test ticket* to an incorrect team. Do not assume your version routes automatically: inspect actual behaviour.
4. Capture the new ticket's ID (redacted), route, assignment and timestamps. Check the help topic, ticket filters, agent permissions and departmental settings until you can identify the rule responsible.
5. Restore the intended rule. Create another new ticket to test correct routing; separately move the misrouted one and record the handover.
6. Capture before/after configuration and audit trail; remove test accounts and tickets.

## Planned fault B: genuine simulated service failure - NOT RUN
Create a synthetic ticket for an intentionally stopped **test-only** service. Capture user symptoms, actual service/process and event-log evidence, at least two candidate causes, a discriminating test, the minimal fix, a service-level validation and an accurate closure note. Ticket entry alone is not technical troubleshooting.

## Evidence record - fill only with observed results
Date, lab version and ticket IDs: NOT RECORDED.
Baseline workflow and intended route: NOT RUN.
Deliberately wrong setting and observed result: NOT RUN.
Tests and actual root cause: NOT RUN.
Correction, post-fix verification and ticket history: NOT RUN.
Rollback and removal of synthetic information: NOT RUN.

## Honest positioning
Describe this as personal support workflow practice. A configured SLA is not real-world SLA performance. Do not imply commercial support employment, a resolved customer outage, or tested incident response until evidence exists.

References: [ticket walkthrough](README.md) | [osTicket post-install configuration](https://github.com/LawrenceDavy/post-install-config).
