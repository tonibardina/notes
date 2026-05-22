---
type: Pain point
belongs_to: "[[Slack Client Product Analysis Summary]]"
client: Sesame
source: slack_channels_data
---

# Client Analysis: Sesame

## Client name

Sesame

## Summary of relevant conversation context

Sesame surfaces a mix of operational bugs and governance gaps. The account needs reliable invoice linking, safer user imports, stronger export controls, and more flexible handling of employee lifecycle and team assignment edge cases.

## Product-related pain points identified

| Pain point | Pain point category | Type of pain point | Estimated criticality | Supporting evidence or excerpts | Suggested product implications or follow-up actions |
| --- | --- | --- | --- | --- | --- |
| CSV user upload can block admin work at critical moments | User management | Bug | High | "p1 Bug" for "problems with user CSV upload" and urgency tied to SLA | Harden imports, show validation failures clearly, and allow non-invite staging for future users. |
| Invoice linking is unreliable | Data integrity and sync operations | Bug | High | "invoice linking to old deal" and "invoice not linked automatically" | Improve invoice-to-deal matching, add diagnostics, and support safe manual recovery without hidden side effects. |
| Deactivated users and team changes are not handled flexibly enough | Employee lifecycle and plan assignment | Workflow limitation | Medium-High | Deactivated users still showing in statements; client cannot date when users leave teams | Add effective-dated team membership and cleaner lifecycle handling in statements. |
| Export governance is too weak for a sensitive compensation environment | Data governance and exports | Missing feature | High | Requests for export tracking, customizable export columns, and a comprehensive audit log | Prioritize audit logs, export access controls, and configurable export payloads for enterprise readiness. |
| Admin segmentation is limited | User organization | Missing feature | Medium | Request for tags on individual employees | Add lightweight employee tagging and filtering to reduce admin workarounds. |

## Suggested product implications or follow-up actions

- Combine Sesame’s requests into a governance-and-operations roadmap slice.
- Focus first on invoice-linking reliability and import stability because those directly affect trust.
- Follow with auditability and export controls to support more mature admin teams.
