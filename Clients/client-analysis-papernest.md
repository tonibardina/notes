---
type: Pain point
belongs_to: "[[Slack Client Product Analysis Summary]]"
client: Papernest
source: slack_channels_data
---

# Client Analysis: Papernest

## Client name

Papernest

## Summary of relevant conversation context

Papernest is a high-admin-overhead account. The client changes plans, targets, and team structures frequently, and Dolfin appears too cumbersome for that operating model. The product challenge here is less raw calculation and more scalable admin ergonomics.

## Product-related pain points identified

| Pain point | Pain point category | Type of pain point | Estimated criticality | Supporting evidence or excerpts | Suggested product implications or follow-up actions |
| --- | --- | --- | --- | --- | --- |
| Rebuilding and updating comp logic month over month is too labor-intensive | Admin workflow and plan management | Missing feature | High | "constantly changing things in Dolfin is not easy"; monthly target and team changes create heavy admin work | Prioritize reusable templates, rule cloning, and lighter-weight plan maintenance workflows. |
| The client needs better support for recurring target and team changes | Target and team administration | Workflow limitation | High | "every month Marco is creating new targets and plans and assigning new teams" | Add bulk operations, target archiving, and easier team reassignment models. |
| Dolfin’s reporting and analytics are not strong enough to displace the client’s own data tooling | Reporting and analytics | Product value gap | Medium | "they already have their dashboards, with their own data analysis, and don’t really rely on Dolfin" | Improve differentiated reporting or stop assuming reporting alone will drive retention for BI-mature clients. |
| Integrations do not create enough resilience when data-side issues appear | Integration reliability | Integration gap | Medium | Existing automation work still depended on client data fixes and issues piled up | Add better integration observability and failure recovery before expanding automation promises. |
| Export/report requests still require manual handling | Reporting and exports | Missing feature | Medium | Repeated reminders to get target values export CSV and override reports | Standardize exports for target values and change tracking. |

## Suggested product implications or follow-up actions

- Position Papernest as a roadmap signal for high-change admin environments.
- Solve for reusable plan logic and bulk admin actions before layering advanced analytics.
- Re-evaluate whether the product is optimized for teams that reconfigure compensation monthly.
