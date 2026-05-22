---
type: Pain point
belongs_to: "[[Slack Client Product Analysis Summary]]"
client: EV
source: slack_channels_data
---

# Client Analysis: EV

## Client name

EV

## Summary of relevant conversation context

EV shows a dense cluster of operational issues across mapping, statements, user access, reporting, and exports. This account generates repeated urgent support work, suggesting the platform is still brittle for large-scale compensation operations.

## Product-related pain points identified

| Pain point | Pain point category | Type of pain point | Estimated criticality | Supporting evidence or excerpts | Suggested product implications or follow-up actions |
| --- | --- | --- | --- | --- | --- |
| Missing agent codes and unmapped deals require repeated manual follow-up | Data integrity and sync operations | Integration gap | High | Repeated reminders to "Send list of Deals without a user mapped due to missing Agent codes" | Add automated detection, reporting, and notifications for unmapped deals and missing owner codes. |
| Statement flows are error-prone | Compensation reliability | Bug | Critical | "error when entering statements"; "missing users in statements list" | Harden statement generation, add pre-flight validation, and monitor regressions around payout views. |
| Manual compensation entry fails | Admin workflow | Bug | High | "error when trying to add a manual compensation" | Improve manual compensation reliability and introduce bulk/manual fallback workflows. |
| Duplicate users and wrong access cause data exposure and confusion | Permissions and user management | Bug | High | "duplicate user with wrong access" and "getting access to no data" | Strengthen identity resolution, duplicate handling, and role validation. |
| Reporting, exports, and manager permissions are not mature enough for client needs | Reporting, exports, and admin controls | Missing feature | Medium | Requests included bulk upload of manual compensations, manager permission levels, export standardization, cumulative GCI, and negative statement summaries | Consolidate these requests into an enterprise admin/reporting package rather than handling them ad hoc. |

## Suggested product implications or follow-up actions

- Prioritize EV as a high-signal account for data integrity automation and statement reliability.
- Build proactive admin alerts for mapping gaps before they impact statements or reports.
- Treat export/reporting standardization and permission granularity as near-term retention levers.
