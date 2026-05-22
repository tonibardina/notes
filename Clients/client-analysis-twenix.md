---
type: Pain point
belongs_to: "[[Slack Client Product Analysis Summary]]"
client: Twenix
source: slack_channels_data
---

# Client Analysis: Twenix

## Client name

Twenix

## Summary of relevant conversation context

Twenix combined trust erosion, admin friction, and reporting gaps. Some issues came from poor client-side process management, but the product still lacked the safeguards and traceability needed to prevent these issues from damaging confidence.

## Product-related pain points identified

| Pain point | Pain point category | Type of pain point | Estimated criticality | Supporting evidence or excerpts | Suggested product implications or follow-up actions |
| --- | --- | --- | --- | --- | --- |
| Admins cannot safely recover from mistaken comp-rule publications | Plan management and admin safety | Missing feature | High | "If I publish a comp rule by mistake, I can't undo it or delete the version" | Add undo, rollback, delete, and version recovery controls for comp rules. |
| Wrong or stale compensation data undermines rep trust | Data integrity and trust | Reliability gap | High | Reps lose trust when compensations "need to either be deleted, or changed... and aren't" | Add safeguards that prevent invalid data from remaining visible after admin mistakes or sync issues. |
| Target and metric management is cluttered and weakly filterable | Admin usability and reporting | Missing feature | Medium-High | Requests for archiving targets, filters, hiding old targets, and removing deactivated users from leaderboards | Improve target lifecycle management and leaderboard hygiene. |
| Reporting and analytics are not sufficient for ongoing management | Reporting and analytics | Missing feature | Medium-High | "Analytics for Global Targets Not Working"; repeated monthly achievement report requests | Add native target-progress reporting and historical views so the client does not rely on manual reports. |
| Weak traceability and HRIS integration contributed to churn | Data traceability and integration strategy | Integration gap | High | "lack of full trust"; suggestion that HRIS integration should be non-negotiable | Treat traceability and HRIS-backed data consistency as core trust infrastructure, not optional add-ons. |
| Role granularity is limited | Permissions and delegation | Missing feature | Medium | Oriol wanted a user-management-only admin role but chose not to add the person | Add narrower admin roles for safe delegation. |

## Suggested product implications or follow-up actions

- Use Twenix as a blueprint for trust-protection features: rollback, traceability, cleaner target management, and HRIS-backed data quality.
- Reduce dependence on manual monthly reporting by giving admins better historical analytics in-product.
- Distinguish clearly between client process failures and product gaps, but solve the gaps that amplify those failures.
