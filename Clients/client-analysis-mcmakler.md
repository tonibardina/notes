---
type: Pain point
belongs_to: "[[Slack Client Product Analysis Summary]]"
client: McMakler
source: slack_channels_data
---

# Client Analysis: McMakler

## Client name

McMakler

## Summary of relevant conversation context

McMakler appears recoverable but trust is fragile. The client needs stronger approval controls, better broker attribution, higher sync reliability, and a more localized experience before expanding usage.

## Product-related pain points identified

| Pain point | Pain point category | Type of pain point | Estimated criticality | Supporting evidence or excerpts | Suggested product implications or follow-up actions |
| --- | --- | --- | --- | --- | --- |
| Approval flow does not feel controlled enough without notifications | Approval workflow | Missing feature | High | Michelle expected emails when it is the next approver’s turn and did not find the flow reliable enough | Add approval notifications and deadline reminders as a standard enterprise workflow capability. |
| Missing broker attribution creates manual work and weak trust in commissions | User mapping and data integrity | Integration gap | High | "Missing Zuführungsmakler is causing a lot of manual work"; need to import ~250 broker users for attribution | Improve user mapping, attribution support, and data health checks for unmapped broker-related fields. |
| Salesforce data is not always showing up in Dolfin | Sync reliability | Integration gap | High | "Data from salesforce is not always showing up in Dolfin" | Build stronger sync diagnostics, alerts, and client-facing status visibility. |
| German localization is not ready for broader rollout | Localization | Missing feature | Medium | Client said having the tool in German is essential for brokers and wants users to select language freely | Prioritize multilingual readiness where expansion depends on local-language adoption. |
| Trust is undermined when wrong compensation values appear and syncs stop silently | Data accuracy and monitoring | Reliability gap | High | "wrong compensation values"; "Their sync stopped" | Expand data health checks and sync-failure monitoring to prevent silent data degradation. |

## Suggested product implications or follow-up actions

- Treat McMakler as a trust rebuild account centered on attribution, sync visibility, and approval controls.
- Bundle localization with rollout readiness instead of treating it as cosmetic.
- Use broker attribution as a forcing function for better mapping and validation workflows.
